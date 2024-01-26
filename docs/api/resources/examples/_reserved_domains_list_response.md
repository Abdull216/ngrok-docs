<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"reserved_domains": [
		{
			"id": "rd_2bV9aFAp1jH7nRGDf5D2Dn6N8v1",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2bV9aFAp1jH7nRGDf5D2Dn6N8v1",
			"created_at": "2024-01-26T17:17:20Z",
			"domain": "myapp.mydomain.com",
			"region": "",
			"cname_target": "2udamkamcl8pjmrff.26tgnvhif4givxxjx.local-ngrok-cname.com",
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"certificate": {
				"id": "cert_2bV9aL1GlmD5TsBX9JPpam1uGCm",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2bV9aL1GlmD5TsBX9JPpam1uGCm"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"acme_challenge_cname_target": null
		},
		{
			"id": "rd_2bV9aEv6gGj5Uze9sKuoOszXZbt",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2bV9aEv6gGj5Uze9sKuoOszXZbt",
			"created_at": "2024-01-26T17:17:20Z",
			"description": "Device 0001 Dashboard",
			"metadata": "{\"service\": \"dashboard\"}",
			"domain": "manage-0001.app.example.com",
			"region": "",
			"cname_target": "4mgkuazanf1yq46m3.26tgnvhif4givxxjx.local-ngrok-cname.com",
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"renews_at": null,
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"started_at": "2024-01-26T17:17:20Z",
					"retries_at": null
				}
			},
			"acme_challenge_cname_target": null
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains",
	"next_page_uri": null
}
```
