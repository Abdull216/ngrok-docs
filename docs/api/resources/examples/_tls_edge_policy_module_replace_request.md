<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Request

```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"inbound":[{"expressions":["conn.TLS.Version.contains(\"1.3\")"],"actions":[{"type":"log","config":{"Metadata":{"Message":"Invalid TLS Version"}}},{"type":"deny"}],"name":"AllowTLS1.3"}]}' \
https://api.ngrok.com/edges/tls/edgtls_2bV9eLfO5lB2fEikzO3ooTgDwVJ/policy
```
