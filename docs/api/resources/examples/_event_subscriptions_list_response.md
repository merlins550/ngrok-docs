<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"event_subscriptions": [
		{
			"created_at": "2025-02-04T10:08:24Z",
			"description": "ip policy creations",
			"destinations": [
				{
					"id": "ed_2sZWiYF6Du9l4xeKqwHoFek0lC4",
					"uri": "https://api.ngrok.com/event_destinations/ed_2sZWiYF6Du9l4xeKqwHoFek0lC4"
				}
			],
			"id": "esb_2sZWiVxAHrm3mRFO9EDnb2AIaZ9",
			"metadata": "{\"environment\": \"staging\"}",
			"sources": [
				{
					"type": "ip_policy_created.v0",
					"uri": "https://api.ngrok.com/event_subscriptions/esb_2sZWiVxAHrm3mRFO9EDnb2AIaZ9/sources/ip_policy_created.v0"
				}
			],
			"uri": "https://api.ngrok.com/event_subscriptions/esb_2sZWiVxAHrm3mRFO9EDnb2AIaZ9"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/event_subscriptions"
}
```
