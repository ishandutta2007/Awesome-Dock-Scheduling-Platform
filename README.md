# Awesome-Dock-Scheduling-Platform

## Top Dock Scheduling Platform Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Warehouse Appointment Automation, Yard Visibility & Carrier Collaboration*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Dock Scheduling and Yard Management**. These tools automate dock appointment booking, digitize gate check-in, optimize trailer movement, and provide real-time visibility into warehouse and yard operations for shippers, 3PLs, carriers, and distribution centers.



**Examples** include GoRamp, Opendock, Descartes Dock Appointment Scheduling, C3 Reservations, YardView, Blue Yonder Network Appointment Scheduling, Transporeon Time Slot Management, FourKites Appointment Manager, Shiptify, and C3 Solutions.



**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom scheduling logic, and transparent yard operations — ideal for logistics teams, 3PLs, and developers seeking vendor-independent dock management. Note that the open-source ecosystem for full dock scheduling platforms remains limited, with most projects being general-purpose resource reservation systems or academic scheduling optimization tools rather than purpose-built warehouse dock software.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[GoRamp](https://www.goramp.com/)**  

  Comprehensive dock and yard orchestration platform combining dock scheduling, driver check-in, yard visibility, gate management, and carrier communication. Integrates with ERP, TMS, and WMS systems via APIs, EDI, or file exchange. Starting at $175/month with free trial and free version available . Case study: The Senator Group achieved unified scheduling across domestic and export teams, replacing fragmented Access database and Outlook calendar systems .



- **[Opendock](https://www.opendock.com/)**  

  Dock appointment scheduling platform emphasizing carrier self-scheduling, real-time slot availability, and automated confirmations. Features calendar grid interface, TV mode display for warehouse floors, two-way SMS communication, reporting and audit history, and API/TMS integrations . Carriers can book, edit, or cancel appointments independently, with 24/7 access and automated email confirmations .



- **[Descartes Dock Appointment Scheduling](https://www.descartes.com/)**  

  Collaborative dock appointment solution distributing scheduling responsibility from warehouse to carriers and suppliers. Features online appointment booking, electronic audit trails, milestone notifications, TMS/WMS integration, recurring appointments, and compliance tracking . Leverages Descartes Global Logistics Network for pre-connected carrier community .



- **[C3 Reservations](https://www.c3solutions.com/)**  

  Web-based dock scheduling system with carrier and supplier portals, flexible constraint modeling, standing appointments, rule-based duration, document attachments, and multilingual UI. Available 24/7 with automated notifications and multi-site visibility . Designed for 3PL contract warehousing, distribution, and bulk material sites .



- **[YardView](https://www.yardview.com/)**  

  Purpose-built yard management system since 1998 with dock scheduling, real-time visibility, gate and access control, yard driver tasking, reporting, and WMS/TMS/ERP integration. Used across 3PL, automotive, cold storage, beverage, and manufacturing industries. SaaS pricing includes unlimited users and transactions .



- **[Blue Yonder Network Appointment Scheduling](https://www.blueyonder.com/)**  

  Cloud-based collaboration solution within Blue Yonder's Global Logistics Network connecting shippers to 12,000+ pre-onboarded carriers. Features self-service carrier portal, constraint-based scheduling, real-time rescheduling, predictive ETA integration, and automated audit trails . Positions as moving from "Static Booking" to "Predictive Orchestration" .



- **[Transporeon Time Slot Management](https://www.transporeon.com/)**  

  Digital resource management platform reproducing actual loading/unloading capacities with automatic arrival time adjustment. Carriers book slots directly while shippers define rules and constraints. Reduces waiting times by up to 40%, increases handling capacity by up to 20%, and shortens loading times by up to 60 minutes . Optional modules include Forward Open Bookings, Quick Login, and Inbound .



- **[FourKites Appointment Manager](https://www.fourkites.com/)**  

  Free cloud-based appointment solution for facilities, carriers, and 3PLs. Kimberly-Clark case study: reduced booking time by 80%, saved 2,000+ hours of work, eliminated 60,000+ emails, and streamlined from 5-step/5-system process to 2-step/1-system . Integrates with major TMS and ERP systems .



- **[Shiptify](https://www.shiptify.com/)**  

  Dock planning module with precise zone and time-slot planning, controlled capacity by niche, flexible opening hours, and dock door assignment. Carriers see only relevant constraints; internal rules can be hidden. Starting at €89/month for SMEs with usage-based pricing for larger operations .



## Open-Source GitHub Projects



- **[LibreBooking](https://github.com/LibreBooking/librebooking)**  

  Open-source, self-hosted scheduling and resource-reservation application (GPL-3.0), actively maintained fork of phpScheduleIt and Booked . Reserve rooms, equipment, and shared resources via calendar views with day, week, and month layouts. Features recurring reservations with conflict detection, approval workflows, groups and role-based permissions, quotas, accessories/add-ons, email/ICS notifications, and full RESTful Web Services API . While not purpose-built for warehouse docks, its resource reservation model can be adapted for dock door scheduling with custom configurations. Deployable on Ubuntu 24.04 LTS with PHP 8.3, MariaDB, and Nginx .



- **[Yard Lense on Edge](https://www.iml.fraunhofer.de/en/fields_of_activity/material-flow-systems/software_engineering/yard-lense-on-edge-ai-supported-yard-logistics-in-real-time.html)**  

  Open-source AI-supported yard logistics solution from Fraunhofer IML developed as part of the Silicon Economy . Uses intelligent cameras with edge computing and computer vision to automatically recognize, assign, and track vehicles in real time — no cloud dependency. Features automatic vehicle detection (avoiding incorrect loading), optimized parking space allocation, yard layout management, and seamless integration with existing yard management or WMS systems . Open source for transparency and long-term independence.



- **[dock-door-assignment (Awesome Supply Chain)](https://github.com/kishorkukreja/awesome-supply-chain)**  

  AI skill for dock door assignment optimization and yard management available via `npx skills add` . Provides expertise in assigning inbound/outbound shipments to dock doors to minimize congestion, reduce dwell time, maximize throughput, and improve warehouse efficiency. Covers dock scheduling, door assignment, truck scheduling, cross-dock optimization, and appointment scheduling . Designed for integration with AI coding environments like Claude Code, Cursor, and OpenClaw.



### Additional Strong Open-Source Options



- **Cal.com** — Open-source scheduling infrastructure (AGPL-3.0) that can be adapted for dock appointment booking with custom resource types and availability rules . Self-hosted via Docker Compose with PostgreSQL and Traefik.

- **Resource reservation systems** — General-purpose open-source booking platforms (e.g., Booked Scheduler forks, Easy!Appointments) that can be configured for dock door slot management with custom fields and constraints.



**Frameworks for building custom dock scheduling solutions**: Combine **LibreBooking** as a foundation for resource reservation logic (adapting rooms/equipment to dock doors), **Yard Lense on Edge** for AI-powered yard vehicle tracking via edge cameras, and **dock-door-assignment** AI skill for optimization heuristics. For a lightweight self-hosted starting point, **Cal.com** can be configured with custom event types representing dock slots. Note that true enterprise dock scheduling with carrier networks, TMS/WMS integration, and compliance audit trails remains primarily commercial territory; open-source stacks provide reservation engines and yard vision foundations that require significant customization for warehouse dock workflows.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Dock scheduling tools handle logistics operations data including carrier information, shipment details, and appointment histories. Self-hosted solutions require proper security hardening, access controls, and data retention policies.

- Open-source dock scheduling platforms are significantly less mature than commercial offerings. Most available projects are general-purpose reservation systems or academic optimization tools that require substantial customization for warehouse dock workflows. Evaluate gaps in carrier portals, TMS/WMS integration, and compliance reporting before deployment.

- The open-source ecosystem provides strong reservation engines and yard vision foundations, but full enterprise dock scheduling with pre-connected carrier networks and automated audit trails remains primarily a commercial offering.



---



**Made for warehouse managers, logistics coordinators, 3PL operators, and supply chain technologists.**  

Let's make dock scheduling more open, transparent, and efficient.
