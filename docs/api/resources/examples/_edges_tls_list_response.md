<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"tls_edges": [
		{
			"id": "edgtls_2bV9e21SkdLOGyz8ddZafV9hhPS",
			"description": "acme tls edge",
			"metadata": "{\"environment\": \"staging\"}",
			"created_at": "2024-01-26T17:17:50Z",
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2bV9e21SkdLOGyz8ddZafV9hhPS",
			"hostports": ["example.com:443"],
			"backend": null,
			"ip_restriction": null,
			"mutual_tls": null,
			"tls_termination": null,
			"policy": null
		},
		{
			"id": "edgtls_2bV9cLIfHwO8jUayTAZXfFyr8PF",
			"description": "acme tls edge",
			"created_at": "2024-01-26T17:17:36Z",
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2bV9cLIfHwO8jUayTAZXfFyr8PF",
			"hostports": ["endpoint-example.com:443"],
			"backend": {
				"enabled": true,
				"backend": {
					"id": "bkdhr_2bV9cEmHXvhUfTzf0VXA8hKWldg",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2bV9cEmHXvhUfTzf0VXA8hKWldg"
				}
			},
			"ip_restriction": null,
			"mutual_tls": null,
			"tls_termination": null,
			"policy": null
		}
	],
	"uri": "https://api.ngrok.com/edges/tls",
	"next_page_uri": null
}
```
