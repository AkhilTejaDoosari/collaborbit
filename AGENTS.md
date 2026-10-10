
<!-- STARKWOLF COLLABORBIT WORKFLOW -->
## CollabOrbit workflow
- Read the existing repository and specification before editing. Report conflicts with the intended Next.js, shadcn/ui, Supabase, and Supabase Google Auth stack; do not rewrite the app merely to match it.
- Spec Kit defines requirements, plan, and tasks. Superpowers guides implementation. OMO coordinates bounded work. OpenCode Loop runs only when explicitly requested; retain OMO Goal disabled.
- For a new page, use 21st to inspect real references and present three distinct layout directions. Wait for the user's selection unless a direction is already selected in this session or repository. Finish one page before starting another.
- Use shadcn for primitives. Keep one spacing, typography, radius, and color system. Avoid decorative gradients, oversized cards, glass panels, floating blobs, empty badges, and invented metrics unless the chosen reference requires them.
- Use Context7 for current technical documentation. If an MCP fails, report it accurately; do not pretend it supplied references or verification.
- Use Chrome DevTools for desktop and mobile inspection. Check real interactions, loading/empty/error states, overflow, keyboard focus, and contrast. Capture screenshots of completed pages.
- Use Supabase Auth and RLS for ownership; enforce authorization on the server/database. Never expose a service-role key or provider credential in the browser.
- This host also runs existing services. Run one build and one browser at a time. Do not alter Docker services, reverse-proxy configuration, backups, or public firewall ports as part of app work.
- Keep development HTTP servers on 127.0.0.1. Use an SSH tunnel for previews until a private phone preview is configured.
- Check Git state before a handoff. Use a feature branch; review changed files and exclude secrets before committing. Pull with --ff-only only when the working tree is clean. Never force-push or reset another machine's work.
- Run checks appropriate to the change. Distinguish installed, connected, and functionally verified tools in reports.

## CampusTable V1 engineering contract
Read START-HERE.md and docs/PRODUCT.md first. Current V1 excludes recruiter, payment, feed, AI, events and task management scope even if older repository guidance mentions them.
Preserve existing Spec Kit integration. Use apps/web for Next.js. Keep secrets out of public Git. Do not alter OpenCode/private services or production infrastructure during implementation. Track tasks and test evidence; no fabricated completion.
