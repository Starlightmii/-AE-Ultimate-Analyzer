# 🚀 AE Ultimate Analyzer

> The most advanced After Effects hardware, plugin, workflow, and version recommendation engine for Windows.

![PowerShell](https://img.shields.io/badge/PowerShell-5.1+-5391FE?logo=powershell)
![Platform](https://img.shields.io/badge/Platform-Windows-blue)
![Adobe After Effects](https://img.shields.io/badge/Adobe-After%20Effects-9999FF)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📖 Overview

AE Ultimate Analyzer is a professional-grade PowerShell toolkit designed to analyze a Windows workstation and determine:

- 🎬 Best After Effects version
- ⚡ Optimal AE settings
- 💾 Cache configuration
- 🔌 Plugin compatibility
- 📊 Performance bottlenecks
- 🚀 Workflow recommendations

Unlike simple hardware checkers, AE Ultimate Analyzer performs deep inspection of hardware, plugins, cache systems, workflows, and projects to generate intelligent recommendations.

---

## ✨ Features

### 🖥️ Hardware Analysis

- CPU architecture detection
- P-Core / E-Core topology
- Thread count analysis
- Turbo frequency detection
- Thermal monitoring
- RAM configuration analysis
- Storage performance inspection
- GPU capability analysis
- Driver validation

### 🎬 After Effects Intelligence

Supports detection of:

- AE 2020
- AE 2021
- AE 2022
- AE 2023
- AE 2024
- AE 2025

Analyzes:

- Memory settings
- Multi-Frame Rendering
- Disk cache
- Expression cache
- Preview configuration
- GPU acceleration

### 🔌 Plugin Compatibility Engine

Automatically scans:

- Twixtor
- Sapphire
- Boris FX Continuum
- Deep Glow
- Element 3D
- Optical Flares
- Trapcode Suite
- Universe
- Particular

### 📊 Benchmark Engine

#### CPU

- Single-core benchmark
- Multi-core benchmark
- Sustained performance

#### RAM

- Bandwidth testing
- Allocation testing
- Cache simulation

#### Storage

- NVMe detection
- Sequential speed
- Random IO
- Cache performance

#### Thermal

- Throttling detection
- Sustained workload testing

### 📁 Project Analysis

Supports:

- `.aepx` parsing
- Composition analysis
- Expression analysis
- Layer statistics
- Effect inventory

Detects:

- Twixtor-heavy projects
- Optical flow workflows
- Deep Glow usage
- Excessive pre-comps
- Heavy expressions
- VFR footage

---

## 🤖 Recommendation Engine

The AI recommendation system evaluates:

| Factor | Weight |
|----------|----------|
| CPU | 25% |
| RAM | 25% |
| Storage | 15% |
| GPU | 15% |
| Plugins | 10% |
| Workflow | 10% |

Example output:

```text
AE 2020 : 88
AE 2022 : 96
AE 2023 : 91
AE 2024 : 89
AE 2025 : 61

Recommended:
AE 2022 v22.6
```

---

## 🏗️ Architecture

```text
AE-Ultimate-Analyzer
│
├── Start-AEAnalyzer.ps1
│
├── Core
│   ├── HardwareScanner.psm1
│   ├── CPUAnalyzer.psm1
│   ├── RAMAnalyzer.psm1
│   ├── StorageAnalyzer.psm1
│   ├── GPUAnalyzer.psm1
│   └── ThermalAnalyzer.psm1
│
├── Adobe
│   ├── InstalledVersions.psm1
│   ├── PreferenceParser.psm1
│   ├── CacheInspector.psm1
│   └── ProjectScanner.psm1
│
├── Plugins
│   ├── TwixtorAnalyzer.psm1
│   ├── SapphireAnalyzer.psm1
│   ├── BCCAnalyzer.psm1
│   └── Element3DAnalyzer.psm1
│
├── Benchmark
│   ├── CPUBenchmark.psm1
│   ├── MemoryBenchmark.psm1
│   └── DiskBenchmark.psm1
│
├── AI
│   ├── VersionScorer.psm1
│   ├── BottleneckDetector.psm1
│   └── RecommendationEngine.psm1
│
├── Reports
│   ├── HtmlDashboard.psm1
│   ├── JsonExport.psm1
│   └── MarkdownExport.psm1
│
└── Database
    ├── ae_versions.json
    ├── plugin_compatibility.json
    ├── cpu_reference.json
    └── gpu_reference.json
```

---

## 📸 Sample Report

```text
==================================================
AE ULTIMATE ANALYZER
==================================================

SYSTEM SCORE
-----------------------------------
CPU ............ 82
GPU ............ 71
RAM ............ 64
Storage ........ 93

WORKFLOW DETECTED
-----------------------------------
Anime Editing
Twixtor Heavy
1080p Editing

PLUGINS
-----------------------------------
Twixtor 7.5
BCC 2024
Sapphire 2024
Deep Glow

BOTTLENECKS
-----------------------------------
1. RAM Pressure
2. VFR Footage
3. Cache Placement

AE VERSION SCORES
-----------------------------------
AE 2020 ......... 88
AE 2022 ......... 96
AE 2023 ......... 91
AE 2024 ......... 89
AE 2025 ......... 61

WINNER
-----------------------------------
AE 2022 v22.6

Confidence: 94%
```

---

## 🚀 Getting Started

### Clone Repository

```bash
git clone https://github.com/yourusername/AE-Ultimate-Analyzer.git
cd AE-Ultimate-Analyzer
```

### Run Analyzer

```powershell
.\Start-AEAnalyzer.ps1
```

### Generate Report

```powershell
.\Start-AEAnalyzer.ps1 -ExportHtml
```

---

## 📋 Roadmap

### Version 1.0

- [x] Hardware Scanner
- [x] RAM Analysis
- [x] GPU Analysis
- [x] Storage Analysis

### Version 2.0

- [ ] Plugin Compatibility Engine
- [ ] Project Analyzer
- [ ] Benchmark Suite
- [ ] AI Recommendation System

### Version 3.0

- [ ] Machine Learning Scoring
- [ ] Cloud Benchmark Database
- [ ] Automatic AE Optimization

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Open a Pull Request

---

## 📜 License

Licensed under the MIT License.

---

## ⭐ Support

If this project helps improve your After Effects workflow:

⭐ Star the repository

🐛 Report bugs

💡 Suggest features

🚀 Contribute improvements

---

> Built for editors who want maximum After Effects performance with minimum guesswork.
