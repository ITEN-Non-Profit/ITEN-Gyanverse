# ITEN Gyanverse Networking & Network Engineering Interview Preparation Repository

Welcome to the **Networking and Network Engineering Interview Preparation** repository (`professional-it-career/networking/interview-preparation`). We share practical, day-to-day, industry work-ready networking interview preparation books and technical study guides here.

Find the current publications and updates below:

## 1. NOC Engineer Interview Preparation Guide: 108 Real-World Scenarios from L1 to L3

* **Book Link:** [NOC Engineer Interview Preparation Guide](https://github.com/ITEN-Non-Profit/ITEN-Gyanverse/blob/main/professional-it-career/networking/interview-preparation/markdown/NOC-Engineer-Interview-Preparation-Guide.md) *(Local file: [`./markdown/NOC-Engineer-Interview-Preparation-Guide.md`](./markdown/NOC-Engineer-Interview-Preparation-Guide.md))*
* **Subtitle:** 108 real-world scenarios for Network Operations Center interviews, from your first NOC role to senior escalation
* **Author:** Jiwan Bhattarai, CCIE #60261, CEH · IT Education Nepal (First Edition, September 2026)
* **Licence:** Creative Commons Attribution 4.0 International (CC BY 4.0)
* **Target Audience:** Entry-level NOC Analysts (`L1`), experienced NOC / Shift Engineers (`L2`), and Senior / Escalation Network Engineers (`L3`) across Enterprise, ISP/Service Provider, and MSP environments.

### Short Description

The [NOC Engineer Interview Preparation Guide](https://github.com/ITEN-Non-Profit/ITEN-Gyanverse/blob/main/professional-it-career/networking/interview-preparation/markdown/NOC-Engineer-Interview-Preparation-Guide.md) consolidates **108 real-world production troubleshooting and operational scenarios (`Q1` to `Q108`)** divided across three career tiers: **25 L1 scenarios**, **73 L2 scenarios**, and **10 L3 scenarios**.

Every scenario follows a consistent six-part engineering structure:
* **Tier and Safety:** Identifies the target interview level (`L1`, `L2`, `L3`) and command safety label (`read-only`, `active test`, `service-affecting`, or `change approval`).
* **Short Answer:** Gives a concise, 30-second response you can state out loud in an interview.
* **What Is Actually Going On:** Explains the underlying protocol mechanism to answer interviewer "why?" follow-up questions.
* **How to Check:** Lists verification commands and procedures tested across Cisco IOS/IOS XE, Cisco ASA, Cisco WLC, Palo Alto, Fortinet, Junos, Linux (Ubuntu/RHEL), Windows Server, and AWS CLI.
* **Watch Out For:** Highlights common traps, overlooked root causes, and operational nuances across Enterprise, ISP, and MSP environments.
* **References:** Links directly to governing RFCs, IEEE standards, ITU-T recommendations, NIST publications, and ITIL 4 / SRE practices.

### Book Contents: Parts I to VI (Chapters 1 to 13)

| Part & Chapter | Scenario Range | Tier Mix | Core Networking & Operational Topics Covered |
| :--- | :--- | :--- | :--- |
| **Part I · Ch. 1: Routing and Switching** | `Q1` – `Q14` | 5 L1 · 7 L2 · 2 L3 | Cross-VLAN reachability, STP topology changes, broadcast storms, ECMP packet loss, OSPF adjacency states, trunk VLAN filtering, control-plane CPU spikes, static routing, CRC/input errors, EtherChannel load-balancing, BGP missing prefixes, and HSRP/VRRP/BFD failover |
| **Part I · Ch. 2: DNS and DHCP** | `Q15` – `Q22` | 4 L1 · 4 L2 | Hostname vs IP triage, intermittent external DNS recursion (EDNS0, DNSSEC, TCP 53), single-client DHCP failures, DHCP scope exhaustion and MAC randomisation, zone timeouts (`dig +trace`), APIPA (`169.254.x.x`), dynamic DNS registration races, and TTL caching |
| **Part II · Ch. 3: Firewall and Security** | `Q23` – `Q34` | 9 L2 · 3 L3 | ACL evaluation order, SIP ALG and 30-second VoIP drops, URL filtering vs TLS decryption failures, perimeter scan triage, IPsec Phase 2 proxy IDs, NAT publishing, 802.1X/NAC quarantine, credential stuffing response, DPI throughput sizing, PMTUD black holes, and multi-vendor VPN interoperability |
| **Part II · Ch. 4: VPN and Remote Access** | `Q35` – `Q41` | 1 L1 · 6 L2 | Split-DNS and SMB over VPN, IKEv2 rekey and repeating disconnects, MTU vs volume-based SA drops, hotel Wi-Fi and captive portals, X.509 certificate chains, split-tunnel misconfiguration, and WAN path latency/MTR analysis |
| **Part II · Ch. 5: Wireless** | `Q42` – `Q49` | 2 L1 · 6 L2 | AP infrastructure vs RF faults, sticky clients and 802.11k/v/r roaming, airtime contention, guest Wi-Fi segmentation leaks, IoT and WPA2-Enterprise/MAB design, CAPWAP AP join failures, 2.4 GHz non-Wi-Fi interference, and carrier Wi-Fi calling vs enterprise VoWLAN |
| **Part III · Ch. 6: Monitoring, Alerting and NOC Process** | `Q50` – `Q64` | 6 L1 · 9 L2 | Alert storms and dependency mapping, alerting pipeline audits, core link flapping, multi-site major incidents, ICMP monitoring false positives, escalation triggers, maintenance window suppression, post-incident documentation, 95th-percentile WAN capacity planning, P1 auto-escalation, shift handovers, and NETCONF/gNMI config drift |
| **Part IV · Ch. 7: Cloud and Load Balancing** | `Q65` – `Q72` | 6 L2 · 2 L3 | Load balancer health check depth, session persistence behind NAT, AWS VPC routing and stateless NACLs vs stateful Security Groups, hybrid cloud BGP flaps, VPN route propagation, Auto Scaling grace periods, cross-region fibre latency floors, and NAT Gateway source translation |
| **Part IV · Ch. 8: VoIP and QoS** | `Q73` – `Q78` | 6 L2 | End-of-day WAN congestion and DSCP EF trust boundaries, one-way RTP audio and SDP analysis, WMM voice over WLAN, SIP session timers (`RFC 4028`), post-upgrade QoS shaper issues, and conference bridge DSP/transcoding ceilings |
| **Part IV · Ch. 9: Physical Layer and Cabling** | `Q79` – `Q84` | 4 L1 · 2 L2 | Split pairs and NEXT cable certification, optical loss budgets and connector cleaning, permanent link vs patch cord isolation, 100BASE-TX vs 1000BASE-T pair requirements, SFP PMD/wavelength/overload diagnostics, and post-surge line-card hardware failures |
| **Part V · Ch. 10: Escalation, ITIL and Communication** | `Q85` – `Q91` | 1 L1 · 6 L2 | Carrier SLA escalation, evidence-based cross-team troubleshooting, multi-incident triage under load, ITIL Problem Management business cases, executive outage communication cadences, rollback vs forward-fix judgement, and change calendar visibility (with STAR prompts) |
| **Part VI · Ch. 11: Server and OS Networking** | `Q92` – `Q96` | 5 L2 | Linux host routing (`ip route get`) and reverse-path filtering, Windows NLA domain profile detection and NIC teaming after updates, Linux ARP flux vs Windows strong host model on dual-NIC servers, TCP window/BDP and NIC offload tuning, and backend TLS certificate mismatches |
| **Part VI · Ch. 12: Miscellaneous Protocols** | `Q97` – `Q101` | 4 L2 · 1 L3 | SMTP greylisting and header timestamp analysis, Active vs Passive FTP and FTPS firewall pinholes, NTP stratum drift breaking Kerberos and TLS, SNMPv3 and ACL mismatches after hardening, and dual-end PCAP analysis for intermittent TCP port failures |
| **Part VI · Ch. 13: IPv6** | `Q102` – `Q108` | 2 L1 · 3 L2 · 2 L3 | Happy Eyeballs (`RFC 8305`) dual-stack fallback delays, link-local (`fe80::`) vs Router Advertisements, rogue RAs and RA Guard, SLAAC M/O flags and RDNSS/DHCPv6, ICMPv6 Type 2 Packet Too Big filtering and PMTUD, dual-stack firewall policy asymmetry, and broken AAAA records |

### Appendices & Revision Tools Included in the Book

* **Appendix A – Study Paths:** Role-specific preparation tracks for **L1 NOC Analysts** (25 scenarios), **L2 NOC Engineers** (73 scenarios), and **L3 Senior/Escalation Engineers** (10 scenarios).
* **Appendix B – Questions-Only Recall Edition:** All 108 scenario prompts without visible answers for spoken active-recall practice.
* **Appendix C – Self-Assessment Tracker:** A 0-to-5 readiness rubric and chapter-by-chapter scoring sheet.
* **Appendix D – Command Reference:** Safety-labelled CLI reference covering Cisco IOS/IOS XE, Cisco ASA, Palo Alto, Fortinet, Cisco WLC, Linux, Windows PowerShell, and AWS CLI.
* **Appendix E – Ports, Protocols and Markings:** Quick-lookup tables for TCP/UDP ports, DoT/DoH/QUIC, IP protocol numbers, mandatory ICMPv6 types, RFC 4594 DSCP markings, voice/wireless thresholds, encapsulation overheads, MTU values, and optical loss budgets.
* **Appendix F – Standards Index:** Direct links to governing IETF RFCs, IEEE standards, ITU-T recommendations, ISO/IEC cabling standards, NIST publications, ITIL 4, and Google SRE references.
* **Appendix G – Research Foundations:** Annotated index of 14 peer-reviewed networking measurement papers (`[G1]`–`[G14]`) backing the mechanisms in the book.
* **Appendix H & Appendix I – Glossary and Edition Corrections:** Definitions of operational networking terms and technical audit notes.

## 2. Future Publications and Updates

Additional networking and network engineering interview preparation books, protocol guides, and scenario collections are coming soon to this repository on the request of global IT community members. Stay tuned for upcoming releases.

## Keywords & Topics

`noc-engineer-interview` `network-engineering-interview` `networking-interview-preparation` `l1-l2-l3-noc` `routing-and-switching` `ospf-troubleshooting` `bgp-troubleshooting` `spanning-tree-protocol` `dns-dhcp-troubleshooting` `firewall-troubleshooting` `ipsec-vpn` `wireless-80211` `voip-qos-dscp` `cloud-networking-aws` `ipv6-troubleshooting` `itil-incident-management` `cisco-ios-cli` `linux-networking` `iten-gyanverse`