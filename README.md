# Core 1 Sims

Hands-on, browser-based IT support simulations for CompTIA A+ Core 1–style training. Every sim is a single self-contained HTML file — no build step, no server, no dependencies. Open `index.html` to browse all of them from one page, or open any simulation file directly.

**Educational Use Notice:** These are training simulations for educational purposes only. They are not real hardware, not a real RAID array or storage system, and are not affiliated with, endorsed by, or a replica of any certification exam or vendor product.

## Getting started

- **Locally:** download the repo and open `index.html` in any modern browser.
- **On GitHub Pages:** enable Pages for this repo (Settings → Pages → deploy from the default branch) and it will serve `index.html` at the repo's Pages URL.
- All sims are mobile-friendly (touch drag-and-drop, responsive layout) as well as desktop-friendly.
- The homepage tile grid cycles through six colors (red, green, blue, yellow, orange, purple) and reflows to a single column on narrow screens.

## Simulations

| Simulation | File | What it covers |
|---|---|---|
| Device Issue Diagnosis | `Device Issue Diagnosis.html` | Diagnose common device problems from symptoms. |
| MFD Printer Deployment & Troubleshooting *(not yet uploaded)* | `MFD Printer Deployment & Troubleshooting.html` | Deploy and troubleshoot a multi-function printer. |
| Mobile Device Troubleshooting *(not yet uploaded)* | `Mobile Device Troubleshooting Simulation.html` | Work through mobile device fault scenarios. |
| Power Source Drag & Drop | `Power Management.html` | Match power sources to the right equipment. |
| Workstation Build & Compatibility Check *(not yet uploaded)* | `Workstation Build & Compatibility Check Simulation.html` | Build a workstation and verify part compatibility. |
| Workstation Hardware Troubleshooting *(not yet uploaded)* | `Workstation Hardware Troubleshooting Simulation.html` | Track down faulty hardware on a workstation. |
| PC Builder | `PC Builder/PC Builder.html` | Assemble a PC from individual components. |
| Gaming PC Diagnostic | `PC Diagnostic/PC Diagnostic.html` | Find and fix issues on a gaming PC build. |
| Printer Component Drag-and-Drop | `Printer Troubleshooting/PrinterPBQ.html` | Identify laser printer components by function. |
| RAID Configuration Challenge | `RAID Configuration/RAID Configuration.html` | Configure the right RAID level for the scenario. |
| RAID Troubleshooting Challenge | `RAID Troubleshooting/RAID Troubleshooting.html` | Diagnose and repair a failing RAID array. |
| **RAID Configuration Challenge (Rebuilt)** | `RS's Raid config1.2.html` | Build a RAID 1, 5, 6, or 10 array to spec — matching pairs for mirrored levels, parity overhead for striped levels — for customers scaling from Small Business to Major Corporation. |
| **RAID Troubleshooting Challenge (Rebuilt)** | `RS's RAID replace.html` | Replace failed drives with a spec-matching spare (capacity and speed, drive type doesn't matter) across four difficulty tiers from Small Business to Major Corporation. |
| WAP Installation Simulation | `WAP Installation/WAP Installation Simulation.html` | Install and cable a wireless access point. |

Some sims ship with an answer key (`*_Answer_Key.pdf` / `*.jpg`) alongside the HTML file.

## Repo structure

```
index.html                        Homepage — tile grid linking to every simulation
README.md                         This file
*.html (repo root)                Single-file sims with no extra assets
PC Builder/                       PC Builder sim + its answer key/image
PC Diagnostic/                    Gaming PC Diagnostic sim + its answer key/image
Printer Troubleshooting/          Printer sim + its answer key/image
RAID Configuration/               Original RAID Configuration sim + its answer key/image
RAID Troubleshooting/             Original RAID Troubleshooting sim + its answer key/image
WAP Installation/                 WAP Installation sim + all its cabling/hardware images
```

## Contributing

These sims are plain HTML/CSS/JS — open any file in a text editor to read or modify it. Keep each simulation self-contained (no external asset or script dependencies) so it keeps working offline and on GitHub Pages.
