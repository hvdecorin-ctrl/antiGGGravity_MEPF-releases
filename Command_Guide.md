# antiGGGravity MEPF — Professional MEPF Toolkit for Revit

> **The definitive command guide and functional documentation for the antiGGGravity MEPF Add-in.**
> Compatible with Revit 2022, 2023, 2024, 2025, 2026, and 2027.
>
> **Current Version:** 1.0.19

---

## 📑 Table of Contents
1. [Introduction](#-introduction)
2. [License Panel](#-license-panel)
3. [Fittings Panel](#-fittings-panel)
4. [Elbows & Traps Panel](#-elbows--traps-panel)
5. [Drainage Design Panel](#-drainage-design-panel)
6. [Water Supply Panel](#-water-supply-panel)
7. [Utilities Panel](#-utilities-panel)
8. [HVAC Panel](#-hvac-panel)
9. [Fire Panel](#-fire-panel)
10. [Coordination Panel](#-coordination-panel)
11. [Fabrication Panel](#-fabrication-panel)
12. [Annotation Panel](#-annotation-panel)
13. [Installation & Licensing](#-installation--licensing)
14. [Support](#-support)

---

## 🚀 Introduction
**antiGGGravity MEPF** is a high-performance productivity suite built by engineers for the MEPF (Mechanical, Electrical, Plumbing & Fire) discipline. It automates the repetitive pipe-routing, fitting, supports, annotation and coordination tasks that consume a large share of a modelling day — letting you focus on design intent rather than dragging connectors.

With **45 commands** across **11 ribbon panels**, the toolkit turns multi-step manual work into single-click operations, all delivered through the **antiG-MEPF** ribbon tab.

> **Design values are yours.** Tools that place geometry to a rule (grades, hanger spacing, insulation, sprinkler spacing, clearances) use the values you enter from the applicable standard or project specification. Any value shown the first time is a labelled placeholder, not a code value.

---

## 🔑 License Panel
*Licensing and activation.*

| Command | Description |
|:---|:---|
| **Hardware ID** | View your machine Hardware ID, check your trial or license status, and activate your license key. |
| **Request License** | Submit a request for a paid license key. A 30-day free trial starts automatically on first use. |
| **Check Update** | Check for new versions of antiGGGravity.MEPF and download updates. |

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

## 📐 Elbows & Traps Panel
*Specialized 45-degree elbow combinations, caps, and traps.*

| Command | Description |
|:---|:---|
| **Transfer 2x45** | Convert any pipe elbow into a 2×45 combo — two 45° elbows joined by a diagonal pipe. |
| **Create 2x45** | Build a 2×45 combo by selecting two pipes — two 45° elbows joined by a diagonal pipe. |
| **Create Trap** | Select a vertical pipe and a horizontal pipe to trim and connect them with a P-trap. |
| **Pipe End Cap** | Select a pipe end to automatically place a 45° elbow and an end cap on the open connector. |

---

## 🚰 Drainage Design Panel
*Automatically connect plumbing fixtures to target drains and grade the network.*

| Command | Description |
|:---|:---|
| **Drainage Design** | The drainage hub — automatically connect fixtures to target drains across multiple connection styles. |
| **Route 01** | Smart Connect 01 — straight-entry layouts (Simple, 45° Drop, Sweep, Parallel Drop) in one window. |
| **Route 02** | Smart Connect 02 — perpendicular entry with Z-Offset and switchable 45 drop / sweep / parallel drop layouts. |
| **Route 03** | Smart Connect 03 — 45° sloped entry with Z-Offset and switchable 45 drop / sweep / parallel drop layouts. |
| **Route 04** | Connect fixtures using a parallel offset and a 45° branch into the main. |
| **Route 05** | Connect fixtures using a 45° sloped offset directly into the main via a Wye. |
| **Auto Slope** | Re-grade a connected drainage network. Pick the most downstream pipe near the end that stays fixed; everything upstream is re-graded to the grade you set per pipe size, fittings stay connected and steep drops are kept. Preview first, then apply — the result lists the new grades and inverts. |

---

## ⚡ Water Supply Panel
*Design water supply piping and connect fixtures to main lines.*

| Command | Description |
|:---|:---|
| **Supply Design** | Design fixture stubs and connect them to a main supply pipe in one step. Creates up to 3 stub pipes from the fixture connector, then routes a vertical riser from the terminal stub to the main pipe elevation and branches to a T-fitting. Supports rotation and tee offset. |

---

## 🧭 Utilities Panel
*Position, align, re-host, support, insulate and repair pipework directly in 3D.*

| Command | Description |
|:---|:---|
| **Place Riser** | Click a point to drop a vertical riser between a start and end level, using the chosen piping system, pipe type, and diameter. |
| **Multi Pipe** | Configure multiple parallel pipes (each with its own level, system type, pipe type, and diameter), then draw the shared path by clicking points. Press ESC to finish and apply. |
| **Align Pipe** | Align multiple pipes to a target pipe by location, top, bottom, or middle in a 3D view. |
| **Rotate** | Select elements, then pick a pipe or duct as the rotation axis to rotate the selection left or right by a chosen angle. |
| **Assign Level** | Reassign picked elements to a target level; level-hosted families keep their absolute elevation by compensating the offset. |
| **Auto Hanger** | Place hangers along pipes, ducts and cable trays — a size-based rule table sets hanger type and max spacing, rod length is measured up to the structure above (incl. linked models), and hangers follow their host when it moves or resizes. Trapeze mode combines side-by-side runs into one hanger. |
| **Insulation by Rule** | Apply or update pipe and duct insulation (incl. fittings and accessories) from a rule table — system type and size range set the insulation type and thickness. Works on the selection, the active view or the whole model. |
| **Reconnect** | Select a pipe fitting with an open connector, then select a pipe — the pipe endpoint is extended or trimmed to meet the fitting connector and connected. |
| **Auto Reconnect** | Scan the active view, whole model or selection for pipe ends that look connected to a fitting but are not joined (touching, running into the socket or stopping just short). Review the list — each row says what will be done or why it cannot be fixed — then **Fix All** trims or extends each pipe onto its fitting connector and joins them in one undo step. Tolerances are adjustable. |
| **Strut Pipe** | Pick a pipe to tee in Stub 1 (rotatable around the pipe axis), then add a connected Stub 2 via a 90° elbow (rotatable around Stub 1's axis). |
| **Fixture Stub** | Pick a plumbing fixture to create three connected stub pipes (vertical + horizontal + vertical). Rotate Stub 2 and Stub 3 independently in 45° steps. |

---

## 🌀 HVAC Panel
*Connect air terminals to ductwork.*

| Command | Description |
|:---|:---|
| **Air Terminal Connect** | Connect diffusers and grilles to the nearest branch duct of the same system (or one picked duct) — flex duct from a round take-off, rigid take-off with elbow and drop, or directly on the duct face. Each terminal is connected on its own, so one failure never leaves a half connection. |

---

## 🔥 Fire Panel
*Lay out sprinkler heads and their branch pipework.*

| Command | Description |
|:---|:---|
| **Sprinkler Layout** | Place sprinkler heads in rooms or spaces (incl. linked models) on a grid that meets the spacing, area per head and wall-distance values you enter for the hazard class. Preview first; the result lists spacing, area per head and any rooms that need checking. |
| **Sprinkler Pipework** | Connect rows of sprinkler heads with branch lines to a picked cross main — a tee (end-fed) or cross (centre-fed) on the main and a drop to each head. Pipe sizes come from the branch and main schedules you enter (no hydraulic calculation). Analyse first; each branch builds or fails on its own, and the whole run is one undo step. |

> Sprinkler spacing and pipe sizing values come from the designer (NZS 4541 / the applicable sprinkler standard and the fire engineer's hydraulic design); the tools place geometry to those values only.

---

## 🔍 Coordination Panel
*Find, check and resolve issues without leaving Revit.*

| Command | Description |
|:---|:---|
| **Clash Checking** | Detect interferences between two element categories (this project or loaded links) — choose Category A and B, run the check, then click a result to zoom to and select the clashing pair. Resolve clashes directly from the results list; combined sleeves are recognised. **Snap** one clash by hand, or **Auto Snap** captures a screenshot of every clash for the Excel report. |
| **Clash Importing** | Load a report (.xlsx) exported from **Clash Checking** or **MEP QA Checker** — the type is detected automatically. Click any row to zoom to and select the elements in the model; QA findings zoom to the exact fault point and show their snapshot. |
| **MEP QA Checker** | One scan of the active view, whole model or selection against switchable checks: open connectors, disconnected fittings, missing systems, drainage grades, missing hangers, insulation against your rules, over-length runs, low clearance, duplicates and overlaps, sprinkler coverage, unsleeved penetrations and clearance to structure (incl. linked models). Click a finding to zoom to it; **Fix With…** opens the tool that fixes it (or reconnects / deletes duplicates directly); **Accept** marks intentional findings for the whole team; compare with the last run; colour findings in the view; summaries by level and system; and export an Excel report with a snapshot per finding. |
| **DeRoute / Void** | All-in-one clash-resolution tool with two modes. **DeRoute** reroutes a pipe, duct, conduit or cable tray around an obstruction (beam, column, wall — in this file or a linked model) with a 45° or 90° jog; **Scan** checks the clearance in every direction first, and a clearance gap is kept from the obstruction face. **Sleeve/Void** places a parametric sleeve or void where an MEP element passes through a wall, floor or beam (including linked structural models), sized with clearance and fire rating. **Auto Scan & Place** batch-places openings for every clash in the active view, nearby openings can be combined into one rectangular opening, and sleeves update automatically when the MEP element moves or resizes (**Sync All** refreshes them all). |

---

## 🏭 Fabrication Panel
*Prepare runs for fabrication.*

| Command | Description |
|:---|:---|
| **Split Length** | Split pipes and ducts into fabrication lengths measured from each run's start, joined by union fittings. Optionally balance a short last piece; hangers are re-linked to the piece they sit on. |

---

## 🏷️ Annotation Panel
*Tag runs and tidy tags and text notes in seconds.*

| Command | Description |
|:---|:---|
| **Auto Tag** | Tag pipes, ducts and cable trays in the active view with the chosen tag types, plus optional invert tags on pipes. Tags are offset from the runs, can repeat along long runs, avoid overlapping other tags, and already-tagged runs are skipped. |
| **Align Tag** | Stack tags and text notes into a neat vertical column. Pre-select tags (or select them after launching), choose straight or elbowed leaders, then pick the top point of the column. Tags are sorted by their element's position so leaders do not cross. |
| **Text Arrange** | Pick one point to align the elbow of every selected tag/text note onto a single common line. Row height, text position and arrow ends stay exactly where they are. Text notes are also forced to attach leaders at the top line on both sides. |

---

## 🔑 Installation & Licensing
### Installation
1. Close all Revit sessions.
2. Download `antiGGGravity_MEPF_Installer_AllVersions.zip` and extract it.
3. Double-click `install.bat` — it automatically detects all compatible Revit versions (2022–2027) installed on your system.
4. Launch Revit. The **antiG-MEPF** tab will appear in the ribbon.

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
A 30-day free trial starts automatically the first time you run any tool — no registration or key needed. To keep using the tools after the trial, activate a license key:

1. Open the **Hardware ID** tool in the **License** panel of the **antiG-MEPF** tab.
2. Copy your unique Hardware ID.
3. Submit it via **Request License**, or email it to [antiGGGravity.info@gmail.com](mailto:antiGGGravity.info@gmail.com) to purchase a license.

---

## 📧 Support
For issues or enquiries: [antiGGGravity.info@gmail.com](mailto:antiGGGravity.info@gmail.com)

---
© 2026 antiGGGravity. All rights reserved. Revit® is a registered trademark of Autodesk, Inc.
