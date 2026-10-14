# SIMULATOR

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-automotive-lightgrey)

> Anticloud-hardened packaging of the upstream project `SIMULATOR` in category **AUTOMOTIVE**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** AUTOMOTIVE · **Upstream:** https://github.com/lgsvl/simulator · **Upstream pin:** `28244ba27ca66e34e2f48ce30812d4f034e39c0b` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

<h1 align="center">SVL Simulator:  An Autonomous Vehicle Simulator</h1>

<div align="center">
<a href="https://github.com/lgsvl/simulator/releases/latest">
<img src="https://img.shields.io/github/release-pre/lgsvl/simulator.svg" alt="Github release" /></a>
<a href="">
<img src="https://img.shields.io/github/downloads/lgsvl/simulator/total.svg" alt="Release downloads" /></a>
</div>
<div align="center">
  <h4>
    <a href="https://svlsimulator.com" style="text-decoration: none">
    Website</a>
    <span> | </span>
    <a href="https://svlsimulator.com/docs" style="text-decoration: none">
    Documentation</a>
    <span> | </span>
    <a href="https://github.com/lgsvl/simulator/releases/latest" style="text-decoration: none">
    Download</a>
  </h4>
</div>

## Sunsetting SVL Simulator

### LG has made the difficult decision to suspend active development of SVL Simulator, as of January 1, 2022.

There are no plans for any new or bugfix releases of SVL Simulator in 2022. There will be no new source code changes pushed to GitHub, and there will be no reviews or merging of Pull Requests submitted on GitHub for SVL Simulator or any of its related plug-ins. There will be no new simulator assets built and shared nor updates made to existing assets by the SVL Simulator team.

