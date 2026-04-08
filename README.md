## Student Vault - Vercel Deployment

This project is deployed as a static site.

### 1. Install Vercel CLI

```powershell
npm install -g vercel
```

### 2. Deploy from this folder

```powershell
vercel
```

During prompts:
- Set up and deploy: `Y`
- Scope: choose your account
- Link to existing project: `N` (for first deployment)
- Project name: choose any name
- Directory: `./`

### 3. Production deploy

```powershell
vercel --prod
```

### Notes
- Entry file is `index.html`.
- Vercel config is in `vercel.json`.
