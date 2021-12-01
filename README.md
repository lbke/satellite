# satellite
A tiny server to do anything you can't do without a tiny server

## Why?

- Next.js handles web pages and SERVERLESS API routes
- Next.js middleware handle proxy features using v8 engine
- `ncc` handles building scripts written in TS
- But nobody handles long-lived jobs:
  - Database daily cleanups
  - Cron jobs of all kind
  - Data computation jobs etc.
  - Basically anything you can't do with a serverless API

Current workaroud is using tools such as GitHub action. But we want to limit the number of 3rd party service we use.

Satellite aims at solving this issue.

## Hosting

We need a serverfull alternative to Vercel:
eg https://railway.app/about
