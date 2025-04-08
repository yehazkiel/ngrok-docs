<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2vRTHbDm0F0z1W5hTGjMDKGjTWk",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2vRTHbDm0F0z1W5hTGjMDKGjTWk"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.eeqvcp8d4i5wxunj.local-ngrok-cname.com",
			"created_at": "2025-04-08T10:06:39Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2vRTHWsZS5RrjAd66GVlHRtdbKo",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2vRTHWsZS5RrjAd66GVlHRtdbKo"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"retries_at": null,
					"started_at": "2025-04-08T10:06:40Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.eeqvcp8d4i5wxunj.local-ngrok-cname.com",
			"created_at": "2025-04-08T10:06:39Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2vRTHgUTARbjKJp2RdIzOKotEa2",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2vRTHgUTARbjKJp2RdIzOKotEa2"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
