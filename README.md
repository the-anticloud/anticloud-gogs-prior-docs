# GOGS PRIOR DOCS

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-software_development-lightgrey)

> Anticloud-hardened packaging of the upstream project `GOGS_PRIOR_DOCS` in category **SOFTWARE DEVELOPMENT**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** SOFTWARE DEVELOPMENT · **Upstream:** https://github.com/gogs/gogs · **Upstream pin:** `dbbd717e923694c36f41b0360515b4374bbe6ee0` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

<p>
  <div align="center">
    <img src="docs/images/logo-light.svg#gh-light-mode-only" alt="Gogs">
    <img src="docs/images/logo-dark.svg#gh-dark-mode-only" alt="Gogs">
  </div>
  <div align="center">
    <a href="https://github.com/gogs/gogs/actions?query=branch%3Amain"><img
  src="https://img.shields.io/github/checks-status/gogs/gogs/main?logo=github&style=for-the-badge" alt="GitHub Workflow Status"></a>
    <a href="https://sourcegraph.com/github.com/gogs/gogs"><img
src="https://img.shields.io/badge/view%20on-Sourcegraph-brightgreen.svg?style=for-the-badge&logo=sourcegraph" alt="Sourcegraph"></a>
  </div>
  <div align="center">
    👉 Deploy on DigitalOcean and <a href="https://m.do.co/c/5aeb02268b55">get $200 in free credits</a>!
  </div>
</p>

## 🔮 Vision

The Gogs (`/gɑgz/`) project aims to build a simple, stable and extensible self-hosted Git service that can be set up in the most painless way. With Go, this can be done with an independent binary distribution across all platforms that Go supports, including Linux, macOS, Windows and ARM-based systems.

## 📡 Overview

