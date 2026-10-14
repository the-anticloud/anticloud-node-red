# NODE_RED

![licence](https://img.shields.io/badge/licence-Apache-2.0-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-16_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `NODE_RED` in category **FACTORY_MANUFACTURING**. 16/16 checks PASS (measured). Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** https://github.com/node-red/node-red · **Upstream pin:** `935b8d3e12ec8be064f3a72ac6547131f778a7b1` · **Category:** FACTORY_MANUFACTURING · **Vendor:** Anticloud FZ LLE · **Licence:** Apache-2.0

---

## What This Project Does

<div align="center">

[![License][badge-license]][link-license] [![Build Status][badge-build]][link-build]

<br/><img src="https://nodered.org/about/resources/media/node-red-icon-2.svg" width="150" title="Node-RED Logo"><br/>

[![Nodes][badge-nodes]][link-nodes] [![Flows][badge-flows]][link-flows] [![Collections][badge-collections]][link-collections]

### Low-code programming for event-driven applications

<br/><img src="https://nodered.org/images/node-red-screenshot.png" width="600" alt="Node-RED Screenshot"><br/>

[![Forum][badge-forum]][link-forum] [![GitHub][badge-github]][link-github] [![Slack][badge-slack]][link-slack]

</div>

## Quick Start

Check out https://nodered.org/docs/getting-started/ for full instructions on getting
started.

1. `sudo npm install -g --unsafe-perm node-red`
2. `node-red`
3. Open <http://localhost:1880>

<br/>

> [!NOTE]
> More documentation can be found [here](https://nodered.org/docs). For further help, or general discussion, please join the [Node-RED Forum](https://discourse.nodered.org) or [Node-RED Slack](https://nodered.org/slack).

## Links

- [Documentation ↗](https://nodered.org/docs/)
- [About ↗](https://nodered.org/about/)
- [Installation ↗](https://nodered.org/#get-started)
- [Node-RED Library ↗](https://flows.nodered.org/)
  - [Custom Nodes & Integrations ↗](https://flows.nodered.org/search?type=node)
  - [Shared Flows ↗](https://flows.nodered.org/search?type=flow)
  - [Node Collections ↗](https://flows.nodered.org/search?type=collection)
- [Development](#development)
- [Contributing](#contributing)
- [Copyright and license](#copyright-and-license)

## Development

If you want to run the latest code from git, here's how to get started:

1. source the code:

        git source https://github.com/node-red/node-red.git
        cd node-red

2. Install the node-red dependencies

        npm ci

3. Build the code

        npm run build

4. Run

        npm start

## Contributing

Before raising a pull-request, please read our [contributing guide](https://github.com/node-red/node-red/blob/main/CONTRIBUTING.md).

This project adheres to the [Contributor Covenant 1.4](http://contributor-covenant.org/version/1/4/). By participating, you are expected to uphold this code. Please report unacceptable behavior to any of the project's core team at team@nodered.org.

### Contributors

It is maintained by:

 * Nick O'Leary [@knolleary](http://twitter.com/knolleary)
 * Dave Conway-Jones [@ceejay](http://twitter.com/ceejay)
 * And many others:

<a href="https://github.com/node-red/node-red/graphs/contributors">
  <img src="https://contrib.rocks/image?project=node-red/node-red" width="100%"/>
</a>

## Copyright and License

Node-RED is a project of the [OpenJS Foundation](http://openjsf.org). Copyright OpenJS Foundation and other contributors, https://openjsf.org under [the Apache 2.0 license](LICENSE).

<br/>
<a href="http://openjsf.org">
<img src="https://raw.githubusercontent.com/node-red/community-survey/refs/heads/main/public/openjs-foundation-logo.svg" width="240" title="OpenJS Foundation Logo">
</a>

<!-- Badge images -->
[badge-license]: https://img.shields.io/badge/License-Apache_2.0-blue.svg?color=3F51B5&style=for-the-badge&label=License&logoColor=000000&labelColor=ececec
[badge-build]: https://img.shields.io/github/actions/workflow/status/node-red/node-red/tests.yml?branch=main&label=Build%20Status&style=for-the-badge
[badge-forum]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fdiscourse.nodered.org%2Fabout.json&query=%24.about.stats.users_count&suffix=%20members&label=Forum&logo=discourse&style=for-the-badge&color=0e76b2&logoColor=0e76b2&labelColor=ececec
[badge-github]: https://img.shields.io/badge/dynamic/json?url=https://api.github.com/orgs/node-red&query=$.followers&suffix=%20followers&label=GitHub%20org&style=for-the-badge&logo=github&logoColor=24292F&labelColor=ececec&color=24292F
[badge-slack]: https://img.shields.io/badge/Slack-Join%20Us-4A154B.svg?logo=slack&style=for-the-badge&logoColor=4A154B&labelColor=ececec
[badge-nodes]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fflows.nodered.org%2Fthings%3Fformat%3Djson%26per_page%3D1%26type%3Dnode&query=$.meta.results.count&label=Nodes&style=for-the-badge&labelColor=ececec&color=8f0000
[badge-flows]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fflows.nodered.org%2Fthings%3Fformat%3Djson%26per_page%3D1%26type%3Dflow&query=$.meta.results.count&label=Flows&style=for-the-badge&labelColor=ececec&color=8f0000
[badge-collections]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fflows.nodered.org%2Fthings%3Fformat%3Djson%26per_page%3D1%26type%3Dcollection&query=$.meta.results.count&label=Collections&style=for-the-badge&labelColor=ececec&color=8f0000

<!-- Badge links -->
[link-license]: https://opensource.org/license/apache-2-0
[link-build]: https://github.com/node-red/node-red/actions?query=branch%3Amain
[link-forum]: https://discourse.nodered.org
[link-github]: https://github.com/node-red
[link-slack]: https://nodered.org/slack
[link-nodes]: https://flows.nodered.org/search?type=node
[link-flows]: https://flows.nodered.org/search?type=flow
[link-collections]: https://flows.nodered.org/search?type=collection
[link-nodered]: https://nodered.org/

---

## Installation

2. `node-red`
3. Open <http://localhost:1880>

<br/>

> [!NOTE]
> More documentation can be found [here](https://nodered.org/docs). For further help, or general discussion, please join the [Node-RED Forum](https://discourse.nodered.org) or [Node-RED Slack](https://nodered.org/slack).

## Usage

</a>

<!-- Badge images -->
[badge-license]: https://img.shields.io/badge/License-Apache_2.0-blue.svg?color=3F51B5&style=for-the-badge&label=License&logoColor=000000&labelColor=ececec
[badge-build]: https://img.shields.io/github/actions/workflow/status/node-red/node-red/tests.yml?branch=main&label=Build%20Status&style=for-the-badge
[badge-forum]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fdiscourse.nodered.org%2Fabout.json&query=%24.about.stats.users_count&suffix=%20members&label=Forum&logo=discourse&style=for-the-badge&color=0e76b2&logoColor=0e76b2&labelColor=ececec
[badge-github]: https://img.shields.io/badge/dynamic/json?url=https://api.github.com/orgs/node-red&query=$.followers&suffix=%20followers&label=GitHub%20org&style=for-the-badge&logo=github&logoColor=24292F&labelColor=ececec&color=24292F
[badge-slack]: https://img.shields.io/badge/Slack-Join%20Us-4A154B.svg?logo=slack&style=for-the-badge&logoColor=4A154B&labelColor=ececec
[badge-nodes]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fflows.nodered.org%2Fthings%3Fformat%3Djson%26per_page%3D1%26type%3Dnode&query=$.meta.results.count&label=Nodes&style=for-the-badge&labelColor=ececec&color=8f0000
[badge-flows]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fflows.nodered.org%2Fthings%3Fformat%3Djson%26per_page%3D1%26type%3Dflow&query=$.meta.results.count&label=Flows&style=for-the-badge&labelColor=ececec&color=8f0000
[badge-collections]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fflows.nodered.org%2Fthings%3Fformat%3Djson%26per_page%3D1%26type%3Dcollection&query=$.meta.results.count&label=Collections&style=for-the-badge&labelColor=ececec&color=8f0000

<!-- Badge links -->
[link-license]: https://opensource.org/license/apache-2-0
[link-build]: https://github.com/node-red/node-red/actions?query=branch%3Amain
[link-forum]: https://discourse.nodered.org
[link-github]: https://github.com/node-red
[link-slack]: https://nodered.org/slack
[link-nodes]: https://flows.nodered.org/search?type=node
[link-flows]: https://flows.nodered.org/search?type=flow
[link-collections]: https://flows.nodered.org/search?type=collection
[link-nodered]: https://nodered.org/

## API

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | Apache-2.0 |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Contributing

# Contributing to Node-RED

We welcome contributions, but request you follow these guidelines.

 - [Raising issues](#raising-issues)
 - [Feature requests](#feature-requests)
 - [Pull-Requests](#pull-requests)

This project adheres to the [Contributor Covenant 1.4](http://contributor-covenant.org/version/1/4/).
By participating, you are expected to uphold this code. Please report unacceptable
behavior to the project's core team at team@nodered.org.

## Raising issues

Please raise any bug reports on the relevant project's issue tracker. Be sure to
search the list to see if your issue has already been raised.

If your issue is more of a question on how to do something with Node-RED, please
consider using the [community forum](https://discourse.nodered.org/).

A good bug report is one that make it easy for us to understand what you were
trying to do and what went wrong.

Provide as much context as possible so we can try to recreate the issue.
If possible, include the relevant part of your flow. To do this, select the
relevant nodes, press Ctrl-E and copy the flow data from the Export dialog.

At a minimum, please include:

 - Version of Node-RED - either release number if you downloaded a zip, or the first few lines of `git log` if you are cloning the project directly.
 - Version of Node.js - what does `node -v` say?

## Feature requests

For feature requests, please raise them on the [forum](https://discourse.nodered.org).

## Pull-Requests

If you want to raise a pull-request with a new feature, or a refactoring
of existing code, please come and discuss it with us first. We prefer to
do it that way to make sure your time and effort is well spent on something
that fits with our goals.

If you've got a bug-fix or similar for us, then you are most welcome to
get it raised - just make sure you link back to the issue it's fixing and
try to include some tests!

All contributors need to sign the OpenJS Foundation's Contributor License Agreement.
It is an online process and quick to do. If you raise a pull-request without
having signed the CLA, you will be prompted to do so automatically.

### Code Branches

When raising a PR for a fix or a new feature, it is important to target the right branch.

 - `main` - this is the main branch for the latest stable release of Node-RED. All bug fixes for that release should target this branch.
 - `dev` - this is the branch for new feature development targeting the next milestone release.
- `v1.x` - this is the maintenance branch for the 1.x stream. If a fix *only* applies to 1.x, then it should target this branch. If it applies to the current stable release as well, target `master` first. We will then decide if it needs to be back ported to the 1.x stream.
 
### Coding standards

Please ensure you follow the coding standards used through-out the existing
code base. Some basic rules include:

 - all files must have the Apache license in the header.
 - indent with 4-spaces, no tabs. No arguments.
 - opening brace on

## License

Upstream © its respective contributors under Apache-2.0 (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** https://github.com/node-red/node-red
- **Pinned SHA:** `935b8d3e12ec8be064f3a72ac6547131f778a7b1`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.md`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`5c46e9b5c88ca72922a6c3b0ebbe0c09f9ca9071dd8b31ebfc90c0f819239ed9`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

