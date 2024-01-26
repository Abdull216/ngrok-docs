<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"id": "ec_2bV9aHgIjSAK7LF9D7XLOej1IQP",
	"type": "https",
	"description": "app servers",
	"created_at": "2024-01-26T17:17:20Z",
	"uri": "https://api.ngrok.com/endpoint_configurations/ec_2bV9aHgIjSAK7LF9D7XLOej1IQP",
	"basic_auth": null,
	"circuit_breaker": null,
	"compression": null,
	"request_headers": {
		"enabled": true,
		"add": {
			"x-frontend": "ngrok"
		},
		"remove": ["cache-control"]
	},
	"response_headers": null,
	"ip_policy": {
		"enabled": true,
		"ip_policies": [
			{
				"id": "ipp_2bV9aE0q7QxUhNDWH0sfF6YA1ZV",
				"uri": "https://api.ngrok.com/ip_policies/ipp_2bV9aE0q7QxUhNDWH0sfF6YA1ZV"
			}
		]
	},
	"mutual_tls": null,
	"tls_termination": null,
	"webhook_validation": null,
	"oauth": null,
	"saml": null,
	"oidc": null,
	"backend": null
}
```
