<p align="center"><img src="https://raw.githubusercontent.com/elasticproject-eu/.github/main/profile/banner_elastic.png" width="100%" alt="ELASTIC: Efficient, portabLe And Secure orchesTration for reliable servICes. Revolutionizing connectivity with smart security"></p>

<p align="center"><a href="https://elasticproject.eu/">Website</a> · <a href="#technology-components">Technology components</a> · <a href="#demonstrators">Demonstrators</a> · <a href="https://cordis.europa.eu/project/id/101139067">CORDIS</a></p>

---

## About ELASTIC

Future 6G services will operate across a highly distributed edge-cloud continuum including IoT devices, industrial edge nodes, private infrastructures, and public clouds. ELASTIC addresses the need for secure, portable, and trustworthy service execution across these complex environments.

**ELASTIC enables:**

- Secure and portable workload execution
- Trustworthy distributed orchestration
- Privacy-preserving edge-cloud services
- Efficient operation across heterogeneous infrastructures
- Resilient and adaptive 6G service deployment

### Core technology pillars

| Technology | Role in ELASTIC |
|---|---|
| **WebAssembly (Wasm)** | Lightweight and portable execution |
| **eBPF** | High-performance observability and communication |
| **Confidential Computing** | Protected processing in trusted environments |
| **Remote Attestation** | Verification of infrastructure trust before execution |
| **Serverless orchestration** | Adaptive deployment from cloud to far edge |

## Demonstrators

ELASTIC validates its vision through two demonstrators and 27 technology components.

| | Demonstrator 1 — Smart Connected Factory of the Future | Demonstrator 2 — Privacy-Preserving Cloud Migration |
|---|---|---|
| **Goal** | Validates a secure and scalable IoT Data Fabric for future industrial environments, enabling trusted data processing and intelligent orchestration across distributed edge-cloud infrastructures. | Validates the secure migration and execution of sensitive enterprise services across cloud-edge infrastructures using confidential computing, attestation, and trusted orchestration. |
| **Scenarios** | Predictive maintenance · Cross-factory data sharing through federated learning | Badge Request Tool (BRT): migration of a sensitive enterprise application managing employee identity and access information |
| **Led by** | Ericsson Finland | Thales DIS |

## ELASTIC Architecture & Innovation Ecosystem

ELASTIC introduces a **modular architecture** for secure and resource-efficient orchestration of 6G services across the cloud-edge continuum.

The framework brings together interoperable technologies for trustworthy execution, intelligent orchestration, confidential computing, observability, and secure communication across heterogeneous infrastructures.

### Five functional blocks

<table>
<tr><th>Functional block</th><th>What it provides</th><th>Components</th><th>Open source</th></tr>
<tr><td nowrap><img src="https://img.shields.io/badge/BLOCK%201-1f6feb?style=flat-square" alt="Block 1"><br><b><a href="#block-1--orchestration">Orchestration</a></b></td><td>Adaptive workload management across distributed edge-cloud infrastructures.</td><td align="center">7</td><td align="center">4</td></tr>
<tr><td nowrap><img src="https://img.shields.io/badge/BLOCK%202-8250df?style=flat-square" alt="Block 2"><br><b><a href="#block-2--isolation--confidentiality">Isolation & Confidentiality</a></b></td><td>Secure workload isolation and confidential execution using WebAssembly and Trusted Execution Environments.</td><td align="center">7</td><td align="center">5</td></tr>
<tr><td nowrap><img src="https://img.shields.io/badge/BLOCK%203-1a7f37?style=flat-square" alt="Block 3"><br><b><a href="#block-3--communication">Communication</a></b></td><td>Efficient, low-latency communication for distributed services and edge-cloud coordination.</td><td align="center">3</td><td align="center">3</td></tr>
<tr><td nowrap><img src="https://img.shields.io/badge/BLOCK%204-bf8700?style=flat-square" alt="Block 4"><br><b><a href="#block-4--monitoring--detection">Monitoring & Detection</a></b></td><td>Runtime observability, performance monitoring, and AI-driven security detection.</td><td align="center">5</td><td align="center">2</td></tr>
<tr><td nowrap><img src="https://img.shields.io/badge/BLOCK%205-cf222e?style=flat-square" alt="Block 5"><br><b><a href="#block-5--trust--access-control">Trust & Access Control</a></b></td><td>Remote attestation, policy enforcement, access control, and zero-trust mechanisms.</td><td align="center">5</td><td align="center">1</td></tr>
</table>

Through these five blocks, ELASTIC develops **27 interoperable technology components** supporting secure, portable, and trustworthy service execution for future 6G ecosystems.

## Technology components

All 27 ELASTIC technology components are listed below, grouped by functional block. **15 are open source** (14 with public code today, 1 to be released soon). For the other 12, contact the partner that develops them; their contact details are given on each component's entry.

