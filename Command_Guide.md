# antiGGGravity MEPF — Professional MEPF Toolkit for Revit

> **The definitive command guide and functional documentation for the antiGGGravity MEPF Add-in.**
> Compatible with Revit 2022, 2023, 2024, 2025, 2026, and 2027.
>
> **Current Version:** 1.0.8

---

## 📑 Table of Contents
1. [Introduction](#-introduction)
2. [Fittings Panel](#-fittings-panel)
3. [Elbow 45 Panel](#-elbow-45-panel)
4. [Drainage Design Panel](#-drainage-design-panel)
5. [Utilities Panel](#-utilities-panel)
6. [Water Supply Panel](#-water-supply-panel)
7. [Clash Checking Panel](#-clash-checking-panel)
8. [License Panel](#-license-panel)
9. [Installation & Licensing](#-installation--licensing)
10. [Support](#-support)

---

## 🚀 Introduction
**antiGGGravity MEPF** is a high-performance productivity suite built by engineers for the MEPF (Mechanical, Electrical, Plumbing & Fire) discipline. It automates the repetitive pipe-routing, fitting, and coordination tasks that consume a large share of a modelling day — letting you focus on design intent rather than dragging connectors.

With **33 specialized commands** across **7 ribbon panels**, the toolkit turns multi-step manual pipe connections into single-click operations, all delivered through the **antiG-MEPF** ribbon tab.

---

## 🔧 Fittings Panel
*Connect main and branch pipes cleanly with a library of preset Tee-Wye and transition layouts.*

| Command | Description |
|:---|:---|
| **Fitting Box** | Hub command combining all fitting tools — pick a fitting type from the dropdown, then select pipes to connect them. |
| **Fitting 01** | Insert a Tee-Wye between a main and branch pipe and connect them cleanly. |
| **Fitting 02** | Insert a Tee-Wye between main and branch pipes using a vertical drop layout. |
| **Fitting 03** | Connect a branch into a sloped main pipe using a Tee-Wye and three 180° elbow sweeps. |
| **Fitting 04** | Connect a branch into a main pipe using a Tee-Wye and a 45° two-elbow sloped transition. |
| **Fitting 05** | Connect main and branch pipes using a perpendicular vertical drop layout. |
| **To 2x45** | Insert a 2×45° offset into a single pipe to shift its centerline using two 45° elbows. |
| **Connect Riser** | Select a vertical riser and a horizontal branch to insert a Tee and connect them at the branch height. |

---

## 📐 Elbow 45 Panel
*Specialized 45-degree elbow combinations, caps, and traps.*

| Command | Description |
|:---|:---|
| **Transfer 2x45** | Convert any pipe elbow into a 2×45 combo — two 45° elbows joined by a diagonal pipe. |
| **Create 2x45** | Build a 2×45 combo by selecting two pipes — two 45° elbows joined by a diagonal pipe. |
| **Create Trap** | Select a vertical pipe and a horizontal pipe to trim and connect them with a P-trap. |
| **Pipe End Cap** | Select a pipe end to automatically place a 45° elbow and an end cap on the open connector. |

---

## 🚰 Drainage Design Panel
*Automatically connect plumbing fixtures to target drains using a range of routing styles.*

| Command | Description |
|:---|:---|
| **Design Route** | The drainage hub — automatically connect fixtures to target drains across multiple connection styles. |
| **Route 01** | Smart Connect 01 — straight-entry layouts (Simple, 45° Drop, Sweep, Parallel Drop) in one window. |
| **Route 02** | Smart Connect 02 — perpendicular entry with Z-Offset and switchable 45 drop / sweep / parallel drop layouts. |
| **Route 03** | Smart Connect 03 — 45° sloped entry with Z-Offset and switchable 45 drop / sweep / parallel drop layouts. |
| **Route 04** | Connect fixtures using a parallel offset and a 45° branch into the main. |
| **Route 05** | Connect fixtures using a 45° sloped offset directly into the main via a Wye. |

---

## 🧭 Utilities Panel
*Position, align, re-host, extend, and construct pipework and elements directly in 3D.*

| Command | Description |
|:---|:---|
| **Place Pipe** | Click a point to drop a vertical riser between a start and end level, using the chosen system, pipe type, and diameter. |
| **Align Pipe** | Align multiple pipes to a target pipe by location, top, bottom, or middle in a 3D view. |
| **Rotate** | Select elements, then pick a pipe or duct as the rotation axis to rotate the selection left or right by a chosen angle. |
| **Assign Level** | Reassign picked elements to a target level; level-hosted families keep their absolute elevation by compensating the offset. |
| **Reconnect** | Select a pipe fitting with an open connector, then select a pipe — the pipe endpoint is extended or trimmed to meet the fitting connector and connected. |
| **Strut Pipe** | Pick a pipe to tee in Stub 1 (rotatable around the pipe axis), then add a connected Stub 2 via a 90° elbow (rotatable around Stub 1's axis). |
| **Fixture Stub** | Pick a plumbing fixture to create three connected stub pipes (vertical + horizontal + vertical). Rotate Stub 2 and Stub 3 independently in 45° steps. |

---

## ⚡ Water Supply Panel
*Design water supply piping and connect fixtures to main lines.*

| Command | Description |
|:---|:---|
| **Design Supply** | Design fixture stubs and connect them to a main supply pipe in one step. Creates up to 3 stub pipes from the fixture connector, then routes a vertical riser from the terminal stub to the main pipe elevation and branches to a T-fitting. Supports rotation and tee offset. |

---

## 🔍 Clash Checking Panel
*Find and resolve interferences without leaving Revit.*

| Command | Description |
|:---|:---|
| **Check Clash** | Detect interferences between two element categories — choose Category A and B, run the check, then click a result to zoom to and select the clashing pair. |
| **Resolve Clash** | Reroute a pipe around an obstruction (beam, column, pipe, wall, etc.) — pick the obstruction then the pipe, choose a direction and 45°/90° elbows, and the pipe jogs past and rejoins its original line. |

---

## 🔑 License Panel
*Licensing and activation.*

| Command | Description |
|:---|:---|
| **Hardware ID** | View your machine Hardware ID and activate your license key. |
| **Request License** | Submit a request for a trial or full license. |
| **Check Update** | Check for new versions of antiGGGravity MEPF and download updates. |

---

## 🔑 Installation & Licensing
### Installation
1. Close all Revit sessions.
2. Download `antiGGGravity_MEPF_Installer_AllVersions.zip` and extract it.
3. Double-click `install.bat` — it automatically detects all compatible Revit versions (2022–2027) installed on your system.
4. Launch Revit. The **antiGGGravity MEPF** tab will appear in the ribbon.

> To remove the add-in from all detected Revit versions, run `uninstall.bat`.

### Supported Revit Versions

| Revit Version | Framework        |
|---------------|------------------|
| 2022          | .NET 4.8         |
| 2023          | .NET 4.8         |
| 2024          | .NET 4.8         |
| 2025          | .NET 8 (Windows) |
| 2026          | .NET 8 (Windows) |
| 2027          | .NET 10 (Windows)|

### License Activation
A license key is required to use antiGGGravity MEPF tools.

1. Open the **Hardware ID** tool in the **antiGGGravity MEPF** License panel.
2. Copy your unique Hardware ID.
3. Submit it via **Request License**, or email it to [antiGGGravity.info@gmail.com](mailto:antiGGGravity.info@gmail.com) to request a trial or purchase a license.

---

## 📧 Support
For issues or enquiries: [antiGGGravity.info@gmail.com](mailto:antiGGGravity.info@gmail.com)

---
© 2026 antiGGGravity. All rights reserved. Revit® is a registered trademark of Autodesk, Inc.
