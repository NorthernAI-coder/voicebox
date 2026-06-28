# NorthernAI roadmap

Upstream: https://github.com/jamiepine/voicebox
Target product: NorthernAI Voice Studio
License posture: MIT, preserving upstream attribution and license terms.
Commercial model: free local/base tier, paid hosted/team workflows around NorthernAI-owned integration layers.

## Phase 0 - Fork hygiene
- Preserve upstream license and notices.
- Keep this fork syncable with upstream.
- Track NorthernAI-specific changes separately from upstream maintenance.
- Open and maintain an Upstream sync policy issue.

## Phase 1 - Product fit review
- Confirm the repo's core workflow still matches NorthernAI Voice Studio.
- Identify production blockers, missing tests, security concerns, and provider/API terms.
- Write a small integration spike before large rebranding work.

## Phase 2 - NorthernAI productization
- Add NorthernAI naming only after the integration shape is proven.
- Keep the base/local workflow free where feasible.
- Package paid hosted/team workflows as NorthernAI-owned orchestration, collaboration, storage, support, deployment, or reliability layers.

## Phase 3 - Operational readiness
- Define upstream sync cadence.
- Add dependency/security review gates.
- Add release notes for NorthernAI-only changes.
- Document rollback paths for every non-upstream patch.

## Product focus
Voice cloning, dictation, narration, dubbing, and creator audio workflows.