# PMO-Office

**DevOps Lab Sheet 1 — Case 2**  
Central Git repository for **PMO planning and inventory** across locations. Artifacts are versioned with Git and hosted on GitHub.

## Case overview

As a PMO member, you maintain planning and inventory data: append to existing files, add new files, commit locally, and push to a **central server** (GitHub).

### Lab steps (completed)

| Step | Description |
|------|-------------|
| 1 | Create a GitHub account |
| 2 | Start a new project **PMO-Office** |
| 3 | Add an Excel sheet for inventory |
| 4 | Commit the changes |
| 5 | Create a local repository on your laptop |
| 6 | Add more files in the local repo |
| 7 | Commit changes in the local repo |
| 8 | Push files to the server |

## Repository links

| Resource | URL |
|----------|-----|
| **GitHub repository** | https://github.com/2025tm93239/PMO-Office |
| **Inventory (Excel)** | https://github.com/2025tm93239/PMO-Office/blob/main/Inventory.xlsx |
| **Git operation screenshots** | https://github.com/2025tm93239/PMO-Office/tree/main/Screenshots |

## Project structure

```
PMO-Office/
├── README.md                                          # This file — project overview
├── Inventory.xlsx                                     # PMO inventory workbook (Excel)
├── Lab 1 Case 2 Assignment Git Operations Execution.docx   # Lab report with screenshots
└── Screenshots/                                       # Evidence of Git commands & GitHub UI
    ├── Screenshot_2026-10-27_10-36-45.png
    ├── Screenshot_2026-10-27_10-40-25.png
    ├── Screenshot_2026-10-27_10-48-36.png
    ├── Screenshot_2026-10-27_11-03-27.png
    ├── Screenshot_2026-10-27_11-03-56.png
    ├── Screenshot_2026-10-27_11-05-00.png
    ├── Screenshot_2026-10-27_11-06-56.png
    ├── Screenshot_2026-10-27_11-16-11.png
    ├── Screenshot_2026-10-27_11-18-56.png
    ├── Screenshot_2026-10-27_11-20-06.png
    └── Screenshot_2026-10-27_12-07-45.png
```

## Local path

```
D:\Bits-pilani\Intro To DEVOPS(CSI ZG514)\Lab Assignment\PMO-Office
```

## Clone and work locally

```bat
cd "D:\Bits-pilani\Intro To DEVOPS(CSI ZG514)\Lab Assignment"
git clone https://github.com/2025tm93239/PMO-Office.git
cd PMO-Office
```

## Typical Git workflow

```bat
git status
git add Inventory.xlsx README.md Screenshots\
git commit -m "Update inventory and documentation"
git pull origin main
git push origin main
```

## Files description

| File / folder | Purpose |
|---------------|---------|
| `Inventory.xlsx` | Master inventory sheet (items, quantities, locations); update and commit when stock changes |
| `Screenshots/` | Screenshots of `git init`, `commit`, `push`, and GitHub repository views for lab submission |
| `Lab 1 Case 2 Assignment Git Operations Execution.docx` | Formatted lab execution report (introduction, summary, embedded screenshots) |

## Related lab work

- **Case 1 (Web-Dev):** `..\Web-Dev` — branching, merge, Java/JavaScript branches  
- **Lab capsule:** `..\LAB Capsules\Lab Capsule -1\` — official lab sheet (M3: Source Code Management)

## Author

BITS WILP — DevOps (CSI ZG514)  
GitHub: [2025tm93239](https://github.com/2025tm93239)
