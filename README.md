# proposal-linkerd-grpc

## Build

```bash
./build.sh
```

## Run

```bash
docker-compose up -d
docker-compose logs -f linkerd
```

```bash
docker-compose exec client client -h linkerd -p 8080
```

| url | module |
| --- | --- |
| http://localhost:9990 | [linkerd dashboard](https://linkerd.io/1/administration/dashboard/) |
| http://localhost:9090 | [Prometheus](https://prometheus.io/) |
| http://localhost:3000/d/iIUiYxbmk/linkerd-viz | [grafana](https://grafana.com/dashboards/3983) |
