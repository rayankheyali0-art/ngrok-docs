<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_30BEEaKxnXSvCui4XkHTO02icFx",
        "uri": "https://api.ngrok.com/tls_certificates/cert_30BEEaKxnXSvCui4XkHTO02icFx"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.26eua9cq3xfuhkbyi.local-ngrok-cname.com",
      "created_at": "2025-07-21T10:07:34Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_30BEEXXvL6Xw7CvHZpljggKbwpU",
      "is_dev": false,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_30BEEXXvL6Xw7CvHZpljggKbwpU"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": {
        "authority": "letsencrypt",
        "private_key_type": "ecdsa"
      },
      "certificate_management_status": {
        "provisioning_job": {
          "error_code": null,
          "msg": "Managed certificate provisioning in progress.",
          "retries_at": null,
          "started_at": "2025-07-21T10:07:34Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.26eua9cq3xfuhkbyi.local-ngrok-cname.com",
      "created_at": "2025-07-21T10:07:34Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_30BEEcKueXn1a6Aofd2a7PruTPS",
      "is_dev": false,
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_30BEEcKueXn1a6Aofd2a7PruTPS"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": null,
      "created_at": "2025-07-21T10:07:03Z",
      "description": "Your dev domain",
      "domain": "koala-social-evidently.ngrok-free.dev",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_30BEAcTgRXRlZ8xee2ViYlqhCJU",
      "is_dev": true,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_30BEAcTgRXRlZ8xee2ViYlqhCJU"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
