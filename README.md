# Taha Tahsin Akyüz

**Computer Engineering | Hardware-Software Co-Design (RISC-V & FPGA) • AI Systems & LLM Agents • Full-Stack & Linux Systems Development**

[LinkedIn](https://www.linkedin.com/in/taha-tahsin-aky%C3%BCz-065a0b231) • [AkyuzIDE Releases](https://github.com/tahatahsinakyuz/AkyuzIDE-releases/releases) • [taha.tahsin.akyuz18@erzurum.edu.tr](mailto:taha.tahsin.akyuz18@erzurum.edu.tr)

---

## About Me

I design and build end-to-end engineering systems spanning digital hardware architecture (**Verilog / RISC-V / FPGA**), local Large Language Model agents (**LLM / NLP / RAG**), and production desktop/web applications.

- **EDA & Hardware Tooling:** Creator of [AkyuzIDE](https://github.com/tahatahsinakyuz/AkyuzIDE-releases), an AI-assisted Electronic Design Automation (EDA) desktop IDE for RISC-V and FPGA development.
- **Computer Architecture & Embedded Systems:** Designed a 5-stage pipelined **RV32I RISC-V** processor core from scratch with hazard detection, forwarding, Wishbone SoC peripherals, and Basys3 FPGA hardware implementations.
- **Applied AI, NLP & Operations Research:** Developing LLM/RAG agents for RISC-V pipeline hazard explanation, demand forecasting models (**XGBoost + LSTM**), and Mixed-Integer Linear Programming (**MILP**) routing optimization.
- **Systems & Full-Stack Engineering:** Building Linux audio routing tools (**AkyuzMix** for PulseAudio/PipeWire) and containerized full-stack web platforms (**FastAPI, React, Electron, MERN, Docker**).

---

## Technical Skills

| Domain | Technologies & Tools |
| :--- | :--- |
| **Hardware, Embedded & EDA** | `Verilog HDL`, `RISC-V (RV32I)`, `Xilinx Vivado`, `Basys3 FPGA`, `Icarus Verilog`, `Wishbone SoC`, `C`, `RISC-V Assembly`, `Tcl` |
| **AI, NLP & Data Science** | `Python`, `Ollama (Local LLM)`, `RAG & Semantic Search`, `XGBoost`, `LSTM`, `PuLP (MILP)`, `NetworkX`, `Streamlit`, `Pytest` |
| **Backend, Desktop & Systems** | `FastAPI`, `Node.js`, `Express.js`, `Electron`, `Linux (PulseAudio / PipeWire)`, `systemd`, `Docker` |
| **Frontend** | `TypeScript`, `JavaScript`, `React`, `Angular`, `Vite`, `Monaco Editor` |
| **Databases & Cloud** | `MongoDB`, `Firebase (Firestore, Hosting, Cloud Functions)`, `MySQL` |

---

## Selected Projects

| Project | Domain | Tech Stack | Overview |
| :--- | :--- | :--- | :--- |
| **[AkyuzIDE](https://github.com/tahatahsinakyuz/AkyuzIDE-releases)** | EDA / AI Desktop IDE | `TypeScript`, `React`, `Electron`, `FastAPI`, `Ollama`, `Verilog` | Desktop IDE for RISC-V and FPGA development featuring a multi-mode AI engineering agent (`agent`/`ask`/`plan`), Icarus Verilog simulation, Vivado synthesis integration, and a RISC-V assembler. |
| **Akyuz RV32I (`akyuz-rv32i`)** | Processor Architecture & FPGA | `Verilog`, `RISC-V Assembly`, `C`, `Tcl`, `Basys3` | Custom 5-stage pipelined RV32I RISC-V processor core with data forwarding, hazard detection unit, Wishbone SoC bus (UART, SPI, GPIO, Timer), VGA controller, and bare-metal C/Assembly applications on FPGA. |
| **ASM-Explain Agent (`NLP`)** | AI / Hardware Analysis | `Python`, `FastAPI`, `Semantic Search`, `LLM`, `Pytest` | Automated analysis agent that parses RV32I assembly traces from Verilog testbenches, detects 5-stage pipeline hazards (RAW, load-use stall, branch flush), and generates cycle-accurate explanations via vector search and local LLMs (255/255 unit tests). |
| **TEKNOFEST Logistics** | Machine Learning & Optimization | `Python`, `XGBoost`, `LSTM`, `PuLP (MILP)`, `NetworkX`, `Streamlit` | E-commerce logistics optimization platform combining warehouse-level daily demand forecasting (XGBoost + LSTM) with Mixed-Integer Linear Programming (MILP) for cost-optimal vehicle assignment and routing. |
| **AkyuzMix** | Linux Systems / Desktop | `TypeScript`, `Electron`, `React`, `PulseAudio / PipeWire` | Multi-device Bluetooth audio mixer for Linux enabling simultaneous audio streaming across multiple headphones/speakers (`module-combine-sink`), real-time waveform metering, and smart stream routing. |
| **Smart Nutrition & Cafeteria (`AkilliBeslenmeTakibi`)** | Full-Stack & AI | `MongoDB`, `Express`, `React`, `Node.js`, `Python ML`, `Docker` | Containerized MERN stack reservation and nutrition tracking platform integrated with an ML data-quality pipeline and Ollama/RAG-powered menu planning engine. |

---

<details>
<summary><strong>Türkçe Versiyon / Turkish Overview (Görmek için tıklayın)</strong></summary>

<br>

### Hakkımda

Donanım mimarisinden (**Verilog, RISC-V, FPGA**) yerel Büyük Dil Modelleri (**LLM / NLP ajanları**) ve modern masaüstü/web uygulamalarına uzanan uçtan uca mühendislik çözümleri geliştiriyorum.

- **EDA ve Donanım Geliştirme Araçları:** RISC-V ve FPGA geliştiricileri için entegre yapay zeka asistanına sahip masaüstü geliştirme ortamı [AkyuzIDE](https://github.com/tahatahsinakyuz/AkyuzIDE-releases) projesini geliştiriyorum.
- **İşlemci Mimarisi ve Gömülü Sistemler:** Sıfırdan 5 aşamalı boru hattına (pipeline) sahip RV32I RISC-V işlemci çekirdeği, Wishbone SoC ve Basys3 FPGA donanım tasarımları üzerine çalışıyorum.
- **Yapay Zeka ve Veri Bilimi:** RISC-V boru hattı çakışmalarını (hazard) analiz eden NLP/LLM ajanları, talep tahmini (XGBoost, LSTM) ve yöneylem araştırması (MILP) optimizasyon modelleri geliştiriyorum.
- **Sistem ve Masaüstü Yazılımları:** Linux ses altyapısı (PulseAudio / PipeWire) için çoklu Bluetooth ses mikseri (AkyuzMix) ve ölçeklenebilir web uygulamaları inşa ediyorum.

### Öne Çıkan Projeler (Özet)

- **[AkyuzIDE](https://github.com/tahatahsinakyuz/AkyuzIDE-releases):** RISC-V ve FPGA geliştirme için AI ajan destekli (`agent`/`ask`/`plan` modlu), Icarus Verilog simülasyonlu, Vivado ve RISC-V Assembler entegreli masaüstü IDE.
- **Akyuz RV32I (`akyuz-rv32i`):** 5 aşamalı boru hattı, hazard detection, forwarding birimi, Wishbone SoC (UART, SPI, GPIO, Timer) ve VGA kontrolcüsü içeren RV32I işlemci çekirdeği.
- **ASM-Explain Agent (`NLP`):** Verilog testbench çıktılarından RV32I assembly komutlarını ayrıştıran ve 5 aşamalı pipeline çakışmalarını vektör arama + yerel LLM ile açıklayan analiz ajanı (255/255 birim testi).
- **TEKNOFEST Lojistik:** Depo bazlı günlük talep tahmini (XGBoost + LSTM) ve Karma Tamsayılı Doğrusal Programlama (MILP) ile araç atama/rotalama optimizasyonu.
- **AkyuzMix:** Linux üzerinde birden fazla Bluetooth kulaklık ve hoparlöre eşzamanlı ses yönlendiren çoklu cihaz ses mikseri.
- **Akıllı Beslenme Takibi:** Yapay zeka (Ollama/RAG) destekli menü planlama, veri kalitesi hattı ve Docker mimarisine sahip MERN stack platformu.

</details>
