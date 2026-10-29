# Workspace applications

This workspace contains three separately organized projects:

| Folder | Application | Status |
|---|---|---|
| [`bmsit-college`](./bmsit-college/) | BMSIT&M static college website | Static HTML/CSS/JavaScript site |
| [`career-compass`](./career-compass/) | CareerCompass AI | Next.js application and resume-processing preview |
| [`medicore-360-legacy`](./medicore-360-legacy/) | MediCore 360 healthcare project files | Legacy schema and documentation; not a complete runnable app |

## Run the college website

Open a terminal in `bmsit-college` and run:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Run CareerCompass

Open a terminal in `career-compass` and run:

```powershell
npm install
npm run dev
```

Use `npm test`, `npm run lint`, and `npm run typecheck` from that folder for checks.

The MediCore folder is separated for reference. It contains healthcare schema artifacts, not a fully implemented third web application.

The root `AGENTS.md` and `.gitignore` apply across the workspace. CareerCompass has its own `package.json`, lockfile, and installed dependencies inside its folder.
