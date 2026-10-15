### Third-party dependencies
- [ ] This PR adds or upgrades a third-party dependency (if not, ignore the rest)
- [ ] Licence checked against the wiki licence policy: <SPDX id> — allowed for <distributed | server-only | test-only>
- [ ] Maintained: release in the last 12 months, no open critical advisory, more than one maintainer or a backing org
- [ ] Alternatives considered: not already covered by Spring / Angular / an existing dependency / ~50 lines of our own code
- [ ] Frontend only: bundle impact checked (`--stats-json`), and it is tree-shakeable or lazy-loaded
- [ ] Backend only: version comes from the BOM `de.yolawo:platform` if the BOM already manages it; no version pinned in the service otherwise
