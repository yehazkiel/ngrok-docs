<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-04-08T10:07:00Z",
			"description": "sample cloud endpoint",
			"domain": {
				"id": "rd_2vRTJYqlzFTExsuPT5K1c04lwX9",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2vRTJYqlzFTExsuPT5K1c04lwX9"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2vRTKGTBq0ebhCOZnEbB4Pn8mgv",
			"metadata": "{\"environment\": \"staging\"}",
			"pooling_enabled": false,
			"proto": "https",
			"public_url": "https://endpoint-example2.com",
			"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
			"type": "cloud",
			"updated_at": "2025-04-08T10:07:00Z",
			"uri": "https://api.ngrok.com/endpoints/ep_2vRTKGTBq0ebhCOZnEbB4Pn8mgv",
			"url": "https://endpoint-example2.com"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-04-08T10:06:58Z",
			"hostport": "08ce47b6b8d7.ngrok.paid:443",
			"id": "ep_2vRTK16wnv1AXFdbCOlYt3d0Kgw",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2vRTHZiGTxAuafYRrhgoejL4dZX",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://08ce47b6b8d7.ngrok.paid",
			"tunnel": {
				"id": "tn_2vRTK16wnv1AXFdbCOlYt3d0Kgw",
				"uri": "https://api.ngrok.com/tunnels/tn_2vRTK16wnv1AXFdbCOlYt3d0Kgw"
			},
			"tunnel_session": {
				"id": "ts_2vRTK1KmYirwqTC9f7QncsT0Lxo",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2vRTK1KmYirwqTC9f7QncsT0Lxo"
			},
			"type": "ephemeral",
			"updated_at": "2025-04-08T10:06:58Z",
			"upstream_url": "http://localhost:80",
			"url": "https://08ce47b6b8d7.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-04-08T10:06:55Z",
			"domain": {
				"id": "rd_2vRTJYqlzFTExsuPT5K1c04lwX9",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2vRTJYqlzFTExsuPT5K1c04lwX9"
			},
			"edge": {
				"id": "edgtls_2vRTJbLPIh6FIrnpEklpSxbQ4eN",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2vRTJbLPIh6FIrnpEklpSxbQ4eN"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2vRTJeaoRZd26ePCzWEaIwwUII8",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-04-08T10:06:55Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
