<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"enabled": true,
	"inbound": [
		{
			"expressions": ["req.URL.contains('v0/')"],
			"actions": [
				{
					"type": "url-rewrite",
					"config": {
						"from": "v0/user/([0-9]+).*",
						"to": "v1/user?id=$1\u0026$args"
					}
				},
				{
					"type": "url-rewrite",
					"config": {
						"from": "v0/super/secret/path/to/admin.*",
						"to": "v1/admin?$is_args$args"
					}
				}
			],
			"name": "Rewrite v0 API Calls to v1."
		},
		{
			"expressions": [
				"req.Method == \"POST\" \u0026\u0026 req.ContentLength \u003e 10000",
				"conn.Geo.CountryCode in [\"BR\", \"CN\", \"CU\", \"IR\", \"NG\", \"RO\", \"RU\", \"SD\", \"SY\", \"UA\"]"
			],
			"actions": [
				{
					"type": "custom-response",
					"config": {
						"content": "access denied",
						"content_type": "text/plain",
						"status_code": 401
					}
				}
			],
			"name": "Block POST Requests With Large Content Length From Specific Countries"
		},
		{
			"expressions": [
				"\"RudeDudes\" in req.Headers[\"User-Agent\"] || \"Scalawags\" in req.Headers[\"User-Agent\"]"
			],
			"actions": [
				{
					"type": "deny",
					"config": {
						"status_code": 400
					}
				}
			],
			"name": "Block User Agents"
		}
	],
	"outbound": [
		{
			"expressions": [
				"res.StatusCode \u003c \"200\" || res.StatusCode \u003e \"300\""
			],
			"actions": [
				{
					"type": "log",
					"config": {
						"Metadata": {
							"edgeId": "edghts_2bV9dbyF8iwVD6Ri9SwTpvc2Z9f",
							"message": "Unsuccessful response",
							"routeId": "edghtsrt_2bV9dhBCM0viYV12xgDqta6v7aX"
						}
					}
				}
			],
			"name": "Log Non Success"
		}
	]
}
```
