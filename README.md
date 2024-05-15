# registrar-ai-tool
An AI tool that seeks to help students discover courses, provide general course registration support, and helps ensure students stay informed on course prerequisites.

## Running Locally

Install docker-compose

Run the backend with `docker-compose up` (frontend coming soon maybe)

Example commands:

```
curl -X POST http://localhost:5000/process_message \
  -H 'Content-Type: application/json; charset=utf-8' \
  -d '{"threadId":"","query_type": "Class Info","user_message":"What course should I take next?", "tags":"[]"}'
```