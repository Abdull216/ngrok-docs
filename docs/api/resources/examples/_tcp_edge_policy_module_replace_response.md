<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"enabled": true,
	"inbound": [
		{
			"expressions": ["conn.ClientIP == \"192.0.2.0\""],
			"actions": [
				{
					"type": "deny",
					"config": null
				}
			],
			"name": "Block IP"
		}
	],
	"outbound": null
}
```
