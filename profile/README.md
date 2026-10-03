# ELASTIC: Efficient, portabLe And Secure orchesTration for reliable servICes

![image](https://github.com/user-attachments/assets/9f084806-571c-46c9-9dbf-b9b9cb05b20c)

---

## Projects

### Cyber-physical WebAssembly System Interfaces (WASI) Hardware Abstraction Layer (HAL)

A standardized set of interfaces to connect WebAssembly applications to hardware on IoT and edge devises using hardware protocols such as USB and I2C. This also allows building device drivers as WebAssembly components.

* I2C WASI proposal: Phase 2
  * Proposal: https://github.com/WebAssembly/wasi-i2c
  * Implementation: https://github.com/idlab-discover/i2c-wasm-components
  * Collaboration with Siemens
* USB WASI proposal: Phase 1
  * Proposal: https://github.com/WebAssembly/wasi-usb
  * Implementation:
    * https://github.com/idlab-discover/usb-wasm
* GPIO WASI proposal: Phase 1
  * Proposal: https://github.com/WebAssembly/wasi-gpio
  * Implementation:
    * https://github.com/idlab-discover/masters-jarno-vanruymbeke
* SPI WASI proposal: Phase 1
  * Proposal: https://github.com/idlab-discover/masters-jarno-vanruymbeke/tree/main/SPI/wit

Partner: [Imec](https://www.imec.be)

---

### Propeller Orchestrator

Propeller is a lightweight orchestration platform developed by Abstract Machines in the context of the ELASTIC project. It enables secure, event-driven deployment and execution of WebAssembly (Wasm) workloads across heterogeneous cloud, edge, and IoT environments — including microcontrollers running RTOS.

Key features include:

* Fast, low-overhead orchestration of serverless (FaaS) workloads
* Support for resource-constrained devices (e.g. ESP32, Zephyr RTOS)
* Secure multi-protocol messaging via the built-in SuperMQ
* OCI-compliant Wasm artefact handling
* No dependency on Kubernetes or heavyweight control planes

Propeller is used in both ELASTIC Demonstrator 1 (6G IoT data fabric services) and Demonstrator 2 (secure workload migration across trust boundaries).

* Repository: https://github.com/absmach/propeller
* Documentation: https://docs.propeller.abstractmachines.fr/

Partner: [Abstract Machines](https://www.abstractmachines.fr)

---

### Wasm Operator

Wasm Operator is a platform to run Kubernetes Operators as Wasm components that only wake up when there are changes to be processed. This reduces their memory footprint and enhances efficiency for edge orchestration.

* Repository: https://github.com/idlab-discover/wasm-operator

Partner: [Imec](https://www.imec.be)

---

### TEEHAL

TEE Hardware Abstraction Layer providing a portable, secure foundation for executing trusted workloads across heterogeneous platforms.
TEEHAL enables unified management and interoperability of Trusted Execution Environments (TEEs) such as AMD SEV and Intel TDX, supporting confidential computing scenarios validated within ELASTIC.

* Repository: https://github.com/elasticproject-eu/wasmhal/

Partner: [LUND University](https://www.lunduniversity.lu.se)

---
### NETTO

NETTO is an eBPF-powered network monitoring tool for Linux that focuses on measuring the CPU utilization of the key kernel tasks responsible for running the network stack. Thanks to a lightweight profiling-centric design, NETTO can provide a detailed breakdown of the low-level kernel runtime operations with minimal and configurable system overhead. NETTO is an essential tool for system administrators that wish to understand their servers’ CPU time allocation, and optimize the networking configuration around it.

* Repository: https://github.com/miolad/netto

Partner: [Politecnico di Torino](https://www.polito.it/)

---
### Pretty Verifier – Static eBPF Code Security Analyzer

Pretty Verifier is a static analysis tool for eBPF C code, developed to detect and explain security issues that would cause verifier rejections in the Linux kernel. It provides early error reporting, clear diagnostic messages, and fix suggestions, based on combined analysis of the C source, compiled object code, and verifier logs.
Developed within the ELASTIC project (Task 1.3), the tool helps developers write eBPF programs that comply with verifier constraints and security requirements.

* Repository: https://github.com/netgroup-polito/pretty-verifier

Partner: [Politecnico di Torino](https://www.polito.it/)

---
### WASI Security

WASI Security defines a portable policy mechanism for enforcing fine-grained permissions on WebAssembly workloads across runtimes and orchestration environments. It provides standardised WASI security policies, fine-grained workload permissions, and secure device and file access.

* Repository: https://github.com/idlab-discover/masters-wasi-security/tree/blocking_rules_policy_file

Partner: [Imec](https://www.imec.be)

---
### HAL Enforcement Service – Automatic MAC Profiles for Wasm Runtime Containers

The HAL Enforcement Service provides policy-based access control for the ELASTIC TEE HAL (TEEHAL). It acts as a standalone gateway that grants WebAssembly workloads restricted access to WasmHAL components, based on YAML policies loaded from a central authority. Together with automatic generation of Mandatory Access Control (MAC) profiles, it enforces least privilege and reduces the attack surface of Wasm workloads.

* Repository: https://github.com/syafiq/enforcement-service

Partner: [LUND University](https://www.lunduniversity.lu.se)

---
### CornDog – Reliable Enclave Migration Protocols

CornDog enables reliable migration of sensitive resources between Trusted Execution Environments (TEEs), so that protected workloads can move securely without data loss or duplication. It is based on a fair-exchange protocol: either both the source and the destination end up with a cryptographic proof that the migration happened, or neither does.

* Atomic migration: no doubt as to who is responsible for a migrated resource
* Accountability: operators can prove that the other node received the same result
* Performance: optimistic protocol, with no external coordination unless a problem occurs
* Fault tolerance: the coordination infrastructure can be replicated

* Repository: https://github.com/elasticproject-eu/corndog

Partner: [Aalto University](https://www.aalto.fi/en)

---
### wacky – WASI Flexibly-defined Capabilities

wacky makes it easy to add custom logic, such as access control, observability or compatibility layers, to existing WebAssembly component applications. It injects "shims" between components by automatically transforming WAC composition scripts. The shims are isolated from other code by the WebAssembly sandbox, and their scaffolds can be generated automatically.

* Repository: https://github.com/elasticproject-eu/wacky

Partner: [Aalto University](https://www.aalto.fi/en)

---
### TCPless – Accelerated Microservices Interconnection

TCPless accelerates TCP communication within and between cluster nodes, improving throughput and reducing latency for microservice-based, cloud-native infrastructures. It extends the Linux TCP subsystem with an eBPF-controlled network bypass for TCP-based inter-process communication, and uses eBPF and RDMA network optimisations.

* Repository: https://github.com/miolad/linux-tcpless

Partner: [Politecnico di Torino](https://www.polito.it/)

---
### eBPF Distributed State Synchronisation

This tool extends eBPF maps across networked hosts, so that distributed eBPF probes can share state with very low latency. It automatically synchronises replicas of eBPF hash maps over a standard TCP/IP network, without kernel modifications.

* Sub-100 µs target delay on data-centre networks
* Eventual-consistency data replication
* Horizontal scalability

* Repository: https://github.com/miolad/ebpf-distributed-htab

Partner: [Politecnico di Torino](https://www.polito.it/)

---
### Mobility Attack Robust IoT Resource Allocation Model

This component uses AutoML to provide robust mobility prediction under mobility-attack conditions, supporting secure network analytics and resource planning in future 6G networks. It is NWDAF-compatible and includes an open simulation framework and research-ready mobility datasets.

* Repository: https://github.com/nwdaf-research/dataset-attack

Partner: [LUND University](https://www.lunduniversity.lu.se)

---

## Partners

<p align="center">
  <a href="https://www.tuc.gr/en/home/">
    <img src="https://github.com/elasticproject-eu/.github/blob/0daa5e9f24a26aeb7e7511b2d867d8ba339ab784/profile/partners_logo/TUC_logo_text.png" height="80">
  </a>&nbsp;&nbsp;&nbsp;
  
  <a href="https://www.ericsson.com/en/about-us/sustainability-and-corporate-responsibility/sustainable-world/">
    <img src="https://github.com/elasticproject-eu/.github/blob/0daa5e9f24a26aeb7e7511b2d867d8ba339ab784/profile/partners_logo/Ericsson_vertical_RGB.png" height="80">
  </a>&nbsp;&nbsp;&nbsp;
  
  <a href="https://telefonicainnovaciondigital.com/">
    <img src="https://github.com/elasticproject-eu/.github/blob/fdb1ef9a49e7aa855c6ce9a317d8c1b53426ef92/profile/partners_logo/TID-removebg-preview.png" height="100">
  </a>&nbsp;&nbsp;&nbsp;
  
  <a href="https://www.thalesgroup.com/en">
    <img src="https://github.com/elasticproject-eu/.github/blob/0daa5e9f24a26aeb7e7511b2d867d8ba339ab784/profile/partners_logo/Thales_LOGO_RGB.jpg" height="80">
  </a>
</p>

<p align="center">
  <a href="https://idlab.technology">
    <img src="https://github.com/elasticproject-eu/.github/blob/0daa5e9f24a26aeb7e7511b2d867d8ba339ab784/profile/partners_logo/Imec_ColourPositive.png" height="30">
  </a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  
  <a href="https://ultraviolet.rs">
    <img src="https://github.com/elasticproject-eu/.github/blob/0daa5e9f24a26aeb7e7511b2d867d8ba339ab784/profile/partners_logo/UltraViolet_logo.svg" height="30">
  </a>&nbsp;&nbsp;&nbsp;&nbsp;
  
  <a href="https://www.aalto.fi/en">
    <img src="https://github.com/elasticproject-eu/.github/blob/0daa5e9f24a26aeb7e7511b2d867d8ba339ab784/profile/partners_logo/aalto-logo-86627-1.png" height="80">
  </a>&nbsp;&nbsp;&nbsp;
  
  <a href="https://www.lunduniversity.lu.se">
    <img src="https://github.com/elasticproject-eu/.github/blob/0daa5e9f24a26aeb7e7511b2d867d8ba339ab784/profile/partners_logo/LundUniversity_C2line_RGB.png" height="80">
  </a>
</p>

<p align="center">
  <a href="https://www.abstractmachines.fr">
    <img src="https://github.com/elasticproject-eu/.github/blob/a89b388ed5e4f654ee25acac19dbcf7ec2836fb0/profile/partners_logo/AMA.png" height="100">
  </a>
  
  <a href="https://zentrixlab.com/">
    <img src="https://github.com/elasticproject-eu/.github/blob/0daa5e9f24a26aeb7e7511b2d867d8ba339ab784/profile/partners_logo/ZentrixLab_logo.png" height="80">
  </a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
  
  <a href="https://www.polito.it">
    <img src="https://github.com/elasticproject-eu/.github/blob/0daa5e9f24a26aeb7e7511b2d867d8ba339ab784/profile/partners_logo/Polito_Logo_2021_BLU.png" height="80">
  </a>
</p>




## Funding information

ELASTIC project has received funding from the Smart Networks and Services Joint Undertaking (SNS JU) under the European Union’s Horizon Europe research and innovation programme under Grant Agreement No 101139067. Views and opinions expressed are however those of the authors only and do not necessarily reflect those of the European Union. Neither the European Union nor the granting authority can be held responsible for them.

<img src="https://github.com/user-attachments/assets/b110aa75-4438-4388-a6a0-8d4b0d76e421" height="40">

<img src="https://github.com/user-attachments/assets/c1b19cf1-c936-433e-a354-919a08801476" height="50">

<img src="https://github.com/user-attachments/assets/e0a71423-65a3-421a-91a2-0b13cfb8b11f" height="50">
