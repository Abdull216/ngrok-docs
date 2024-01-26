<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Request

```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"inbound":[{"expressions":["conn.ClientIP == \"192.0.2.0\""],"actions":[{"type":"deny"}],"name":"Block IP"}]}' \
https://api.ngrok.com/edges/tcp/edgtcp_2bV9e8q0ZTldCubHYDpLPX8IsVQ/policy
```