- Please visit [our home page](https://gogs.io) for user documentation.
- Please refer to [CHANGELOG.md](CHANGELOG.md) for list of changes in each releases.
- Want to try it before doing anything else? Do it [online](https://try.gogs.io/gogs/gogs)!
- Having trouble? Help yourself with [troubleshooting](https://gogs.io/asking/troubleshooting) or ask questions in [Discussions](https://github.com/gogs/gogs/discussions).
- Want to help with localization? Check out the [localization documentation](https://gogs.io/advancing/localization).
- Ready to get hands dirty? Read our [contributing guide](.github/CONTRIBUTING.md).
- Hmm... What about APIs? We have experimental support with [documentation](https://gogs.io/api-reference).

## 💌 Features

- User dashboard, user profile and activity timeline.
- Access projects via SSH, HTTP and HTTPS protocols.
- User, organization and project management.
- project and organization webhooks, including Slack, Discord and Dingtalk.
- project Git hooks, deploy keys and Git LFS.
- project issues, pull requests, wiki, protected branches and collaboration.
- Migrate and mirror projects with wiki from other code hosts.
- Web editor for quick editing project files and wiki.
- Jupyter Notebook and PDF rendering.
- Authentication via SMTP, LDAP, reverse proxy, GitHub.com and GitHub Enterprise with 2FA.
- Customize HTML templates, static files and many others.
- Rich database backend support, including PostgreSQL, MySQL, MariaDB, SQLite3 or any database backend that speaks one of those protocols.
- Have localization over [31 languages](https://crowdin.com/project/gogs).

## 💾 Hardware requirements

- A Raspberry Pi or $5 Digital Ocean Droplet is more than enough to get you started. Some even use 64MB RAM Docker [CaaS](https://www.docker.com/blog/containers-as-a-service-caas/).
- 2 CPU cores and 512MB RAM would be the baseline for teamwork.
- Increase CPU cores when your team size gets significantly larger, memory footprint remains low.

## 💻 Browser support

- Please see [Semantic UI](https://github.com/Semantic-Org/Semantic-UI#browser-support) for specific versions of supported browsers.
- The smallest resolution officially supported is **1024*768**, however the UI may still look right in smaller resolutions, but no promises or fixes.

## 📜 Installation

Please follow [the guide in our documentation](https://gogs.io/getting-started/installation).

### Deploy to cloud

- [Cloudron](https://www.cloudron.io/store/gogs.html)
- [YunoHost](https://github.com/YunoHost-Apps/gogs_ynh)
- [alwaysdata](https://www.alwaysdata.com/en/marketplace/gogs/)

### Tutorials

- [Private Git Web Portal in Raspberry PI With Gogs](https://peppe8o.com/private-git-web-portal-in-raspberry-pi-with-gogs/)
- [How To Set Up Gogs on Ubuntu 14.04](https://www.digitalocean.com/community/tutorials/how-to-set-up-gogs-on-ubuntu-14-04)
- [Run your own GitHub-like service with the help of Docker](https://blog.hypriot.com/post/run-your-own-github-like-service-with-docker/)
- [Dockerized Gogs git server and alpine postgres in 20 minutes or less](https://garthwaite.org/docker-gogs.html)
- [Host Your Own Private GitHub with Gogs](https://eladnava.com/host-your-own-private-github-with-gogs-io/)
- [使用 Gogs 搭建自己的 Git 服务器](https://blog.mynook.info/post/host-your-own-git-server-using-gogs/) (Chinese)
- [阿里云上 Ubuntu 14.04 64 位安装 Gogs](https://my.oschina.net/luyao/blog/375654) (Chinese)
- [Installing Gogs on FreeBSD](https://www.codejam.info/2015/03/installing-gogs-on-freebsd.html)
- [How to install Gogs on a Linux Server (DigitalOcean)](https://www.youtube.com/watch?v=deSfX0gqefE)

## 📦 Software, service and product support

- [Jenkins](https://plugins.jenkins.io/gogs-webhook/) (CI)
- [Puppet](https://forge.puppet.com/modules/Siteminds/gogs) (IT)
- [Synology](https://www.synology.com) (Docker)
- [Syncloud](https://syncloud.org/) (App Store)

## 🙇‍♂️ Acknowledgments

<p>This project is proudly supported by:</p>
<p>
  <a href="https://m.do.co/c/5aeb02268b55">
    <img src="https://opensource.nyc3.cdn.digitaloceanspaces.com/attribution/assets/SVG/DO_Logo_horizontal_blue.svg" width="201px">
  </a>
</p>

Other acknowledgments:

- Thanks [Egon Elbre](https://twitter.com/egonelbre) for designing the original version of the logo.
- Thanks [Mintlify](https://mintlify.com) for sponsoring open source documentation plan.
- Thanks [Crowdin](https://crowdin.com) for sponsoring open source translation plan.
- Thanks [Buildkite](https://buildkite.com) for sponsoring open source CI/CD plan.

## 👋 Contributors

- See [contributors page](https://github.com/gogs/gogs/graphs/contributors) for top 100 contributors.
- See [TRANSLATORS](conf/locale/TRANSLATORS) for public list of translators.

## ⚖️ License

This project is under the MIT License. See the [LICENSE](https://github.com/gogs/gogs/blob/main/LICENSE) file for the full license text.

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Node.js / npm** (manifests: package.json, pnpm-lock.yaml; scanned in UPSTREAM_CLONE)
- Top-level source layout: `cmd/`, `conf/`, `docker/`, `docker-next/`, `internal/`, `public/`, `scripts/`, `templates/`, `web/`
- Snapshot size: **2615 files**, **103535 lines of code** (measured; see Benchmarks)
- Primary languages: `.png` (895), `.go` (302), `(none)` (216), `.js` (172), `.bcmap` (168), `.tmpl` (138)
- Upstream commit pinned for this packaging: `dbbd717e923694c36f41b0360515b4374bbe6ee0`

---

## Installation

No installation section was found in the upstream readme, so the commands below are generated from the manifests detected in this project directory.

```sh
# from this project directory
npm install        # or: npm ci
npm run build      # if a build script is declared
```

Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

- 2 CPU cores and 512MB RAM would be the baseline for teamwork.
- Increase CPU cores when your team size gets significantly larger, memory footprint remains low.

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

- Please refer to [CHANGELOG.md](CHANGELOG.md) for list of changes in each releases.
- Want to try it before doing anything else? Do it [online](https://try.gogs.io/gogs/gogs)!
- Having trouble? Help yourself with [troubleshooting](https://gogs.io/asking/troubleshooting) or ask questions in [Discussions](https://github.com/gogs/gogs/discussions).
- Want to help with localization? Check out the [localization documentation](https://gogs.io/advancing/localization).
- Ready to get hands dirty? Read our [contributing guide](.github/CONTRIBUTING.md).
- Hmm... What about APIs? We have experimental support with [documentation](https://gogs.io/api-reference).

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Node.js / npm |
| Manifests detected | package.json, pnpm-lock.yaml |
| Files in snapshot | 2615 |
| Lines of code | 103535 |
| Dependency references | 183 |
| Dependencies by ecosystem | go: 143, npm: 40 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| go | github.com/cockroachdb/errors | v1.13.0 | go.mod |
| go | github.com/derision-test/go-mockgen/v2 | v2.1.1 | go.mod |
| go | github.com/editorconfig/editorconfig-core-go/v2 | v2.6.4 | go.mod |
| go | github.com/fatih/color | v1.18.0 | go.mod |
| go | github.com/flamego/binding | v1.3.0 | go.mod |
| go | github.com/flamego/cache | v1.5.1 | go.mod |
| go | github.com/flamego/captcha | v1.3.0 | go.mod |
| go | github.com/flamego/flamego | v1.13.0 | go.mod |
| go | github.com/flamego/session | v1.3.0 | go.mod |
| go | github.com/flamego/validator | v1.0.0 | go.mod |
| go | github.com/glebarez/go-sqlite | v1.21.2 | go.mod |
| go | github.com/glebarez/sqlite | v1.11.0 | go.mod |
| go | github.com/go-ldap/ldap/v3 | v3.4.13 | go.mod |
| go | github.com/go-macaron/binding | v1.2.0 | go.mod |
| go | github.com/go-macaron/cache | v0.0.0-20190810181446-10f7c57e2196 | go.mod |
| ... | (168 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- `Dockerfile`
- `package.json`

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `.github/CONTRIBUTING.md`:*

# Welcome to Gogs contributing guide

Thank you for investing your time in contributing to our projects!

Read our [Code of Conduct](https://go.dev/conduct) to keep our community approachable and respectable.

In this guide you will get an overview of the contribution workflow from opening an issue, creating a PR, reviewing, and merging the PR.

Use the table of contents icon <img src="https://github.com/github/docs/raw/50561895328b8f369694973252127b7d93899d83/assets/images/table-of-contents.png" width="25" height="25" /> on the top left corner of this document to get to a specific section of this guide quickly.

## New contributor guide

To get an overview of the project, read the [README](/README.md). Here are some resources to help you get started with open source contributions:

- [Finding ways to contribute to open source on GitHub](https://docs.github.com/en/get-started/exploring-projects-on-github/finding-ways-to-contribute-to-open-source-on-github)
- [Set up Git](https://docs.github.com/en/get-started/quickstart/set-up-git)
- [GitHub flow](https://docs.github.com/en/get-started/quickstart/github-flow)
- [Collaborating with pull requests](https://docs.github.com/en/github/collaborating-with-pull-requests)
- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
- [Talk, then code](https://www.craft.do/s/kyHVs6OoE4Dj5V)

In addition to the general guides with open source contributions, you would also need to:

- Have basic knowledge about web applications development, database management systems and programming in [Go](https://go.dev/).
- Have a working local development setup with a reasonable good IDE or editor like [Visual Studio Code](https://code.visualstudio.com/docs/languages/go), [GoLand](https://www.jetbrains.com/go/) or [Vim](https://github.com/fatih/vim-go).
- [Set up your development environment](/docs/dev/local_development.md).

## Issues

### Ask for help

Before opening an issue, please make sure the problem you're encountering isn't already addressed on the [Troubleshooting](https://gogs.io/asking/troubleshooting) and [FAQs](https://gogs.io/asking/faq) pages.

### Create a new issue

- For questions, ask in [Discussions](https://github.com/gogs/gogs/discussions).
- [Check to make sure](https://docs.github.com/en/github/searching-for-information-on-github/searching-on-github/searching-issues-and-pull-requests#search-by-the-title-body-or-comments) someone hasn't already opened a similar [issue](https://github.co

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
Copyright (c) The Gogs Authors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `GOGS_PRIOR_DOCS` (category: SOFTWARE DEVELOPMENT)
- **Upstream URL:** https://github.com/gogs/gogs
- **Pinned commit (SHA):** `dbbd717e923694c36f41b0360515b4374bbe6ee0`
- **Branch:** main
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`a3a6f01d780b2f2e67b24dff6f909356a7d480314deb16a22bd2b85b0b1af6a6`.

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

