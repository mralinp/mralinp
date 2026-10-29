# Ali Naderi Parizi

![AI and systems engineering](https://img.shields.io/badge/AI_%26_Systems-Engineering-1f2937?style=for-the-badge)
![Engineering leadership](https://img.shields.io/badge/Engineering-Leadership-334155?style=for-the-badge)
![Applied research](https://img.shields.io/badge/Applied-Research-475569?style=for-the-badge)

I build systems from hardware to production software. My work spans passwordless authentication, AI infrastructure, and machine learning for 3D medical imaging, with hands-on engineering across firmware, operating systems, backend services, and deployment.

[![Website](https://img.shields.io/badge/Website-111827?style=for-the-badge)](https://alinaderiparizi.com)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=2zycrawAAAAJ&hl=en)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge)](https://www.linkedin.com/in/ali-naderi-parizi-5a0a74107/)
[![Email](https://img.shields.io/badge/Email-334155?style=for-the-badge)](mailto:me@alinaderiparizi.com)

## 💼 Experience

- **SciNext — CTO, AI.** Designed and built the production platform and AI applications, including Kubernetes infrastructure, GitOps delivery, and observability.
- **IDmelon — engineering lead.** Led engineering on FIDO2 passwordless authentication from R&D to production. Shipped Windows sign-in with security keys for local accounts.
- **Medical imaging research.** Developed methods for breast lesion classification from 3D ultrasound. Published in *Expert Systems with Applications*.
- **Embedded engineering.** Designing and building FPGA, microcontroller, and embedded Linux systems since 2017, including a custom Linux system-on-board.
- **Competitive programming.** Former ACM ICPC representative and coach.

## 📡 Featured work — X28 OpenWrt

[**Native OpenWrt for the ZLT X28 5G router**](https://github.com/mralinp/zlt-x28-openwrt)

I’m bringing OpenWrt 23.05 to a locked-down MediaTek MT6890-based router, integrating the vendor kernel and modem stack with standard OpenWrt networking and management.

- Built USB recovery and guarded flashing tools, with hash-verified backups of all 51 NAND partitions.
- Integrated 5G data into netifd with a custom cellular protocol and LuCI configuration page, supporting IPv4, IPv6, and dual-stack connections.
- Implemented A/B boot-counter handling to preserve fallback to stock firmware.
- Built a reproducible image pipeline that combines public OpenWrt packages with proprietary components extracted locally from the owner’s device.

The native image boots and carries 5G traffic on physical hardware. The project is in beta, validated on one unit; Wi-Fi client and throughput testing and a dedicated recovery slot remain in progress.

## 🔬 Ongoing research — 3D breast ultrasound

[**Breast lesion classification in 3D ABUS**](https://github.com/mralinp/abus-classification) · [Research project page](https://alinaderiparizi.com/abus-classification/)

I’m working with colleagues at the Iran Image Processing Lab on an open research project studying how lesion geometry can help distinguish benign and malignant masses in automated breast ultrasound. It builds on our [published work on Laplace–Beltrami spectra and dual-path CNNs](https://doi.org/10.1016/j.eswa.2025.129973).

- Reproduced classical radiomics methods on TDSC-ABUS; extending the comparison to deep learning methods under a shared evaluation protocol.
- Investigating what Laplace–Beltrami spectra capture about lesion shape and how stable these representations are under segmentation errors.
- Developing and evaluating spectral shape descriptors, with code, experiments, and the research roadmap available publicly.

The research is ongoing, with a follow-up paper in preparation.

## 🛠️ Selected projects

| Project | Description |
|---|---|
| [MQute](https://github.com/mralinp/MQute) | Async Python framework for MQTT services with FastAPI-style routing, typed payloads, dependency injection, middleware, and broker-free testing. |
| [ez-crawl](https://ezcrawl.ir) | Visual web scraping pipelines with LLM-based extraction and CSV/JSON export. |
| [wrtforge](https://github.com/mralinp/wrtforge) | OpenWrt setup over SSH, with VPN and tunneling tools and a recovery slot. |
| [tdsc-abus2023-pytorch](https://github.com/mralinp/tdsc-abus2023-pytorch) | A PyTorch dataset package for the TDSC-ABUS 2023 breast ultrasound challenge, available on PyPI. |
| [khiar-ware](https://github.com/mralinp/khiar-ware) | Archived C++ CS:GO game modification project exploring game memory and security concepts, with a Python offset updater. |
| [saffron-cut](https://github.com/mralinp/RefineDet-detecting-saffron-flowers-endpoint) | PyTorch reimplementation of RefineDet that predicts flower centers and cutting angles for a robotic harvesting application. |
| [RangLoom](https://github.com/mralinp/RangLoom) | A Persian carpet color-mixing app for sampling colors from images and suggesting base-color blends. |
| [mojo-spartan6-projects](https://github.com/mralinp/mojo-spartan6-projects) | Verilog projects for a Spartan-6 FPGA, built and flashed from macOS. |
| [latex-academic-template](https://github.com/mralinp/latex-academic-template) | A Docker-based academic LaTeX setup that runs without a local TeX installation. |
| [Persian TTS](https://tts.jome-farmer.ir) | Transformer-based Persian speech synthesis and voice cloning. |
| [JoME](https://jome-farmer.ir) | An irrigation system with an ESP32 controller, flow measurement, a mobile app, and a FastAPI/MQTT backend. |
| [acm-code-book](https://github.com/mralinp/acm-code-book) | Competitive programming reference implementations covering graphs, geometry, dynamic programming, strings, and data structures. |

[More repositories →](https://github.com/mralinp?tab=repositories)

## ⚙️ Technical focus

![Languages and tools: Python, PyTorch, TensorFlow, C++, C, Rust, Java, TypeScript, React, Next.js, Tailwind CSS, FastAPI, Django, PostgreSQL, MongoDB, Docker, Kubernetes, Prometheus, Grafana, Linux, Bash, Git](https://skillicons.dev/icons?i=python,pytorch,tensorflow,cpp,c,rust,java,ts,react,nextjs,tailwind,fastapi,django,postgres,mongodb,docker,kubernetes,prometheus,grafana,linux,bash,git&perline=11)

- **Machine learning:** Python, PyTorch, Lightning, Transformers, NumPy, SciPy; medical imaging, computer vision, and speech synthesis.
- **Infrastructure:** Linux, Kubernetes, Argo CD, Docker, Prometheus, Grafana, Loki, and Tempo.
- **Security and embedded systems:** FIDO2, Windows credential providers, Java Card, C/C++, Verilog, microcontrollers, and OpenWrt.
- **Applications:** TypeScript, React, FastAPI, Django, and PostgreSQL.

---

From Pariz. Outside engineering: rock music, strength training, running, and my family’s pistachio farm. Former professional basketball player.
