<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/2920/2920329.png" />

# 📡 AERIS-10 PLFM Radar System

### Sistema Open Source de Radar Phased Array con modulación Pulse LFM 🚀

<p align="center">
  <b>AERIS-10</b> es una plataforma de radar open source diseñada para investigación, SDR avanzado y desarrollo de tecnologías de detección mediante arreglos phased array de 10.5 GHz.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/OpenSource-RADAR-blueviolet?style=for-the-badge">
  <img src="https://img.shields.io/badge/FPGA-SignalProcessing-orange?style=for-the-badge&logo=xilinx&logoColor=white">
  <img src="https://img.shields.io/badge/STM32-Embedded-blue?style=for-the-badge&logo=stmicroelectronics&logoColor=white">
  <img src="https://img.shields.io/badge/Python-GUI-3776AB?style=for-the-badge&logo=python&logoColor=white">
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/NawfalMotii79/PLFM_RADAR?style=for-the-badge">
  <img src="https://img.shields.io/github/forks/NawfalMotii79/PLFM_RADAR?style=for-the-badge">
  <img src="https://img.shields.io/github/watchers/NawfalMotii79/PLFM_RADAR?style=for-the-badge">
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-características">Características</a> •
  <a href="#-arquitectura">Arquitectura</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación">Instalación</a> •
  <a href="#-documentación">Documentación</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**AERIS-10 PLFM Radar System** es un sistema radar open source basado en tecnología phased array y modulación Pulse Linear Frequency Modulated (PLFM), diseñado para investigación avanzada, experimentación SDR y desarrollo de sistemas de detección modernos.

La plataforma permite:

- 📡 Desarrollo de radar phased array
- 🧠 Procesamiento digital de señales
- 🎯 Beam steering electrónico
- 📊 Procesamiento Doppler y FFT
- 🌍 Integración GPS/IMU
- 🖥️ Visualización en tiempo real
- ⚡ Investigación FPGA
- 🚀 Experimentación RF avanzada

---

# ✨ Características

## 📡 Sistema radar

- 📶 Modulación Pulse LFM
- 🎯 Beam Steering ±45°
- 📡 Antenas phased array
- 🌐 Escaneo mecánico 360°
- ⚡ Procesamiento en FPGA
- 📊 Detección Doppler

---

## 🧠 Procesamiento DSP

- FFT Processing
- Pulse Compression
- MTI Filtering
- CFAR Detection
- Down Conversion I/Q
- Signal Filtering

---

## ⚙️ Arquitectura modular

- 🔌 Power Management Board
- 📡 Frequency Synthesizer
- 🧠 FPGA Processing Unit
- 📶 RF Front-End
- 🛰️ GPS + IMU
- ❄️ Thermal Monitoring

---

## 🖥️ GUI y visualización

- GUI interactiva en Python
- 📍 Integración de mapas
- 📊 Visualización de targets
- 🎛️ Panel de control radar
- 📡 Monitoreo en tiempo real
- 🔄 Comunicación USB

---

# 🛰️ Variantes del sistema

## 📡 AERIS-10N (Nexus)

Versión compacta enfocada en corto alcance.

### Características

- Alcance de 3 km
- Antena 8x16 Patch Array
- Bajo consumo energético
- Diseño compacto
- Ideal para pruebas SDR

---

## 🚀 AERIS-10X (Extended)

Versión avanzada de largo alcance.

### Características

- Alcance de 20 km
- Antena 32x16 Waveguide
- Amplificadores GaN
- Mayor potencia RF
- Uso profesional y experimental

---

# 🏗️ Arquitectura del sistema

## 🔌 Power Management

Sistema encargado de alimentar y proteger todos los módulos electrónicos.

### Funciones

- Secuenciación eléctrica
- Protección energética
- Filtrado de voltajes
- Gestión térmica

---

## 📡 Frequency Synthesizer

Generación de frecuencias y sincronización del sistema radar.

### Componentes

- AD9523-1
- ADF4382
- DAC Clocking
- ADC Synchronization

---

## 🧠 FPGA Processing

Unidad central de procesamiento digital.

### Funcionalidades

- Generación de chirps
- Captura ADC
- FFT Doppler
- Pulse Compression
- MTI & CFAR
- Comunicación USB

---

## 🎛️ STM32 Controller

Microcontrolador principal del sistema.

### Funciones

- Configuración periférica
- Control beamforming
- GPS/IMU Integration
- Thermal Monitoring
- Stepper Motor Control
- RF Switching

---

# 📊 Especificaciones técnicas

