# docker-minio
Wrapper image for MinIO, starting a server with data in `/data`.

The base is the last successful Blink Labs image of MinIO
`RELEASE.2025-09-07T16-13-09Z-cpuv1`, pinned by its amd64/arm64 manifest digest.
It preserves the published runtime after the upstream image became unavailable.
Retain this base digest in GHCR when changing image retention policies.
