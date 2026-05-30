# AI Gateway Design

Planned endpoints:

- `POST /api/ai/chat`
- `POST /api/ai/text-to-image`
- `POST /api/ai/get-image`
- `POST /api/ai/nano-image`

The gateway should isolate provider credentials from the frontend and make it possible to switch between model providers without rewriting UI code.
