# q-id.app

App Clip hosting for Disco Q-ID authentication demo.

## Setup

This repo is deployed via GitHub Pages to serve the Apple App Site Association (AASA) file required for App Clip invocation.

### DNS Configuration

Add these A records to your domain:

| Type | Name | Value |
|------|------|-------|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |

### GitHub Pages Settings

1. Settings → Pages
2. Source: Deploy from branch
3. Branch: main, folder: / (root)
4. Custom domain: q-id.app
5. Enforce HTTPS: checked

## Files

- `/.well-known/apple-app-site-association` - AASA file for App Clip
- `/index.html` - Landing page with App Store link
