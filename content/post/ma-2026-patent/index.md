---
title: "Patent issued: Reconfigurable Unmanned Vehicles (US 12,654,839 B2)"
summary: "US 12,654,839 B2 covers a modular UAV and ground-aerial vehicle architecture that adapts its airframe and control configuration to mission requirements."
date: '2026-10-02'
lastmod: '2026-10-02'
draft: false
featured: false
authors:
  - admin
tags:
  - UAV
  - Autonomous Systems
  - Vehicle Design
  - Control Systems
categories:
  - Patents
---

I am glad to share that **U.S. Patent 12,654,839 B2**, *Reconfigurable Unmanned Vehicles*, was issued on June 16, 2026. This patent was initially conceived more than five years ago, with my former colleagues Dr. Victor Maldonado and Dr. Donald Docimo, during my time at Texas Tech University. It is thus particularly gratifying to see the patent granted after a long examination process.

The invention defines a modular architecture for unmanned aerial vehicles (UAVs) and hybrid unmanned ground-aerial vehicles (UGAVs). A common blended-wing-body module provides the central structure, onboard control system, and interfaces for interchangeable components. The disclosed configurations include wing panels optimized for either high-speed/long-range or low-speed/high-endurance missions, vertical-tail modules, and vertical-takeoff-and-landing (VTOL) fin modules. A ground-aerial configuration further incorporates a powertrain and wheel module.

## Key technical ideas

- **Mission-specific airframe reconfiguration.** Wing and tail/VTOL modules can be selected and mounted based on mission parameters such as range, cruise speed, payload, and VTOL capability.
- **A common mechanical and electrical interface.** Quick lock/release interfaces couple the modules to the blended-wing-body platform while also providing the electrical connection to the vehicle controller.
- **Configuration-aware control.** Powered modules can include logic circuits that identify the installed configuration to the controller. The specification describes using the resulting signal to select appropriate throttle and control behavior for the vehicle variant.
- **A unified aerial and ground-aerial design framework.** The patent addresses both fixed-wing UAV variants and configurations that combine aerial propulsion with wheeled terrestrial operation.

The issued claims cover the modular vehicle systems and a method for defining mission parameters, choosing the corresponding wing and tail/VTOL modules, mounting them to the blended-wing-body module, and controlling the selected propulsion hardware.

The patent traces to U.S. provisional application 63/128,750, filed December 21, 2020. The non-provisional application was filed December 21, 2021 and published as [US 2024/0043144 A1](https://patents.justia.com/patent/20240043144). The complete issued document is available from the [USPTO as US 12,654,839 B2](https://ppubs.uspto.gov/api/pdf/downloadPdf/US-12654839-B2?source=USPAT&requestToken=eyJzdWIiOiJkMmRhZGUwNy02YmQ2LTRkZWYtYjhkNi05NmM5YTVkZDIwOTkiLCJ2ZXIiOiIzNTdiZTcxMi05ZDZkLTRhOTEtODcwZi1lMGM5ZGM3YjFhMmEiLCJleHAiOjB9).

*This post is a technical summary of the public patent record; the issued claims define the scope of the patent.*
