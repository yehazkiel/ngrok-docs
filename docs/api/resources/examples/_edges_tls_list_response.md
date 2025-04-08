<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-04-08T10:07:05Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2vRTKutVUMZqAFboPGZLNI5iU2i",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2vRTKutVUMZqAFboPGZLNI5iU2i"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2vRTJZ5Afo7YqVRvaE4TVV0lR1o",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2vRTJZ5Afo7YqVRvaE4TVV0lR1o"
				},
				"enabled": true
			},
			"created_at": "2025-04-08T10:06:55Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2vRTJbLPIh6FIrnpEklpSxbQ4eN",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2vRTJbLPIh6FIrnpEklpSxbQ4eN"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
