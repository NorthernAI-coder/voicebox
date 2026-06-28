# Upstream sync policy

This fork tracks https://github.com/jamiepine/voicebox.

## Local remote setup
`ash
git remote add upstream https://github.com/jamiepine/voicebox.git
git fetch upstream
`

## Sync cadence
- Check upstream weekly while this repo is actively evaluated.
- Fast-forward cleanly when possible.
- Prefer small NorthernAI commits so upstream merges stay reviewable.
- Re-run the repo's own tests/build after each upstream sync.

## Suggested sync flow
`ash
git checkout main
git fetch origin
git fetch upstream
git merge --ff-only upstream/main
git push origin main
`

If fast-forward is not possible, create a sync branch and resolve conflicts there before updating $branch.

## Commercial guardrails
- Keep upstream license and notices intact.
- Do not remove upstream attribution.
- Keep paid hosted/team features in NorthernAI-owned layers unless the upstream license and contribution policy clearly permit deeper changes.