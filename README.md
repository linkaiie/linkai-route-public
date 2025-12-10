# LinkAI Route

**LinkAI Route** is a unified API gateway for accessing multiple AI model providers through a single, consistent interface.  
Developers can top up credits, call models using a unified API format, and manage their usage in one place.

This repository contains the public documentation, early API specification, and development roadmap for the LinkAI Route platform.

---

## 🌐 Official Website
https://linkai.ie  
(Product pages & console will be available under subdomains.)

---

## 🚀 What is LinkAI Route?

LinkAI Route provides:

- A unified API endpoint for multiple AI providers  
- Credit-based billing system  
- Usage logging & analytics  
- API key management  
- Dynamic model routing  
- Developer-friendly dashboard

Our goal is to make AI integration easier, more flexible, and provider-agnostic.

---

## 🧩 Example API (Early Preview)

```bash
POST /v1/chat
Authorization: Bearer <your_api_key>
Content-Type: application/json
````

```json
{
  "provider": "openai",
  "model": "gpt-5.2",
  "messages": [
    {"role": "user", "content": "Hello from LinkAI Route"}
  ]
}
```

This is an early preview of the planned unified interface.

---

## 📚 Documents

* [API Design](./API_DESIGN.md)
* [Roadmap](./ROADMAP.md)
* [Changelog](./CHANGELOG.md)

---

## 🏗️ Project Status

LinkAI Route is currently under active development.
The first private beta is planned for release soon.

---

## 📩 Contact

info[at]linkai.ie