We will make a reasonable effort to keep the [wise.svlsimulator.com](https://wise.svlsimulator.com) website up and running through at least Thursday, June 30, 2022, and will also maintain the [SVLSimulator.com](https://SVLSimulator.com) web site including the [simulator documentation](https://www.svlsimulator.com/docs/) pages through at least Thursday, June 30, 2022.

At this time we do not plan to remove the [SVL Simulator source code](https://github.com/lgsvl/simulator) (and related plug-in) projects from GitHub. The open source project and source code will remain available for anyone who wants to build (or modify) SVL Simulator.

We apologize for any inconvenience this may cause and appreciate your understanding.

Sincerely,

The SVL Simulator team

<br/>

### Questions

##### **Q: Will SVL Simulator run locally without the [wise.svlsimulator.com](https://wise.svlsimulator.com) web site?**

A: The latest released version of SVL (2021.3) requires the use of the WISE (web user interface) cloud service to download assets, configure simulation clusters, and create and launch simulations. It may be possible to remove this dependency (e.g. in a fork; see below) and then build and launch a local simulator instance.

##### **Q: Will LG release the source code for the WISE (web user interface) cloud service?**

A: There are no plans at this time to release the source code for WISE.

##### **Q: Would LG be interested in transferring the SVL Simulator project to someone interested in taking over the project?**

A: There are no plans at this time to transfer the SVL Simulator project (or the WISE cloud service).

##### **Q: Will the Simulator Software License Agreement be changed?**

A: There are no plans at this time to change the [Simulator Software License Agreement](https://github.com/lgsvl/simulator/blob/master/LICENSE).

##### **Q: Can users share source code changes and forks of SVL Simulator?**

A: As a GitHub project, anyone is able to create their own fork; in fact, there are already over 500 such forks of the [SVL Simulator project](https://github.com/lgsvl/simulator). Users can then make changes and even submit pull requests back to the original (parent) project. While we have no plans to review or merge such changes into the main project, users are free to review open PRs and create their own local build from their own or any other public fork.

##### **Q: Can users share new builds of SVL Simulator?**

A: The [Simulator Software License Agreement](https://github.com/lgsvl/simulator/blob/master/LICENSE) allows you to “modify or create derivative works of the Licensed Materials” and only restricts their commercial use. Therefore, it is ok for users to share new builds of SVL Simulator as long as such builds are not sold or otherwise used for commercial purposes.

##### **Q: What about the SVL Simulator Premium product and/or cloud simulation service?**

A: There are no plans at this time to offer a SVL Simulator Premium product or cloud service.

##### **Q: Can users still post technical questions on GitHub?**

A: Technical questions may be posted to the [SVL Simulator Issues](https://github.com/lgsvl/simulator/issues) page on GitHub but may not be answered by the SVL Simulator team. We encourage users to help each other with questions or issues that are posted.

##### **Q: What if there are other questions not addressed in this document?**

A: Other questions may be posted to the [SVL Simulator Issues](https://github.com/lgsvl/simulator/issues) page on GitHub.

<br/>

------ 
# Project README

## Stay Informed

Check out our latest [news](https://www.svlsimulator.com/news/) and subscribe to our [mailing list](http://eepurl.com/htlRjH) to get the latest updates.

## Introduction

LG Electronics America R&D Lab has developed an HDRP Unity-based multi-robot simulator for autonomous vehicle developers. 
We provide an out-of-the-box solution which can meet the needs of developers wishing to focus on testing their autonomous vehicle algorithms. 
It currently has integration with The Autoware Foundation's [Autoware.auto](https://gitlab.com/autowarefoundation/autoware.auto/AutowareAuto) and Baidu's [Apollo](https://github.com/ApolloAuto/apollo) platforms, can generate HD maps, and can be immediately used for testing and validation of a whole system with little need for custom integrations. 
We hope to build a collaborative community among robotics and autonomous vehicle developers by open sourcing our efforts. 

*To use the simulator with Apollo 6.0 or master, first download the simulator binary, then follow our [Running with latest Apollo](https://www.svlsimulator.com/docs/system-under-test/apollo-master-instructions/) docs.*

*(excerpt; full text in `UPSTREAM_CLONE/`)*

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Unknown (no standard manifest detected)** (manifests: none detected; scanned in UPSTREAM_CLONE)
- Top-level source layout: `Assets/`, `Docker/`, `Jenkins/`, `Packages/`, `ProjectSettings/`
- Snapshot size: **7292 files**, **463561 lines of code** (measured; see Benchmarks)
- Primary languages: `.meta` (3910), `.cs` (1963), `.png` (290), `.hlsl` (256), `.shader` (118), `.prefab` (115)
- Upstream commit pinned for this packaging: `28244ba27ca66e34e2f48ce30812d4f034e39c0b`

---

## Installation

We apologize for any inconvenience this may cause and appreciate your understanding.

Sincerely,

The SVL Simulator team

<br/>

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

Sincerely,

The SVL Simulator team

<br/>

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

<span> | </span>
    <a href="https://github.com/lgsvl/simulator/releases/latest" style="text-decoration: none">
    Download</a>
  </h4>
</div>

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Unknown (no standard manifest detected) |
| Manifests detected | none |
| Files in snapshot | 7292 |
| Lines of code | 463561 |
| Dependency references | 22 |
| Dependencies by ecosystem | go: 17, native: 1, npm: 4 |
| Upstream license | No license file present in the upstream snapshot |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| npm | com.unity.render-pipelines.core | 10.7.0 | Packages/com.unity.render-pipelines.high-definition/package.json |
| npm | com.unity.shadergraph | 10.7.0 | Packages/com.unity.render-pipelines.high-definition/package.json |
| npm | com.unity.visualeffectgraph | 10.7.0 | Packages/com.unity.render-pipelines.high-definition/package.json |
| npm | com.unity.render-pipelines.high-definition-config | 10.7.0 | Packages/com.unity.render-pipelines.high-definition/package.json |
| native | OpenCV | - | Assets/Plugins/LineSegmentDetector/source/CMakeLists.txt |
| go | github.com/davecgh/go-spew | v1.1.1 | Assets/Plugins/DockerDotNet/tools/specgen/go.mod |
| go | github.com/docker/docker | v20.10.2+incompatible | Assets/Plugins/DockerDotNet/tools/specgen/go.mod |
| go | github.com/docker/go-connections | v0.4.0 | Assets/Plugins/DockerDotNet/tools/specgen/go.mod |
| go | github.com/docker/go-units | v0.4.0 | Assets/Plugins/DockerDotNet/tools/specgen/go.mod |
| go | github.com/gogo/protobuf | v1.3.1 | Assets/Plugins/DockerDotNet/tools/specgen/go.mod |
| go | github.com/google/go-cmp | v0.5.4 | Assets/Plugins/DockerDotNet/tools/specgen/go.mod |
| go | github.com/kr/text | v0.2.0 | Assets/Plugins/DockerDotNet/tools/specgen/go.mod |
| go | github.com/moby/term | v0.0.0-20201216013528-df9cb8a40635 | Assets/Plugins/DockerDotNet/tools/specgen/go.mod |
| go | github.com/morikuni/aec | v1.0.0 | Assets/Plugins/DockerDotNet/tools/specgen/go.mod |
| go | github.com/opencontainers/go-digest | v1.0.0 | Assets/Plugins/DockerDotNet/tools/specgen/go.mod |
| ... | (7 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

##### **Q: Will LG release the source code for the WISE (web user interface) cloud service?**

A: There are no plans at this time to release the source code for WISE.

##### **Q: Would LG be interested in transferring the SVL Simulator project to someone interested in taking over the project?**

A: There are no plans at this time to transfer the SVL Simulator project (or the WISE cloud service).

##### **Q: Will the Simulator Software License Agreement be changed?**

A: There are no plans at this time to change the [Simulator Software License Agreement](https://github.com/lgsvl/simulator/blob/master/LICENSE).

##### **Q: Can users share source code changes and forks of SVL Simulator?**

A: As a GitHub project, anyone is able to create their own fork; in fact, there are already over 500 such forks of the [SVL Simulator project](https://github.com/lgsvl/simulator). Users can then make changes and even submit pull requests back to the original (parent) project. While we have no plans to review or merge such changes into the main project, users are free to review open PRs and create their own local build from their own or any other public fork.

##### **Q: Can users share new builds of SVL Simulator?**

A: The [Simulator Software License Agreement](https://github.com/lgsvl/simulator/blob/master/LICENSE) allows you to “modify or create derivative works of the Licensed Materials” and only restricts their commercial use. Therefore, it is ok for users to share new builds of SVL Simulator as long as such builds are not sold or otherwise used for commercial purposes.

##### **Q: What about the SVL Simulator Premium product and/or cloud simulation service?**

A: There are no plans at this time to offer a SVL Simulator Premium product or cloud service.

##### **Q: Can users still post technical questions on GitHub?**

A: Technical questions may be posted to the [SVL Simulator Issues](https://github.com/lgsvl/simulator/issues) page on GitHub but may not be answered by the SVL Simulator team. We encourage users to help each other with questions or issues that are posted.

##### **Q: What if there are other questions not addressed in this document?**

A: Other questions may be posted to the [SVL Simulator Issues](https://github.com/lgsvl/simulator/issues) page on GitHub.

<br/>

------

*Section quoted from the upstream readme.*
Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

Upstream contributions: fork the `SIMULATOR` project, create a feature branch, and open a pull request against upstream. Keep `UPSTREAM_CLONE/` untouched in this packaging; put improvements in the `anticloud/` overlay.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: No license file present in the upstream snapshot** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
SIMULATOR SOFTWARE LICENSE AGREEMENT

DO NOT DOWNLOAD, INSTALL ACCESS, COPY, OR USE ANY PORTION OF THE LICENSED MATERIALS (DEFINED BELOW) UNTIL YOU HAVE READ AND ACCEPTED THE TERMS OF THIS AGREEMENT.  BY INSTALLING, COPYING, ACCESSING, OR USING THE LICENSED MATERIALS, YOU ACCEPT AND AGREE TO BE LEGALLY BOUND BY THE TERMS AND CONDITIONS OF THIS AGREEMENT.  If You do not agree to be bound by, or the entity for whose benefit You act has not authorized You to accept these terms and conditions, do not install, access, copy, or use the LG Simulator Software and destroy all copies in your possession.

This Software License Agreement (“Agreement”), effective upon your acceptance of this Agreement (“Effective Date”), is between Zenith Electronics, LLC with offices located at 5150 Great America Parkway, Santa Clara, CA 95054 (“LG”) and "You." “You” or “Your” refers to you or your employer or other entity for whose benefit you act, as applicable.  

1	PURPOSE; LICENSE GRANT AND RESTRICTIONS. 

1.1	Purpose.  This Agreement governs the use of the LG Simulator Software and any accompanying documentation, code, content owned or provided by LG (“LG Content”) and related materials (collectively, the “Licensed Material”) described in more detail in Exhibit A, made available to You by LG.  

1.2	License Grant.  Subject to the terms and conditions of this Agreement, LG grants You a nonexclusive, sublicensable as permitted herein, royalty-free, worldwide, perpetual, irrevocable license for software development and related purposes (the “Purpose”).  Any permitted sublicense must be on the same terms and conditions as contained herein.  

1.3	Restrictions.  You may not: (a) reverse engineer, decompile, or disassemble the executable or binary builds of Licensed Material, or otherwise attempt to defeat, avoid, by-pass, remove, deactivate or otherwise circumvent any software protection mechanisms in or included with the binary builds of Licensed Material including, without limitation, any such mechanism used to restrict or control the functionality of the binary builds of Licensed Material; (b) use or reproduce the Licensed Material for any reason other than the Purpose; (c) sell or otherwise transfer or make available the Licensed Material, any copies of the Licensed Material, or any information derived from the Licensed Material in any form to any third parties for commercial purposes; or (d) remove or alter any proprietary notices or marks on the Licensed Material.

1.4	Derivative Works.  You may modify or create derivative works of the Licensed Materials (“Derivatives”).  Any Derivatives created shall have the same restrictions and limitations as listed in Sections 1.2, 1.3, 1.4 and 4.1 herein. Your use of Derivatives outside the scope of this Agreement shall require a separate license agreement.  Derivatives do not include LG Content, or other content or data bundled with, created by or otherwise displayed as a result of using the Licensed Materials (“Simulator Content”).

1.5	Limitations.  	You may not use Licensed Materials and Derivatives as software-as-a-service, platform-as-a-service, infrastructure-as-a-service or other similar online service for commercial purposes.  Commercial purposes include, but are not limited to activities of sale, rent, or transfer for charge or other consideration received, directly or indirectly, to a third party in connection with a business or endeavor intended for profit.

```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original No license file present in the upstream snapshot terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `No license file present in the upstream snapshot` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `SIMULATOR` (category: AUTOMOTIVE)
- **Upstream URL:** https://github.com/lgsvl/simulator
- **Pinned commit (SHA):** `28244ba27ca66e34e2f48ce30812d4f034e39c0b`
- **Branch:** master
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`6a2b0be28f49a38f81500b0f3c22d9e8b61b31ed4d88bd1cba43fc80f54772c5`.

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



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.



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

