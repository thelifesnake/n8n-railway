# n8n on Railway

Deploy a lightweight version of [n8n](https://n8n.io) on Railway with basic auth.

## How to Deploy

1. Click "Deploy from GitHub" on Railway.
2. Paste this repository link.
3. Set the following environment variables:

```
N8N_BASIC_AUTH_USER=admin
N8N_BASIC_AUTH_PASSWORD=senhaforte
```

4. Access your n8n instance at: `https://<project>.up.railway.app`