# Vadim Kalduzov

**English** | [Русский](README.ru.md)

**Computer Science Student**  
Interested in OS administration (Linux/Windows), OpenWrt firmware builds, and applied software development.

---

## Focus & Technical Background

- **Linux & Embedded:** Daily administration of Arch Linux; hands-on familiarity with Debian and ALT Linux. Building OpenWrt from source (Buildroot), Device Tree (DTS) editing, and working with MT7621/MT7981 router hardware.
- **Windows Systems:** Installation, configuration, and troubleshooting of desktop Windows (Windows 95–11), plus basic Windows Server setup.
- **Programming & Scripting:** Python and Bash scripting, basic SQL, and reading/navigating existing Java codebases.
- **Applied Machine Learning:** Tabular data preprocessing, model evaluation, and ONNX export for local inference.

---

## Featured Work

- **[OpenWrt: D-Link DIR-1260 R1 Support](https://github.com/openwrt/openwrt/pull/25233)** (Upstream PR #25233)  
  Adapted an [initial community patch](https://github.com/Lucky1openwrt/openwrt/commit/b03f52df9c7f1b5490607926dbf0256065705f24) for the D-Link DIR-1260 Rev. R1 router (MediaTek MT7621DAT) to the current OpenWrt codebase. Fixed LED definitions, replaced the hardcoded 40 MB firmware partition limit in DTS to utilize the full 128 MB NAND (~100 MB usable space), enabled USB host support, and verified hardware operation and official `kmod` compatibility.

- **[ML MedClass Experiments: ONNX Manifest & CLI Packaging](https://github.com/Nikon59/ml-medclass-experiments)** (Fork of `RedT0wer/ml-medclass-experiments`)  
  Contributed to the upstream Python tabular classification framework and extended a fork (`feature/onnx-mobile-export`) for mobile deployment: added `generate_mobile_manifest.py` to export Z-score normalization parameters, feature bounds, and SHA-256 model checksums into `model_manifest.json`, and configured GitHub Actions to package standalone Linux/Windows CLI binaries.

- **[Pancreatitis (Pancreolana): Local ONNX Inference Fork](https://github.com/Nikon59/Pancreatitis)** (Fork of `Pancreatitis`)  
  Modified an existing Android prototype to run local ONNX models (ONNX Runtime 1.31.0) instead of text similarity heuristics. Extracted platform-independent logic into a Java 17 `:core` module, updated the UI to Material 3, stripped out external cloud sync and pre-populated database files (initializing an empty local SQLite DB via an offline login stub), and added local keystore encryption.

---

## Contact & Opportunities

- **Email:** vadimkalduzov05@gmail.com
