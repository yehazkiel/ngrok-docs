<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"event_subscriptions": [
		{
			"created_at": "2025-04-08T10:07:01Z",
			"description": "ip policy creations",
			"destinations": [
				{
					"id": "ed_2vRTKN3p87BYCqDgbFO8FtQqubY",
					"uri": "https://api.ngrok.com/event_destinations/ed_2vRTKN3p87BYCqDgbFO8FtQqubY"
				}
			],
			"id": "esb_2vRTKPML46VcrcWqfZlsTkDfvra",
			"metadata": "{\"environment\": \"staging\"}",
			"sources": [
				{
					"type": "ip_policy_created.v0",
					"uri": "https://api.ngrok.com/event_subscriptions/esb_2vRTKPML46VcrcWqfZlsTkDfvra/sources/ip_policy_created.v0"
				}
			],
			"uri": "https://api.ngrok.com/event_subscriptions/esb_2vRTKPML46VcrcWqfZlsTkDfvra"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/event_subscriptions"
}
```
