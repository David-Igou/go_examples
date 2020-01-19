# Webhook

You can validate functionality locally with `curl -H "Content-Type: application/json" -X POST -d '{"username": "test", "content": "hello"}' http://localhost:8080/webhook`

Still figuring out when to use json unmarshall vs json decode, but decode is very easy to get started with.
