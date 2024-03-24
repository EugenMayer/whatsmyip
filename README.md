# What's my IP?

Docker image `ghrc.io/eugenmayer/whatsmyip` to simply return ones IP - DynDNS or similar usecases.

# Start

```bash
docker run -p 80:8080 mdevey/whatsmyip
```

Access `http://localhost` and you get your ip.

Supports Load-Balancers with `X-Forward-For` / `X-Real-Ip`

# Helm chart

See [helm-chart](https://github.com/EugenMayer/helm-charts/tree/main/charts/whatsmyip)