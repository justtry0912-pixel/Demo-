# Motion Ad Studio Kit
### A Claude-ready workflow for creating premium motion graphics advertisements

Build repeatable, client-ready motion-ad concepts with a structured brief, creative direction, storyboards, production prompts, and quality checks.

> **What this is:** a reusable creative workflow and prompt toolkit. It does not guarantee that every generated video is production-ready or that sales are guaranteed. Always review output, assets, brand claims, and licensing before delivery.

## What you get
- `CLAUDE.md` — project-wide instructions for Claude
- `prompts/01-creative-brief.md` — gather the information needed for an ad
- `prompts/02-concept-and-storyboard.md` — concepts, hooks, scenes, timing and sound
- `prompts/03-production-and-code.md` — implementation brief for motion tools or code
- `prompts/04-revision-workflow.md` — structured revision instructions
- `prompts/05-client-delivery.md` — handoff and quality-control checklist
- `briefs/example-product-brief.json` — example input brief
- `docs/SELLING-GUIDE.md` — packaging, positioning and client workflow
- `docs/LICENSING-CHECKLIST.md` — practical rights and disclosure checks
- `templates/CLIENT-QUESTIONNAIRE.md` — intake form you can send to clients

## Quick start with Claude
1. Upload this repository folder to Claude (or open it in a Claude-supported coding workspace).
2. Ask Claude to read `CLAUDE.md` first.
3. Fill in `briefs/example-product-brief.json` or complete the client questionnaire.
4. Run the prompts in order: brief → concept/storyboard → production → revisions → delivery.
5. Review all claims, product details, visuals, music, fonts, footage and exports before delivering.

## Recommended production outputs
For each campaign, request:
- 3 distinct creative concepts
- 1 selected concept with a timed storyboard
- a 6–15 second vertical ad (9:16) plus requested cutdowns
- a 16:9 or 1:1 adaptation when needed
- on-screen copy, captions, CTA and thumbnail frame
- editable project/source files where your tools support them
- a version log and delivery checklist

Claude may produce code, shot plans, prompts or editing instructions depending on the tools and references you provide. Rendering may require separate software and assets.

## Repository structure
```text
motion-ad-studio-kit/
├── CLAUDE.md
├── README.md
├── LICENSE
├── prompts/
├── briefs/
├── docs/
└── templates/
```

## How to make it your own
- Replace example branding and add your own original demo work.
- Add before/after breakdowns and licensed sample assets.
- Include a clear scope, revision limit, turnaround estimate and delivery format in your offer.
- Do not promise viral results, specific ROAS, or guaranteed sales.

## License
See `LICENSE`. The included text and workflows are provided for adaptation. Third-party tools, models, music, fonts, footage, trademarks and client assets have separate terms.
