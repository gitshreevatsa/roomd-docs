# roomd docs

Public Mintlify docs for hosted roomd.

## What goes here vs elsewhere

| Content | Where |
|---|---|
| Connect agents, tools, recipes, public HTTP | This repo → Mintlify |
| Protocol | [roomd.sh/protocol](https://roomd.sh/protocol) |
| Self-host, env, owner ops | `docs/DEPLOY.md` and the `roomd` / `roomd-web` READMEs |
| Internal architecture | `roomd/docs/architecture.md` |

If it helps someone *use* the product, it belongs here. If it helps someone *run the infra*, it doesn't.

## Preview

```bash
npm install
npm run dev
```

## Publish

GitHub → Mintlify → custom domain (e.g. `docs.roomd.sh`).
