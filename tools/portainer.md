[< Back](./../README.md)

# Portainer

### Create volume
```bash
	docker volume create portainer_data
```

### Install Portainer
```bash
	docker run -d -p 8000:8000 -p 9000:9000 --name portainer --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer
```

### Upgrade Portainer
```bash
	docker pull portainer/portainer
	
	docker stop portainer
	
	docker rm portainer
	
	# install command
	docker run -d -p 8000:8000 -p 9000:9000 --name portainer --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer
```
