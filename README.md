# Pulse Mock Tool Repository

Short description
This repository contains a small mock tool and sample data for exploring and testing pulse data visuals and behavior.

Repository structure
- [data/](data/) — data files and samples  
  - [`data/sample/pulse_data.json`](data/sample/pulse_data.json) — sample pulse data used by the mock tool
- [src/](src/) — source and mock UI
  - [`src/mock-tool/PULSE_mock_report.html`](src/mock-tool/PULSE_mock_report.html) — configurable mock UI you can open in a browser
- [exec-report/](exec-report/)  
  - [`exec-report/exec-report.md`](exec-report/exec-report.md) — execution notes and report

Quick start
1. Open the mock UI directly in a browser:
   - Open [`src/mock-tool/PULSE_mock_report.html`](src/mock-tool/PULSE_mock_report.html) in your browser.
2. Or serve the repo locally (recommended for file access) and open the mock UI:
```sh
# from the repository root
python3 -m http.server 8000
# then open:
http://localhost:8000/src/mock-tool/PULSE_2_configurable.html