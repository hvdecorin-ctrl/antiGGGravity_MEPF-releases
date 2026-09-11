# antiGGGravity MEPF — Professional MEPF Toolkit for Revit

> **The definitive command guide and functional documentation for the antiGGGravity MEPF Add-in.**
> Compatible with Revit 2022, 2023, 2024, 2025, 2026, and 2027.
>
> **Current Version:** 1.0.18

---

## 📑 Table of Contents
1. [Introduction](#-introduction)
2. [Fittings Panel](#-fittings-panel)
3. [Elbow 45 Panel](#-elbow-45-panel)
4. [Drainage Design Panel](#-drainage-design-panel)
5. [Utilities Panel](#-utilities-panel)
6. [Water Supply Panel](#-water-supply-panel)
7. [Coordination Panel](#-coordination-panel)
8. [Annotation Panel](#-annotation-panel)
9. [License Panel](#-license-panel)
10. [Installation & Licensing](#-installation--licensing)
11. [Support](#-support)

---

## 🚀 Introduction
**antiGGGravity MEPF** is a high-performance productivity suite built by engineers for the MEPF (Mechanical, Electrical, Plumbing & Fire) discipline. It automates the repetitive pipe-routing, fitting, and coordination tasks that consume a large share of a modelling day — letting you focus on design intent rather than dragging connectors.

With **35 commands** across **8 ribbon panels**, the toolkit turns multi-step manual pipe connections into single-click operations, all delivered through the **antiG-MEPF** ribbon tab.

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
| **Drainage Design** | The drainage hub — automatically connect fixtures to target drains across multiple connection styles. |
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
| **Place Riser** | Click a point to drop a vertical riser between a start and end level, using the chosen piping system, pipe type, and diameter. |
| **Multi Pipe** | Configure multiple parallel pipes (each with its own level, system type, pipe type, and diameter), then draw the shared path by clicking points. Press ESC to finish and apply. |
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
| **Supply Design** | Design fixture stubs and connect them to a main supply pipe in one step. Creates up to 3 stub pipes from the fixture connector, then routes a vertical riser from the terminal stub to the main pipe elevation and branches to a T-fitting. Supports rotation and tee offset. |

---

## 🔍 Coordination Panel
*Find and resolve interferences without leaving Revit.*

| Command | Description |
|:---|:---|
| **Clash Checking** | Detect interferences between two element categories — choose Category A and B, run the check, then click a result to zoom to and select the clashing pair. Resolve clashes directly from the results list; combined sleeves are recognised. |
| **Clash Importing** | Load a clash report (.xlsx) exported from Clash Checking — browse to the file, then click any row to zoom to and select the clashing elements in the model. |
| **DeRoute / Void** | Combined clash-resolution tool. **DeRoute** mode reroutes a pipe, duct, conduit, or cable tray around an obstruction with a jog. **Void** mode places a parametric sleeve/void where an MEP element penetrates a wall, floor, or beam. Switch modes with the toggle at the top of the panel. **Auto Scan & Place** (Source mode) finds and treats penetrations in the host project and linked models. |

---

## 🏷️ Annotation Panel
*Tidy tags and text notes in seconds.*

| Command | Description |
|:---|:---|
| **Align Tag** | Stack tags and text notes into a neat vertical column. Pre-select tags (or select them after launching), choose straight or elbowed leaders, then pick the top point of the column. Tags are sorted by their element's position so leaders do not cross. |
| **Text Arrange** | Pick one point to align the elbow of every selected tag/text note onto a single common line. Row height, text position and arrow ends stay exactly where they are. Text notes are also forced to attach leaders at the top line on both sides. |

---

## 🔑 License Panel
*Licensing and activation.*

| Command | Description |
|:---|:---|
| **Hardware ID** | View your machine Hardware ID, check your trial or license status, and activate your license key. |
| **Request License** | Submit a request for a paid license key. A 30-day free trial starts automatically on first use. |
| **Check Update** | Check for new versions of antiGGGravity MEPF and download updates. |

---

## 🔑 Installation & Licensing
### Installation
1. Close all Revit sessions.
2. Download `antiGGGravity_MEPF_Installer_AllVersions.zip` and extract it.
3. Double-click `install.bat` — it automatically detects all compatible Revit versions (2022–2027) installed on your system.
4. Launch Revit. The **antiG-MEPF** tab will appear in the ribbon.

> To remove the add-in from all detected Revit versions, run `uninstall.bat`.
>
> **Installed from the Autodesk Design and Make Marketplace?** Run the downloaded installer instead, and uninstall from Windows **Settings > Apps > Installed apps**.

### Supported Revit Versions

| Revit Version | Framework        |
|---------------|------------------|
| 2022          | .NET 4.8         |
| 2023          | .NET 4.8         |
| 2024          | .NET 4.8         |
| 2025          | .NET 8 (Windows) |
| 2026          | .NET 8 (Windows) |
| 2027          | .NET 10 (Windows)|

### Free Trial & License Activation
**A 30-day free trial starts automatically** the first time you run any tool — no registration, email or key is required. Open **Hardware ID** in the License panel at any time to see the remaining trial days.

To keep using the tools after the trial:
1. Click **Request License** in the License panel, choose a license period, then click **Send Email** or **Copy Request**.
2. Enter the activation key you receive in the License Manager (**Hardware ID** button) and click **Activate License**.

> When the trial ends, all tools except the License panel require an activation key.

---

## 📧 Support
For issues or enquiries: [antiGGGravity.info@gmail.com](mailto:antiGGGravity.info@gmail.com)

---
© 2026 antiGGGravity. All rights reserved. Revit® is a registered trademark of Autodesk, Inc.