<table>
<tr><th>Component</th><th>Partner</th><th>Availability</th><th>Code</th><th>Docs</th></tr>
<tr><td colspan="5"><a href="#block-1--orchestration"><img src="https://img.shields.io/badge/BLOCK%201-Orchestration-1f6feb?style=flat-square" alt="Block 1: Orchestration"></a></td></tr>
<tr><td><a href="#propeller-orchestrator">Propeller Orchestrator</a></td><td>Abstract Machines</td><td><img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source"></td><td><a href="https://github.com/absmach/propeller">Repo</a></td><td><a href="https://propeller.absmach.eu/docs">Docs</a></td></tr>
<tr><td><a href="#wasm-operator">Wasm-operator</a></td><td>imec</td><td><img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source"></td><td><a href="https://github.com/idlab-discover/wasm-operator">Repo</a></td><td><a href="https://doi.org/10.48550/arXiv.2209.01077">Paper</a></td></tr>
<tr><td><a href="#federated-learning-as-a-service">Federated Learning as a Service</a></td><td>Telefónica Innovación Digital</td><td><img src="https://img.shields.io/badge/Access-on%20request-6e7781?style=flat-square" alt="Access on request"></td><td>—</td><td>—</td></tr>
<tr><td><a href="#federated-learning-toolbox">Federated Learning Toolbox</a></td><td>Zentrix Lab</td><td><img src="https://img.shields.io/badge/Access-on%20request-6e7781?style=flat-square" alt="Access on request"></td><td>—</td><td><a href="https://zentrixlab.com/">Info</a></td></tr>
<tr><td><a href="#light-weight-security-orchestrator-for-edge-devices">Light-weight Security Orchestrator for Edge Devices</a></td><td>Thales SIX</td><td><img src="https://img.shields.io/badge/Access-on%20request-6e7781?style=flat-square" alt="Access on request"></td><td>—</td><td>—</td></tr>
<tr><td><a href="#tee-software-management-agent">TEE Software Management Agent</a></td><td>Ultraviolet</td><td><img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source"></td><td><a href="https://github.com/absmach/propeller/tree/main/proplet">Repo</a></td><td><a href="https://propeller.absmach.eu/docs/tee">Docs</a></td></tr>
<tr><td><a href="#reliable-enclave-migration-protocols">Reliable Enclave Migration Protocols</a></td><td>Aalto University</td><td><img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source"></td><td><a href="https://github.com/elasticproject-eu/corndog">Repo</a></td><td>—</td></tr>
<tr><td colspan="5"><a href="#block-2--isolation--confidentiality"><img src="https://img.shields.io/badge/BLOCK%202-Isolation%20%26%20Confidentiality-8250df?style=flat-square" alt="Block 2: Isolation & Confidentiality"></a></td></tr>
<tr><td><a href="#data-protection-at-rest-at-the-edge-with-tee-solution">Data Protection at Rest at the Edge with TEE Solution</a></td><td>Thales SIX</td><td><img src="https://img.shields.io/badge/Access-on%20request-6e7781?style=flat-square" alt="Access on request"></td><td>—</td><td>—</td></tr>
<tr><td><a href="#wasmhal-trust-teehal">WasmHAL-Trust (TEEHAL)</a></td><td>Lund University</td><td><img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source"></td><td><a href="https://github.com/elasticproject-eu/wasmhal">Repo</a></td><td>—</td></tr>
<tr><td><a href="#wasi-security">WASI Security</a></td><td>imec</td><td><img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source"></td><td><a href="https://github.com/idlab-discover/masters-wasi-security/tree/blocking_rules_policy_file">Repo</a></td><td>—</td></tr>
<tr><td><a href="#automatic-mac-profiles-for-wasm-runtime-containers">Automatic MAC Profiles for Wasm Runtime Containers</a></td><td>Lund University</td><td><img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source"></td><td><a href="https://github.com/syafiq/enforcement-service">Repo</a></td><td><a href="https://github.com/syafiq/enforcement-service/blob/HEAD/GETTING_STARTED.md">Docs</a></td></tr>
<tr><td><a href="#wasmhal-hardware-sdk">WasmHAL Hardware SDK</a></td><td>imec</td><td><img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source"></td><td><a href="https://github.com/idlab-discover/usb-wasm">Repo</a></td><td>—</td></tr>
<tr><td><a href="#static-ebpf-code-security-analyser-pretty-verifier">Static eBPF Code Security Analyser (Pretty Verifier)</a></td><td>Politecnico di Torino</td><td><img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source"></td><td><a href="https://github.com/netgroup-polito/pretty-verifier">Repo</a></td><td><a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6727186">Paper</a></td></tr>
<tr><td><a href="#witchcraft-a-webassembly-component-hooking-framework">WITCHCRAFT: A WebAssembly Component Hooking Framework</a></td><td>Ericsson Finland</td><td><img src="https://img.shields.io/badge/Access-on%20request-6e7781?style=flat-square" alt="Access on request"></td><td>—</td><td>—</td></tr>
<tr><td colspan="5"><a href="#block-3--communication"><img src="https://img.shields.io/badge/BLOCK%203-Communication-1a7f37?style=flat-square" alt="Block 3: Communication"></a></td></tr>
<tr><td><a href="#accelerated-microservices-interconnection">Accelerated Microservices Interconnection</a></td><td>Politecnico di Torino</td><td><img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source"></td><td><a href="https://github.com/miolad/linux-tcpless">Repo</a></td><td>—</td></tr>
<tr><td><a href="#ebpf-distributed-state-synchronisation">eBPF Distributed State Synchronisation</a></td><td>Politecnico di Torino</td><td><img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source"></td><td><a href="https://github.com/miolad/ebpf-distributed-htab">Repo</a></td><td>—</td></tr>
<tr><td><a href="#static-analysis-of-interaction-between-wasm-modules">Static Analysis of Interaction between Wasm Modules</a></td><td>Aalto University</td><td><img src="https://img.shields.io/badge/Open%20source-to%20be%20released-1a7f37?style=flat-square" alt="Open source, to be released"></td><td><a href="https://github.com/elasticproject-eu/wasm-attestation">Soon</a></td><td>—</td></tr>
<tr><td colspan="5"><a href="#block-4--monitoring--detection"><img src="https://img.shields.io/badge/BLOCK%204-Monitoring%20%26%20Detection-bf8700?style=flat-square" alt="Block 4: Monitoring & Detection"></a></td></tr>
<tr><td><a href="#netto">NETTO</a></td><td>Politecnico di Torino</td><td><img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source"></td><td><a href="https://github.com/miolad/netto">Repo</a></td><td><a href="https://iris.polito.it/retrieve/handle/11583/2992332/086c1e80-0c27-4850-91b9-a958bd405edd/netdev-0x17-paper34-talk-paper.pdf">Paper</a></td></tr>
<tr><td><a href="#observability-framework-for-serverless-workloads">Observability Framework for Serverless Workloads</a></td><td>Ericsson Finland</td><td><img src="https://img.shields.io/badge/Access-on%20request-6e7781?style=flat-square" alt="Access on request"></td><td>—</td><td><a href="https://youtu.be/5P1HITjYWmE">Info</a></td></tr>
<tr><td><a href="#artificial-intelligence-intrusion-detection-system">Artificial Intelligence Intrusion Detection System</a></td><td>Technical University of Crete</td><td><img src="https://img.shields.io/badge/Access-on%20request-6e7781?style=flat-square" alt="Access on request"></td><td>—</td><td>—</td></tr>
<tr><td><a href="#lightweight-hardware-based-cryptography-module">Lightweight Hardware-based Cryptography Module</a></td><td>Technical University of Crete</td><td><img src="https://img.shields.io/badge/Access-on%20request-6e7781?style=flat-square" alt="Access on request"></td><td>—</td><td>—</td></tr>
<tr><td><a href="#mobility-attack-robust-iot-resource-allocation-model">Mobility Attack Robust IoT Resource Allocation Model</a></td><td>Lund University</td><td><img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source"></td><td><a href="https://github.com/nwdaf-research/dataset-attack">Repo</a></td><td><a href="https://zenodo.org/records/13969430">Paper</a></td></tr>
<tr><td colspan="5"><a href="#block-5--trust--access-control"><img src="https://img.shields.io/badge/BLOCK%205-Trust%20%26%20Access%20Control-cf222e?style=flat-square" alt="Block 5: Trust & Access Control"></a></td></tr>
<tr><td><a href="#remote-attestations-platform">Remote Attestations Platform</a></td><td>Thales DIS</td><td><img src="https://img.shields.io/badge/Access-on%20request-6e7781?style=flat-square" alt="Access on request"></td><td>—</td><td>—</td></tr>
<tr><td><a href="#key-broker-service">Key Broker Service</a></td><td>Thales DIS</td><td><img src="https://img.shields.io/badge/Access-on%20request-6e7781?style=flat-square" alt="Access on request"></td><td>—</td><td>—</td></tr>
<tr><td><a href="#multi-platform-attestation-component">Multi-platform Attestation Component</a></td><td>Ericsson Finland</td><td><img src="https://img.shields.io/badge/Access-on%20request-6e7781?style=flat-square" alt="Access on request"></td><td>—</td><td><a href="https://youtu.be/cs7SY35RHa4">Info</a></td></tr>
<tr><td><a href="#lightweight-abac-solution">Lightweight ABAC Solution</a></td><td>Thales SIX</td><td><img src="https://img.shields.io/badge/Access-on%20request-6e7781?style=flat-square" alt="Access on request"></td><td>—</td><td>—</td></tr>
<tr><td><a href="#wasi-flexibly-defined-capabilities">WASI Flexibly-defined Capabilities</a></td><td>Aalto University</td><td><img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source"></td><td><a href="https://github.com/elasticproject-eu/wacky">Repo</a></td><td>—</td></tr>
</table>

