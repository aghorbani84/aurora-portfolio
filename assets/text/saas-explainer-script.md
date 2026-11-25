# SaaS Explainer — 60-Second Portfolio Sample

**SAMPLE / PORTFOLIO DEMO — fictional product, not client work.**

This video is a portfolio sample made to demonstrate explainer-video
production (script, voiceover, original motion graphics, music bed).
The product shown, **FlowBoard**, is a fictional demo product invented
for this sample only. It is not a real company, not a real client, and
nothing in the video is a testimonial, a customer claim, or a measured
result. All claims are generic descriptions of the fictional product's
concept. No real company names, no copied copy, no stock footage,
images, or audio were used.

- **Product (fictional):** FlowBoard — a demo project-board tool
- **Format:** 1920×1080, 30 fps, H.264 + AAC, ~60 seconds
- **Voiceover:** Piper TTS, voice `en_US-amy-medium` (local model, no download)
- **Visuals:** Original art drawn in code (PIL) — no stock images
- **Music:** Original gentle pad generated in code with numpy (C–Am–F–G),
  mixed quietly under the voiceover — no copyrighted audio
- **Audio:** voice gain 0.85, `alimiter=limit=0.8:level=false`,
  measured true peak −1.77 dBTP, integrated loudness −18.4 LUFS
- **Production files:** `saas-explainer-work/` (build.py, gen_assemble.py,
  assemble.sh, lines.txt, line1–6.wav, scene1–6.png, music.wav)

## Full voiceover script (word-for-word)

**Scene 1 — The problem (0.0–10.3 s)**

> Every team knows this feeling. Work is scattered across chats,
> documents, and inboxes, and nobody can see what is actually
> getting done.

**Scene 2 — Meet the product (10.3–22.0 s)**

> Meet FlowBoard — a simple project board that puts your whole
> team's work in one place. FlowBoard is a fictional product,
> created only for this portfolio demo.

**Scene 3 — Drag and done (22.0–32.3 s)**

> Drag a card from To Do to Done, and the whole team sees it
> instantly. No status meetings. No chasing down answers.

**Scene 4 — Stay organised (32.3–41.1 s)**

> Boards, lists, and due dates keep everything organised, so a
> small team can focus on the work itself — not on managing
> the work.

**Scene 5 — Runs anywhere (41.1–47.8 s)**

> It runs in the browser on any device, with nothing to install,
> and your team's data stays yours.

**Scene 6 — Close (47.8–57.5 s)**

> FlowBoard is fictional — but this video is real work. If you
> need an explainer like this for your product, let's talk.

## Scene list (visuals)

| # | Time | Visual | On-screen text |
|---|------|--------|----------------|
| 1 | 0.0–10.3 s | Scattered app pills (Chat, Email, Doc, Inbox, Notes, Spreadsheet, Meeting) around a large "?" | "Work is scattered everywhere." / "Chats, docs, inboxes — and no clear picture." |
| 2 | 10.3–22.0 s | Original three-column board mockup: TO DO / DOING / DONE with cards | "FlowBoard" / "Meet FlowBoard." / "One board for your whole team's work." |
| 3 | 22.0–32.3 s | A card mid-drag from TO DO toward DONE, amber arrow | "Drag. Done. Everyone sees it." / "No status meetings. No chasing answers." |
| 4 | 32.3–41.1 s | Checklist with three ticked items, one open | "Organised, without the overhead." / "Boards, lists and due dates — all in one place." |
| 5 | 41.1–47.8 s | Browser window (flowboard.demo) beside a phone | "Runs anywhere. Nothing to install." / "In the browser, on any device — your data stays yours." |
| 6 | 47.8–57.5 s | Closing card with the FlowBoard wordmark | "FlowBoard" / "A fictional demo product." / "Made only as a portfolio sample." / "A fictional product. A real explainer." / "Need one like this for your product? Let's talk." |

Every scene carries an amber badge: **"PORTFOLIO DEMO · FICTIONAL PRODUCT"**.

## Verification (2026-11-25)

- `ffprobe`: duration **57.53 s**, 1920×1080, 30 fps, video H.264,
  audio AAC 48 kHz, 7.9 MB
- Full decode (`ffmpeg -v error -i file -f null -`): **clean, no errors**
- Loudness (`loudnorm`): integrated −18.37 LUFS, true peak **−1.77 dBTP**
  (at or below the −1 dBTP ceiling)
- Two rendered frames visually checked: badge fully legible on all
  scenes, headlines and subheads fully in frame, no clipped text.

## Distribution

Not sent, posted, or published anywhere. Portfolio sample only.
