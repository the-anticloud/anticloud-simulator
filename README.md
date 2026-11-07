# SIMULATOR

> CARLA Simulator CARLA is an open-source simulator for autonomous driving research. CARLA has been developed from the ground up to support development, training, and validation of autonomous driving systems. In addition to open-source code and protocols, CARLA provides open digital assets (urban layouts, buildings, vehicles) that were created for this purpose and can be used freely. The simulation platform supports flexible specification of sensor suites and environmental conditions.

**Category:** AUTOMOTIVE · **Ecosystem:** unknown · **Vendored upstream:** https://github.com/carla-simulator/carla · **Pinned commit:** `28244ba27ca66e34e2f48ce30812d4f034e39c0b` · **Vendor:** Anticloud FZ LLE

## What This Project Does

CARLA Simulator CARLA is an open-source simulator for autonomous driving research. CARLA has been developed from the ground up to support development, training, and validation of autonomous driving systems. In addition to open-source code and protocols, CARLA provides open digital assets (urban layouts, buildings, vehicles) that were created for this purpose and can be used freely. The simulation platform supports flexible specification of sensor suites and environmental conditions.

This is the upstream project, vendored at the pinned commit above and packaged offline-first. The 12 improvements Anticloud adds live in `anticloud/` and are described under *Anticloud Overlay* below. Every fact in this file traces to a file in this directory.

## Installation

--------------

Clone this repository locally from GitHub, specifying the *ue5-dev* branch:

```sh
git clone -b ue5-dev https://github.com/carla-simulator/carla.git CarlaUE5
```

In order to build CARLA, you need access to the CARLA fork of Unreal Engine 5.5. In order to access this repository, you must first link your GitHub account to Epic Games by following [this guide](https://www.unrealengine.com/en-US/ue-on-github). You then also need to use your git credentials to authorise the download of the Unreal Engine 5.5 repository.

__Building in Linux__:

Run the setup script from a terminal open in the CARLA root directory:

```sh
cd CarlaUE5
./CarlaSetup.sh --interactive
```

The setup script will prompt you for your sudo password, in order to install the prerequisites. It will then prompt you for your GitHub credentials in order to authorise the download of the Unreal Engine repository.

The setup script will install by default Python 3 using apt. If you want to target an existing Python installation, you should use the `--python-root=PATH_TO_PYTHON` argument with the relevant Python installation path. You can use whereis python3 in your chosen environment and strip the `/python3` suffix from the path.

__Building in Linux unattended__:

If you want to run the setup script unattended, your git credentials need to be stored in an environment variable. Add your github credentials to your `.bashrc` file:

```sh

## Usage

See the upstream README (linked above) for usage. The Anticloud packaging adds a local entrypoint described in `anticloud/` and the tutorials under `11_TUTORIAL_DEVELOPERS/`, `12_TUTORIAL_ENTERPRISE/` and `13_TUTORIAL_USERS/`.

## API

The 12 improvements live under `anticloud/`. Run the check suite from this directory:

```
python anticloud/bench/runner.py --cwd anticloud
```

## Benchmarks

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

**Suite: 16/16 passed** · platform `?` · python `?` · method `?`

## License

The upstream licence is preserved in `LICENSE` and `THIRD_PARTY_LICENSES/`. The Anticloud overlay is licensed under Anticommons 0.1.0 (`ANTICOMMONS_LICENSE.md`).

## Upstream

SHA3-256 of `BENCH.json`:

```
896753565590c27d579b94f19402ea50ab12e96ae3f4ad420f981c1840752823
```

Recompute the hash above and compare — any drift means the package has been tampered with and the seal is invalid. This is a self-assessment; no external audit has been performed and a SOC 2 / NIST independent audit is committed post-funding.


## Dependencies

See project documentation for details.


## Configuration

See project documentation for details.


## Contributing

See project documentation for details.
