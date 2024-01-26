<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"event_subscriptions": [
		{
			"id": "esb_2bV9d99FjKXdLecDhnKZlvwJjhB",
			"uri": "https://api.ngrok.com/event_subscriptions/esb_2bV9d99FjKXdLecDhnKZlvwJjhB",
			"created_at": "2024-01-26T17:17:43Z",
			"metadata": "{\"environment\": \"staging\"}",
			"description": "ip policy creations",
			"sources": [
				{
					"type": "ip_policy_created.v0",
					"uri": "https://api.ngrok.com/event_subscriptions/esb_2bV9d99FjKXdLecDhnKZlvwJjhB/sources/ip_policy_created.v0"
				}
			],
			"destinations": [
				{
					"id": "ed_2bV9dDI4mYshbBZ7P73VP59jPI0",
					"uri": "https://api.ngrok.com/event_destinations/ed_2bV9dDI4mYshbBZ7P73VP59jPI0"
				}
			]
		}
	],
	"uri": "https://api.ngrok.com/event_subscriptions",
	"next_page_uri": null
}
```
