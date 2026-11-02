# Taha Tahsin Akyüz

**Bilgisayar Mühendisliği | Donanım-Yazılım Birlikte Tasarımı (RISC-V & FPGA) • Yapay Zeka Sistemleri • Full-Stack & Sistem Geliştirme**

[LinkedIn](https://www.linkedin.com/in/taha-tahsin-aky%C3%BCz-065a0b231) • [AkyuzIDE Sürümleri (Releases)](https://github.com/tahatahsinakyuz/AkyuzIDE-releases/releases)

---

## Hakkımda

Donanım mimarisinden (Verilog, RISC-V, FPGA) yerel Büyük Dil Modelleri (LLM / NLP ajanları) ve modern masaüstü/web uygulamalarına uzanan uçtan uca mühendislik çözümleri geliştiriyorum.

- **EDA ve Donanım Geliştirme Araçları:** RISC-V ve FPGA geliştiricileri için entegre yapay zeka asistanına sahip masaüstü geliştirme ortamı [AkyuzIDE](https://github.com/tahatahsinakyuz/AkyuzIDE-releases) projesini geliştiriyorum.
- **İşlemci Mimarisi ve Gömülü Sistemler:** Sıfırdan 5 aşamalı boru hattına (pipeline) sahip RV32I RISC-V işlemci çekirdeği, Wishbone SoC ve Basys3 FPGA donanım tasarımları üzerine çalışıyorum.
- **Yapay Zeka ve Veri Bilimi:** RISC-V boru hattı çakışmalarını (hazard) analiz eden NLP/LLM ajanları, talep tahmini (XGBoost, LSTM) ve yöneylem araştırması (MILP) optimizasyon modelleri geliştiriyorum.
- **Sistem ve Masaüstü Yazılımları:** Linux ses altyapısı (PulseAudio / PipeWire) için çoklu Bluetooth ses mikseri (AkyuzMix) ve ölçeklenebilir web/mobil uygulamalar inşa ediyorum.

---

## Teknik Yetkinlikler

| Alan | Teknolojiler ve Araçlar |
| :--- | :--- |
| **Donanım, Gömülü Sistemler & EDA** | `Verilog HDL`, `RISC-V (RV32I)`, `Xilinx Vivado`, `Basys3 FPGA`, `Icarus Verilog`, `Wishbone SoC`, `C`, `RISC-V Assembly`, `Tcl` |
| **Yapay Zeka, NLP & Veri Bilimi** | `Python`, `Ollama (Local LLM)`, `RAG & Semantic Search`, `XGBoost`, `LSTM`, `PuLP (MILP)`, `NetworkX`, `Streamlit` |
| **Backend, Masaüstü & Sistem** | `FastAPI`, `Node.js`, `Express.js`, `Electron`, `Linux (PulseAudio / PipeWire)`, `systemd`, `Docker` |
| **Frontend & Mobil** | `TypeScript`, `JavaScript`, `React`, `Angular`, `Vite`, `Kotlin (Android)` |
| **Veritabanı & Bulut** | `MongoDB`, `Firebase (Firestore, Hosting, Cloud Functions)`, `MySQL` |

---

## Öne Çıkan Projeler

| Proje | Alan | Teknolojiler | Açıklama |
| :--- | :--- | :--- | :--- |
| **[AkyuzIDE](https://github.com/tahatahsinakyuz/AkyuzIDE-releases)** | EDA / AI IDE | `TypeScript`, `React`, `Electron`, `FastAPI`, `Ollama`, `Verilog` | RISC-V ve FPGA geliştirme için AI ajan destekli (`agent`/`ask`/`plan` modlu), Icarus Verilog simülasyonlu, Vivado ve RISC-V Assembler entegreli masaüstü IDE. |
| **Akyuz RV32I (`akyuz-rv32i`)** | İşlemci Mimarisi & FPGA | `Verilog`, `RISC-V Assembly`, `C`, `Tcl`, `Basys3` | 5 aşamalı boru hattı (pipeline), hazard detection, forwarding birimi, Wishbone SoC (UART, SPI, GPIO, Timer), VGA kontrolcüsü ve donanım üzerinde çalışan uygulamalar içeren RV32I işlemci çekirdeği. |
| **ASM-Explain Agent (`NLP`)** | AI / Donanım Analizi | `Python`, `FastAPI`, `Semantic Search`, `LLM`, `Pytest` | Verilog testbench çıktılarından RV32I assembly komutlarını ayrıştıran, 5 aşamalı pipeline çakışmalarını tespit edip vektör arama ve yerel LLM ile teknik açıklamalar üreten analiz ajanı (255/255 birim testi). |
| **TEKNOFEST Lojistik** | Veri Bilimi & Optimizasyon | `Python`, `XGBoost`, `LSTM`, `PuLP (MILP)`, `NetworkX`, `Streamlit` | E-ticaret lojistiğinde depo bazlı günlük talep tahmini ve Karma Tamsayılı Doğrusal Programlama (MILP) ile minimum maliyetli araç atama ve rotalama optimizasyonu. |
| **AkyuzMix** | Linux Sistem / Masaüstü | `TypeScript`, `Electron`, `React`, `PulseAudio / PipeWire` | Linux üzerinde birden fazla Bluetooth kulaklık ve hoparlöre eşzamanlı ses yönlendiren, gerçek zamanlı dalga formu (waveform) ve cihaz bazlı seviye kontrolü sunan ses mikseri. |
| **Akıllı Beslenme Takibi** | Full-Stack & AI | `MongoDB`, `Express`, `React`, `Node.js`, `Python ML`, `Docker` | Yapay zeka (Ollama/RAG) destekli menü planlama, veri kalitesi hattı (pipeline) ve konteyner mimarisine sahip akıllı beslenme ve yemekhane rezervasyon platformu. |
| **Salvage Dive (`denizaltimobil`)** | Mobil Uygulama / Oyun | `Kotlin`, `Android`, `Custom Game Engine` | Sabit zaman adımlı (fixed-timestep) oyun motoru, derinlik/oksijen yönetimi, dinamik ganimet üretimi ve tersane ekonomisine sahip Android oyunu. |