| Característica | AERIS-10N | AERIS-10X |
|----------------|-----------|------------|
| Frecuencia | 10.5 GHz | 10.5 GHz |
| Alcance | 3 km | 20 km |
| Antena | 8x16 Patch Array | 32x16 Waveguide |
| Beam Steering | ±45° | ±45° |
| Escaneo | 360° | 360° |
| Potencia | ~1W×16 | 10W×16 |
| Procesamiento | FPGA + STM32 | FPGA + STM32 |

---

# 🛠️ Tecnologías utilizadas

## ⚙️ Hardware

<p>
  <img src="https://skillicons.dev/icons?i=arduino,raspberrypi" />
</p>

- FPGA Xilinx
- STM32
- RF Electronics
- ADAR1000
- LTC5552
- AD9523
- ADF4382

---

## 🧠 Software

<p>
  <img src="https://skillicons.dev/icons?i=python,c,cpp" />
</p>

- Python GUI
- Embedded C
- FPGA HDL
- DSP Algorithms
- Signal Processing

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,linux" />
</p>

- Git
- GitHub
- Vivado
- VS Code
- Linux
- SDR Toolchain

---

# 📂 Estructura del proyecto

```bash
RadarDeteccionObjetos/
│
├── 1_Documentation/                # Documentación técnica
├── 2_Theory/                       # Fundamentos radar
├── 3_Software/                     # GUI y herramientas
├── 4_Schematics and Boards Layout/ # PCB y esquemáticos
├── 5_Simulations/                  # Simulaciones
├── 6_Manufacturing/                # Producción
├── 7_Testing/                      # Validación
├── 8_Utils/                        # Recursos
├── 9_Firmware/                     # Firmware FPGA/STM32
├── docs/                           # GitHub Pages
├── LICENSE
└── README.md
```

---

# ⚡ Instalación

## 📋 Requisitos

- Python 3.8+
- Vivado FPGA Tools
- STM32 Toolchain
- Linux o Windows
- Hardware RF compatible

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isairey/RadarDeteccionObjetos.git
```

---

## 2️⃣ Entrar al proyecto

```bash
cd RadarDeteccionObjetos
```

---

## 3️⃣ Instalar dependencias

```bash
pip install -r requirements.txt
```

---

## 4️⃣ Configurar FPGA

Abrir proyecto en:

```bash
Vivado
```

Cargar firmware desde:

```bash
/9_Firmware/
```

---

## 5️⃣ Ejecutar GUI

```bash
python main.py
```

---

# 📡 Pipeline de procesamiento

## 🔄 Flujo radar

1. 📶 Generación de chirps LFM
2. 📡 Conversión RF
3. 🎯 Beam Steering
4. 🧠 Captura ADC
5. 📊 FFT Doppler
6. 🎯 CFAR Detection
7. 🖥️ Visualización GUI

---

# 📚 Documentación

## 📖 Recursos disponibles

- Arquitectura del sistema
- Hardware Bring-Up
- FPGA Reports
- DSP Documentation
- Release Notes
- Simulation Reports

---

# 📊 Funcionalidades principales

## 📡 Radar phased array

- Beam steering electrónico
- Escaneo dinámico
- Control RF avanzado
- Seguimiento de objetivos

---

## 🧠 DSP y FPGA

- Procesamiento en tiempo real
- FFT acelerada
- Pulse compression
- Filtrado digital

---

## 🛰️ Integración avanzada

- GPS Tracking
- IMU Correction
- Thermal Monitoring
- USB Communication

---

# 🧠 Objetivos del proyecto

## 🎯 Investigación y desarrollo

- Democratizar tecnología radar
- Facilitar investigación SDR
- Experimentación DSP
- Desarrollo phased array
- Aprendizaje FPGA
- Sistemas embebidos avanzados

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- ☁️ Cloud Radar Processing
- 🤖 AI Target Detection
- 📱 Mobile Monitoring
- 🌍 Tracking avanzado
- 📡 Beamforming inteligente
- ⚡ Optimización FPGA
- 🛰️ Integración satelital

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/new-feature
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/new-feature
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes — Radar Systems Engineer

Ingeniero apasionado por sistemas radar open source, DSP, FPGA y tecnologías phased array 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto  
🛰️ Contribuye al desarrollo open source

---

# 📜 Licencia

Proyecto open source bajo:

- 🛠️ CERN-OHL-P para hardware
- 💻 MIT License para software y firmware

Orientado a investigación, educación y desarrollo de tecnologías radar avanzadas.

---

<div align="center">

### 📡 AERIS-10 PLFM Radar System — tecnología radar open source para la nueva generación 🚀

</div>
