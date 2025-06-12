<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-06-12T10:07:22Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2yP4NqjxIBa8AAXQaqYs4aaz66h",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2yP4NqjxIBa8AAXQaqYs4aaz66h"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2yP4OWWhDWT8vdQTW19QUhqjwgQ",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-06-12T10:07:22Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2yP4OWWhDWT8vdQTW19QUhqjwgQ",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-06-12T10:07:20Z",
      "hostport": "248613435398.ngrok.paid:443",
      "id": "ep_2yP4OGEb0mECx16mJurgqTHYFcm",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2yP4LxMKR9eY1ivrCy7PuMnSTYP",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://248613435398.ngrok.paid",
      "tunnel": {
        "id": "tn_2yP4OGEb0mECx16mJurgqTHYFcm",
        "uri": "https://api.ngrok.com/tunnels/tn_2yP4OGEb0mECx16mJurgqTHYFcm"
      },
      "tunnel_session": {
        "id": "ts_2yP4OKgOuqLe4c6ma2XtfXv9t8z",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2yP4OKgOuqLe4c6ma2XtfXv9t8z"
      },
      "type": "ephemeral",
      "updated_at": "2025-06-12T10:07:20Z",
      "upstream_url": "http://localhost:80",
      "url": "https://248613435398.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-06-12T10:07:17Z",
      "domain": {
        "id": "rd_2yP4NqjxIBa8AAXQaqYs4aaz66h",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2yP4NqjxIBa8AAXQaqYs4aaz66h"
      },
      "edge": {
        "id": "edgtls_2yP4NvSgZQYE5Tvwi9tAWIqGsGt",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2yP4NvSgZQYE5Tvwi9tAWIqGsGt"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2yP4NutFNLzBHSnNAUZHw1dJMIE",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-06-12T10:07:17Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
