# proposal-linkerd-grpc

## Run

```bash
docker-compose up -d
docker-compose logs -f linkerd
```

```bash
go get -u github.com/nokamoto/example-ping-service-client
example-ping-service-client -h localhost -p 8080
```

| url | module |
| --- | --- |
| http://localhost:9990 | [linkerd dashboard](https://linkerd.io/1/administration/dashboard/) |
| http://localhost:9090 | [Prometheus](https://prometheus.io/) |
| http://localhost:3000/d/iIUiYxbmk/linkerd-viz | [grafana](https://grafana.com/dashboards/3983) |
