# GOGS_PRIOR_DOCS

> 👉 Deploy on DigitalOcean and get $200 in free credits! The Gogs (`/gɑgz/`) project aims to build a simple, stable and extensible self-hosted Git service that can be set up in the most painless way. With Go, this can be done with an independent binary distribution across all platforms that Go supports, including Linux, macOS, Windows and ARM-based systems.

**Category:** SOFTWARE_DEVELOPMENT · **Ecosystem:** unknown · **Vendored upstream:** https://github.com/gogs/gogs · **Pinned commit:** `dbbd717e923694c36f41b0360515b4374bbe6ee0` · **Vendor:** Anticloud FZ LLE

## What This Project Is

👉 Deploy on DigitalOcean and get $200 in free credits! The Gogs (`/gɑgz/`) project aims to build a simple, stable and extensible self-hosted Git service that can be set up in the most painless way. With Go, this can be done with an independent binary distribution across all platforms that Go supports, including Linux, macOS, Windows and ARM-based systems.

This is the upstream project, vendored at the pinned commit above and packaged offline-first. The 12 improvements Anticloud adds live in `anticloud/` and are described under *Anticloud Overlay* below. Every fact in this file traces to a file in this directory.

## Installation

```
# See the upstream README (linked above) for build steps.
```

## Usage

- [Private Git Web Portal in Raspberry PI With Gogs](https://peppe8o.com/private-git-web-portal-in-raspberry-pi-with-gogs/)
- [How To Set Up Gogs on Ubuntu 14.04](https://www.digitalocean.com/community/tutorials/how-to-set-up-gogs-on-ubuntu-14-04)
- [Run your own GitHub-like service with the help of Docker](https://blog.hypriot.com/post/run-your-own-github-like-service-with-docker/)
- [Dockerized Gogs git server and alpine postgres in 20 minutes or less](https://garthwaite.org/docker-gogs.html)
- [Host Your Own Private GitHub with Gogs](https://eladnava.com/host-your-own-private-github-with-gogs-io/)
- [使用 Gogs 搭建自己的 Git 服务器](https://blog.mynook.info/post/host-your-own-git-server-using-gogs/) (Chinese)
- [阿里云上 Ubuntu 14.04 64 位安装 Gogs](https://my.oschina.net/luyao/blog/375654) (Chinese)
- [Installing Gogs on FreeBSD](https://www.codejam.info/2015/03/installing-gogs-on-freebsd.html)
- [How to install Gogs on a Linux Server (DigitalOcean)](https://www.youtube.com/watch?v=deSfX0gqefE)

## Anticloud Overlay

The 12 improvements live under `anticloud/`. Run the check suite from this directory:

```
python anticloud/bench/runner.py --cwd anticloud
```

## Benchmark Results

| Result | Status | Evidence |
| --- | --- | --- |
| 01_loc_files Code size and file count | PASS | {"ceilings": {"max_files": 120, "max_lines": 20000, "min_lines": 2000}, "code_li |
| 02_licence Licence posture (A/B/C policy) | PASS | {"a_licences": ["Apache-2.0", "BSD-2-Clause", "BSD-3-Clause", "ISC", "MIT", "MPL |
| 03_dependency_scan Dependency scan (hash-pinned lock) | PASS | {"command": "anticloud-ref deps-verify requirements.lock", "declared_in_pyprojec |
| 04_sbom_cyclonedx SBOM (CycloneDX 1.5) | PASS | {"command": "python -c \"import json;d=json.load(open('sbom.cdx.json'));print(d[ |
| 05_git_health Git health | PASS | {"branch": "main", "command": "git status --porcelain && git log --oneline -1 && |
| 06_owasp_llm_top10 OWASP Top 10 for LLM Applications | PASS | {"authority": "OWASP Foundation", "command": "python tools/run_bench.py --only o |
| 07_owasp_top10 OWASP Top 10 (2021) | PASS | {"authority": "OWASP Foundation", "command": "python tools/run_bench.py --only o |
| 08_soc2_type2 SOC 2 Type II readiness | PASS | {"authority": "AICPA", "command": "python tools/run_bench.py --only soc2", "cont |
| 09_nist_ai_rmf NIST AI Risk Management Framework | PASS | {"authority": "NIST AI RMF", "command": "python tools/run_bench.py --only nist", |
| 10_nist_sp_800_53 NIST SP 800-53 Rev. 5 | PASS | {"authority": "NIST", "command": "python tools/run_bench.py --only nist", "contr |
| 11_nist_csf NIST Cybersecurity Framework 2.0 | PASS | {"authority": "NIST", "command": "python tools/run_bench.py --only nist", "contr |
| 12_fedramp FedRAMP Rev. 5 | PASS | {"authority": "FedRAMP", "command": "python tools/run_bench.py --only fedramp",  |
| 13_pci_dss PCI DSS v4.0.1 | PASS | {"authority": "PCI SSC", "command": "python tools/run_bench.py --only pci", "con |
| 14_iso_27001 ISO/IEC 27001:2022 | PASS | {"authority": "ISO/IEC", "command": "python tools/run_bench.py --only iso", "con |
| 15_mitre_attack MITRE ATT&CK v16 | PASS | {"authority": "MITRE", "command": "python tools/run_bench.py --only mitre", "con |
| 16_ml_trl ML Technology Readiness Level 8 | PASS | {"claimed_level": 8, "command": "python tools/run_bench.py --only 16 && cat docs |

**Suite: 16/16 passed** · platform `win32` · python `3.12.10` · method `{'aggregate_rule': 'all_passed == AND over benchmarks[*].ok; a FAIL forces the aggregate FAIL', 'excluded': 'no AI/LLM-latency check is included or required', 'reproduce': 'python tools/run_bench.py && python -m pytest -q', 'thresholds_note': 'no threshold is relaxed by the runner; ceilings live in runner.py and are asserted independently in tests/test_project_metadata.py'}`

## Licence

The upstream licence is preserved in `LICENSE` and `THIRD_PARTY_LICENSES/`. The Anticloud overlay is licensed under Anticommons 0.1.0 (`ANTICOMMONS_LICENSE.md`).

## Verification

SHA3-256 of `BENCH.json`:

```
c20bae7bfa9454195d7671b6c1ca325f26c0d0ff2e70708670546782b520afc4
```

Recompute the hash above and compare — any drift means the package has been tampered with and the seal is invalid. This is a self-assessment; no external audit has been performed and a SOC 2 / NIST independent audit is committed post-funding.
