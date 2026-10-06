# Awesome-Telecom-Network-Automation

## Top Telecom Network Automation Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on OSS/BSS, Network Orchestration & Open-Source SDN/NFV Platforms*  

**Last updated: October 2026**



This repository tracks notable **commercial telecom network automation platforms** and **open-source projects** that automate service provisioning, network orchestration, and operations support systems (OSS) for communications service providers (CSPs). These tools span the full lifecycle from service design through fulfillment to assurance.



**Examples** include AWS Telco Network Builder, Nokia AVA, Ericsson Dynamic Orchestration, Amdocs Intelligent Networking Suite, Netcracker Digital OSS, Cisco Crosswork, Juniper Paragon, Blue Planet (Ciena), VMware Telco Cloud, and Mavenir MAVair (the category leaders).



**Open-source emphasis**: Telecom network automation is anchored by **ETSI OpenSourceMANO (OSM)** and **ONAP** as the two major orchestration frameworks, with **OSM** positioned as lightweight and ETSI-compliant while **ONAP** excels in closed-loop automation . **Nephio** represents the Kubernetes-native future for distributed edge networks. **ONOS** provides carrier-grade SDN control, and **OpenSlice** delivers open-source OSS for Network-as-a-Service. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[AWS Telco Network Builder](https://aws.amazon.com/telco-network-builder/)**  

  AWS's managed service for deploying and managing telecom network functions on AWS. **Automates network function lifecycle management** with integration into AWS infrastructure.



- **[Nokia AVA](https://www.nokia.com/networks/ava/)**  

  Nokia's AI-powered network automation and assurance platform. **Best for Nokia-centric networks** with AI-driven operations.



- **[Ericsson Dynamic Orchestration](https://www.ericsson.com/)**  

  Ericsson's orchestration solution for service providers. **Best for Ericsson ecosystem integration**.



- **[Amdocs Intelligent Networking Suite](https://www.amdocs.com/)**  

  Amdocs' comprehensive OSS/BSS suite with network automation capabilities.



- **[Netcracker Digital OSS](https://www.netcracker.com/)**  

  Netcracker's microservices-based Digital BSS/OSS suite, fully compliant with TM Forum, MEF, ETSI, and 3GPP standards . **Integrates with OSM** for network resource orchestration .



- **[Cisco Crosswork](https://www.cisco.com/)**  

  Cisco's network automation and assurance platform for service provider networks.



- **[Juniper Paragon](https://www.juniper.net/)**  

  Juniper's network automation suite with intent-based networking.



- **[Blue Planet (Ciena)](https://www.blueplanet.com/)**  

  Ciena's inventory, orchestration, and assurance software.



- **[VMware Telco Cloud](https://www.vmware.com/)**  

  VMware's telco cloud platform for NFV infrastructure and orchestration.



- **[Mavenir MAVair](https://www.mavenir.com/)**  

  Mavenir's cloud-native RAN and network automation solutions.



## Open-Source GitHub Projects



### Network Orchestration (NFV/SDN)



- **[ETSI Open Source MANO (OSM)](https://osm.etsi.org/)**  

  **The leading open-source Management and Orchestration (MANO) stack aligned with ETSI NFV standards**, Apache-2.0 licensed . **Orchestrates cloud-native network services across VM and Kubernetes environments** — supports the full lifecycle of telco-grade services . Features **declarative models, intent-based workflows, and GitOps-style operations** . **Modular and extensible** with SDK and expanded VIM support including OpenStack, AWS, Azure, GCP, and VMware . **Production-grade with two releases per year** (January and July) . **The de facto open-source MANO standard** for service providers wanting ETSI-compliant orchestration. **Best for lightweight, standards-compliant network service orchestration** .



- **[ONAP (Open Network Automation Platform)](https://www.onap.org/)**  

  **The comprehensive open-source platform for real-time, policy-driven service orchestration and automation**, hosted by the Linux Foundation . **Enables rapid automation of physical and virtual network functions** with complete lifecycle management . **Excels in closed-loop automation** but is **resource-intensive** . **Best for large-scale, complex network automation** requiring policy-driven orchestration.



- **[Nephio](https://nephio.org/)**  

  **Kubernetes-based cloud-native orchestration framework** representing the future for distributed and edge-native networks . **Adopts cloud-native approach** for multi-domain, multi-cloud 5G networks . **Best for Kubernetes-native, edge-distributed network automation**.



- **[ETSI OpenSlice](https://www.etsi.org/)**  

  **Open-source Operations Support System (OSS) for Network-as-a-Service (NaaS)** based on TM Forum's Open Digital Architecture . **2026Q2 release adds secret management (HashiCorp Vault), IETF RFC 9543 Network Slice Service controller, MCP stack enhancements, and AI components** . **HypO 2026.06** enables federation of multiple OpenSlice deployments into unified service ecosystems . **Best for NaaS and network slicing automation** .



- **[ETSI TeraFlowSDN](https://labs.etsi.org/rep/tfs/controller)**  

  **Cloud-native SDN controller enabling smart connectivity services for networks beyond 5G**, originating from the EU H2020 TeraFlow project . **Best for research and next-generation SDN control**.



### SDN Controllers



- **[ONOS (Open Network Operating System)](https://opennetworking.org/onos/)**  

  **Carrier-grade SDN controller designed for high scalability, availability, and performance**, written in Java . **Primarily for service provider networks** but also usable for enterprise campus and data center networks . **Modular architecture** keeps north-south and east-west workflows separated for easier customization . **Distributed core** scales out to accommodate physically distributed systems while remaining logically centralized . **Intent Framework** enables applications to specify requirements (e.g., more bandwidth) with the system configuring accordingly — supports **~1 million intent requests per second** . Contributors include AT&T, NTT, China Unicom, Intel, NEC, and Ciena . **The reference open-source SDN controller for service providers** . **Best for carrier-grade SDN deployments**.



- **[OpenDaylight (ODL)](https://www.opendaylight.org/)**  

  **Linux Foundation SDN controller** focused more on data center networks and merging legacy networks with SDN . **Best for data center SDN and brownfield deployments** .



### RAN Intelligent Controllers (RIC)



- **[O-RAN Software Community (OSC) RIC](https://o-ran-sc.org/)**  

  **The reference Near-RT RIC implementation according to O-RAN specifications** . **Built as a set of separate modules** including Routing Manager, E2 Manager, Subscription Manager, xApp Manager, and SDL (Redis-backed shared data layer) . **The only open-source Near-RT RIC supporting E2SM-CCC** for cell configuration and control workflows . **Integrates with OAI 5G RAN and OCUDU** . **Trade-off**: Microservice architecture introduces overhead — E2 Agent to xApp round-trip latency exceeds 1ms . **Best for O-RAN-compliant RAN automation** .



- **[FlexRIC](https://github.com/eurus-project)**  

  **Near-RT RIC from EURECOM focused on minimizing overhead and simplicity for xApp developers** . **Introduces iApp (Internal Application for Controller Specialization)** concept . **Ultra-lean, low-latency control framework** . **Best for lightweight, high-performance RAN control** .



- **[ONOS RIC (μONOS RIC)](https://github.com/onosproject)**  

  **Cloud-native Near-RT RIC built on ONOS SDN controller framework**, deployed via Kubernetes and Helm . **Modular microservices architecture** with E2 termination, subscription management, and xApp hosting . **Made progress with SD-RAN 1.5 migration** of three xApps to standardized E2SM-RC . **Best for ONOS-based RAN automation** .



### 5G Core & RAN



- **[Free5GC](https://free5gc.org/)**  

  **Open-source 5G core network** following microservices-based architecture with cloud-native principles . Apache-2.0 licensed . **Best for cloud-native 5G core deployments**.



- **[Open5GS](https://open5gs.org/)**  

  **Open-source 5G core network** evolved from EPC with more traditional monolithic approach . GNU AGPL v3.0 licensed . **Best for simpler 5G core deployments**.



- **[OAI (OpenAirInterface)](https://openairinterface.org/)**  

  **Research-oriented 5G implementation** for core and RAN with research flexibility and standards compliance . OAI Public License V1.1 . **Best for academic and advanced feature development** .



- **[srsRAN](https://srsran.com/)**  

  **Open-source 4G/5G software radio access network** focused on implementing commonly used features efficiently . GNU AGPL v3.0 licensed . **Best for small-scale commercial deployments and private networks** .



- **[UERANSIM](https://github.com/aligungr/UERANSIM)**  

  **Open-source 5G UE and RAN simulator** — cost-effective alternative to 5G testing equipment . GPL-3.0 licensed . **Note**: does not implement physical layer; declining support . **Best for testing 5G core networks** .



### OSS/BSS



- **[NMS Prime (Community Edition)](https://github.com/cablelabs/os-provisioning)**  

  **Modular CRM, BSS, and OSS platform for telcos and ISPs** . **Community Edition delivers complete OSS Provisioning layer** — technology-agnostic service activation for DOCSIS, FTTH, FTTx, DSL, and WiFi . **Built on Laravel/PHP 8** with PostgreSQL, Icinga2, Prometheus, Grafana, and Cacti . **Best for ISPs wanting full-stack OSS control** .



- **[DISCOBOLE](https://www.ow2.org/)**  

  **Cloud-native BSS suite aligned with TM Forum standards** supporting full Order-to-Bill lifecycle . **Selected for deployment in 2026 at Orange subsidiaries in Europe and MEA** . **Best for TM Forum-compliant BSS** .



### Additional Strong Open-Source Options



- **OpenSlice** — ETSI OSS for NaaS .

- **TeraFlowSDN** — Cloud-native SDN controller .

- **Nephoran Intent Operator** — LLM-enhanced Nephio R5 and O-RAN automation .

- **srsRAN** — 4G/5G RAN implementation .

- **UERANSIM** — 5G UE/RAN simulator .



**Frameworks for building custom telecom automation**: Choose based on scale and standards requirements. **ETSI OSM** for lightweight, ETSI-compliant NFV orchestration . **ONAP** for comprehensive, policy-driven automation at scale . **Nephio** for Kubernetes-native, edge-distributed networks . **ONOS** for carrier-grade SDN control . **OSC RIC** for O-RAN-compliant RAN automation . **OpenSlice** for NaaS and network slicing . Note that true enterprise telecom automation with vendor-supported SLAs, global deployment experience, and integrated OSS/BSS remains primarily commercial territory; open-source stacks provide strong orchestration, SDN control, and RAN automation foundations that require integration for complete service provider operations.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Telecom network automation platforms manage critical communications infrastructure. Self-hosted solutions require proper security hardening, high-availability configuration, and compliance with telecom regulations.

- **ONAP is resource-intensive** — it excels in closed-loop automation but requires significant infrastructure . **OSM is lighter** and suitable for constrained deployments .

- **RAN automation is complex** — OSC RIC requires Kubernetes expertise and Helm charts for xApp deployment . Latency exceeds 1ms under typical Kubernetes conditions .

- **Open-source telecom platforms require specialized expertise** — NFV, SDN, and O-RAN concepts are complex. Commercial platforms provide vendor support and implementation services.

- The open-source ecosystem provides strong orchestration, SDN control, and RAN automation foundations, but **vendor-supported SLAs, global deployment experience, and integrated OSS/BSS** remain primarily commercial offerings.



---



**Made for telecom engineers, network architects, and service providers seeking automation sovereignty.**  

Let's make telecom network automation more open, transparent, and standards-compliant.
