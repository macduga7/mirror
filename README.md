# Mirror — Style & Beauty MVP (FlutterFlow + ChatGPT Agent)

A lightweight starter pack to build **Mirror**, a style/beauty companion focused on outfits, makeup, and hair.

## What’s inside
- `docs/PRD.md` – MVP goals, scope, and guardrails
- `docs/user_flows.md` – flows & acceptance criteria
- `docs/data_model.json` – Firestore collections
- `docs/prompts/` – system prompt, JSON schemas, and few‑shot
- `flutterflow/prompts/` – copy‑paste prompts for “Prompt to Page/Component”
- `.github/ISSUE_TEMPLATE/` – issue templates
- `LICENSE` – MIT

## Quick start (15–30 min)
1. Create a new FlutterFlow project → *AI → Prompt to Page/Component* → paste prompts from `flutterflow/prompts/`.
2. **Firebase:** enable Auth, Firestore, Storage. Create collections from `docs/data_model.json`.
3. **AI Agent:** Add one agent (OpenAI provider). Enable text + image. Paste system message from `docs/prompts/system_stylist.md`. For screens that need structure, set “response schema” using `docs/prompts/json_schemas.md`.
4. Hook actions: call the agent from chat/actions, parse JSON into cards and steppers.
5. Optional: connect GitHub and push this repo.

## Non‑goals (for MVP)
- No medical or diagnosis content. Purely style/beauty assistance.
- No realtime AR try‑on; we use static images for v1.
