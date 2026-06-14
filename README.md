# Backend Service

Minimal Go HTTP service used by the parent deployment-pipeline repository.

- `GET /health` returns HTTP 200 when healthy.
- The deploy artifact is a single Linux `amd64` binary.
- The target VM runs it through `app-backend.service`.
