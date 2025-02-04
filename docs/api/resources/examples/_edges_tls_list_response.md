<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-02-04T10:08:29Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2sZWjAFOhJ7vxOq2h5xCtFVeUvB",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2sZWjAFOhJ7vxOq2h5xCtFVeUvB"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2sZWhk9N2XAgQUZfhCCitIP0bi5",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2sZWhk9N2XAgQUZfhCCitIP0bi5"
				},
				"enabled": true
			},
			"created_at": "2025-02-04T10:08:18Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2sZWhqQ6QBvFng1MLD0ydx4l5Kj",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2sZWhqQ6QBvFng1MLD0ydx4l5Kj"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
