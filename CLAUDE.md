# jointheailab.ai

The AI Lab landing page. This is the **body** (code). The **brain** (planning, decisions, event details, content) lives at:

```
~/Developer/app.avry/the-ai-lab/
```

Read `the-ai-lab/HANDOFF.md` for session state, `the-ai-lab/the-ai-lab.md` for event details, `the-ai-lab/INDEX.md` for full context.

## Dynamic Redirect

`vercel.json` contains a `/go` redirect (302) to the Telegram invite link. This is what QR codes on printed flyers encode (`jointheailab.ai/go`). The destination can be changed anytime by editing vercel.json and pushing - Vercel auto-deploys.

## Deploy

Hosted on Vercel. Push to GitHub `main` branch triggers auto-deploy.
Domain DNS: Namecheap (registrar-servers.com), root A record -> Vercel.
