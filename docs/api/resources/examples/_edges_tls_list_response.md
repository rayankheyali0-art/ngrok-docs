<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-07-21T10:08:01Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_30BEHvUCZeyzZZo90HwhuA3xzsl",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_30BEHvUCZeyzZZo90HwhuA3xzsl"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_30BEGbCesKDepgdCTUinx1PrzK4",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_30BEGbCesKDepgdCTUinx1PrzK4"
        },
        "enabled": true
      },
      "created_at": "2025-07-21T10:07:50Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_30BEGZnKhhfF316tg5LwL4MlCzq",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_30BEGZnKhhfF316tg5LwL4MlCzq"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
