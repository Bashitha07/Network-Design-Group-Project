# Enterprise Network Design Project

> **Computer Networks (IE2004)** — Enterprise network design and implementation plan for Software Solutions (Pvt) Ltd.

![Status](https://img.shields.io/badge/status-academic%20project-blue)
![Course](https://img.shields.io/badge/course-IE2004-informational)
![Location](https://img.shields.io/badge/location-Colombo%2C%20Sri%20Lanka-success)

## 📌 Overview

This repository contains the documentation, network diagrams, and design artefacts for an enterprise network proposed for **Software Solutions (Pvt) Ltd**, a software development and IT consulting company based in Colombo 03, Sri Lanka.

The design focuses on a reliable, scalable, and secure network for a two-storey commercial office. It includes wired and wireless connectivity, layered switching, internet access, inter-floor fiber uplinks, power protection, and a detailed implementation budget.

## 🎯 Project Objectives

- Design a practical enterprise network for a two-storey office environment.
- Provide reliable connectivity for wired workstations, network devices, and wireless clients.
- Apply a hierarchical network architecture with core/distribution and access layers.
- Support future growth through structured cabling, VLAN-ready switching, and scalable wireless infrastructure.
- Document the proposed topology, floor layouts, equipment, services, and estimated costs.

## 🏢 Enterprise Profile

| Item | Details |
| --- | --- |
| **Company** | Software Solutions (Pvt) Ltd |
| **Business** | Software development and IT consulting |
| **Location** | Colombo 03, Sri Lanka |
| **Building** | Two-storey commercial building |
| **Floor area** | 18.0 m × 9.0 m — 162 m² per floor |
| **Wired devices** | 41 |
| **Wireless clients** | 60+ |
| **Internet service** | SLT Fiber Business 100 — 100 Mbps symmetric connection |

## 🧱 Network Architecture

The proposed design follows a structured, layered approach:

```text
                         Internet
                            │
                 SLT Fiber Business 100
                            │
                    Cisco ISR4331 Router
                            │
              ┌─────────────┴─────────────┐
              │                           │
      Core/Distribution Layer      Core/Distribution Layer
       Cisco Catalyst 3650          Cisco Catalyst 3650
              │                           │
       OM3 fiber uplink between floors
              │                           │
       Access switches and wireless APs
              │
        Wired and wireless endpoints
```

### Core components

- **Internet gateway:** Cisco ISR4331 router connected to the SLT Fiber Business 100 service.
- **Core/distribution layer:** Cisco Catalyst 3650-24PS Layer 3 switches with PoE+ support.
- **Inter-floor connectivity:** OM3 fiber uplinks between the building floors.
- **Access layer:** Cisco Catalyst 2960-24TT and Ubiquiti switches.
- **Wireless infrastructure:** Cisco Aironet 1832i and Ubiquiti UniFi 6 Lite access points.
- **Power protection:** APC Smart-UPS units for the MDF and IDF network areas.

## 📶 Wireless and Wired Connectivity

The network is designed to support:

- 41 wired office and infrastructure devices.
- More than 60 wireless clients.
- Wireless coverage across both floors.
- PoE-powered network devices where supported.
- Dedicated inter-floor connectivity using OM3 fiber.
- Future segmentation and expansion through managed switching infrastructure.

## 💰 Estimated Project Cost

| Cost category | Subtotal (LKR) | Percentage |
| --- | ---: | ---: |
| Active network equipment | 1,253,500 | 57.9% |
| Passive network components | 457,810 | 21.1% |
| Internet service provider | 177,000 | 8.2% |
| Installation labour and services | 240,540 | 11.1% |
| Miscellaneous and tools | 35,900 | 1.7% |
| **Total estimated cost** | **2,164,750** | **100.0%** |

> **Note:** Costs are planning estimates for the academic project and may vary based on supplier pricing, installation requirements, taxes, and service-provider terms.

## 📁 Repository Structure

```text
.
├── diagrams/
│   ├── Floor plans and network layouts
│   ├── End-device placement diagrams
│   └── Cisco Packet Tracer topology designs
├── docs/
│   └── Full project report PDF
└── README.md
```

## 👥 Group Members

| # | Student ID | Name |
| ---: | --- | --- |
| 1 | IT24103485 | B.A. Sellapperuma |
| 2 | IT24101849 | K.P.O.N. Jayaweera |
| 3 | IT24103461 | K.P.D.H. Ariyasena |
| 4 | IT24101852 | V.N. Thilanka |
| 5 | IT24103452 | E.A.W.D. Dharmarathna |

## 🛠️ Tools and Technologies

- Cisco Packet Tracer
- Cisco ISR4331 router
- Cisco Catalyst 3650-24PS Layer 3 switches
- Cisco Catalyst 2960-24TT access switches
- Ubiquiti switching and wireless equipment
- Cisco Aironet 1832i access points
- Ubiquiti UniFi 6 Lite access points
- OM3 multimode fiber
- APC Smart-UPS power protection

## 📚 Documentation

For the complete design rationale, addressing plan, equipment selection, diagrams, implementation details, and cost calculations, see the files in the [`docs/`](docs/) and [`diagrams/`](diagrams/) directories.

## 🎓 Academic Context

This project was prepared for the **Computer Networks — IE2004** course at the **Sri Lanka Institute of Information Technology (SLIIT)** as an enterprise network design exercise.

---

<div align="center">
  <sub>Network Design Group Project · IE2004 · SLIIT</sub>
</div>
