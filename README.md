# Bly — release snapshots

**A career agent that runs your job search out of your own inbox, on your own machine.**
Free, open source, local-first.

```sh
npm i -g @yellow-pine/bly
```

- Website: **[bly.fyi](https://bly.fyi)**
- Package: **[`@yellow-pine/bly`](https://www.npmjs.com/package/@yellow-pine/bly)** (Apache-2.0)

## What this repository is

This repo holds **one commit per released version** of Bly. Each release's full source lands
here, tagged, and `npm publish` runs from here — which is also what lets npm generate
[provenance](https://docs.npmjs.com/generating-provenance-statements) attestations, since those
are only produced for public source repositories.

Development happens in a private monorepo alongside its sibling product, so this repo carries no
development history, no issues and no pull requests. **Open source, but not open development:**
every released version's source is public under Apache-2.0; the day-to-day history is not.

Bly was developed in the open for a period in 2026 and moved back into the monorepo on
2026-09-12, because developing it beside its sibling was worth more than a separate repo was.

## Reporting something

Security issues: please use the contact address on [bly.fyi](https://bly.fyi). Because pull
requests are not part of this repo's workflow, patches are best sent as a description of the
change rather than as a branch.
