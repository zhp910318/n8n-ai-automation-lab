# n8n AI Automation Lab — free workflow templates

Practical n8n workflows for content and ops automation. This repo holds the **free** templates from [AI Automation Lab](https://payhip.com/haopengailab). Import them, run them, change them.

> ✅ **Now an official n8n template** — [Generate social content hooks with OpenAI GPT-4o-mini](https://n8n.io/workflows/20418-generate-social-content-hooks-with-openai-gpt-4o-mini/) is live in the n8n template gallery. Install it straight into your n8n instance, or import the JSON below.

## Included

### 🪝 AI Hook Generator (`workflow.json`)
Type a topic, get **10 scroll-stopping hooks** in five styles (bold claim, contrarian, specific number, question, mistake/warning). Each under 120 characters, ready to paste into a post or a video script.

**How to use**
1. n8n → **Workflows → Import from File** → select `workflow.json`
2. Open **Generate Hooks (LLM)** → pick your **OpenAI** credential
3. Open **Input** → set `topic`, `audience`, `tone`
4. Click **Test workflow**

**Output:** `hooks` — JSON array of `{ "style": "...", "text": "..." }`.

**Copy-paste examples:** [`EXAMPLES.md`](EXAMPLES.md) — 3 ready inputs (founder content, freelancer leads, newsletter teasers) with sample outputs.

**Install from the official n8n gallery:** [n8n.io → Generate social content hooks with OpenAI GPT-4o-mini](https://n8n.io/workflows/20418-generate-social-content-hooks-with-openai-gpt-4o-mini/)

Works with any OpenAI-compatible model (default `gpt-4o-mini`). One LLM call per run — well under a cent.

### 📝 Meeting Notes → Action Items (`meeting-notes-to-action-items/workflow.json`)
Paste a messy transcript or a pasted meeting chat and get a clean debrief: a short **summary**, the **decisions**, a table of **action items with owner + due date**, and a ready-to-send **follow-up email**.

**How to use**
1. n8n → **Workflows → Import from File** → select `meeting-notes-to-action-items/workflow.json`
2. Open **Summarize Meeting with OpenAI** → pick your **OpenAI** credential
3. Open **Set Meeting Notes and Attendees** → paste your notes into `raw_notes` and set `meeting_title`, `attendees`, `tone`
4. Click **Test workflow**

**Output:** `meeting_summary` — Markdown with Summary / Decisions / Action items / Follow-up email.

Works with any OpenAI-compatible model (default `gpt-4o-mini`). One LLM call per run.

## The rest of the engine
Free templates here get you started. The paid workflows in the [AI Automation Lab store](https://payhip.com/haopengailab) do the whole job end-to-end:

- **AI Content Repurposing Engine** — one input → X thread + LinkedIn post + newsletter + 5 hooks
- **AI SEO Blog Engine** — one keyword → publish-ready ~1,400-word article
- **AI Inbox Triage & Reply Drafter** — classify, prioritise and draft replies to every email

## Contributing / ideas
Open an issue if you want a variant (different model, different output format, scheduling via cron node). Free templates stay free.

## License
MIT — use them, ship them, change them.
