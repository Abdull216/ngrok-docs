<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Request

```bash
curl \
-X POST \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"description":"acme weighted","metadata":"{\"environment\": \"staging\"}","backends":{"bkdhr_2bV9dEy47gsriIwXzRtpECIPaqn":0,"bkdhr_2bV9dG5kQ58CK77HPwZIGhM9wJh":1}}' \
https://api.ngrok.com/backends/weighted
```
