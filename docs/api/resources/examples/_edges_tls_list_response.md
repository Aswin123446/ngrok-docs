<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-06-12T10:07:28Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2yP4PIw6pgsiYJylIaeIahUHNb8",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2yP4PIw6pgsiYJylIaeIahUHNb8"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2yP4NvCzPozQpl2vU2VjY5CxpGs",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2yP4NvCzPozQpl2vU2VjY5CxpGs"
        },
        "enabled": true
      },
      "created_at": "2025-06-12T10:07:17Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2yP4NvSgZQYE5Tvwi9tAWIqGsGt",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2yP4NvSgZQYE5Tvwi9tAWIqGsGt"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
