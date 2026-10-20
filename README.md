# skill-bridge

An enterprise agentic job-matching and skill-gap platform. The repository is organized as two independent npm projects:

- `frontend/` — Next.js with TypeScript, the App Router, and Tailwind CSS.
- `backend/` — NestJS with TypeScript.

## Requirements

- Node.js (LTS recommended)
- npm

## Start the frontend

```powershell
cd frontend
npm run dev
```

The frontend is available at `http://localhost:3000`.

## Start the backend

```powershell
cd backend
npm run start:dev
```

The backend also defaults to port `3000`. To run both applications at the same time, start the backend on another port:

```powershell
$env:PORT=3001
npm run start:dev
```

## Common commands

Run these from the corresponding project folder:

| Project | Build | Check |
| --- | --- | --- |
| Frontend | `npm run build` | `npm run lint` |
| Backend | `npm run build` | `npm test` |
