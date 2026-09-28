# 3za28 — local working copy (static single-file app)

- Production: https://3za28.vercel.app
- Vercel project: 3za28 (static, no build command)
- `index.html` = exact production snapshot (fetched live, byte-identical).
- Linked via `.vercel/project.json` — deploy only on explicit approval:
  `vercel deploy --prod --yes --cwd D:\3za28`
- Backend (Supabase, shared with M3ZA): read-only unless a task says otherwise.
- Old snapshots live in `D:\3za28_backup_2026-09-01` (do not edit).
