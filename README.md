# Enterprise SEO Communication Translator

Version 0.1.0. Built for Jose Ponce Jr.

A text-first skill for making SEO and AI visibility work understandable to business readers. It translates meaning and decision relevance, not just technical terms into corporate-sounding synonyms.

## What it does

- **Translate:** explains what a phrase may communicate, gives better wording, and states any material evidence condition.
- **Convert:** rewrites a report or update for leadership, with a separate change record and section-coverage check.
- **Audit:** reviews one page or supplied excerpt and shows exact wording replacements, priorities, and missing business explanations.

It preserves facts, scope, tense, status, and commitments. It does not manufacture results, rename paid or owned content as independent validation, or turn proposed work into completed work.

## Use it here

Ask the assistant to use `enterprise-seo-communication`, then supply the text or document. Helpful context is the audience, purpose, desired length, and whether the output is internal or intended for sharing.

Examples:

> Use enterprise-seo-communication to translate this for a marketing VP: We are migrating Yoast to RankMath.

> Use enterprise-seo-communication to convert this audit into a short executive update. Keep completed work, proposals, and decisions separate.

> Use enterprise-seo-communication to audit this page for enterprise buyers. Show the original wording, what they may hear, what to say instead, and why.

On hosts supporting skill slash commands, `/enterprise-seo-communication` is an alternative entry point.

## Package use elsewhere

Keep `SKILL.md`, `references/`, and `templates/` together. Load `SKILL.md` through the host's supported skill import or file-reading mechanism. The skill routes the assistant to the required reference and template files. If the host supports ZIP skill uploads, use the packaged folder rather than uploading `SKILL.md` alone.

No executable code, API keys, additional account, or package installation is required for pasted text. File and URL inputs depend on the host's permitted reading tools. A page excerpt can be audited without browser access. This build does not establish compatibility with every host or with Claude's current importer.

## Important boundaries

This is a writing assistant, not a technical SEO certification, live ranking measurement, full-site crawler, or publishing tool. It produces drafts for authorized review. It does not send, publish, change accounts, or approve client wording.

The portable package contains generalized instructions and fictional teaching examples. It excludes private meeting transcripts, stakeholder profiles, client budgets, and source-corpus paths. The original research and PRD remain in the owner's private workspace.

Preserve the original source when converting a document. Credentials and unauthorized other-client information must not be repeated, including in original-text fields or change records.

## Files

- `SKILL.md`: entry point and workflow.
- `references/business-translation.md`: audience questions, business explanations, terminology.
- `references/meaning-and-evidence.md`: fact preservation, claim status, privacy, source coverage.
- `references/worked-examples.md`: complete phrase, document, and page examples.
- `references/acceptance-tests.md`: maintenance scenarios and acceptance rules, not test results.
- `templates/phrase.md`, `templates/document.md`, `templates/page-audit.md`: output formats.

## Ownership

Proprietary. Redistribution requires the owner's permission. Delivery to Jose is not distribution to colleagues or clients.
