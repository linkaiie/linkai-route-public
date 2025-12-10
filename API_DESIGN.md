# LinkAI Route — API Design (Preview)

## Unified Chat Endpoint

```

POST /v1/chat
Authorization: Bearer <api_key>

````

### Request Body

```json
{
  "provider": "openai | deepseek | anthropic | gemini",
  "model": "string",
  "messages": [
    {"role": "user", "content": "string"}
  ],
  "temperature": 0.7,
  "max_tokens": 2048
}
````

### Response Format

```json
{
  "id": "msg_12345",
  "provider": "openai",
  "model": "gpt-4",
  "object": "chat.completion",
  "created": 1700000000,
  "usage": {
    "prompt_tokens": 10,
    "completion_tokens": 50,
    "total_tokens": 60
  },
  "message": {
    "role": "assistant",
    "content": "Hello! This is a unified response."
  }
}
```
