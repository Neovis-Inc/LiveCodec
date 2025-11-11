# LiveCodec

**LiveCodec** is a lightweight codec installation package for Windows,  
developed and distributed by **Neovis Inc.** to improve multimedia playback compatibility.  
It installs essential DirectShow filters and FFmpeg-based decoders, enabling most video and audio files to play correctly on systems that lack codecs.

---

## 📦 Overview

- **Purpose:** Fix “video or audio not playing” issues by installing open codecs.  
- **Technology Base:**  
  - [LAV Filters](https://github.com/Nevcairiel/LAVFilters) — GPL v2  
  - [FFmpeg](https://ffmpeg.org/) — LGPL v2.1+  
- **License Compliance:** Fully GPL/LGPL compliant; all original source codes are provided or mirrored below.  
- **Supported Formats:** H.264, H.265/HEVC, VP9, AV1, AAC, AC3, DTS, MP3, FLAC, OGG, and more.

---

## 📁 Directory Layout

```
LiveCodec/
├─ bin/
│ ├─ LAVSplitter.ax
│ ├─ LAVAudio.ax
│ ├─ LAVVideo.ax
│ ├─ avcodec-lav-62.dll
│ ├─ avformat-lav-62.dll
│ ├─ avutil-lav-60.dll
│ ├─ swresample-lav-6.dll
│ ├─ swscale-lav-9.dll
│ └─ avfilter-lav-11.dll
│
├─ licenses/
│ ├─ GPL-2.0.txt
│ ├─ LGPL-2.1.txt
│ ├─ CHANGELOG.txt
│ ├─ THIRD-PARTY-NOTICES.txt
│ └─ OFFER.txt
│
└─ opensource/
├─ lav-filters/
│ ├─ LAVFilters-0.80-x64.zip
│ └─ SHA256.txt
│
└─ ffmpeg/
├─ ffmpeg-7.0.3.tar.xz
└─ SHA256.txt
```

---

## 🧩 Components and Licenses

### LAV Filters v0.80
- **Author:** Hendrik N. Leppkes (Nevcairiel)  
- **License:** [GPL v2](licenses/GPL-2.0.txt)  
- **Source:** [https://github.com/Nevcairiel/LAVFilters/releases/tag/0.80](https://github.com/Nevcairiel/LAVFilters/releases/tag/0.80)  

### FFmpeg (used within LAV Filters)
- **License:** [LGPL v2.1+](licenses/LGPL-2.1.txt)  
- **Source:** [https://ffmpeg.org/download.html](https://ffmpeg.org/download.html)  

### License Summary

| Component | License | Description |
|------------|----------|-------------|
| **LAV Filters** | GPL v2 | DirectShow audio/video splitters & decoders |
| **FFmpeg** | LGPL v2.1+ | Multimedia codec framework used by LAV Filters |
| **LiveCodec Installer (.nsi)** | Proprietary (Neovis Inc.) | Independent installation script (not GPL code) |

See [licenses/THIRD-PARTY-NOTICES.txt](licenses/THIRD-PARTY-NOTICES.txt) for full third-party information.

---

## 📜 Source Code Offer (GPL/LGPL Compliance)

Per GPL v2 and LGPL v2.1, Neovis Inc. offers to provide the full corresponding source code for all redistributed open-source components for a period of **three (3) years** from the date of distribution.

You can:
- Download directly from this repository under `/opensource/`, or  
- Request by email: **info@neovis.net**

See [licenses/OFFER.txt](licenses/OFFER.txt) for the complete offer.

---

## 🏢 Publisher

**Neovis Inc.**  
#A59-708, 100 Crystal-ro, Seo-gu, Incheon, Republic of Korea  
📧 info@neovis.net  
🌐 [https://livecodec.co.kr](https://livecodec.co.kr) · [https://github.com/neovis-inc/LiveCodec](https://github.com/neovis-inc/LiveCodec)

---

## ⚠️ Disclaimer

LiveCodec includes third-party open-source components distributed under their respective licenses.  
Neovis Inc. provides these components **unmodified** and **without warranty**.  
Use of this installer implies acceptance of the associated open-source licenses.

---

© 2025 **Neovis Inc.** All rights reserved.
