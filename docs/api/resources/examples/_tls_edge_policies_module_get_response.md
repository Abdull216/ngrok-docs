<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"enabled": true,
	"inbound": [
		{
			"expressions": ["conn.TLS.Version.contains(\"1.3\")"],
			"actions": [
				{
					"type": "log",
					"config": {
						"Metadata": {
							"Message": "Invalid TLS Version"
						}
					}
				},
				{
					"type": "deny",
					"config": null
				}
			],
			"name": "AllowTLS1.3"
		}
	],
	"outbound": null
}
```
