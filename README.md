# docs

My docs site, built with [Mintlify](https://mintlify.com).

## local preview

```bash
npm i -g mint
mint dev
```

Runs at http://localhost:3000. Run this from the repo root (where `docs.json` is).

If stuff acts weird: `mint update`. 404 on a page usually means `docs.json` is wrong or you're in the wrong folder.

## deploy

Hooked up through Mintlify's GitHub app — push to `main` and it deploys. Settings: [Mintlify dashboard](https://dashboard.mintlify.com/settings/organization/github-app)

More: https://mintlify.com/docs
