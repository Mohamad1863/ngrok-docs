
#### Example Response
```json
{
  "endpoint_configurations": [
    {
      "id": "ec_2GguzVkisO0WwcmVrDJ1FnjLEZ9",
      "type": "https",
      "description": "app servers",
      "metadata": "",
      "created_at": "2022-10-26T22:20:10Z",
      "uri": "https://api.ngrok.com/endpoint_configurations/ec_2GguzVkisO0WwcmVrDJ1FnjLEZ9",
      "basic_auth": null,
      "circuit_breaker": null,
      "compression": null,
      "request_headers": {
        "enabled": true,
        "add": {
          "x-frontend": "ngrok"
        },
        "remove": [
          "cache-control"
        ]
      },
      "response_headers": null,
      "ip_policy": null,
      "mutual_tls": null,
      "tls_termination": null,
      "webhook_validation": null,
      "oauth": null,
      "saml": null,
      "oidc": null,
      "backend": null
    },
    {
      "id": "ec_2GguzTwtXuOoxiHfAKp6CxX4Xmh",
      "type": "https",
      "description": "web servers",
      "metadata": "",
      "created_at": "2022-10-26T22:20:10Z",
      "uri": "https://api.ngrok.com/endpoint_configurations/ec_2GguzTwtXuOoxiHfAKp6CxX4Xmh",
      "basic_auth": null,
      "circuit_breaker": {
        "enabled": true,
        "tripped_duration": 0,
        "rolling_window": 0,
        "num_buckets": 0,
        "volume_threshold": 0,
        "error_threshold_percentage": 0.2
      },
      "compression": {
        "enabled": true
      },
      "request_headers": null,
      "response_headers": {
        "enabled": true,
        "add": {
          "content-security-policy": "script-src 'self'",
          "x-frame-options": "DENY"
        },
        "remove": []
      },
      "ip_policy": null,
      "mutual_tls": null,
      "tls_termination": null,
      "webhook_validation": null,
      "oauth": null,
      "saml": null,
      "oidc": null,
      "backend": null
    }
  ],
  "uri": "https://api.ngrok.com/endpoint_configurations",
  "next_page_uri": null
}