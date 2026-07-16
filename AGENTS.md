# Kulus legal-site agent guide

This repository contains the standalone public legal pages for Kulus. It is static HTML, but its content governs privacy and health-data expectations.

## Read first

Read this file, the README, and `/Users/joseph.malone/ios_code/hamumu-ios/ECOSYSTEM.md` when a change affects shared Kulus statements. The organiser Kulus handoff owns current project status.

## Working rules

- Preserve dirty user work and keep changes limited to the requested legal-page behavior.
- Do not put personal data, credentials, tokens, or internal operational details in public pages.
- Treat privacy, account-deletion, retention, sharing, and contact language as product or legal-owner decisions. Do not invent policy commitments.
- Keep public claims consistent with the current product and backend behavior. Escalate conflicts instead of silently changing either side.
- Preserve accessible, semantic HTML and verify redirects and links after edits.

## Completion

There is no build step. Validate changed HTML with an available local checker or focused inspection, run `git diff --check`, then commit only intended files and push the configured branch when safe.
