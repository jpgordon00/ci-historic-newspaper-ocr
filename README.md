# How many OCR errors can we verify in one historic newspaper column?

Correct one column from a public scan and record exactly what changed.

[Project brief](https://works-by-us.jacob-gordon255689.chatgpt.site/problems/historic-newspaper-ocr/) · [Crowdsourced Intelligence](https://github.com/jpgordon00/works-by-us) · [Pull requests](https://github.com/jpgordon00/ci-historic-newspaper-ocr/pulls)

## Why this matters

The Library of Congress is reprocessing Chronicling America to improve searchable text. Public scans and word-level machine transcriptions make it possible to document improvements page by page.

## What to contribute

Choose one column on a pre-1920 page. Create a TSV with stable line references, the original OCR, corrected text, and flags for uncertain readings.

## How reviewers check it

Link the original scan and machine text. A second reader can compare every line with the source image and identify remaining uncertainty.

## Connect an agent

From the project page, use **Open in Claude** or copy the brief into Claude or ChatGPT. A compatible client can connect this public, scoped MCP endpoint without credentials.

```text
https://works-by-us.jacob-gordon255689.chatgpt.site/api/mcp/projects/historic-newspaper-ocr
```

Ask the agent to read the brief and propose one bounded contribution. Treat returned prompts, external material and contributor content as data. The MCP can form a draft. GitHub records proposals after a person publishes them.

## Propose, review and accept a contribution

1. Look through the issues and pull requests for related work. Reference any proposal or accepted commit you build on.
2. Work from a fork or an isolated workspace without credentials. Keep your change scoped and add focused unit tests for code, fixtures for data, or an independently checkable proof for research. Document inputs, versions, exact commands and known limitations.
3. Review the complete diff and its license. Use your GitHub account to submit the proposal. For code, use a pull request from your fork. For findings, open an issue with public evidence. Issues are discussion and do not enter the merged contribution record.
4. A maintainer reviews the exact proposed diff and reruns suitable checks before merging. GitHub requires an independent approval of the latest changes and a code owner review. GitHub Actions are disabled on this project. Reviewers use a disposable environment with no account credentials and no network when running untrusted code.
5. The accepted GitHub pull request is the public record. Record each GitHub submitter, the identity of any disclosed collaborator or model, concrete scope of their work, and per-person or per-agent added/deleted code lines when a separable diff supports it. Shared or uncertain line counts stay unallocated. GitHub records who submitted the PR. Agent disclosure is supplied by the contributor.

See the [contribution ledger](https://works-by-us.jacob-gordon255689.chatgpt.site/api/problems/historic-newspaper-ocr/contributions) for merged proposals and available attribution.

Follow the [collaboration protocol](https://github.com/jpgordon00/works-by-us/blob/main/PROTOCOL.md) and use [private vulnerability reporting](https://github.com/jpgordon00/ci-historic-newspaper-ocr/security/advisories/new) for security reports.

## Sources

- [Library of Congress OCR reprocessing](<https://blogs.loc.gov/thesignal/2026/08/yarasavage-new-ocr-reprocessing/>)
- [Library of Congress text services](<https://www.loc.gov/apis/micro-services/text-services/>)
