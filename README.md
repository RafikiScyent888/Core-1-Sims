# Core 1 Sims

Hands-on, browser-based IT support simulations for CompTIA A+ Core 1–style training. Every sim is a single self-contained HTML file — no build step, no server, no dependencies. Open `index.html` to browse all of them from one page, or open any simulation file directly.

**Educational Use Notice:** These are training simulations for educational purposes only. They are not real hardware, not a real RAID array or storage system, and are not affiliated with, endorsed by, or a replica of any certification exam or vendor product.

## Getting started

- **Locally:** download the repo and open `index.html` in any modern browser.
- **On GitHub Pages:** enable Pages for this repo (Settings → Pages → deploy from the default branch) and it will serve `index.html` at the repo's Pages URL.
- All sims are mobile-friendly (touch drag-and-drop, responsive layout) as well as desktop-friendly.

## Simulations

| Simulation | File | What it covers |
|---|---|---|
| Device Issue Diagnosis | `Sims-Folder/Device Issue Diagnosis.html` | Diagnose common device problems from symptoms. |
| MFD Printer Deployment & Troubleshooting | `Sims-Folder/MFD Printer Deployment & Troubleshooting.html` | Deploy and troubleshoot a multi-function printer. |
| Mobile Device Troubleshooting | `Sims-Folder/Mobile Device Troubleshooting Simulation.html` | Work through mobile device fault scenarios. |
| Power Source Drag & Drop | `Sims-Folder/Power_Management.html` | Match power sources to the right equipment. |
| Workstation Build & Compatibility Check | `Sims-Folder/Workstation Build & Compatibility Check Simulation.html` | Build a workstation and verify part compatibility. |
| Workstation Hardware Troubleshooting | `Sims-Folder/Workstation Hardware Troubleshooting Simulation.html` | Track down faulty hardware on a workstation. |
| PC Builder | `Sims-Folder/PC Builder/PC Builder.html` | Assemble a PC from individual components. |
| Gaming PC Diagnostic | `Sims-Folder/PC Diagnostic/PC Diagnostic.html` | Find and fix issues on a gaming PC build. |
| Printer Component Drag-and-Drop | `Sims-Folder/Printer Troubleshooting/PrinterPBQ.html` | Identify laser printer components by function. |
| RAID Configuration Challenge | `Sims-Folder/RAID Configuration/RAID Configuration.html` | Configure the right RAID level for the scenario. |
| RAID Troubleshooting Challenge | `Sims-Folder/RAID Troubleshooting/RAID Troubleshooting.html` | Diagnose and repair a failing RAID array. |
| **RAID Configuration Challenge (Rebuilt)** | `Sims-Folder/RS's Raid config 1.2.html` | Build a RAID 1, 5, 6, or 10 array to spec — matching pairs for mirrored levels, parity overhead for striped levels — for customers scaling from Small Business to Major Corporation. |
| **RAID Troubleshooting Challenge (Rebuilt)** | `Sims-Folder/RS's Raid replace.html` | Replace failed drives with a spec-matching spare (capacity and speed, drive type doesn't matter) across four difficulty tiers from Small Business to Major Corporation. |
| WAP Installation Simulation | `Sims-Folder/WAP Installation/WAP Installation Simulation.html` | Install and cable a wireless access point. |

Some sims ship with an answer key (`*_Answer_Key.pdf` / `*.jpg`) alongside the HTML file, in the same folder.

## Repo structure

```
index.html            Homepage — tile grid linking to every simulation
README.md             This file
Sims-Folder/           All simulations, each self-contained (HTML + any images/answer keys it needs)
```

## Contributing

These sims are plain HTML/CSS/JS — open any file in a text editor to read or modify it. Keep each simulation self-contained (no external asset or script dependencies) so it keeps working offline and on GitHub Pages.
