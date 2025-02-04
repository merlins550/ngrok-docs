<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-02-04T10:08:23Z",
			"description": "sample cloud endpoint",
			"domain": {
				"id": "rd_2sZWhpE9VxEJ12dum4R7qdYpYws",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2sZWhpE9VxEJ12dum4R7qdYpYws"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2sZWiNn6rM5A7QFtyWkgCmJp3Dy",
			"metadata": "{\"environment\": \"staging\"}",
			"pooling_enabled": false,
			"proto": "https",
			"public_url": "https://endpoint-example2.com",
			"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
			"type": "cloud",
			"updated_at": "2025-02-04T10:08:23Z",
			"uri": "https://api.ngrok.com/endpoints/ep_2sZWiNn6rM5A7QFtyWkgCmJp3Dy",
			"url": "https://endpoint-example2.com"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-04T10:08:21Z",
			"hostport": "4ad243898c87.ngrok.paid:443",
			"id": "ep_2sZWiAdxUfhg5mjOeTRawS75YR3",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2sZWfgBk1IRIwxMGUxba9eBFT1R",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://4ad243898c87.ngrok.paid",
			"tunnel": {
				"id": "tn_2sZWiAdxUfhg5mjOeTRawS75YR3",
				"uri": "https://api.ngrok.com/tunnels/tn_2sZWiAdxUfhg5mjOeTRawS75YR3"
			},
			"tunnel_session": {
				"id": "ts_2sZWiDWSX8NaqgBtZZRv85J6xgj",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2sZWiDWSX8NaqgBtZZRv85J6xgj"
			},
			"type": "ephemeral",
			"updated_at": "2025-02-04T10:08:21Z",
			"upstream_url": "http://localhost:80",
			"url": "https://4ad243898c87.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-04T10:08:19Z",
			"domain": {
				"id": "rd_2sZWhpE9VxEJ12dum4R7qdYpYws",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2sZWhpE9VxEJ12dum4R7qdYpYws"
			},
			"edge": {
				"id": "edgtls_2sZWhqQ6QBvFng1MLD0ydx4l5Kj",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2sZWhqQ6QBvFng1MLD0ydx4l5Kj"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2sZWhmsxhCCvn1blsN2vAplqaIT",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-02-04T10:08:19Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
