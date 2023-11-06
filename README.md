# docker-grpc-health-check-server

This repository contains a simple gRPC server that only serves the purpose of providing health checks.
It's useful for deployment and operational testing.

# Usage
```bash
$ docker run --rm -p 9090:9090 amothic/grpc-health-check-server:latest

# Health Check
$ grpc-health-probe -addr=localhost:9090
```
