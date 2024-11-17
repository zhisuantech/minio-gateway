# minio-gateway

Convert MinIO's TLS authentication to standard HTTP  
To integrate CSI-S3 with the MinIO tenant created by MinIO Operator.

Reference link: https://github.com/envoyproxy/examples/blob/main/tls-sni/envoy-client.yaml

Reference guide: https://www.envoyproxy.io/docs/envoy/latest/start/sandboxes/tls

Generate an Envoy proxy for https://minio.minio.svc.cluster.local, using the CA from the service account, converting HTTPS to HTTP.

Modify MinIO's service address to myminio-hl.minio.svc.cluster.local if needed.
