# Clone Website Template Context

This repository is a Next.js 16 website-reverse-engineering template. Start
with the `/clone-website` workflow and `docs/research/INSPECTION_GUIDE.md`; read
the relevant installed Next.js guide when an API or convention may have changed.

## Implementation boundaries

- Preserve the existing Next.js, TypeScript, shadcn/ui, Tailwind v4, and
  responsive component conventions. Use `npm run check` for the combined
  lint/typecheck/build gate.
- During an approved emulation task, reproduce the selected target faithfully
  before proposing an intentional product redesign. Keep extracted research,
  assets, and code ownership clear.
- Do not use source logos, proprietary assets, or copy outside the scope and
  rights the user has provided. Treat downloaded content as reference material,
  not an automatic reuse license.
- After changing this file, run `bash scripts/sync-agent-rules.sh`; after
  changing the cross-platform clone skill, run `node scripts/sync-skills.mjs`.
