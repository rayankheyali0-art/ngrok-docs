<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-21T10:07:55Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_30BEGZa405261JmzMtIuusSRWk3",
        "uri": "https://api.ngrok.com/reserved_domains/rd_30BEGZa405261JmzMtIuusSRWk3"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_30BEHBIIYPIrk0lqyjeOaL7Ola8",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-07-21T10:07:55Z",
      "uri": "https://api.ngrok.com/endpoints/ep_30BEHBIIYPIrk0lqyjeOaL7Ola8",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-21T10:07:52Z",
      "hostport": "9107de1f86e0.ngrok.paid:443",
      "id": "ep_30BEGqjL2cErZnqp3WQ3ZOpSSJV",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_30BEATZyz2GeG9YboZVwcPHTiUY",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://9107de1f86e0.ngrok.paid",
      "tunnel": {
        "id": "tn_30BEGqjL2cErZnqp3WQ3ZOpSSJV",
        "uri": "https://api.ngrok.com/tunnels/tn_30BEGqjL2cErZnqp3WQ3ZOpSSJV"
      },
      "tunnel_session": {
        "id": "ts_30BEGpWQFa2uwbv1mkTcarmYpqx",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_30BEGpWQFa2uwbv1mkTcarmYpqx"
      },
      "type": "ephemeral",
      "updated_at": "2025-07-21T10:07:52Z",
      "upstream_url": "http://localhost:80",
      "url": "https://9107de1f86e0.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-21T10:07:50Z",
      "domain": {
        "id": "rd_30BEGZa405261JmzMtIuusSRWk3",
        "uri": "https://api.ngrok.com/reserved_domains/rd_30BEGZa405261JmzMtIuusSRWk3"
      },
      "edge": {
        "id": "edgtls_30BEGZnKhhfF316tg5LwL4MlCzq",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_30BEGZnKhhfF316tg5LwL4MlCzq"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_30BEGZrtwjl430GcofboweExhy6",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-07-21T10:07:50Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
