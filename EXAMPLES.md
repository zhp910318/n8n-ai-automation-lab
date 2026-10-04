# AI Hook Generator — 3 copy-paste examples

Import `workflow.json` once (n8n → Workflows → Import from File), then change the **Input** node values per example below and hit **Test workflow**. Each run costs one `gpt-4o-mini` call (well under a cent).

## Example 1 — Founder / startup content

**Input**
- `topic`: `why most content fails to get clicks`
- `audience`: `founders and creators`
- `tone`: `direct, curious, no hype`

**What you get** — 10 hooks, mixed styles, e.g.
- (bold claim) "Your content isn't boring. Your first line is."
- (contrarian) "Stop writing better content. Start writing better first lines."
- (specific number) "7 words decide whether anyone reads your post."
- (question) "Why do 90% of posts die in the first 2 seconds?"
- (mistake/warning) "The #1 hook mistake: starting with background, not tension."

## Example 2 — Freelancer / client acquisition

**Input**
- `topic`: `how I find clients without cold DMs`
- `audience`: `freelancers and solo consultants`
- `tone`: `practical, honest, no guru talk`

**What you get** — 10 hooks angled at client pain, e.g.
- (bold claim) "I booked 3 clients without sending a single cold DM."
- (contrarian) "Cold outreach is the slowest way to get clients."
- (specific number) "2 posts a week brought me 11 inbound leads."
- (question) "What if clients came to you instead?"
- (mistake/warning) "Stop pitching. Start posting proof."

## Example 3 — Newsletter / SEO teaser

**Input**
- `topic`: `a 15-minute repurposing system for one blog post`
- `audience`: `newsletter writers and bloggers`
- `tone`: `clear, useful, specific`

**What you get** — 10 hooks you can reuse as email subject lines or H2s, e.g.
- (bold claim) "One post can feed your newsletter for a month."
- (contrarian) "You don't need more ideas. You need more formats."
- (specific number) "15 minutes turns 1 post into 9 assets."
- (question) "Why write from scratch every week?"
- (mistake/warning) "Reposting links isn't repurposing. This is."

## Tweak the prompt

Open **Generate Hooks (LLM)** → edit the user message to bias output:
- Shorter/punchier: add `Each hook under 60 characters.`
- One style only: replace the style list with e.g. `Use only contrarian style.`
- Another language: add `Write the hooks in <language>.`

## Go further (paid, end-to-end)

This free template is one step. The paid workflows in
[AI Automation Lab](https://payhip.com/haopengailab) run the whole pipeline:

- **AI Content Repurposing Engine ($29)** — one input → X thread + LinkedIn post + newsletter + 5 hooks
- **AI SEO Blog Engine ($34)** — one keyword → publish-ready ~1,400-word article
- **AI Inbox Triage & Reply Drafter ($24)** — classify, prioritise and draft replies to every email
