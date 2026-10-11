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