<br>

<p align="center"><img src="https://img.shields.io/badge/BLOCK%201-ORCHESTRATION-1f6feb?style=for-the-badge" alt="Block 1: Orchestration"></p>

## Block 1 · Orchestration

> **Adaptive workload management across distributed edge-cloud infrastructures.**
>
> Components in this block: [Propeller Orchestrator](#propeller-orchestrator) · [Wasm-operator](#wasm-operator) · [Federated Learning as a Service](#federated-learning-as-a-service) · [Federated Learning Toolbox](#federated-learning-toolbox) · [Light-weight Security Orchestrator for Edge Devices](#light-weight-security-orchestrator-for-edge-devices) · [TEE Software Management Agent](#tee-software-management-agent) · [Reliable Enclave Migration Protocols](#reliable-enclave-migration-protocols)

### Propeller Orchestrator

<img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source">

*Cloud-to-IoT lightweight orchestration*

Propeller enables secure and lightweight orchestration of WebAssembly workloads across distributed edge-cloud and IoT environments, including constrained and resource-limited devices.

- Kubernetes integration via operator
- WebAssembly-native deployment
- Real-time FaaS execution
- Event-driven service management
- Ultra-lightweight footprint
- IoT and microcontroller support
- Low-latency distributed services
- Secure cloud-edge deployment

Propeller is used in both ELASTIC Demonstrator 1 (6G IoT data fabric services) and Demonstrator 2 (secure workload migration across trust boundaries).

**Repository:** https://github.com/absmach/propeller<br>
**Documentation:** https://propeller.absmach.eu/docs<br>
**Partner:** [Abstract Machines](https://www.abstractmachines.fr)

<br>

### Wasm-operator

<img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source">

*Efficient WebAssembly orchestration for Kubernetes*

Wasm-operator enables Kubernetes operators to run as event-based serverless functions in WebAssembly, reducing memory usage and improving efficiency in low-resource environments.

- Kubernetes operator optimisation
- Reduced memory footprint
- WebAssembly-based runtime efficiency
- Compatibility with kube-rs operators

**Repository:** https://github.com/idlab-discover/wasm-operator<br>
**Paper:** https://doi.org/10.48550/arXiv.2209.01077<br>
**Partner:** [imec](https://www.imec.be)

<br>

### Federated Learning as a Service

<img src="https://img.shields.io/badge/Access-on%20request-6e7781?style=flat-square" alt="Access on request">

*Privacy-preserving machine learning across the computing continuum*

FLaaS enables collaborative machine learning across the computing continuum without centralising raw data, supporting privacy-preserving AI in heterogeneous environments.

- Hybrid federated and split learning as a service
- Machine learning training on constrained devices
- Privacy-preserving and TEE-enhanced secure model training
- Lower adoption barrier for distributed machine learning

**Partner:** [Telefónica Innovación Digital](https://telefonicainnovaciondigital.com/)<br>
**Contact:** Fionn Mc Inerney (fionn.mcinerney@telefonica.com)

<br>

### Federated Learning Toolbox

<img src="https://img.shields.io/badge/Access-on%20request-6e7781?style=flat-square" alt="Access on request">

*Privacy-preserving collaborative AI across distributed environments*

The Federated Learning Toolbox enables organisations to collaboratively train AI models across distributed industrial environments while keeping sensitive data local. The framework supports scalable and portable AI execution across heterogeneous cloud and edge systems.

- Privacy-preserving AI training without raw data sharing
- Collaborative analytics across distributed industrial environments
- Portable execution across heterogeneous cloud and edge infrastructures
- Modular and scalable orchestration of federated AI workflows
- Support for secure cross-organisational AI collaboration

**More information:** https://zentrixlab.com/<br>
**Partner:** [Zentrix Lab](https://zentrixlab.com/)<br>
**Contact:** office@zentrixlab.eu

<br>

### Light-weight Security Orchestrator for Edge Devices

<img src="https://img.shields.io/badge/Access-on%20request-6e7781?style=flat-square" alt="Access on request">

*Security orchestration at the edge*

This component manages and deploys WebAssembly security functions according to security policies and SSLAs, enabling adaptive protection across edge and cloud environments.

- Lightweight security orchestration
- Policy-driven workload protection
- SSLA-aware security enforcement
- Dynamic adaptation to threats
- Security for constrained edge devices

**Partner:** [Thales SIX](https://www.thalesgroup.com/en)<br>
**Contact:** Dhouha Ayed (dhouha.ayed@thalesgroup.com)

<br>

### TEE Software Management Agent

<img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source">

*Secure workload lifecycle management inside TEEs*

The TEE Software Management Agent supports secure execution, attestation, cryptographic handling, and policy enforcement for sensitive workloads running inside Trusted Execution Environments.

- Trusted workload execution enablement
- Secure enclave lifecycle management
- Remote attestation support
- Propeller Orchestrator integration
- Security policy enforcement

**Repository:** https://github.com/absmach/propeller/tree/main/proplet<br>
**Documentation:** https://propeller.absmach.eu/docs/tee<br>
**Guide — Run inside a TEE:** https://github.com/absmach/propeller/blob/main/proplet/README.md#run-inside-a-tee<br>
**Partner:** [Ultraviolet](https://ultraviolet.rs)

<br>

### Reliable Enclave Migration Protocols

<img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source">

*Fault-tolerant migration for confidential workloads*

This component enables reliable migration of sensitive resources between TEEs, ensuring that protected workloads can move securely without data loss or duplication.

- **Atomic migration between platforms:** No doubt as to who is responsible for a migrated resource after-the-fact
- **Accountability:** System operators can act confidently once migration completes, since they can prove that the other node will receive the same result
- **Performance:** Optimistic protocol allows migration to proceed without any external coordination nodes unless a problem occurs
- **Fault-tolerance:** Coordination infrastructure can be replicated to avoid single points of failure

**Repository:** https://github.com/elasticproject-eu/corndog<br>
**Partner:** [Aalto University](https://www.aalto.fi/en)

<p align="right"><a href="#technology-components">↑ Back to component overview</a></p>

<br>

<p align="center"><img src="https://img.shields.io/badge/BLOCK%202-ISOLATION%20%26%20CONFIDENTIALITY-8250df?style=for-the-badge" alt="Block 2: Isolation & Confidentiality"></p>

## Block 2 · Isolation & Confidentiality

> **Secure workload isolation and confidential execution using WebAssembly and Trusted Execution Environments.**
>
> Components in this block: [Data Protection at Rest at the Edge with TEE Solution](#data-protection-at-rest-at-the-edge-with-tee-solution) · [WasmHAL-Trust (TEEHAL)](#wasmhal-trust-teehal) · [WASI Security](#wasi-security) · [Automatic MAC Profiles for Wasm Runtime Containers](#automatic-mac-profiles-for-wasm-runtime-containers) · [WasmHAL Hardware SDK](#wasmhal-hardware-sdk) · [Static eBPF Code Security Analyser (Pretty Verifier)](#static-ebpf-code-security-analyser-pretty-verifier) · [WITCHCRAFT: A WebAssembly Component Hooking Framework](#witchcraft-a-webassembly-component-hooking-framework)

### Data Protection at Rest at the Edge with TEE Solution

<img src="https://img.shields.io/badge/Access-on%20request-6e7781?style=flat-square" alt="Access on request">

*Transparent encryption for secure edge workloads*

This component protects data at rest generated by WebAssembly workloads running inside TEEs, enabling transparent encryption for sensitive edge environments.

- Edge-ready data protection
- Data-at-rest confidentiality on untrusted hosts
- Protection for WASM workloads
- TEE-based secure processing
- Hardware root-of-trust integration

**Partner:** [Thales SIX](https://www.thalesgroup.com/en)<br>
**Contact:** Louis Cailliot (louis.cailliot@thalesgroup.com)

<br>

### WasmHAL-Trust (TEEHAL)

<img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source">

*Portable WebAssembly execution across confidential environments*

WasmHAL-Trust provides a Hardware Abstraction Layer (HAL) for secure and portable WebAssembly workloads across different Trusted Execution Environments.

- WASI-compliant HAL interface
- Portable confidential workloads across different Trusted Execution Environments (TEEs)
- Multi-TEE (AMD SEV-SNP, Intel TDX) execution support
- Protected storage capabilities
- Attestation interface
- Cryptographic operations interface
- Secure migration support

**Repository:** https://github.com/elasticproject-eu/wasmhal<br>
**Partner:** [Lund University](https://www.lunduniversity.lu.se)

<br>

### WASI Security

<img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source">

*Standardised access control policies for WebAssembly workloads*

WASI Security defines a portable policy mechanism for enforcing fine-grained permissions across WebAssembly runtimes and orchestration environments.

- Standardised WASI security policies
- Fine-grained workload permissions
- Secure device and file access

**Repository:** https://github.com/idlab-discover/masters-wasi-security/tree/blocking_rules_policy_file<br>
**Partner:** [imec](https://www.imec.be)

<br>

### Automatic MAC Profiles for Wasm Runtime Containers

<img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source">

*Automated least-privilege protection for WebAssembly workloads*

This component automatically generates restrictive Mandatory Access Control profiles in compliance with the ELASTIC Wasm HAL for WebAssembly workloads, reducing privileges and minimising attack surfaces.

- Automatic MAC profile generation
- Least-privilege enforcement
- Reduced attack surface
- Wasm workload profiling
- Low configuration effort
- Runtime protection automation

**Repository:** https://github.com/syafiq/enforcement-service<br>
**Getting started:** https://github.com/syafiq/enforcement-service/blob/HEAD/GETTING_STARTED.md<br>
**Architecture:** https://github.com/syafiq/enforcement-service/blob/HEAD/ARCHITECTURE.md<br>
**Partner:** [Lund University](https://www.lunduniversity.lu.se)

<br>

### WasmHAL Hardware SDK

<img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source">

*Secure hardware access for WebAssembly applications*

WasmHAL Hardware SDK enables WebAssembly applications to securely access hardware interfaces across platforms through standardised APIs and runtime extensions.

- Sandboxed device drivers
- USB, I2C, SPI & GPIO support
- Supporting multi-decade support periods
- Microcontrollers & embedded Linux

**WASI standardisation proposals** (WebAssembly System Interface)

| Interface | Proposal | Phase | Implementation |
|---|---|---|---|
| I2C | [wasi-i2c](https://github.com/WebAssembly/wasi-i2c) | Phase 2 | [i2c-wasm-components](https://github.com/idlab-discover/i2c-wasm-components) (in collaboration with Siemens) |
| USB | [wasi-usb](https://github.com/WebAssembly/wasi-usb) | Phase 1 | [usb-wasm](https://github.com/idlab-discover/usb-wasm) |
| GPIO | [wasi-gpio](https://github.com/WebAssembly/wasi-gpio) | Phase 1 | [masters-jarno-vanruymbeke](https://github.com/idlab-discover/masters-jarno-vanruymbeke) |
| SPI | [SPI WIT definitions](https://github.com/idlab-discover/masters-jarno-vanruymbeke/tree/main/SPI/wit) | Phase 1 | — |

**Repository:** https://github.com/idlab-discover/usb-wasm<br>
**Partner:** [imec](https://www.imec.be)

<br>

### Static eBPF Code Security Analyser (Pretty Verifier)

<img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source">

*Early security feedback for eBPF developers*

This analyser detects security issues in eBPF C source code before deployment, helping developers understand and fix issues earlier in the development process.

- Security-aware eBPF development
- Clear verifier error explanations
- Developer-friendly fix guidance
- Reduced debugging time

**Repository:** https://github.com/netgroup-polito/pretty-verifier<br>
**Paper (preprint):** https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6727186<br>
**Partner:** [Politecnico di Torino](https://www.polito.it/)

<br>

### WITCHCRAFT: A WebAssembly Component Hooking Framework

<img src="https://img.shields.io/badge/Access-on%20request-6e7781?style=flat-square" alt="Access on request">

*Granular access control, observability, and custom logic for WebAssembly Component Model applications*

This framework enables dynamic interception of WebAssembly Component function calls at runtime, supporting access control enforcement, observability, and arbitrary logic injection without modifying guest binaries.

- Function call interception at component boundaries
- Runtime-swappable interception logic compiled as native dynamic libraries
- Argument inspection and modification, call bypass, and termination
- WIT-based Rust-native hook development kit
- Runtime interaction and persistent state across invocations
- Built on Wasmtime with Canonical ABI conformance

**Partner:** [Ericsson Finland](https://www.ericsson.com)<br>
**Contact:** Joonas Bjork (joonas.bjork@ericsson.com), Rajat Kandoi (rajat.kandoi@ericsson.com)

<p align="right"><a href="#technology-components">↑ Back to component overview</a></p>

<br>

<p align="center"><img src="https://img.shields.io/badge/BLOCK%203-COMMUNICATION-1a7f37?style=for-the-badge" alt="Block 3: Communication"></p>

## Block 3 · Communication

> **Efficient, low-latency communication for distributed services and edge-cloud coordination.**
>
> Components in this block: [Accelerated Microservices Interconnection](#accelerated-microservices-interconnection) · [eBPF Distributed State Synchronisation](#ebpf-distributed-state-synchronisation) · [Static Analysis of Interaction between Wasm Modules](#static-analysis-of-interaction-between-wasm-modules)

### Accelerated Microservices Interconnection

<img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source">

*High-performance networking for cloud-native services*

This component accelerates TCP communication within and between cluster nodes, improving throughput and reducing latency for micro services-based infrastructures.

- Ready for cloud-native deployments
- Intra- and inter-node acceleration
- eBPF and RDMA network optimizations
- Higher throughput and lower latency for TCP traffic

**Repository:** https://github.com/miolad/linux-tcpless<br>
**Partner:** [Politecnico di Torino](https://www.polito.it/)

<br>

### eBPF Distributed State Synchronisation

<img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source">

*Ultra-low-latency eBPF state sharing across servers*

This component extends eBPF maps across networked hosts, enabling fast state synchronisation between distributed eBPF probes.

- Sub-100µs target delay on data-center networks
- Eventual-consistency data replication
- Unlimited horizontal scalability
- Supports hash maps, more to come
- No kernel modifications required

**Repository:** https://github.com/miolad/ebpf-distributed-htab<br>
**Partner:** [Politecnico di Torino](https://www.polito.it/)

<br>

### Static Analysis of Interaction between Wasm Modules

<img src="https://img.shields.io/badge/Open%20source-to%20be%20released-1a7f37?style=flat-square" alt="Open source, to be released">

*Trust verification for distributed WebAssembly applications*

This component analyses interactions between WebAssembly modules before runtime, supporting secure composition and attestation of distributed serverless applications.

- Static analysis of WebAssembly components to obtain deployment-independent module-to-module connections
- Attestation protocol to establish identity of whole application deployment, not just individual TEEs
- Attested RPC between Wasm components located on different machines
- Incorporating WebAssembly into the RATS ecosystem

**Repository (code to be released):** https://github.com/elasticproject-eu/wasm-attestation<br>
**Partner:** [Aalto University](https://www.aalto.fi/en)<br>
**Contact:** Parsa Sadri Sinaki (parsa.sadrisinaki@aalto.fi)

<p align="right"><a href="#technology-components">↑ Back to component overview</a></p>

<br>

<p align="center"><img src="https://img.shields.io/badge/BLOCK%204-MONITORING%20%26%20DETECTION-bf8700?style=for-the-badge" alt="Block 4: Monitoring & Detection"></p>

## Block 4 · Monitoring & Detection

> **Runtime observability, performance monitoring, and AI-driven security detection.**
>
> Components in this block: [NETTO](#netto) · [Observability Framework for Serverless Workloads](#observability-framework-for-serverless-workloads) · [Artificial Intelligence Intrusion Detection System](#artificial-intelligence-intrusion-detection-system) · [Lightweight Hardware-based Cryptography Module](#lightweight-hardware-based-cryptography-module) · [Mobility Attack Robust IoT Resource Allocation Model](#mobility-attack-robust-iot-resource-allocation-model)

### NETTO

<img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source">

*Real-time visibility into Linux network stack cost*

NETTO measures the CPU overhead of Linux network functions in real-time, helping operators identify bottlenecks and optimize network performance.

- Real-time, low-overhead network profiling
- eBPF+perf instrumentation
- Userspace data analysis
- Intuitive stack trace visualisation with Grafana Pyroscope
- Bottleneck identification

**Repository:** https://github.com/miolad/netto<br>
**Paper (Netdev 0x17):** https://iris.polito.it/retrieve/handle/11583/2992332/086c1e80-0c27-4850-91b9-a958bd405edd/netdev-0x17-paper34-talk-paper.pdf<br>
**Partner:** [Politecnico di Torino](https://www.polito.it/)

<br>

### Observability Framework for Serverless Workloads

<img src="https://img.shields.io/badge/Access-on%20request-6e7781?style=flat-square" alt="Access on request">

*Operational visibility for WebAssembly serverless environments*

This framework provides targeted observability for WebAssembly-based serverless workloads, supporting performance monitoring.

- Observability for WASM based serverless workloads (Spinkube)
- Based on eBPF uprobe mechanism, possible to extend for non-WASM workloads
- Rule-based data collection using ring buffers
- Kafka-based data output using OpenTelemetry-inspired format
- Low-overhead observability using Rust based userspace data collector

**More information:** https://youtu.be/5P1HITjYWmE<br>
**Partner:** [Ericsson Finland](https://www.ericsson.com)<br>
**Contact:** Miika Komu (miika.komu@ericsson.com)

<br>

### Artificial Intelligence Intrusion Detection System

<img src="https://img.shields.io/badge/Access-on%20request-6e7781?style=flat-square" alt="Access on request">

*AI-driven cybersecurity for edge and 6G infrastructures*

This component provides AI-enhanced and hardware-accelerated intrusion detection for real-time threat monitoring and adaptive cybersecurity across edge, IoT, cloud and 5G/6G ecosystems.

- AI-driven intrusion detection
- Adaptive anomaly & threat detection
- Hardware-accelerated low-latency monitoring
- Continuous learning & signature refinement
- Edge, IoT, cloud & 5G/6G security support

**Partner:** [Technical University of Crete](https://www.tuc.gr/en/home/)<br>
**Contact:** Grigorios Chrysos (gxrysos@tuc.gr)

<br>

### Lightweight Hardware-based Cryptography Module

<img src="https://img.shields.io/badge/Access-on%20request-6e7781?style=flat-square" alt="Access on request">

*Hardware-accelerated lightweight cryptography*

This component provides hardware-accelerated lightweight cryptography for secure, energy-efficient and real-time communications across edge, IoT and next-generation 5G/6G ecosystems.

- Real-time encryption and authentication
- Energy-efficient lightweight cryptography
- Advanced data integrity protection
- Secure edge, IoT & 5G/6G communication

**Partner:** [Technical University of Crete](https://www.tuc.gr/en/home/)<br>
**Contact:** Grigorios Chrysos (gxrysos@tuc.gr)

<br>

### Mobility Attack Robust IoT Resource Allocation Model

<img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source">

*Robust mobility prediction for secure 6G networks*

This component uses AutoML to provide robust mobility under mobility attack conditions for future 6G network analytics and resource allocation.

- Mobility attack resilience
- Secure mobility prediction
- AutoML-based modelling
- NWDAF compatible
- Open simulation framework
- Assist 6G resource planning
- Research-ready mobility datasets

**Repository:** https://github.com/nwdaf-research/dataset-attack<br>
**Paper (FMEC 2024, open access):** https://zenodo.org/records/13969430<br>
**Partner:** [Lund University](https://www.lunduniversity.lu.se)

<p align="right"><a href="#technology-components">↑ Back to component overview</a></p>

<br>

<p align="center"><img src="https://img.shields.io/badge/BLOCK%205-TRUST%20%26%20ACCESS%20CONTROL-cf222e?style=for-the-badge" alt="Block 5: Trust & Access Control"></p>

## Block 5 · Trust & Access Control

> **Remote attestation, policy enforcement, access control, and zero-trust mechanisms.**
>
> Components in this block: [Remote Attestations Platform](#remote-attestations-platform) · [Key Broker Service](#key-broker-service) · [Multi-platform Attestation Component](#multi-platform-attestation-component) · [Lightweight ABAC Solution](#lightweight-abac-solution) · [WASI Flexibly-defined Capabilities](#wasi-flexibly-defined-capabilities)

### Remote Attestations Platform

<img src="https://img.shields.io/badge/Access-on%20request-6e7781?style=flat-square" alt="Access on request">

*Hardware-agnostic trust verification for confidential computing*

This platform supports remote attestation across multiple cloud providers and TEE architectures, enabling trust verification before sensitive workloads are executed.

- Multi-cloud attestation support
- Intel TDX and ARM Trust Zone support
- Hardware-agnostic verification
- Trust before execution
- Confidential computing enablement
- Multi-tenant security assurance
- Public cloud trust validation
- Interoperability across TEEs

**Partner:** [Thales DIS](https://www.thalesgroup.com/en)<br>
**Contact:** Volker Breuer (volker.breuer@thalesgroup.com)

<br>

### Key Broker Service

<img src="https://img.shields.io/badge/Access-on%20request-6e7781?style=flat-square" alt="Access on request">

*Attestation-based key release for secure workload migration*

The Key Broker Service releases cryptographic keys only after successful attestation, enabling secure migration and execution of sensitive workloads in trusted environments.

- Key release after attestation
- Secure workload migration
- BYOK/HYOK support potential
- Customer-controlled cryptographic keys
- Public cloud confidentiality
- Secure secret provisioning
- Compliance-aware key management
- Trust-linked cloud execution

**Partner:** [Thales DIS](https://www.thalesgroup.com/en)<br>
**Contact:** Volker Breuer (volker.breuer@thalesgroup.com)

<br>

### Multi-platform Attestation Component

<img src="https://img.shields.io/badge/Access-on%20request-6e7781?style=flat-square" alt="Access on request">

*Unified attestation across heterogeneous platforms*

This component verifies remote attestation evidence from multiple different TEE platforms through a unified mechanism, supporting trust establishment across diverse infrastructures.

- TEE vendor agnostic remote attestation
- Confidential Computing interoperability
- Unified multi-platform verification interface
- Attestation based on WebAssembly components
- Decoupling of TEE platform and verifier lifecycles
- Reduced TEE vendor and verification service dependency
- Data Fabric trust establishment support
- Data producer/consumer attestation

**More information:** https://youtu.be/cs7SY35RHa4<br>
**Partner:** [Ericsson Finland](https://www.ericsson.com)<br>
**Contact:** Jimmy Kjällman (jimmy.kjallman@ericsson.com)

<br>

### Lightweight ABAC Solution

<img src="https://img.shields.io/badge/Access-on%20request-6e7781?style=flat-square" alt="Access on request">

*Fine-grained access control for secure edge environments*

The Lightweight ABAC solution enforces attribute-based access control policies for WebAssembly orchestration and runtime interactions in resource-constrained environments.

- Light-weight attribute-based access control
- Fine-grained policy enforcement
- Zero-trust architecture alignment
- WASM container protection
- Edge-ready security policies

**Partner:** [Thales SIX](https://www.thalesgroup.com/en)<br>
**Contact:** Cyril Dangerville (cyril.dangerville@thalesgroup.com)

<br>

### WASI Flexibly-defined Capabilities

<img src="https://img.shields.io/badge/Open%20source-2da44e?style=flat-square" alt="Open source">

*Custom access control policies for WebAssembly applications*

This component enables easy instrumentation of existing WebAssembly applications with custom logic.

- Easily insert observability, access control, or compatibility layers into WebAssembly components
- Automatically transform WAC scripts without manual effort
- Shims are isolated from other code by the WebAssembly sandbox
- Auto-generate shim scaffolds for easy development

**Repository:** https://github.com/elasticproject-eu/wacky<br>
**Partner:** [Aalto University](https://www.aalto.fi/en)

<p align="right"><a href="#technology-components">↑ Back to component overview</a></p>

---

## Partners

<table align="center">
<tr><td align="center" valign="middle" width="25%"><a href="https://www.tuc.gr/en/home/"><img src="https://github.com/elasticproject-eu/.github/blob/0daa5e9f24a26aeb7e7511b2d867d8ba339ab784/profile/partners_logo/TUC_logo_text.png" height="75" alt="Technical University of Crete"></a><br><sub>Technical University of Crete</sub></td><td align="center" valign="middle" width="25%"><a href="https://www.ericsson.com"><img src="https://github.com/elasticproject-eu/.github/blob/0daa5e9f24a26aeb7e7511b2d867d8ba339ab784/profile/partners_logo/Ericsson_vertical_RGB.png" height="70" alt="Ericsson"></a><br><sub>Ericsson</sub></td><td align="center" valign="middle" width="25%"><a href="https://telefonicainnovaciondigital.com/"><img src="https://github.com/elasticproject-eu/.github/blob/fdb1ef9a49e7aa855c6ce9a317d8c1b53426ef92/profile/partners_logo/TID-removebg-preview.png" width="230" alt="Telefónica Innovación Digital"></a><br><sub>Telefónica Innovación Digital</sub></td><td align="center" valign="middle" width="25%"><a href="https://www.thalesgroup.com/en"><img src="https://github.com/elasticproject-eu/.github/blob/0daa5e9f24a26aeb7e7511b2d867d8ba339ab784/profile/partners_logo/Thales_LOGO_RGB.jpg" height="50" alt="Thales"></a><br><sub>Thales</sub></td></tr>
<tr><td align="center" valign="middle" width="25%"><a href="https://www.imec.be"><img src="https://github.com/elasticproject-eu/.github/blob/0daa5e9f24a26aeb7e7511b2d867d8ba339ab784/profile/partners_logo/Imec_ColourPositive.png" width="130" alt="imec"></a><br><sub>imec</sub></td><td align="center" valign="middle" width="25%"><a href="https://ultraviolet.rs"><img src="https://github.com/elasticproject-eu/.github/blob/0daa5e9f24a26aeb7e7511b2d867d8ba339ab784/profile/partners_logo/UltraViolet_logo.svg" width="170" alt="Ultraviolet"></a><br><sub>Ultraviolet</sub></td><td align="center" valign="middle" width="25%"><a href="https://www.aalto.fi/en"><img src="https://github.com/elasticproject-eu/.github/blob/0daa5e9f24a26aeb7e7511b2d867d8ba339ab784/profile/partners_logo/aalto-logo-86627-1.png" height="90" alt="Aalto University"></a><br><sub>Aalto University</sub></td><td align="center" valign="middle" width="25%"><a href="https://www.lunduniversity.lu.se"><img src="https://github.com/elasticproject-eu/.github/blob/0daa5e9f24a26aeb7e7511b2d867d8ba339ab784/profile/partners_logo/LundUniversity_C2line_RGB.png" height="85" alt="Lund University"></a><br><sub>Lund University</sub></td></tr>
<tr><td align="center" valign="middle" width="25%"><a href="https://www.abstractmachines.fr"><img src="https://github.com/elasticproject-eu/.github/blob/a89b388ed5e4f654ee25acac19dbcf7ec2836fb0/profile/partners_logo/AMA.png" height="100" alt="Abstract Machines"></a><br><sub>Abstract Machines</sub></td><td align="center" valign="middle" width="25%"><a href="https://zentrixlab.com/"><img src="https://github.com/elasticproject-eu/.github/blob/0daa5e9f24a26aeb7e7511b2d867d8ba339ab784/profile/partners_logo/ZentrixLab_logo.png" height="52" alt="Zentrix Lab"></a><br><sub>Zentrix Lab</sub></td><td align="center" valign="middle" width="25%"><a href="https://www.polito.it"><img src="https://github.com/elasticproject-eu/.github/blob/0daa5e9f24a26aeb7e7511b2d867d8ba339ab784/profile/partners_logo/Polito_Logo_2021_BLU.png" height="55" alt="Politecnico di Torino"></a><br><sub>Politecnico di Torino</sub></td><td width="25%"></td></tr>
</table>

## Funding information

ELASTIC project has received funding from the Smart Networks and Services Joint Undertaking (SNS JU) under the European Union’s Horizon Europe research and innovation programme under Grant Agreement No 101139067. Views and opinions expressed are however those of the authors only and do not necessarily reflect those of the European Union. Neither the European Union nor the granting authority can be held responsible for them.

<img src="https://github.com/user-attachments/assets/b110aa75-4438-4388-a6a0-8d4b0d76e421" height="40">

<img src="https://github.com/user-attachments/assets/c1b19cf1-c936-433e-a354-919a08801476" height="50">

<img src="https://github.com/user-attachments/assets/e0a71423-65a3-421a-91a2-0b13cfb8b11f" height="50">
