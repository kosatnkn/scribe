# Mock Servers

- [APISprout](https://github.com/danielgtaylor/apisprout)
```bash
docker run -p 8088:8000 --name apisprout_sample --rm --env SPROUT_VALIDATE_REQUEST=1 -v D:/Development/go/catalyst/doc/api/openapi.yaml:/api.yaml danielgtaylor/apisprout /api.yaml
```