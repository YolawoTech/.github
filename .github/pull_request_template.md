<!-- 2–4 sentences: what was wrong or what this adds, what changed, where it stands. The diff shows the lines; say what the reviewer cannot read off it. -->

<!-- Link what this PR resolves, if anything: `Closes YolawoTech/projects#N` (board ticket), `Closes YolawoTech/bugs#N` (bug or debt item) or a Trello card URL. -->

<!-- Optional, only when true: ## Unresolved (open findings or a decision for the reviewer) · ## Manual steps (exact command) · ## Not in here (surprising missing scope) · a screenshot for UI changes -->

<details><summary>Third-party dependencies (tick only if this PR adds or upgrades one)</summary>

- [ ] This PR adds or upgrades a third-party dependency (if not, ignore the rest)
- [ ] Licence checked against the [wiki licence policy](https://github.com/YolawoTech/wiki/blob/main/operations/open-source-license-compliance.md#licence-policy): [SPDX id] — allowed for [distributed | server-only | test-only]
- [ ] Maintained: release in the last 12 months, no open critical advisory, more than one maintainer or a backing org
- [ ] Alternatives considered: not already covered by Spring / Angular / an existing dependency / ~50 lines of our own code
- [ ] Frontend only: bundle impact checked (`--stats-json`), and it is tree-shakeable or lazy-loaded
- [ ] Backend only: version comes from the BOM `de.yolawo:platform` if the BOM already manages it; no version pinned in the service otherwise

</details>
