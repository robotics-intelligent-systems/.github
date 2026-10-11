# Robotics & Intelligent Systems

**Robotics · Engineering simulation · Digital twins · Technical AI · Domain integration**

Robotics & Intelligent Systems brings together the **JFX portfolio** of modular
engineering research, reference architectures and software pilots. We connect
**robotics, simulation, digital twins and technical AI** with domain workflows
in manufacturing, agriculture, infrastructure, healthcare research, scientific
education and enterprise systems.

Our engineering approach uses **shared knowledge and AI services, domain-owned
adapters and explicit integration contracts**. Each project retains its models,
data and acceptance decisions. Model-based systems engineering (MBSE) connects
requirements, design, manufacturing and simulation with traceable evidence.

The catalog below makes each project's **current status, indicative MVP maturity
and proposed next AI-assisted task** visible. Architecture proposals, executable
pilots and validated integrations are distinguished by repository evidence.

[Browse repositories](https://github.com/orgs/robotics-intelligent-systems/repositories)
· [Explore the project catalog](#project-catalog)
· [Get involved](#contributing-and-collaboration)

## Explore

- [CAD Concept Gallery](#cad-concept-gallery)

- [Our Focus](#our-focus)
- [Project Catalog](#project-catalog)
  - [Project Progress Guide](#reading-the-progress-bars)
  - [Robotics and Industrial Simulation](#robotics-and-industrial-simulation)
  - [Applied Artificial Intelligence](#applied-artificial-intelligence)
  - [Agriculture and Built Environment](#agriculture-and-built-environment)
  - [Enterprise and Business Systems](#enterprise-and-business-systems)
  - [Maritime, Aerospace and Mobility](#maritime-aerospace-and-mobility)
  - [Energy and Scientific Modeling](#energy-and-scientific-modeling)
  - [Education and Infrastructure](#education-and-infrastructure)
- [Shared Services and Integration Priorities](#shared-services-and-integration-priorities)
- [Complementary Projects under sdk2035](#complementary-projects-under-sdk2035)
- [Technology and Architecture](#technology-and-architecture)
- [Getting Started](#getting-started)
- [Contributing and Collaboration](#contributing-and-collaboration)

## Our Focus

| Area | Engineering direction |
| --- | --- |
| Simulation and digital twins | Connect models, state, telemetry and experimental evidence |
| Robotics and industrial systems | Explore sensing, interfaces, control and simulation workflows |
| Technical AI and knowledge | Retrieve source-linked evidence, extract knowledge and evaluate model outputs |
| Agriculture and built environment | Explore farm operations, resource scenarios, buildings and infrastructure twins |
| Enterprise systems | Connect business processes, data and management platforms |
| Scientific education | Support computational learning, reproducible experiments and research |

Repositories have different levels of maturity. Some contain architecture
proposals or research compendia; others contain models or software. Each project's
README, source, releases and validation evidence define its current capabilities.

## Project Catalog

The catalog groups **47 JFX projects** by primary domain. It is a curated entry
point, not a complete inventory of the organization or a single deployable product.

### Reading the progress bars

**Snapshot: 2026-10-10.** These are editorial estimates of maturity toward a first
validated MVP, based on repository READMEs and visible contents; they are **not**
measured completion percentages, effort estimates or delivery commitments.

| Indicative stage | Bar | Evidence required |
| --- | --- | --- |
| Concept · ~10% | `█░░░░░░░░░` | Scope described; executable implementation not established |
| Architecture · ~20% | `██░░░░░░░░` | Design documents, contracts or architecture assets |
| Contract harness · ~30% | `███░░░░░░░` | Executable bounded scenario/interface checks; simulator integration pending |
| Pilot · ~50% | `█████░░░░░` | Executable bounded pilot documented; broader validation pending |
| Validated MVP · ~80% | `████████░░` | Reproducible end-to-end acceptance evidence |
| Released scope · 100% | `██████████` | Declared MVP scope accepted and released |

**N/A** means a local integration milestone is not defined or inherited source
has not been assessed. Upstream maturity does not measure this portfolio's work.
Tasks are **AI-assisted proposals**, inferred from documented scope and gaps,
rather than an approved issue backlog. Maintainers review generated artifacts
and acceptance evidence. This snapshot is updated manually as milestones change.

### Robotics and Industrial Simulation

| Repository | Focus | Status | Estimated progress | Next AI-assisted task (proposed) |
| --- | --- | --- | --- | --- |
| [jfxai4mhers](https://github.com/robotics-intelligent-systems/jfxai4mhers) | Humanoid/exoskeleton robotics, simulation, learning and deployment architecture | Architecture / documentation | `██░░░░░░░░` ~20% | Draft one robot-description contract and reproducible simulation fixture. |
| [jfxai4rss](https://github.com/robotics-intelligent-systems/jfxai4rss) | Robotic-surgery simulation, medical imaging and biomedical engineering research | Architecture / documentation | `██░░░░░░░░` ~20% | Specify one non-clinical training scenario and simulation acceptance criteria. |
| [jfxai4rpcs](https://github.com/robotics-intelligent-systems/jfxai4rpcs) | Robotic pest-control systems | Architecture / documentation | `██░░░░░░░░` ~20% | Draft a labeled crop-observation fixture and reviewed detection workflow. |
| [jfxai4rffs](https://github.com/robotics-intelligent-systems/jfxai4rffs) | Robotic firefighting systems and simulation | Architecture / documentation | `██░░░░░░░░` ~20% | Specify one virtual training scenario and instructor-reviewed acceptance cases. |
| [jfxosms](https://github.com/robotics-intelligent-systems/jfxosms) | Microfactory engineering, manufacturing simulation and operator decision-support architecture | Architecture / documentation | `██░░░░░░░░` ~20% | Draft one inventory/production scenario with baseline optimization checks. |
| [jfxlms4air](https://github.com/robotics-intelligent-systems/jfxlms4air) | Localization and mapping for autonomous inspection robots | Architecture / documentation | `██░░░░░░░░` ~20% | Draft one recorded inspection dataset and localization evaluation protocol. |
| [jfxrtess](https://github.com/robotics-intelligent-systems/jfxrtess) | Real-time simulation, testing and rapid control prototyping | Architecture / documentation | `██░░░░░░░░` ~20% | Specify one model-in-the-loop test with timing and artifact provenance. |
| [jfxai4ceps](https://github.com/robotics-intelligent-systems/jfxai4ceps) | Chemical and process simulation | Architecture / documentation | `██░░░░░░░░` ~20% | Draft one process-model contract with units, balances and solver checks. |
| [jfxscada](https://github.com/robotics-intelligent-systems/jfxscada) | Supervisory control and data acquisition | Architecture / documentation | `██░░░░░░░░` ~20% | Draft one read-only telemetry adapter and replayable alarm fixture. |

### Applied Artificial Intelligence

| Repository | Focus | Status | Estimated progress | Next AI-assisted task (proposed) |
| --- | --- | --- | --- | --- |
| [jfxai4arch](https://github.com/robotics-intelligent-systems/jfxai4arch) | Technical knowledge and agent architecture, with an initial local RAG pilot | Executable RAG pilot | `█████░░░░░` ~50% | Draft a source-grounded evaluation set and validate optional local-model generation. |
| [jfxai4bio](https://github.com/robotics-intelligent-systems/jfxai4bio) | Bioinformatics | Architecture / documentation | `██░░░░░░░░` ~20% | Specify one public-dataset analysis workflow with reproducibility checks. |
| [jfxai4dia](https://github.com/robotics-intelligent-systems/jfxai4dia) | Physics-driven industrial design automation, CAD and engineering validation | Architecture / documentation | `██░░░░░░░░` ~20% | Specify one CAD-to-simulation case with units and validation evidence. |
| [jfxai4cv](https://github.com/robotics-intelligent-systems/jfxai4cv) | Medical imaging, segmentation, scientific visualization and computer-vision research | Architecture / documentation | `██░░░░░░░░` ~20% | Draft a de-identified research imaging fixture and segmentation evaluation criteria. |
| [jfxai4nlp](https://github.com/robotics-intelligent-systems/jfxai4nlp) | NLP, knowledge extraction, code intelligence and AI evaluation architecture | Architecture / documentation | `██░░░░░░░░` ~20% | Draft an extraction schema, labeled sample set and evaluation criteria. |
| [jfxai4cbs](https://github.com/robotics-intelligent-systems/jfxai4cbs) | Cybersecurity | Concept / technology compendium | `█░░░░░░░░░` ~10% | Define an isolated defensive log-analysis exercise and detection metrics. |
| [jfxai4rs](https://github.com/robotics-intelligent-systems/jfxai4rs) | Remote sensing | Architecture / documentation | `██░░░░░░░░` ~20% | Draft one geospatial dataset contract with coordinates and provenance checks. |
| [jfxai4mar](https://github.com/robotics-intelligent-systems/jfxai4mar) | Augmented reality applications | Architecture / documentation | `██░░░░░░░░` ~20% | Specify one recorded spatial-annotation workflow and interaction checks. |
| [jfxai4mad](https://github.com/robotics-intelligent-systems/jfxai4mad) | Travel coordination, Odoo/Flectra modernization research, professional collaboration and adult social-discovery concepts | Architecture / documentation | `██░░░░░░░░` ~20% | Draft one travel-coordination workflow with consent and data-boundary checks. |

### Agriculture and Built Environment

| Repository | Focus | Status | Estimated progress | Next AI-assisted task (proposed) |
| --- | --- | --- | --- | --- |
| [jfxfmis](https://github.com/robotics-intelligent-systems/jfxfmis) | Farm management, precision agriculture, agricultural digital twins and telemetry | Architecture / documentation | `██░░░░░░░░` ~20% | Draft one observation-to-twin contract and replayable farm scenario. |
| [jfxai4bss](https://github.com/robotics-intelligent-systems/jfxai4bss) | Buildings, infrastructure, smart communities and built-environment digital-twin architecture | Architecture / documentation | `██░░░░░░░░` ~20% | Specify one asset/telemetry mapping and calibration acceptance criteria. |

### Enterprise and Business Systems

| Repository | Focus | Status | Estimated progress | Next AI-assisted task (proposed) |
| --- | --- | --- | --- | --- |
| [jfxotbs](https://github.com/robotics-intelligent-systems/jfxotbs) | Aviation operations, travel/booking management and rescue digital-twin architecture | Architecture / documentation | `██░░░░░░░░` ~20% | Draft one booking/operations contract and mocked itinerary reconciliation cases. |
| [jfxhms](https://github.com/robotics-intelligent-systems/jfxhms) | Hospital management | Architecture / documentation | `██░░░░░░░░` ~20% | Draft one synthetic FHIR workflow with access and audit acceptance cases. |
| [jfxai4bpm](https://github.com/robotics-intelligent-systems/jfxai4bpm) | Business process management | Architecture / documentation | `██░░░░░░░░` ~20% | Specify one business-process model with event and state-transition fixtures. |
| [jfxai4ats](https://github.com/robotics-intelligent-systems/jfxai4ats) | Automated trading, market data, risk and financial messaging architecture | Architecture / documentation | `██░░░░░░░░` ~20% | Draft one trade-record contract and reconciliation acceptance cases. |
| [jfxai4obs](https://github.com/robotics-intelligent-systems/jfxai4obs) | Loan management, open banking, payments and financial engineering | Architecture / documentation | `██░░░░░░░░` ~20% | Draft a sandbox payment contract with idempotency and reconciliation cases. |
| [jfxai4ftm](https://github.com/robotics-intelligent-systems/jfxai4ftm) | Food-truck and mobile food-service management, fleet logistics and digital twins | Architecture / documentation | `██░░░░░░░░` ~20% | Draft one order-to-inventory workflow with fleet-event fixtures. |
| [jfxai4ohs](https://github.com/robotics-intelligent-systems/jfxai4ohs) | B2B commerce, procurement and proposed Mercado Libre MCP/REST integration | Architecture / documentation | `██░░░░░░░░` ~20% | Draft one catalog adapter contract and mocked authorization/error checks. |
| [jfxbsc](https://github.com/robotics-intelligent-systems/jfxbsc) | Balanced scorecard and strategy performance management | Architecture / documentation | `██░░░░░░░░` ~20% | Define one KPI-to-initiative traceability schema and evaluation fixture. |
| [jfxai4moms](https://github.com/robotics-intelligent-systems/jfxai4moms) | Mine management | Architecture / documentation | `██░░░░░░░░` ~20% | Draft one synthetic geological-data contract with units and provenance checks. |
| [jfxai4crm](https://github.com/robotics-intelligent-systems/jfxai4crm) | Customer relationship management | Architecture / documentation | `██░░░░░░░░` ~20% | Draft one consent-scoped CRM record contract and mocked adapter checks. |
| [jfxai4rts](https://github.com/robotics-intelligent-systems/jfxai4rts) | Recruitment tracking | Architecture / documentation | `██░░░░░░░░` ~20% | Draft one synthetic application schema and human-reviewed extraction evaluation. |

### Maritime, Aerospace and Mobility

| Repository | Focus | Status | Estimated progress | Next AI-assisted task (proposed) |
| --- | --- | --- | --- | --- |
| [jfxmbdss](https://github.com/robotics-intelligent-systems/jfxmbdss) | OpenTwin MBDSS: maritime digital twins, distributed simulation and AI-assisted analysis | Architecture / documentation | `██░░░░░░░░` ~20% | Specify one archived maritime simulation job with provenance and replay checks. |
| [jfxnpss](https://github.com/robotics-intelligent-systems/jfxnpss) | Jet propulsion and engine modeling | Architecture / documentation | `██░░░░░░░░` ~20% | Specify one propulsion-model comparison with units and reference-result checks. |
| [jfxjts](https://github.com/robotics-intelligent-systems/jfxjts) | Civil flight training and mission-simulation architecture | Scenario + executable contract harness; 13 tests passed | `███░░░░░░░` ~30% | Implement one qualified civilian flight-model adapter with pinned provenance, SI/frame checks and recorded replay tolerances. |
| [jfxai4mss](https://github.com/robotics-intelligent-systems/jfxai4mss) | Marine systems and control simulation | Architecture / documentation | `██░░░░░░░░` ~20% | Specify one marine model exchange with units and solver compatibility checks. |
| [jfxai4mjas](https://github.com/robotics-intelligent-systems/jfxai4mjas) | Transient simulation of reconfigurable models | Architecture / documentation | `██░░░░░░░░` ~20% | Draft one versioned aircraft-model contract and offline validation fixture. |
| [jfxai4mass](https://github.com/robotics-intelligent-systems/jfxai4mass) | Automotive and driving simulation | Architecture / documentation | `██░░░░░░░░` ~20% | Specify one recorded mobility scenario and reproducible evaluation criteria. |
| [jfxai4scss](https://github.com/robotics-intelligent-systems/jfxai4scss) | Small-satellite simulation | Architecture / documentation | `██░░░░░░░░` ~20% | Draft one archived satellite-simulation artifact schema and replay checks. |
| [jfxai4mlrss](https://github.com/robotics-intelligent-systems/jfxai4mlrss) | Spaceflight, modular launch-system and mission-simulation research | Architecture / documentation | `██░░░░░░░░` ~20% | Draft a simulation-artifact catalog with provenance and reproducibility checks. |

[JFXJTS scenario delivery](https://github.com/robotics-intelligent-systems/jfxjts/blob/main/docs/training/civil-navigation-interruption.md)
· [Validation evidence](https://github.com/robotics-intelligent-systems/jfxjts/blob/main/docs/training/validation-2026-10-10.md)
— instructor controls and synthetic replay checks delivered on 2026-10-10.
The ~30% estimate reflects contract maturity; flight dynamics and simulator integration remain pending.

### Energy and Scientific Modeling

| Repository | Focus | Status | Estimated progress | Next AI-assisted task (proposed) |
| --- | --- | --- | --- | --- |
| [jfxoqss](https://github.com/robotics-intelligent-systems/jfxoqss) | Open quantum systems simulation | Architecture / documentation | `██░░░░░░░░` ~20% | Specify one small quantum experiment and reference-solver comparison. |
| [jfxoss](https://github.com/robotics-intelligent-systems/jfxoss) | Optical systems simulation | Architecture / documentation | `██░░░░░░░░` ~20% | Draft one optical-bench simulation contract and reference-result fixture. |
| [jfxorss](https://github.com/robotics-intelligent-systems/jfxorss) | Radar systems simulation | Architecture / documentation | `██░░░░░░░░` ~20% | Draft one archived research dataset manifest with units and provenance checks. |
| [jfxai4mess](https://github.com/robotics-intelligent-systems/jfxai4mess) | Multi-energy systems, renewable power, storage and co-simulation architecture | Architecture / documentation | `██░░░░░░░░` ~20% | Specify one energy-balance scenario and co-simulation acceptance criteria. |
| [jfxai4nhes](https://github.com/robotics-intelligent-systems/jfxai4nhes) | Nuclear hybrid energy systems | Architecture / documentation | `██░░░░░░░░` ~20% | Draft one published research-model comparison and uncertainty evidence checklist. |

### Education and Infrastructure

| Repository | Focus | Status | Estimated progress | Next AI-assisted task (proposed) |
| --- | --- | --- | --- | --- |
| [jfxcms](https://github.com/robotics-intelligent-systems/jfxcms) | Programming contests, scientific education, AI-assisted learning and simulation/PME preparation | Architecture / documentation | `██░░░░░░░░` ~20% | Draft one programming exercise with reproducible grading and learning evidence. |
| [jfxlms](https://github.com/robotics-intelligent-systems/jfxlms) | Learning management systems | Architecture / documentation | `██░░░░░░░░` ~20% | Specify one course/enrollment adapter and grade-persistence checks. |
| [jfxnms](https://github.com/robotics-intelligent-systems/jfxnms) | Network management systems | Architecture / documentation | `██░░░░░░░░` ~20% | Draft one read-only network inventory contract and telemetry replay fixture. |

## CAD Concept Gallery

Reviewed on **2026-10-11** across all **47 projects in the JFX project catalog**: **20 projects contain 62 concept images** in `MBSE/CAD`; 27 have no images in that directory. This scope covers the profile's JFX portfolio, not every fork or reference repository in the organization.

These are visual concept studies, not verified CAD geometry or demonstrated performance. Descriptions follow repository documentation where available and otherwise describe the asset's named subject conservatively. Each project groups its concepts into two columns: name and description on the left, linked thumbnail on the right. Click a thumbnail or **Open preview** to open the source image. [Review coverage](cad-review.md).

### [jfxai4mhers](https://github.com/robotics-intelligent-systems/jfxai4mhers)

| Concept and description | Preview |
| :--- | :---: |
| **OpenTwin EXO expedition suit**<br>Modular expedition-suit concept for studying subsystem packaging, interfaces and simulation requirements. | <a href="https://github.com/robotics-intelligent-systems/jfxai4mhers/blob/main/MBSE/CAD/h2fly-opentwin-exo-modular-expedition-suit-concept-v3.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4mhers/main/MBSE/CAD/h2fly-opentwin-exo-modular-expedition-suit-concept-v3.jpg" alt="OpenTwin EXO expedition suit" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4mhers/blob/main/MBSE/CAD/h2fly-opentwin-exo-modular-expedition-suit-concept-v3.jpg) |

### [jfxrtess](https://github.com/robotics-intelligent-systems/jfxrtess)

| Concept and description | Preview |
| :--- | :---: |
| **AM-B amphibious motorcycle**<br>Motorcycle concept for studying rider balance, water immersion, propulsion and transition controls. | <a href="https://github.com/robotics-intelligent-systems/jfxrtess/blob/main/MBSE/CAD/amphibious-motorcycle-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxrtess/main/MBSE/CAD/amphibious-motorcycle-concept.jpg" alt="AM-B amphibious motorcycle" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxrtess/blob/main/MBSE/CAD/amphibious-motorcycle-concept.jpg) |
| **AM-S amphibious sport roadster**<br>Roadster concept connecting occupant packaging, road dynamics, hull loading and water-mode transitions. | <a href="https://github.com/robotics-intelligent-systems/jfxrtess/blob/main/MBSE/CAD/amphibious-sport-roadster.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxrtess/main/MBSE/CAD/amphibious-sport-roadster.jpg" alt="AM-S amphibious sport roadster" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxrtess/blob/main/MBSE/CAD/amphibious-sport-roadster.jpg) |
| **AM-U6 amphibious utility vehicle**<br>Utility-vehicle concept for exploring cargo restraint, load distribution, waterline and service access. | <a href="https://github.com/robotics-intelligent-systems/jfxrtess/blob/main/MBSE/CAD/deeper-vehicle-immersion-in%20water-mode.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxrtess/main/MBSE/CAD/deeper-vehicle-immersion-in%20water-mode.jpg" alt="AM-U6 amphibious utility vehicle" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxrtess/blob/main/MBSE/CAD/deeper-vehicle-immersion-in%20water-mode.jpg) |

### [jfxai4dia](https://github.com/robotics-intelligent-systems/jfxai4dia)

| Concept and description | Preview |
| :--- | :---: |
| **Hybrid gyrodyne air taxi**<br>Modular hybrid gyrodyne concept for air-taxi requirements and subsystem integration. | <a href="https://github.com/robotics-intelligent-systems/jfxai4dia/blob/main/MBSE/CAD/modular-hybrid-gyrodyne-air-taxi.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4dia/main/MBSE/CAD/modular-hybrid-gyrodyne-air-taxi.jpg" alt="Hybrid gyrodyne air taxi" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4dia/blob/main/MBSE/CAD/modular-hybrid-gyrodyne-air-taxi.jpg) |
| **OpenTwin personal eVTOL**<br>Personal electric vertical-flight concept for requirements, interfaces and digital-twin exploration. | <a href="https://github.com/robotics-intelligent-systems/jfxai4dia/blob/main/MBSE/CAD/opentwin-personal-evtol-digital-twin-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4dia/main/MBSE/CAD/opentwin-personal-evtol-digital-twin-concept.jpg" alt="OpenTwin personal eVTOL" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4dia/blob/main/MBSE/CAD/opentwin-personal-evtol-digital-twin-concept.jpg) |
| **Twin-float amphibious gyroplane**<br>Gyroplane concept with twin floats for studying amphibious operation and integration. | <a href="https://github.com/robotics-intelligent-systems/jfxai4dia/blob/main/MBSE/CAD/twin-float-amphibious-gyroplane.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4dia/main/MBSE/CAD/twin-float-amphibious-gyroplane.jpg" alt="Twin-float amphibious gyroplane" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4dia/blob/main/MBSE/CAD/twin-float-amphibious-gyroplane.jpg) |

### [jfxai4mad](https://github.com/robotics-intelligent-systems/jfxai4mad)

| Concept and description | Preview |
| :--- | :---: |
| **Hydrojet submersible**<br>Dolphin-inspired submersible concept for exploring vehicle form and hydrojet integration. | <a href="https://github.com/robotics-intelligent-systems/jfxai4mad/blob/main/MBSE/CAD/dolphin-inspired-hydrojet-submersible-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4mad/main/MBSE/CAD/dolphin-inspired-hydrojet-submersible-concept.jpg" alt="Hydrojet submersible" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4mad/blob/main/MBSE/CAD/dolphin-inspired-hydrojet-submersible-concept.jpg) |
| **OpenTwin amphibious ATV**<br>Modular amphibious all-terrain vehicle concept for mobility and digital-twin studies. | <a href="https://github.com/robotics-intelligent-systems/jfxai4mad/blob/main/MBSE/CAD/opentwin-modular-amphibious-atv-digital-twin-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4mad/main/MBSE/CAD/opentwin-modular-amphibious-atv-digital-twin-concept.jpg" alt="OpenTwin amphibious ATV" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4mad/blob/main/MBSE/CAD/opentwin-modular-amphibious-atv-digital-twin-concept.jpg) |
| **OpenTwin shared-retreat habitat**<br>Cutaway concept of a modular shared habitat for studying spaces, access, utilities and structural interfaces. | <a href="https://github.com/robotics-intelligent-systems/jfxai4mad/blob/main/MBSE/CAD/opentwin-modular-habitat-shared-retreat-cutaway.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4mad/main/MBSE/CAD/opentwin-modular-habitat-shared-retreat-cutaway.jpg" alt="OpenTwin shared-retreat habitat" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4mad/blob/main/MBSE/CAD/opentwin-modular-habitat-shared-retreat-cutaway.jpg) |

### [jfxfmis](https://github.com/robotics-intelligent-systems/jfxfmis)

| Concept and description | Preview |
| :--- | :---: |
| **Multi-level floating farm**<br>Stacked growing-space concept integrating marine structures, utilities and agricultural logistics. | <a href="https://github.com/robotics-intelligent-systems/jfxfmis/blob/main/MBSE/CAD/Overall-3D-view-of-the-Proposed-Multi-level-Floating-Farm-MFF.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxfmis/main/MBSE/CAD/Overall-3D-view-of-the-Proposed-Multi-level-Floating-Farm-MFF.jpg" alt="Multi-level floating farm" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxfmis/blob/main/MBSE/CAD/Overall-3D-view-of-the-Proposed-Multi-level-Floating-Farm-MFF.jpg) |
| **Floating farm**<br>Concept connecting floating agriculture, fish production, renewable supply and shore operations. | <a href="https://github.com/robotics-intelligent-systems/jfxfmis/blob/main/MBSE/CAD/floating-farm-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxfmis/main/MBSE/CAD/floating-farm-concept.jpg" alt="Floating farm" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxfmis/blob/main/MBSE/CAD/floating-farm-concept.jpg) |
| **Modular floating farm island**<br>Terraced agriculture concept with modular structures and resource-loop interfaces. | <a href="https://github.com/robotics-intelligent-systems/jfxfmis/blob/main/MBSE/CAD/modular-floating-farm-island-digital-twin.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxfmis/main/MBSE/CAD/modular-floating-farm-island-digital-twin.jpg" alt="Modular floating farm island" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxfmis/blob/main/MBSE/CAD/modular-floating-farm-island-digital-twin.jpg) |
| **Offshore blue-economy twins**<br>Concept board connecting floating infrastructure, aquaculture, support vessels and digital replicas. | <a href="https://github.com/robotics-intelligent-systems/jfxfmis/blob/main/MBSE/CAD/offshore-blue-economy-open-source-digital-twins-concept-v1.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxfmis/main/MBSE/CAD/offshore-blue-economy-open-source-digital-twins-concept-v1.jpg" alt="Offshore blue-economy twins" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxfmis/blob/main/MBSE/CAD/offshore-blue-economy-open-source-digital-twins-concept-v1.jpg) |

### [jfxai4bss](https://github.com/robotics-intelligent-systems/jfxai4bss)

| Concept and description | Preview |
| :--- | :---: |
| **Floating offshore stadium**<br>Floating venue concept for event spaces, hospitality, docking and shared services. | <a href="https://github.com/robotics-intelligent-systems/jfxai4bss/blob/main/MBSE/CAD/floating-offshore-stadium-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4bss/main/MBSE/CAD/floating-offshore-stadium-concept.jpg" alt="Floating offshore stadium" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4bss/blob/main/MBSE/CAD/floating-offshore-stadium-concept.jpg) |
| **Modular floating community**<br>Housing and shared-services concept; the source filename does not establish hurricane resistance. | <a href="https://github.com/robotics-intelligent-systems/jfxai4bss/blob/main/MBSE/CAD/hurricane-proof-self-elevating-floating-house-boat-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4bss/main/MBSE/CAD/hurricane-proof-self-elevating-floating-house-boat-concept.jpg" alt="Modular floating community" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4bss/blob/main/MBSE/CAD/hurricane-proof-self-elevating-floating-house-boat-concept.jpg) |
| **Modular offshore platform**<br>Platform concept integrating living, operations, research, lifting and mission-module spaces. | <a href="https://github.com/robotics-intelligent-systems/jfxai4bss/blob/main/MBSE/CAD/self-propelled-twin-hulled-semi-submersible-platform.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4bss/main/MBSE/CAD/self-propelled-twin-hulled-semi-submersible-platform.jpg" alt="Modular offshore platform" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4bss/blob/main/MBSE/CAD/self-propelled-twin-hulled-semi-submersible-platform.jpg) |

### [jfxotbs](https://github.com/robotics-intelligent-systems/jfxotbs)

| Concept and description | Preview |
| :--- | :---: |
| **OpenTwin VTOL Rescue LH2**<br>Cutaway rescue-aircraft concept integrating a modular bay, hydrogen storage, fuel cells and electric propulsion. | <a href="https://github.com/robotics-intelligent-systems/jfxotbs/blob/main/MBSE/CAD/OpenTwin_VTOL_Rescue_LH2_Cutaway_Concept_v1.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxotbs/main/MBSE/CAD/OpenTwin_VTOL_Rescue_LH2_Cutaway_Concept_v1.jpg" alt="OpenTwin VTOL Rescue LH2" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxotbs/blob/main/MBSE/CAD/OpenTwin_VTOL_Rescue_LH2_Cutaway_Concept_v1.jpg) |
| **Modular GCS trailer**<br>Mobile ground-control and simulation-station concept for equipment and operator-space integration. | <a href="https://github.com/robotics-intelligent-systems/jfxotbs/blob/main/MBSE/CAD/jfxotbs-modular-gcs-trailer-digital-twin-simulation-concept-v1.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxotbs/main/MBSE/CAD/jfxotbs-modular-gcs-trailer-digital-twin-simulation-concept-v1.jpg" alt="Modular GCS trailer" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxotbs/blob/main/MBSE/CAD/jfxotbs-modular-gcs-trailer-digital-twin-simulation-concept-v1.jpg) |
| **Modular underground hangar**<br>Hangar concept for storage, maintenance, surface access, ventilation and energy interfaces. | <a href="https://github.com/robotics-intelligent-systems/jfxotbs/blob/main/MBSE/CAD/modular-underground-hangar-digital-twin.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxotbs/main/MBSE/CAD/modular-underground-hangar-digital-twin.jpg" alt="Modular underground hangar" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxotbs/blob/main/MBSE/CAD/modular-underground-hangar-digital-twin.jpg) |
| **Modular floating airport**<br>Concept connecting floating modules, airfield spaces, terminals, utilities and maritime access. | <a href="https://github.com/robotics-intelligent-systems/jfxotbs/blob/main/MBSE/CAD/open-modular-mega-floating-airport.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxotbs/main/MBSE/CAD/open-modular-mega-floating-airport.jpg" alt="Modular floating airport" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxotbs/blob/main/MBSE/CAD/open-modular-mega-floating-airport.jpg) |

### [jfxhms](https://github.com/robotics-intelligent-systems/jfxhms)

| Concept and description | Preview |
| :--- | :---: |
| **Large medical support ship**<br>Ship concept for arranging medical-support spaces and maritime mission interfaces. | <a href="https://github.com/robotics-intelligent-systems/jfxhms/blob/main/MBSE/CAD/large-medical-support-ship-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxhms/main/MBSE/CAD/large-medical-support-ship-concept.jpg" alt="Large medical support ship" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxhms/blob/main/MBSE/CAD/large-medical-support-ship-concept.jpg) |
| **Medical patrol boat**<br>Small-vessel concept for coastal or river medical-support missions. | <a href="https://github.com/robotics-intelligent-systems/jfxhms/blob/main/MBSE/CAD/medical-patrol-boat-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxhms/main/MBSE/CAD/medical-patrol-boat-concept.jpg" alt="Medical patrol boat" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxhms/blob/main/MBSE/CAD/medical-patrol-boat-concept.jpg) |
| **Modular medical vessel**<br>Medical-support vessel concept with modular mission spaces and service interfaces. | <a href="https://github.com/robotics-intelligent-systems/jfxhms/blob/main/MBSE/CAD/modular-medical-vessel-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxhms/main/MBSE/CAD/modular-medical-vessel-concept.jpg" alt="Modular medical vessel" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxhms/blob/main/MBSE/CAD/modular-medical-vessel-concept.jpg) |

### [jfxai4ftm](https://github.com/robotics-intelligent-systems/jfxai4ftm)

| Concept and description | Preview |
| :--- | :---: |
| **OpenTwin explorer motorhome**<br>Modular expedition motorhome concept for living-space and mobility studies. | <a href="https://github.com/robotics-intelligent-systems/jfxai4ftm/blob/main/MBSE/CAD/opentwin-modular-explorer-motorhome-digital-twin-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4ftm/main/MBSE/CAD/opentwin-modular-explorer-motorhome-digital-twin-concept.jpg" alt="OpenTwin explorer motorhome" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4ftm/blob/main/MBSE/CAD/opentwin-modular-explorer-motorhome-digital-twin-concept.jpg) |
| **OpenTwin mini teardrop RV**<br>Compact modular recreational-trailer concept for packaging and digital-twin exploration. | <a href="https://github.com/robotics-intelligent-systems/jfxai4ftm/blob/main/MBSE/CAD/opentwin-modular-mini-teardrop-rv-digital-twin-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4ftm/main/MBSE/CAD/opentwin-modular-mini-teardrop-rv-digital-twin-concept.jpg" alt="OpenTwin mini teardrop RV" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4ftm/blob/main/MBSE/CAD/opentwin-modular-mini-teardrop-rv-digital-twin-concept.jpg) |
| **Rising-roof expedition motorhome**<br>Expedition motorhome concept exploring an expandable roof and accommodation layout. | <a href="https://github.com/robotics-intelligent-systems/jfxai4ftm/blob/main/MBSE/CAD/rising-roof-expedition-motorhome.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4ftm/main/MBSE/CAD/rising-roof-expedition-motorhome.jpg" alt="Rising-roof expedition motorhome" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4ftm/blob/main/MBSE/CAD/rising-roof-expedition-motorhome.jpg) |

### [jfxai4moms](https://github.com/robotics-intelligent-systems/jfxai4moms)

| Concept and description | Preview |
| :--- | :---: |
| **Floating dry dock**<br>Dock concept integrating maintenance areas, cranes, keel supports, ballast and logistics. | <a href="https://github.com/robotics-intelligent-systems/jfxai4moms/blob/main/MBSE/CAD/floating-dry-dock-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4moms/main/MBSE/CAD/floating-dry-dock-concept.jpg" alt="Floating dry dock" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4moms/blob/main/MBSE/CAD/floating-dry-dock-concept.jpg) |
| **Offshore platform**<br>Self-elevating platform concept with working deck, accommodation, utilities and subsea interfaces. | <a href="https://github.com/robotics-intelligent-systems/jfxai4moms/blob/main/MBSE/CAD/offshore-platform-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4moms/main/MBSE/CAD/offshore-platform-concept.jpg" alt="Offshore platform" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4moms/blob/main/MBSE/CAD/offshore-platform-concept.jpg) |
| **OpenTwin Ocean Mining research vehicle**<br>Cutaway concept of an uncrewed research vehicle for prospecting, sampling and environmental observation. | <a href="https://github.com/robotics-intelligent-systems/jfxai4moms/blob/main/MBSE/CAD/opentwin-ocean-mining-digital-twin-cutaway-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4moms/main/MBSE/CAD/opentwin-ocean-mining-digital-twin-cutaway-concept.jpg" alt="OpenTwin Ocean Mining research vehicle" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4moms/blob/main/MBSE/CAD/opentwin-ocean-mining-digital-twin-cutaway-concept.jpg) |

### [jfxmbdss](https://github.com/robotics-intelligent-systems/jfxmbdss)

| Concept and description | Preview |
| :--- | :---: |
| **Hydrogen-hybrid amphibious transport**<br>High-wing cargo-aircraft concept with electric propulsion and twin floats. | <a href="https://github.com/robotics-intelligent-systems/jfxmbdss/blob/main/MBSE/CAD/hydrogen-hybrid-amphibious-transport-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxmbdss/main/MBSE/CAD/hydrogen-hybrid-amphibious-transport-concept.jpg" alt="Hydrogen-hybrid amphibious transport" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxmbdss/blob/main/MBSE/CAD/hydrogen-hybrid-amphibious-transport-concept.jpg) |
| **OpenTwin Marine ground-effect platform**<br>Waterborne transport concept with a broad wing and interchangeable mission modules. | <a href="https://github.com/robotics-intelligent-systems/jfxmbdss/blob/main/MBSE/CAD/liberty-lifter-seaplane-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxmbdss/main/MBSE/CAD/liberty-lifter-seaplane-concept.jpg" alt="OpenTwin Marine ground-effect platform" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxmbdss/blob/main/MBSE/CAD/liberty-lifter-seaplane-concept.jpg) |
| **Mobile offshore base**<br>Floating-base concept for modular logistics and offshore-support spaces. | <a href="https://github.com/robotics-intelligent-systems/jfxmbdss/blob/main/MBSE/CAD/mobile-offshore-base-digital-twin.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxmbdss/main/MBSE/CAD/mobile-offshore-base-digital-twin.jpg" alt="Mobile offshore base" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxmbdss/blob/main/MBSE/CAD/mobile-offshore-base-digital-twin.jpg) |
| **OpenTwin USV H2**<br>Uncrewed surface-vessel concept combining cargo handling, hydrogen energy and supervised research. | <a href="https://github.com/robotics-intelligent-systems/jfxmbdss/blob/main/MBSE/CAD/opentwin-usv-h2-digital-twin-cutaway-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxmbdss/main/MBSE/CAD/opentwin-usv-h2-digital-twin-cutaway-concept.jpg" alt="OpenTwin USV H2" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxmbdss/blob/main/MBSE/CAD/opentwin-usv-h2-digital-twin-cutaway-concept.jpg) |

### [jfxnpss](https://github.com/robotics-intelligent-systems/jfxnpss)

| Concept and description | Preview |
| :--- | :---: |
| **Modular reusable aerospace shuttle**<br>Reusable-shuttle concept for high-level mission and subsystem integration studies. | <a href="https://github.com/robotics-intelligent-systems/jfxnpss/blob/main/MBSE/CAD/modular-reusable-aerospace-shuttle-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxnpss/main/MBSE/CAD/modular-reusable-aerospace-shuttle-concept.jpg" alt="Modular reusable aerospace shuttle" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxnpss/blob/main/MBSE/CAD/modular-reusable-aerospace-shuttle-concept.jpg) |
| **Supersonic freighter**<br>Freighter concept for exploring aerospace configuration and cargo packaging; performance remains unverified. | <a href="https://github.com/robotics-intelligent-systems/jfxnpss/blob/main/MBSE/CAD/supersonic-freighter-digital-twin-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxnpss/main/MBSE/CAD/supersonic-freighter-digital-twin-concept.jpg" alt="Supersonic freighter" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxnpss/blob/main/MBSE/CAD/supersonic-freighter-digital-twin-concept.jpg) |
| **Supersonic research demonstrator**<br>Research-aircraft concept for studying configuration and simulation requirements. | <a href="https://github.com/robotics-intelligent-systems/jfxnpss/blob/main/MBSE/CAD/supersonic-research-demonstrator.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxnpss/main/MBSE/CAD/supersonic-research-demonstrator.jpg" alt="Supersonic research demonstrator" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxnpss/blob/main/MBSE/CAD/supersonic-research-demonstrator.jpg) |

### [jfxjts](https://github.com/robotics-intelligent-systems/jfxjts)

| Concept and description | Preview |
| :--- | :---: |
| **Hybrid-electric amphibious aircraft**<br>Modular aircraft concept connecting amphibious configuration and hybrid-electric integration. | <a href="https://github.com/robotics-intelligent-systems/jfxjts/blob/main/MBSE/CAD/modular-hybrid-electric-amphibious-aircraft.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxjts/main/MBSE/CAD/modular-hybrid-electric-amphibious-aircraft.jpg" alt="Hybrid-electric amphibious aircraft" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxjts/blob/main/MBSE/CAD/modular-hybrid-electric-amphibious-aircraft.jpg) |
| **Hybrid STOL air taxi**<br>Air-taxi concept for exploring short-field mission requirements and modular integration. | <a href="https://github.com/robotics-intelligent-systems/jfxjts/blob/main/MBSE/CAD/modular-hybrid-stol-air-taxi.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxjts/main/MBSE/CAD/modular-hybrid-stol-air-taxi.jpg" alt="Hybrid STOL air taxi" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxjts/blob/main/MBSE/CAD/modular-hybrid-stol-air-taxi.jpg) |
| **OpenTwin LH2 hybrid helicopter**<br>Helicopter concept for hydrogen-energy packaging and hybrid-propulsion interfaces. | <a href="https://github.com/robotics-intelligent-systems/jfxjts/blob/main/MBSE/CAD/opentwin-lh2-hybrid-helicopter-digital-twin-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxjts/main/MBSE/CAD/opentwin-lh2-hybrid-helicopter-digital-twin-concept.jpg" alt="OpenTwin LH2 hybrid helicopter" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxjts/blob/main/MBSE/CAD/opentwin-lh2-hybrid-helicopter-digital-twin-concept.jpg) |
| **Robotic motion simulator**<br>Motion-platform concept for studying simulator hardware and training interfaces. | <a href="https://github.com/robotics-intelligent-systems/jfxjts/blob/main/MBSE/CAD/robotic-motion-simulator.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxjts/main/MBSE/CAD/robotic-motion-simulator.jpg" alt="Robotic motion simulator" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxjts/blob/main/MBSE/CAD/robotic-motion-simulator.jpg) |

### [jfxai4mss](https://github.com/robotics-intelligent-systems/jfxai4mss)

| Concept and description | Preview |
| :--- | :---: |
| **Amphibious recreational vehicle**<br>RV concept connecting accommodation, road mobility and water-mode requirements. | <a href="https://github.com/robotics-intelligent-systems/jfxai4mss/blob/main/MBSE/CAD/amphibious-rv-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4mss/main/MBSE/CAD/amphibious-rv-concept.jpg" alt="Amphibious recreational vehicle" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4mss/blob/main/MBSE/CAD/amphibious-rv-concept.jpg) |
| **River cruiser**<br>River-vessel concept for studying passenger spaces and maritime integration. | <a href="https://github.com/robotics-intelligent-systems/jfxai4mss/blob/main/MBSE/CAD/river-cruiser-ship-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4mss/main/MBSE/CAD/river-cruiser-ship-concept.jpg" alt="River cruiser" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4mss/blob/main/MBSE/CAD/river-cruiser-ship-concept.jpg) |
| **Solar amphibious catamaran**<br>Catamaran concept connecting amphibious mobility and solar-energy integration. | <a href="https://github.com/robotics-intelligent-systems/jfxai4mss/blob/main/MBSE/CAD/solar-powered-amphibious-catamaran-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4mss/main/MBSE/CAD/solar-powered-amphibious-catamaran-concept.jpg" alt="Solar amphibious catamaran" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4mss/blob/main/MBSE/CAD/solar-powered-amphibious-catamaran-concept.jpg) |

### [jfxai4mjas](https://github.com/robotics-intelligent-systems/jfxai4mjas)

| Concept and description | Preview |
| :--- | :---: |
| **OpenTwin H2 seaglider and floating hangar**<br>Waterborne-aircraft and hangar concept linking electric propulsion, energy logistics and moorings. | <a href="https://github.com/robotics-intelligent-systems/jfxai4mjas/blob/main/MBSE/CAD/opentwin-h2-seaglider-floating-hangar-digital-twin-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4mjas/main/MBSE/CAD/opentwin-h2-seaglider-floating-hangar-digital-twin-concept.jpg" alt="OpenTwin H2 seaglider and floating hangar" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4mjas/blob/main/MBSE/CAD/opentwin-h2-seaglider-floating-hangar-digital-twin-concept.jpg) |
| **OpenTwin MAD LH2**<br>Compact personal-aircraft cutaway exploring hydrogen storage, fuel cells, batteries and avionics interfaces. | <a href="https://github.com/robotics-intelligent-systems/jfxai4mjas/blob/main/MBSE/CAD/opentwin-mad-lh2-digital-twin-cutaway-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4mjas/main/MBSE/CAD/opentwin-mad-lh2-digital-twin-cutaway-concept.jpg" alt="OpenTwin MAD LH2" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4mjas/blob/main/MBSE/CAD/opentwin-mad-lh2-digital-twin-cutaway-concept.jpg) |
| **OpenTwin AirJet BWB cargo UAV**<br>Blended-wing-body cargo concept with modular payloads and electric-propulsion energy interfaces. | <a href="https://github.com/robotics-intelligent-systems/jfxai4mjas/blob/main/MBSE/CAD/uav-cargo-bwb-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4mjas/main/MBSE/CAD/uav-cargo-bwb-concept.jpg" alt="OpenTwin AirJet BWB cargo UAV" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4mjas/blob/main/MBSE/CAD/uav-cargo-bwb-concept.jpg) |

### [jfxai4mass](https://github.com/robotics-intelligent-systems/jfxai4mass)

| Concept and description | Preview |
| :--- | :---: |
| **OpenTwin amphibious agricultural UGV**<br>Uncrewed agricultural-vehicle concept for modular field operations and amphibious mobility studies. | <a href="https://github.com/robotics-intelligent-systems/jfxai4mass/blob/main/MBSE/CAD/opentwin-amphibious-ugv-agricultural-robot-digital-twin-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4mass/main/MBSE/CAD/opentwin-amphibious-ugv-agricultural-robot-digital-twin-concept.jpg" alt="OpenTwin amphibious agricultural UGV" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4mass/blob/main/MBSE/CAD/opentwin-amphibious-ugv-agricultural-robot-digital-twin-concept.jpg) |
| **OpenTwin Explorer habitat**<br>Habitat concept exploring mobile and fixed configurations and service interfaces. | <a href="https://github.com/robotics-intelligent-systems/jfxai4mass/blob/main/MBSE/CAD/opentwin-explorer-mobile-fixed-habitat-digital-twin-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4mass/main/MBSE/CAD/opentwin-explorer-mobile-fixed-habitat-digital-twin-concept.jpg" alt="OpenTwin Explorer habitat" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4mass/blob/main/MBSE/CAD/opentwin-explorer-mobile-fixed-habitat-digital-twin-concept.jpg) |
| **OpenTwin modular protected truck**<br>Protected-truck concept for studying vehicle packaging and modular mission interfaces. | <a href="https://github.com/robotics-intelligent-systems/jfxai4mass/blob/main/MBSE/CAD/opentwin-modular-armor-truck-digital-twin-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4mass/main/MBSE/CAD/opentwin-modular-armor-truck-digital-twin-concept.jpg" alt="OpenTwin modular protected truck" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4mass/blob/main/MBSE/CAD/opentwin-modular-armor-truck-digital-twin-concept.jpg) |

### [jfxai4scss](https://github.com/robotics-intelligent-systems/jfxai4scss)

| Concept and description | Preview |
| :--- | :---: |
| **Modular hydrogen airship**<br>Airship concept with twin-turbine imagery; the asset alone does not establish hydrogen's technical role. | <a href="https://github.com/robotics-intelligent-systems/jfxai4scss/blob/main/MBSE/CAD/modular-hydrogen-airship-with-twin-turbines.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4scss/main/MBSE/CAD/modular-hydrogen-airship-with-twin-turbines.jpg" alt="Modular hydrogen airship" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4scss/blob/main/MBSE/CAD/modular-hydrogen-airship-with-twin-turbines.jpg) |
| **Modular hydrogen-electric helicopter**<br>Aerial-platform concept for exploring hydrogen-electric subsystem integration. | <a href="https://github.com/robotics-intelligent-systems/jfxai4scss/blob/main/MBSE/CAD/modular-hydrogen-electric-helicopter-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4scss/main/MBSE/CAD/modular-hydrogen-electric-helicopter-concept.jpg" alt="Modular hydrogen-electric helicopter" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4scss/blob/main/MBSE/CAD/modular-hydrogen-electric-helicopter-concept.jpg) |
| **Solar HAPS glider**<br>High-altitude aerial-platform concept for solar-energy and mission studies, stored in the satellite portfolio project. | <a href="https://github.com/robotics-intelligent-systems/jfxai4scss/blob/main/MBSE/CAD/solar-haps-glider-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4scss/main/MBSE/CAD/solar-haps-glider-concept.jpg" alt="Solar HAPS glider" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4scss/blob/main/MBSE/CAD/solar-haps-glider-concept.jpg) |

### [jfxai4mlrss](https://github.com/robotics-intelligent-systems/jfxai4mlrss)

| Concept and description | Preview |
| :--- | :---: |
| **Modular air launch**<br>High-level air-launch concept for mission architecture and simulation studies. | <a href="https://github.com/robotics-intelligent-systems/jfxai4mlrss/blob/main/MBSE/CAD/modular-air-launch-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4mlrss/main/MBSE/CAD/modular-air-launch-concept.jpg" alt="Modular air launch" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4mlrss/blob/main/MBSE/CAD/modular-air-launch-concept.jpg) |
| **Modular rocket**<br>Launch-vehicle concept for studying module boundaries and requirements traceability. | <a href="https://github.com/robotics-intelligent-systems/jfxai4mlrss/blob/main/MBSE/CAD/modular-rocket-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4mlrss/main/MBSE/CAD/modular-rocket-concept.jpg" alt="Modular rocket" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4mlrss/blob/main/MBSE/CAD/modular-rocket-concept.jpg) |
| **Multi-body launch configuration**<br>Multi-body launch concept for high-level configuration and interface exploration. | <a href="https://github.com/robotics-intelligent-systems/jfxai4mlrss/blob/main/MBSE/CAD/multibody-launch-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4mlrss/main/MBSE/CAD/multibody-launch-concept.jpg" alt="Multi-body launch configuration" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4mlrss/blob/main/MBSE/CAD/multibody-launch-concept.jpg) |

### [jfxai4mess](https://github.com/robotics-intelligent-systems/jfxai4mess)

| Concept and description | Preview |
| :--- | :---: |
| **Coastal hydrogen energy hub**<br>Concept linking electricity, water treatment, electrolysis, gaseous storage, distribution and fuel cells. | <a href="https://github.com/robotics-intelligent-systems/jfxai4mess/blob/main/MBSE/CAD/coastal-hydrogen-energy-hub-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4mess/main/MBSE/CAD/coastal-hydrogen-energy-hub-concept.jpg" alt="Coastal hydrogen energy hub" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4mess/blob/main/MBSE/CAD/coastal-hydrogen-energy-hub-concept.jpg) |
| **Floating tidal-energy platform**<br>Tidal-stream concept with submerged turbines, moorings, export cables and maintenance interfaces. | <a href="https://github.com/robotics-intelligent-systems/jfxai4mess/blob/main/MBSE/CAD/floating-tidal-energy-concept.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4mess/main/MBSE/CAD/floating-tidal-energy-concept.jpg" alt="Floating tidal-energy platform" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4mess/blob/main/MBSE/CAD/floating-tidal-energy-concept.jpg) |
| **Modular floating wind**<br>Wind-platform concept integrating a turbine, buoyancy structures, moorings and electrical export. | <a href="https://github.com/robotics-intelligent-systems/jfxai4mess/blob/main/MBSE/CAD/modular-floating-wind-digital-twin.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4mess/main/MBSE/CAD/modular-floating-wind-digital-twin.jpg" alt="Modular floating wind" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4mess/blob/main/MBSE/CAD/modular-floating-wind-digital-twin.jpg) |

### [jfxai4nhes](https://github.com/robotics-intelligent-systems/jfxai4nhes)

| Concept and description | Preview |
| :--- | :---: |
| **Nuclear-electric ocean research vessel**<br>Research-vessel concept for high-level energy and maritime integration studies. | <a href="https://github.com/robotics-intelligent-systems/jfxai4nhes/blob/main/MBSE/CAD/nuclear-electric-ocean-research-vessel.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4nhes/main/MBSE/CAD/nuclear-electric-ocean-research-vessel.jpg" alt="Nuclear-electric ocean research vessel" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4nhes/blob/main/MBSE/CAD/nuclear-electric-ocean-research-vessel.jpg) |
| **Modular floating energy platform**<br>Floating energy-infrastructure concept for module and service-interface exploration. | <a href="https://github.com/robotics-intelligent-systems/jfxai4nhes/blob/main/MBSE/CAD/open-modular-floating-energy-twin.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4nhes/main/MBSE/CAD/open-modular-floating-energy-twin.jpg" alt="Modular floating energy platform" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4nhes/blob/main/MBSE/CAD/open-modular-floating-energy-twin.jpg) |
| **Modular subsea energy platform**<br>Subsea energy concept for high-level packaging and digital-twin requirements. | <a href="https://github.com/robotics-intelligent-systems/jfxai4nhes/blob/main/MBSE/CAD/open-modular-subsea-energy-twin.jpg"><img src="https://raw.githubusercontent.com/robotics-intelligent-systems/jfxai4nhes/main/MBSE/CAD/open-modular-subsea-energy-twin.jpg" alt="Modular subsea energy platform" width="220"></a><br>[Open preview](https://github.com/robotics-intelligent-systems/jfxai4nhes/blob/main/MBSE/CAD/open-modular-subsea-energy-twin.jpg) |

### Projects awaiting CAD concept images

- [jfxai4rss](https://github.com/robotics-intelligent-systems/jfxai4rss) — No concept images found in `MBSE/CAD` during this review.
- [jfxai4rpcs](https://github.com/robotics-intelligent-systems/jfxai4rpcs) — No concept images found in `MBSE/CAD` during this review.
- [jfxai4rffs](https://github.com/robotics-intelligent-systems/jfxai4rffs) — No concept images found in `MBSE/CAD` during this review.
- [jfxosms](https://github.com/robotics-intelligent-systems/jfxosms) — No concept images found in `MBSE/CAD` during this review.
- [jfxlms4air](https://github.com/robotics-intelligent-systems/jfxlms4air) — No concept images found in `MBSE/CAD` during this review.
- [jfxai4ceps](https://github.com/robotics-intelligent-systems/jfxai4ceps) — No concept images found in `MBSE/CAD` during this review.
- [jfxscada](https://github.com/robotics-intelligent-systems/jfxscada) — No concept images found in `MBSE/CAD` during this review.
- [jfxai4arch](https://github.com/robotics-intelligent-systems/jfxai4arch) — No concept images found in `MBSE/CAD` during this review.
- [jfxai4bio](https://github.com/robotics-intelligent-systems/jfxai4bio) — No concept images found in `MBSE/CAD` during this review.
- [jfxai4cv](https://github.com/robotics-intelligent-systems/jfxai4cv) — No concept images found in `MBSE/CAD` during this review.
- [jfxai4nlp](https://github.com/robotics-intelligent-systems/jfxai4nlp) — No concept images found in `MBSE/CAD` during this review.
- [jfxai4cbs](https://github.com/robotics-intelligent-systems/jfxai4cbs) — No concept images found in `MBSE/CAD` during this review.
- [jfxai4rs](https://github.com/robotics-intelligent-systems/jfxai4rs) — No concept images found in `MBSE/CAD` during this review.
- [jfxai4mar](https://github.com/robotics-intelligent-systems/jfxai4mar) — No concept images found in `MBSE/CAD` during this review.
- [jfxai4bpm](https://github.com/robotics-intelligent-systems/jfxai4bpm) — No concept images found in `MBSE/CAD` during this review.
- [jfxai4ats](https://github.com/robotics-intelligent-systems/jfxai4ats) — No concept images found in `MBSE/CAD` during this review.
- [jfxai4obs](https://github.com/robotics-intelligent-systems/jfxai4obs) — No concept images found in `MBSE/CAD` during this review.
- [jfxai4ohs](https://github.com/robotics-intelligent-systems/jfxai4ohs) — No concept images found in `MBSE/CAD` during this review.
- [jfxbsc](https://github.com/robotics-intelligent-systems/jfxbsc) — No concept images found in `MBSE/CAD` during this review.
- [jfxai4crm](https://github.com/robotics-intelligent-systems/jfxai4crm) — No concept images found in `MBSE/CAD` during this review.
- [jfxai4rts](https://github.com/robotics-intelligent-systems/jfxai4rts) — No concept images found in `MBSE/CAD` during this review.
- [jfxoqss](https://github.com/robotics-intelligent-systems/jfxoqss) — No concept images found in `MBSE/CAD` during this review.
- [jfxoss](https://github.com/robotics-intelligent-systems/jfxoss) — No concept images found in `MBSE/CAD` during this review.
- [jfxorss](https://github.com/robotics-intelligent-systems/jfxorss) — No concept images found in `MBSE/CAD` during this review.
- [jfxcms](https://github.com/robotics-intelligent-systems/jfxcms) — No concept images found in `MBSE/CAD` during this review.
- [jfxlms](https://github.com/robotics-intelligent-systems/jfxlms) — No concept images found in `MBSE/CAD` during this review.
- [jfxnms](https://github.com/robotics-intelligent-systems/jfxnms) — No concept images found in `MBSE/CAD` during this review.

## Shared Services and Integration Priorities

The proposed division of responsibilities gives **JFXAI4ARCH** a shared technical
knowledge and inference role, with **JFXAI4NLP** focused on language extraction,
code intelligence and evaluation. Domain projects own their engineering workflows,
validation and decisions. Cross-project interfaces remain integration work unless
the corresponding repositories document an implementation.

An [initial local RAG pilot](https://github.com/robotics-intelligent-systems/jfxai4arch/blob/main/docs/rag/PILOT.md)
is available in JFXAI4ARCH: Markdown/TXT retrieval with LlamaIndex interfaces,
source hashes and line references, optional local Ollama generation, a Langfuse
metadata adapter and Bruno API checks. It is a small single-user baseline;
real-model quality and a live Langfuse deployment still need validation. It does
not establish a portfolio-wide knowledge platform or document-level access control.

The next integrations are **proposed pilots**, selected according to available
data and maintainers:

| Direction | Host projects | Evidence required before adoption |
| --- | --- | --- |
| Technical answers with sources | JFXAI4ARCH + JFXAI4NLP | Curated questions, retrieval quality, supported citations, abstention and latency |
| Text-to-CAD and manufacturing artifacts | JFXAI4DIA + JFXOSMS, with JFXAI4BSS for building applications | Geometry, units, dimensions, simulation results and traceable artifacts |
| Inspection and mapping | JFXLMS4AIR | Versioned LiDAR captures, annotated changes and registration/detection metrics |
| Agricultural scenarios | JFXFMIS, with JFXSCADA for telemetry | Soil/crop/water inputs, units, calibration and reproducible scenarios |
| Enterprise adapters | JFXAI4BPM + JFXAI4CRM + JFXAI4OHS | Explicit API contracts, scoped access, audit records and regression checks |
| Embedded laboratory workflows | JFXRTESS + JFXSCADA | Reproducible firmware builds and measured bench results |

Components from a technology compendium are candidates, tools or references until
adoption is supported by a versioned implementation and domain-specific tests.
AI-generated suggestions remain inputs to engineering review; geometry checks,
code tests, simulations and domain validation determine acceptance.

## Complementary Projects under sdk2035

These repositories are maintained under **sdk2035**, separately from the
organization's catalog. They are complementary integration candidates with their
own scope, implementation status and licensing.

| Repository | Complementary role | Status | Estimated progress | Next AI-assisted task (proposed) |
| --- | --- | --- | --- | --- |
| [sdk2035/jfxlcdp](https://github.com/sdk2035/jfxlcdp) | Low-code authoring and declarative interfaces | Architecture / documentation | `██░░░░░░░░` ~20% | Specify one metadata-to-JavaFX screen and its acceptance tests. |
| [sdk2035/jfxengine](https://github.com/sdk2035/jfxengine) | Engineering visualization and model integration in 3D environments | Architecture / documentation | `██░░░░░░░░` ~20% | Turn one SysML-to-visualization use case into a testable vertical slice. |
| [sdk2035/jfxmodelica](https://github.com/sdk2035/jfxmodelica) | Physical modeling, simulation and digital-twin architecture | Architecture / documentation | `██░░░░░░░░` ~20% | Draft one FMU/worker simulation contract and reproducible example. |
| [sdk2035/jfxlegacy2modern](https://github.com/sdk2035/jfxlegacy2modern) | Legacy-code analysis and modernization workflows | Architecture / documentation | `██░░░░░░░░` ~20% | Select one legacy fixture and draft behavior-preserving migration checks. |

A reference to one of these projects or to an upstream fork does not establish an
installed dependency or a completed cross-project integration.

## Technology and Architecture

The portfolio favors **replaceable services, versioned artifacts and explicit
contracts**. Technology choices belong to each project and deployment profile.

| Layer | Integration direction |
| --- | --- |
| Interfaces and visualization | JavaFX for desktop experiences; web interfaces where the use case requires them |
| Language and model engineering | JVM components, Rascal/Spoon and domain-specific languages where appropriate; GraalVM/Truffle are evaluated per component |
| Scientific and AI workloads | Python, Julia, R or native workers behind documented APIs when separate runtimes fit the workload |
| Physical modeling | Modelica and discipline-specific solvers with explicit units, parameters and validation |
| Knowledge and inference | Source-linked retrieval, replaceable model endpoints and measured answer quality |
| Robotics, telemetry and enterprise integration | Project-owned adapters for devices, ROS, data acquisition and business systems |
| Evidence and observability | Versioned jobs, artifact provenance, API checks and reproducible domain evaluations |

Libraries may run in-process where compatibility is established. Scientific
workers and external systems may use separate services. Development tools,
datasets, hardware designs and documentation belong to the appropriate workflow,
not automatically to a product's runtime. The portfolio does not require every
component to execute within GraalVM or a single application.

Select a small baseline first. Add distributed execution, semantic caching,
additional databases or cloud services when measurements and deployment needs
justify them. Record the chosen versions, upstream provenance, artifact licenses,
maintainer, integration contract and validation results for every adopted component.

## Getting Started

1. Select a project from the catalog and read its scope and implementation status.
2. Review its license, upstream references and contribution instructions.
3. Follow that repository's documented prerequisites and build or inspection steps.
4. Use its issues to discuss a reproducible problem or a scoped improvement.

For a runnable technical-knowledge starting point, follow the
[JFXAI4ARCH pilot guide](https://github.com/robotics-intelligent-systems/jfxai4arch/blob/main/docs/rag/PILOT.md).
For an example of a domain architecture, inspect the maritime engineering project:

```bash
git clone https://github.com/robotics-intelligent-systems/jfxmbdss.git
cd jfxmbdss
```

Cloning retrieves the repository; it does not install or launch a simulation
platform. Build commands, runtime versions and optional dependencies belong in
the selected project's documentation.

## Contributing and Collaboration

We welcome contributions to documentation, requirements, models, adapters,
educational material, test cases and reproducible experiments.

For a project-specific contribution:

- Open an issue in the relevant repository with the goal, context and expected outcome.
- Identify whether the work concerns a proposal, prototype or implemented feature.
- Submit a focused pull request with validation evidence and upstream attribution.
- Follow the repository's license and contribution guidance.

Research and technical collaboration proposals can begin in the relevant project's
issues. Browse the [organization repositories](https://github.com/orgs/robotics-intelligent-systems/repositories)
to find the closest domain.

**Model before integration. Validate with evidence. Keep components replaceable.**
