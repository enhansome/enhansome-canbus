# Awesome CAN Bus with stars

[![GitHub stars](https://badgen.net/github/stars/iDoka/awesome-canbus)](https://GitHub.com/iDoka/awesome-canbus/stargazers/) ⭐ 3,429 | 🐛 6 | 📅 2026-08-07
[![GitHub forks](https://badgen.net/github/forks/iDoka/awesome-canbus)](https://GitHub.com/iDoka/awesome-canbus/network/) ⭐ 3,429 | 🐛 6 | 📅 2026-08-07
[![GitHub watchers](https://badgen.net/github/watchers/iDoka/awesome-canbus/)](https://GitHub.com/iDoka/awesome-canbus/watchers/) ⭐ 3,429 | 🐛 6 | 📅 2026-08-07
[![GitHub contributors](https://badgen.net/github/contributors/iDoka/awesome-canbus)](https://GitHub.com/iDoka/awesome-canbus/graphs/contributors/) ⭐ 3,429 | 🐛 6 | 📅 2026-08-07
[![GitHub pull-requests merged](https://badgen.net/github/merged-prs/iDoka/awesome-canbus)](https://github.com/iDoka/awesome-canbus/pulls?q=is%3Amerged) ⭐ 3,429 | 🐛 6 | 📅 2026-08-07
[![GitHub latest commit](https://badgen.net/github/last-commit/iDoka/awesome-canbus)](https://GitHub.com/iDoka/awesome-canbus/commit/) ⭐ 3,429 | 🐛 6 | 📅 2026-08-07

<p align="center"><img src="https://github.com/iDoka/awesome-canbus/raw/main/media/can_logo.png" alt="CAN logo"/></p>

<!--<p align="center">
<img src="https://github.com/iDoka/awesome-canbus/raw/main/media/can_logo.png" alt="CAN logo"/>
</p>-->

<!-- # :tractor: Awesome Tools, Hardware and Resources for CAN Bus 
[![GitHub latest commit](https://badgen.net/github/last-commit/iDoka/awesome-canbus)](https://GitHub.com/iDoka/awesome-canbus/commit/)
[![GitHub forks](https://badgen.net/github/forks/iDoka/awesome-canbus)](https://GitHub.com/iDoka/awesome-canbus/network/)
[![GitHub stars](https://badgen.net/github/stars/iDoka/awesome-canbus)](https://GitHub.com/iDoka/awesome-canbus/stargazers/)
[![GitHub watchers](https://badgen.net/github/watchers/iDoka/awesome-canbus/)](https://GitHub.com/iDoka/awesome-canbus/watchers/)
[![GitHub contributors](https://img.shields.io/github/contributors/iDoka/badges.svg)](https://GitHub.com/iDoka/badges/graphs/contributors/)
[![GitHub contributors](https://badgen.net/github/contributors/iDoka/awesome-canbus)](https://GitHub.com/iDoka/awesome-canbus/graphs/contributors/)
[![PR welcome issues still open](https://badgen.net/https/pr-welcome-badge.vercel.app/api/badge/fastify/help)](https://github.com/iDoka/awesome-canbus/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/iDoka/awesome-canbus.svg)](https://GitHub.com/iDoka/awesome-canbus/pull/)
[![GitHub pull-requests merged](https://badgen.net/github/merged-prs/iDoka/awesome-canbus)](https://github.com/iDoka/awesome-canbus/pulls?q=is%3Amerged)
[![GitHub latest commit](https://badgen.net/github/last-commit/iDoka/awesome-canbus)](https://GitHub.com/iDoka/awesome-canbus/commit/)
-->

> :tractor: Awesome Tools, Hardware And Resources For CAN Bus

This curated list helps a reverse engineering CAN bus devices with lightly specializing in automotive embedded controller software and communication understanding.

> **Note**
> Items marked as "🔝" are highly recommended.

<!--lint disable double-link-->

Permanent URL to this list: <https://github.com/iDoka/awesome-canbus> ⭐ 3,429 | 🐛 6 | 📅 2026-08-07

<!--lint enable double-link-->

## Contents

* [Hacking and Reverse Engineering tools](#hacking-and-reverse-engineering-tools)
* [Test equipment and simulators](#test-equipment-and-simulators)
* [Protocols](#protocols)
  * [OBD-II tools](#obd-ii-tools)
  * [UDS](#uds)
  * [ISO-TP](#iso-tp)
  * [J1939 Tools](#j1939-tools)
  * [J2534 Tools](#j2534-tools)
* [Utils](#utils)
  * [Common](#common)
  * [Linux related](#linux-related)
  * [GUI Tools](#gui-tools)
  * [TUI Tools](#tui-tools)
  * [Python Tools](#python-tools)
  * [CAN-over-IP](#can-over-ip)
  * [Other Utils](#other-utils)
  * [Libraries](#libraries)
  * [Examples](#examples)
* [CAN Database](#can-database)
  * [Formats (DBC, KCD)](#formats-dbc-kcd)
  * [Converters and Parsers](#converters-and-parsers)
  * [DBC only](#dbc-only)
* [Hardware](#hardware)
  * [ARM](#arm)
  * [Arduino](#arduino)
  * [Espressif Systems (ESP8266, ESP32)](#espressif-systems-esp8266-esp32)
  * [SBC](#sbc)
  * [IP cores for ASIC and FPGA](#ip-cores-for-asic-and-fpga)
  * [Others HW](#others-hw)
  * [Hardware related tools](#hardware-related-tools)

## Hacking and Reverse Engineering tools

* 🔝[CarHackingTools](https://github.com/jgamblin/CarHackingTools) ⚠️ Archived - Collection of Common Car Hacking Tools a scripts collection to help jump start car research and hacking.
* 🔝[Caring Caribou](https://github.com/CaringCaribou/caringcaribou) ⭐ 943 | 🐛 14 | 🌐 Python | 📅 2026-06-12 - A friendly car security exploration tool for the CAN bus.
* 🔝[CANalyzat0r](https://github.com/schutzwerk/CANalyzat0r) ⭐ 794 | 🐛 3 | 🌐 Python | 📅 2022-02-21 - Security analysis toolkit for proprietary car protocols.
* 🔝[CAN\_Reverse\_Engineering](https://github.com/brent-stone/CAN_Reverse_Engineering) ⭐ 451 | 🐛 5 | 🌐 Python | 📅 2024-04-27 - Automated Payload Reverse Engineering Pipeline for the Controller Area Network (CAN) protocol.
* 🔝[CANToolz](https://github.com/CANToolz/CANToolz) ⭐ 305 | 🐛 21 | 🌐 Python | 📅 2023-05-07 - Black-box CAN network analysis framework.
* 🔝[carhacking](https://github.com/daedalus/carhacking) ⭐ 119 | 🐛 0 | 🌐 Python | 📅 2024-01-12 - Car hacking scripts and docs collection.
* [parse\_can\_logs](https://github.com/v-ivanyshyn/parse_can_logs) ⭐ 97 | 🐛 3 | 🌐 Python | 📅 2024-06-28 - Parse CAN logs and visualize data streams on plot.
* [reversegear](https://github.com/linklayer/reversegear) ⭐ 54 | 🐛 1 | 🌐 Python | 📅 2023-09-08 - Offline Reverse Engineering Tools for Automotive Networks.
* [ReCAN](https://github.com/Cyberdefence-Lab-Murcia/ReCAN) ⭐ 51 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2020-05-03 - Reverse engineering of Controller Area Networks.

<!--lint disable double-link-->

* [GVRET](https://github.com/collin80/GVRET) ⭐ 112 | 🐛 10 | 🌐 C++ | 📅 2018-10-16 - Generalized Electric Vehicle Reverse Engineering Tool (Arduino FW).

<!--lint enable double-link-->

* [Scapy](https://github.com/secdev/scapy) ⭐ 12,487 | 🐛 134 | 🌐 Python | 📅 2026-08-18 - Python-based interactive packet manipulation program & library. Supports CAN/ISOTP/UDS/GMLAN plus many other protocols.
* [canDrive](https://github.com/adamtheone/canDrive) ⭐ 679 | 🐛 25 | 🌐 C | 📅 2023-05-27 - Tools for hacking your car.
* [canhack](https://github.com/kentindell/canhack) ⭐ 393 | 🐛 9 | 🌐 C | 📅 2024-04-01 - A low-level CAN protocol hacking library.
* [uds-server](https://github.com/zombieCraig/uds-server) ⭐ 357 | 🐛 5 | 🌐 C | 📅 2025-10-08 - CAN UDS Simulator and Fuzzer.
* [UDSim](https://github.com/zombieCraig/UDSim) ⭐ 333 | 🐛 4 | 🌐 C++ | 📅 2022-12-10 - Unified Diagnostic Services Simulator and Fuzzer (successor of uds-server).
* [Carpunk](https://github.com/souravbaghz/Carpunk) ⭐ 329 | 🐛 0 | 🌐 Shell | 📅 2025-04-20 - CAN injection toolkit and successor of CANghost.
* 🔝[can-explorer](https://github.com/Tbruno25/can-explorer) ⭐ 302 | 🐛 1 | 🌐 Python | 📅 2026-04-23 - A CAN bus visualization tool to aid in reverse engineering.
* [canTot](https://github.com/shipcod3/canTot) ⭐ 150 | 🐛 2 | 🌐 Python | 📅 2024-10-15 - Quick and dirty canbus h4xing framework.
* [CANghost](https://github.com/souravbaghz/CANghost) ⭐ 140 | 🐛 0 | 🌐 Shell | 📅 2021-09-10 - Automated Script For Hacking Into CAN Bus.
* [CANalyse](https://github.com/KartheekLade/CANalyse) ⭐ 120 | 🐛 1 | 🌐 Python | 📅 2021-07-25 - A vehicle network analysis and attack tool.
* [CAN-RE-Tool](https://github.com/openvehicles/CAN-RE-Tool) ⭐ 90 | 🐛 0 | 🌐 Perl | 📅 2021-03-30 - Reverse engineering tool for systems based on CAN bus communications.
* [CANanalyze](https://github.com/renault/cananalyze) ⭐ 88 | 🐛 3 | 🌐 Python | 📅 2024-11-13 - This framework can be used to interact with automotive protocols like CAN/ISOTP/UDS.

## Test equipment and simulators

* [ELM327-emulator](https://github.com/Ircama/ELM327-emulator) ⭐ 669 | 🐛 17 | 🌐 Python | 📅 2026-02-22 - ELM327 Emulator for testing software interfacing OBDII via ELM327 adapter supporting multi-ECU simulation.
* [ECU-simulator](https://github.com/lbenthins/ecu-simulator) ⚠️ Archived - Tool that simulates some vehicle diagnostic services. It can be used to test OBD-II dongles or tester tools that support the UDS (ISO 14229) and ISO-TP (ISO 15765-2) protocols.
* [canerrsim](https://github.com/zeljkoavramovic/canerrsim) ⭐ 7 | 🐛 1 | 🌐 C | 📅 2026-02-02 - CAN bus error frame simulator and monitor for testing error conditions using SocketCAN.

## Protocols

### OBD-II tools

* [DDT4All](https://github.com/cedricp/ddt4all) ⭐ 1,819 | 🐛 1 | 🌐 Python | 📅 2026-07-14 - Tool to create your own ECU parameters screens and connect to a CAN network with a cheap ELM327 interface.
* [pyvit](https://github.com/linklayer/pyvit) ⚠️ Archived - Python Vehicle Interface Toolkit *(archived)*.
* [freediag](https://github.com/fenugrec/freediag) ⭐ 485 | 🐛 14 | 🌐 C | 📅 2024-09-09 - Free diagnostic software for OBD-II compliant motor vehicles.
* [OBDium](https://github.com/provrb/obdium) ⭐ 336 | 🐛 5 | 🌐 Rust | 📅 2026-07-21 - Vehicle diagnostics app for live OBD-II data, fault code analysis, and offline VIN decoding over ELM327 adapters.
* [OBD2-Scantool](https://github.com/AustinMurphy/OBD2-Scantool) ⭐ 246 | 🐛 2 | 🌐 Python | 📅 2023-03-17 - A python scantool to read OBD2 info from cars.
* [ELM327SLCAN](https://github.com/qnx425/ELM327SLCAN) ⭐ 74 | 🐛 0 | 🌐 C | 📅 2019-01-26 - ELM327 based vehicle's CAN bus sniffer.
* [Arduino-OBD2-Async](https://github.com/v-ivanyshyn/Arduino-OBD2-Async) ⭐ 22 | 🐛 0 | 🌐 C++ | 📅 2018-08-09 - Arduino OBD library with asynchronous data requesting.
* [CAN-Shark](https://github.com/quantyle/CAN-Shark) ⭐ 19 | 🐛 0 | 🌐 C++ | 📅 2023-12-17 - Working with OBD PIDs from Arduino + MCP2515 shield.
* [O2OO](https://www.vanheusden.com/O2OO/) - OBD-II compliant car diagnostic tool. It reads sensor data from a car into an SQLite database.

### UDS

*ISO 14229 Standard*

* [uds-c](https://github.com/openxc/uds-c) ⭐ 823 | 🐛 6 | 🌐 C | 📅 2021-08-16 - Unified Diagnostics Service (UDS) and OBD-II C Library.
* [python-UDSonCAN](https://github.com/pylessard/python-udsoncan) ⭐ 725 | 🐛 9 | 🌐 Python | 📅 2026-08-09 - Python implementation of UDS ISO-14229 standard.
* [iso14229](https://github.com/driftregion/iso14229) ⭐ 355 | 🐛 7 | 🌐 C | 📅 2026-08-20 - C implementation of UDS ISO-14229 server and client for embedded systems.

### ISO-TP

*ISO 15765-2 Standard*

* [isotp-c](https://github.com/openxc/isotp-c) ⭐ 356 | 🐛 8 | 🌐 C | 📅 2021-08-16 - An implementation of the ISO-TP (ISO15765-2) CAN protocol in C.
* [python-can-IsoTP](https://github.com/pylessard/python-can-isotp) ⭐ 314 | 🐛 4 | 🌐 Python | 📅 2026-06-26 - Python implementation of the ISO-TP (ISO15765-2) CAN protocol.
* [CanTp](https://github.com/Sauci/CanTp) ⭐ 69 | 🐛 2 | 🌐 C | 📅 2026-04-13 - Implementation of the CanTp module (ISO 15765-2), according to AUTOSAR specification v4.4.0.
* [aioisotp](https://github.com/christiansandberg/aioisotp) ⚠️ Archived - ISO-TP implemenation for asyncio Python.

### J1939 Tools

*SAE J1939 Standard*

* [Open-SAE-J1939](https://github.com/DanielMartensson/Open-SAE-J1939) ⭐ 642 | 🐛 0 | 🌐 C | 📅 2026-06-25 - SAE J1939 protocol free to use for embedded systems or PC with CAN-bus.
* [J1939-Framework](https://github.com/famez/J1939-Framework) ⭐ 173 | 🐛 9 | 🌐 C++ | 📅 2024-02-18 - Framework to work with J1939 Frames used in CAN bus in bus, car and trucks industries.
* [python-can-j1939](https://github.com/juergenH87/python-can-j1939) ⭐ 142 | 🐛 49 | 🌐 Python | 📅 2026-02-04 - Package provides SAE J1939 support for Python developers.
* [Pretty-J1939](https://github.com/nmfta-repo/pretty_j1939) ⭐ 81 | 🐛 11 | 🌐 Python | 📅 2026-04-15 - Python libs and scripts for pretty-printing J1939 logs.
* [TruckDevil](https://github.com/LittleBlondeDevil/TruckDevil) ⭐ 62 | 🐛 5 | 🌐 Python | 📅 2026-04-04 - A tool and framework for interacting with and assessing ECUs that use J1939 for communications on the CANBUS.
* [test-can-j1939](https://github.com/kurt-vd/test-can-j1939) ⭐ 43 | 🐛 1 | 🌐 C | 📅 2018-01-17 - How to use CAN J1939 on linux.
* [python-j1939](https://github.com/milhead2/python-j1939) ⭐ 39 | 🐛 10 | 🌐 Python | 📅 2023-09-15 - SAE J1939 support dependent on python-can package. Provides codec and filtering by PGN but not full SPN decoding.
* [libj1939](https://github.com/paoloteti/libj1939) ⭐ 32 | 🐛 2 | 🌐 C | 📅 2021-01-28 - Library to work with J1939 Frames (intended to be used in microcontrollers).
* [J1939-CANBUS](https://github.com/taha842/J1939-CANBUS) ⭐ 15 | 🐛 0 | 🌐 C++ | 📅 2020-03-31 - Supported Engines CAT, Perkins, Wartsalla, MTU, VOLVO.
* [can-utils with J1939 support](https://github.com/kurt-vd/can-utils/tree/j1939-v6) ⭐ 10 | 🐛 0 | 🌐 C | 📅 2021-06-24 - Fork of can-utils with a few additional tools for J1939.
* [embr::j1939](https://github.com/malachi-iot/j1939) ⭐ 9 | 🐛 3 | 🌐 C++ | 📅 2024-07-22 - Lean, portable J1939 library for embedded MCUs.

### J2534 Tools

*SAE J2534 Standard*

<!--lint disable no-repeat-punctuation-->

<!-- * [~~JCanalog~~](https://github.com/ZacharyWalsh57/JCanalog) - ~~Easy To Use J2534 Vehicle Logger~~ _(left for history)_. -->

<!--lint enable no-repeat-punctuation-->

* [SharpWrap2534](https://github.com/MEAT-Inc/SharpWrap2534) ⭐ 33 | 🐛 6 | 🌐 C# | 📅 2024-07-07 - The Ultimate J2534 Wrapper Suite.
* [gocanflasher](https://github.com/roffe/gocanflasher) ⭐ 27 | 🐛 0 | 🌐 Go | 📅 2025-11-18 - Trionic 5/7/8 CANbus flasher with J2534 support.
* [j2534-tcp](https://github.com/brandonros/j2534-tcp) - Virtual J2534 driver over TCP/IP.

## Utils

### Common

* [BUSMASTER](https://github.com/rbei-etas/busmaster) ⭐ 1,072 | 🐛 670 | 🌐 C++ | 📅 2023-07-11 - An Open Source Software tool to simulate, analyze and test data bus systems such as CAN.
* [CANiBUS](https://github.com/Hive13/CANiBUS/) ⚠️ Archived - CAN Device Vehicle Research Server (OpenGarages.org).
* [CANopenTerm](https://github.com/CANopenTerm/CANopenTerm) ⭐ 76 | 🐛 5 | 🌐 C | 📅 2026-08-06 - Tool for developing, testing and analyzing CANopen CC & CAN CC networks and devices.
* [signalbroker-server](https://github.com/AleksandarFilipov/signalbroker-server) ⭐ 33 | 🐛 1 | 🌐 Elixir | 📅 2020-09-03 - Tool to read and write CAN/LIN/flexray and other buses using gRPC which allows usage of preferred language.
* 🔝[cantools](https://github.com/mwkpe/cantools) ⭐ 24 | 🐛 0 | 🌐 C++ | 📅 2021-11-23 - Collection of CLI tools for the CAN bus network.

### Linux related

* 🔝[Linux CAN Utils](https://github.com/linux-can/can-utils) ⭐ 2,907 | 🐛 62 | 🌐 C | 📅 2026-05-12 - Linux-CAN / SocketCAN user space useful utils.
* [J1939](https://docs.kernel.org/networking/j1939.html) - Linux kernel support (kernel >= 5.4) also see [can-j1939 kernel module](https://github.com/linux-can/can-utils/blob/master/can-j1939-install-kernel-module.md) ⭐ 2,907 | 🐛 62 | 🌐 C | 📅 2026-05-12.
* [can-isotp](https://github.com/hartkopp/can-isotp) ⭐ 288 | 🐛 4 | 🌐 C | 📅 2023-10-24 - Linux Kernel Module for ISO 15765-2:2016 CAN transport protocol (part of the Linux kernel >= 5.10).
* [elmcan](https://github.com/norly/elmcan) ⭐ 92 | 🐛 0 | 🌐 C | 📅 2024-05-05 - Linux SocketCAN kernel driver for ELM327 based devices (kernel >= 6.0).
* [gs\_usb](https://github.com/ryedwards/gs_usb) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2023-01-25 - Linux/Windows CAN driver based on WCID for Geschwister Schneider USB/CAN devices and candleLight USB CAN interfaces.
* [CAN support in Linux](https://elinux.org/CAN_Bus#CAN_Support_in_Linux) - Linux kernel support for CAN hardware interfaces.
* [SocketCAN](https://docs.kernel.org/networking/can.html) - Linux kernel support (kernel >= 2.6).

### GUI Tools

* [PlotJuggler](https://github.com/facontidavide/PlotJuggler) ⭐ 6,124 | 🐛 159 | 🌐 C++ | 📅 2026-08-10 - The Powerful Time Series Visualization Tool (With panda hardware, cabana and plotjuggler, you can quickly RE the entire car in a few days).
* [SavvyCAN](https://github.com/collin80/SavvyCAN) ⭐ 1,778 | 🐛 283 | 🌐 C++ | 📅 2026-05-15 - Cross-platform Qt based GUI analysis tool. Supports SocketCAN compatible interfaces.
* [CANdevStudio from GENIVI](https://github.com/GENIVI/CANdevStudio) ⭐ 1,140 | 🐛 37 | 🌐 C++ | 📅 2025-07-21 - CAN simulation software using a drag-and-drop style GUI with interconnected functional blocks.
* [ICSim](https://github.com/zombieCraig/ICSim) ⭐ 973 | 🐛 21 | 🌐 C | 📅 2025-09-18 - Instrument Cluster Simulator for SocketCAN by OpenGarages.
* [EcuBus-Pro](https://github.com/ecubus/EcuBus-Pro) ⭐ 843 | 🐛 56 | 🌐 C++ | 📅 2026-08-18 - A powerful automotive ECU development tool. UDS, CAN-TP, DOIP, LIN , Script(TS) like CAPL.
* [TSMaster](https://github.com/TOSUN-Shanghai/TSMaster) ⭐ 424 | 🐛 85 | 📅 2026-07-07 - Powerful open environment for automotive bus monitoring, simulation, testing, diagnostics, calibration and so on *(Closed source)*.
* [CANgaroo](https://github.com/HubertD/cangaroo) ⭐ 420 | 🐛 22 | 🌐 C++ | 📅 2023-10-27 - Qt-based CAN bus analyzer software.
* [Kayak](https://github.com/dschanoeh/Kayak) ⚠️ Archived - Java-based CAN traffic GUI analysis tool *(archived)*.
* [CANviz](https://github.com/Chanchaldhiman/CANviz) ⭐ 279 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-08 - Browser-based CAN bus analyzer with J1939 and CANopen CiA 301/402 passive decode. Installs via pip, no native app required. Works with almost any CAN harware including low cost ones.
* [CANBUS-Analyzer](https://github.com/amund7/CANBUS-Analyzer) ⭐ 257 | 🐛 11 | 🌐 C# | 📅 2024-07-05 - Development tool/companion software for graphs, displays and analyzes both known and unknown CANBUS packets.
* [CANtact-app](https://github.com/linklayer/cantact-app) ⭐ 230 | 🐛 18 | 🌐 Java | 📅 2020-04-13 - Desktop application for CANtact hardware interface.
* [Seeed-USB-CAN-Analyzer](https://github.com/SeeedDocument/USB-CAN-Analyzer/) ⭐ 128 | 🐛 9 | 📅 2024-06-03 - Closed source binary for noname Chinese USB-CAN adapter.
* [CAN++](https://github.com/TDahlmann/canpp) ⭐ 93 | 🐛 1 | 🌐 C | 📅 2026-04-28 - Windows program for receiving and transmitting CAN bus messages. After import of CAN data base files (`*.dbc` or `*.kcd`) CAN signals are shown in symbolic form. In addition they can be shown as graphics (wave forms).
* [CAN-Monitor-qt](https://github.com/tixiv/CAN-Monitor-qt) ⭐ 85 | 🐛 2 | 🌐 C++ | 📅 2019-07-20 - Universal CAN bus monitoring program.
* [CANcool](https://github.com/MHS-Elektronik/CANcool) ⭐ 73 | 🐛 0 | 🌐 Pascal | 📅 2025-05-11 - CAN bus Analyser and Simulation Software with CAN-FD support.
* [CANLogger](https://github.com/olegel/CANLogger) ⭐ 69 | 🐛 1 | 🌐 C# | 📅 2019-05-28 - CAN bus logger and analyzer tool.
* [PlotJuggler::CAN-dbs](https://github.com/PlotJuggler/plotjuggler-CAN-dbs) ⭐ 61 | 🐛 1 | 🌐 C++ | 📅 2026-03-25 - Plugin to visualize CAN .dbs (or .dbc?) files in PlotJuggler.
* [wxCAN-Sniffer](https://github.com/KruFFT/wxCAN-Sniffer) ⭐ 46 | 🐛 4 | 🌐 C++ | 📅 2025-05-20 - CAN bus sniffer (PC side) with animation and chart.
* [Plotter and Scanner from SmartGauges](https://github.com/smartgauges/obd2-bt-stm32/tree/master/qt) ⭐ 42 | 🐛 3 | 🌐 C | 📅 2024-04-28 - Scanning and visualizing tool for automotive systems.
* [CAN-X](https://github.com/karlyamashita/CAN-X) ⭐ 37 | 🐛 2 | 🌐 C# | 📅 2025-11-15 - C# CAN bus analyzer software.
* [openCanSuite](https://github.com/sebi2k1/openCanSuite) ⭐ 32 | 🐛 1 | 🌐 C++ | 📅 2017-04-05 - Set of tools for analyzing, simulating and visualizing a CAN system.
* [CANAL-View](https://github.com/rusoku/CANAL-View) ⭐ 23 | 🐛 0 | 🌐 C++ | 📅 2023-06-05 - Qt GUI for TouCAN USB to CAN bus converter.
* [OpenSourceLogger](https://github.com/DanielMartensson/OpenSourceLogger) ⭐ 23 | 🐛 0 | 🌐 C | 📅 2023-06-19 - Data acquisition software that can collect measurement, analyze CAN-messages and send SAE-J1939 messages to other ECUs.
* [SLSS-CANAnalyser](https://github.com/SeppHansen/SLSS-CANAnalyser) ⭐ 17 | 🐛 0 | 🌐 C++ | 📅 2023-02-11 - SLSS CANAnalyser is Windows CAN-Bus-Analysis-Software to show, record and evaluate CAN-Bus signals.
* [Novo Bus Analyzer](https://github.com/reymor/novobusanalyzer) ⭐ 17 | 🐛 8 | 🌐 C++ | 📅 2025-03-21 - Fork of BUSMASTER (BUSMASTER is an Open Source Software tool to simulate, analyze and test data bus systems such as CAN).
* [bootCAN](https://github.com/friessssss/bootCAN) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2026-07-27 - Allows monitoring, tracing, and plotting of messages, as well as .SYM decoding and message transmitting.

### TUI Tools

* [canair](https://github.com/philipkocanda/canair) ⭐ 21 | 🐛 2 | 🌐 Python | 📅 2026-08-19 - CLI/TUI for reverse engineering CAN/UDS diagnostics over-the-air using a WiCAN or a generic ELM327 dongle.
* [socanui](https://github.com/miwagner/socanui) ⭐ 14 | 🐛 0 | 🌐 Go | 📅 2025-03-10 - SocketCAN User Interface for the Terminal.
* [canscope](https://github.com/OlegShishlyannikov/canscope.git) ⭐ 6 | 🐛 0 | 🌐 C++ | 📅 2026-06-25 - CAN bus inspection and reverse-engineering tool.

### Python Tools

* 🔝[cantools](https://github.com/cantools/cantools) ⭐ 2,272 | 🐛 128 | 🌐 Python | 📅 2026-08-21 - CAN BUS tools in Python.

<!--lint disable double-link-->

* 🔝[python-can](https://github.com/hardbyte/python-can) ⭐ 1,585 | 🐛 271 | 🌐 Python | 📅 2026-07-01 - CAN package provides controller area network support for Python developers.

<!--lint enable double-link-->

* [strym](https://github.com/jmscslgroup/strym) ⭐ 38 | 🐛 8 | 🌐 Python | 📅 2026-07-07 - Real time CAN data logging and visualization tool to work with USB-CAN Interface.
* [canviewer](https://github.com/tsabelmann/canviewer) ⭐ 11 | 🐛 1 | 🌐 C++ | 📅 2021-08-25 - GUI program that allows the inspection of incoming can-bus messages, either from recorder can-bus data or live data.

<!--lint disable double-link-->

* [can4python](https://github.com/caran/can4python) ⭐ 43 | 🐛 7 | 🌐 Python | 📅 2022-12-26 - A package for handling CAN bus signals on Linux SocketCAN.

<!--lint enable double-link-->

* [CanoPy](https://github.com/tbruno25/canopy) ⭐ 302 | 🐛 1 | 🌐 Python | 📅 2026-04-23 - A python gui used to visualize and plot message payloads in real time.
* [CanCat](https://github.com/atlas0fd00m/CanCat) ⭐ 217 | 🐛 7 | 🌐 Python | 📅 2023-04-07 - Swiss army knife of CAN often used in cars and building automation, etc.
* [Python-Vector-CANoe](https://github.com/hmq2018/Python-Vector-CANoe) ⭐ 116 | 🐛 5 | 🌐 Python | 📅 2023-03-03 -  Control Vector CANoe API by Python.
* [Robotell-USB-CAN-Python](https://github.com/nopnop2002/Robotell-USB-CAN-Python) ⭐ 30 | 🐛 2 | 🌐 Python | 📅 2026-04-25 - Python program for Robotell USB-CAN Adapter.
* [python-socketcan-monitor](https://github.com/P1kachu/python-socketcan-monitor) ⭐ 30 | 🐛 0 | 🌐 Python | 📅 2019-08-29 - Script to display data from a CAN bus over network interfaces.
* [Pyfuzz\_can](https://github.com/bhass1/pyfuzz_can) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2018-01-16 - May be used in research to inject messages into a truck and cause acceleration, cluster spoofing, and degrade brake performance.
* [py4can](https://github.com/SikkandarSulaiman/py4can) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2019-07-22 - Python utility to send and receive CAN messages through CANalyzer.
* [PythonVectorXL](https://github.com/Prindl/PythonVectorXL) - Complete python ctypes wrapper lib for the Vector XL Driver Library. Contains the #define instructions, struct/union typdef instructions and function definitions (loads the DLL as well) of the 'vxlapi.h' *(Windows only)*. Inspired by `python-can`.

### CAN-over-IP

* [cannelloni](https://github.com/mguentner/cannelloni) ⭐ 470 | 🐛 8 | 🌐 C++ | 📅 2026-08-21 - SocketCAN over Ethernet tunnel.
* [canny](https://github.com/m10k/canny) ⭐ 35 | 🐛 3 | 🌐 C | 📅 2023-04-08 - Simple CAN-over-IP gateway.
* [tincan](https://github.com/mwkpe/tincan) ⭐ 18 | 🐛 0 | 🌐 C++ | 📅 2025-06-18 - Visualization of CAN bus traffic via UDP interface.
* [pican](https://github.com/ovravna/pican) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2017-06-05 - TCP CAN reader.

### Other Utils

* [c0f](https://github.com/zombieCraig/c0f/) ⭐ 95 | 🐛 1 | 🌐 Ruby | 📅 2015-09-29 - CAN bus fingerprinting tool is designed to analyze CAN bus traffic and fingerprint the Maker and Model.
* [Seeed-USB-CAN-Linux](https://github.com/alexmohr/usb-can) ⭐ 44 | 🐛 2 | 🌐 C | 📅 2026-07-01 - CLI Linux Support for noname Chinese USB-CAN adapter.
* [Candle.NET](https://github.com/elliotwoods/Candle.NET) ⭐ 34 | 🐛 2 | 🌐 C | 📅 2024-08-06 - .NET wrapper for the Candle API for candlelight CAN bus gateways/analysers (e.g. CANable, CANtact, etc).
* [canqv](https://github.com/kurt-vd/canqv) ⭐ 10 | 🐛 0 | 🌐 C | 📅 2020-07-16 - Quick CAN frame inspection using CAN\_RAW.
* [canSerializer](https://github.com/zainahm3d/canSerializer) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2022-08-11 - Lib for serializing and deserializing CAN frames for transmission over a non CAN transport layer (Can be used to transport CAN frames over UART, SPI, etc).
* [opendlv-device-can-replay](https://github.com/chalmers-revere/opendlv-device-can-replay) ⚠️ Archived - OpenDLV Microservice to replay captured CAN frames to a CAN interface.

### Libraries

* [iso15765-canbus](https://github.com/devcoons/iso15765-canbus) ⭐ 194 | 🐛 0 | 🌐 C | 📅 2026-06-22 -  Implementation of ISO15765-2 in C.
* [JavaCAN](https://github.com/pschichtel/JavaCAN) ⭐ 67 | 🐛 6 | 🌐 Java | 📅 2026-08-19 - A Java binding library for SocketCAN with support for RAW, BCM and ISO-TP sockets using epoll-based event-driven IO.
* [CanKit](https://github.com/pkuyo/CanKit) ⭐ 39 | 🐛 7 | 🌐 C# | 📅 2026-08-06 - Cross-platform C#/.NET CAN communication library with a unified API across multiple CAN adapters.
* [go-socketcan](https://github.com/linklayer/go-socketcan) ⭐ 31 | 🐛 2 | 🌐 Go | 📅 2019-04-03 - Golang library for SocketCAN.
* [libwecan](https://github.com/nisennenmondai/libwecan) ⭐ 22 | 🐛 0 | 🌐 C | 📅 2023-02-11 - Header only lib to encode and decode CAN signal.
* [VCAN](https://github.com/TheMatjaz/VCAN) ⭐ 19 | 🐛 0 | 🌐 C | 📅 2020-04-28 - A tiny virtual CAN and CAN-FD bus library in C.
* [CANvenient](https://github.com/CANopenTerm/CANvenient) ⭐ 11 | 🐛 0 | 🌐 C | 📅 2026-07-03 - An abstraction layer for multiple CAN APIs on Windows and Linux.
* [IMCTFD](https://github.com/tonton81/IMCTFD) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2018-11-26 - Improved Microchip CAN Teensy FlexData Library MCP2517FD.
* [Qt CAN Bus](https://doc.qt.io/qt-5/qtcanbus-backends.html) - A multiplatform C++ plugin based library with support for various CAN Devices (SocketCAN, Sys Tec, PEAK, Virtual).

### Examples

* [CAN-Examples](https://github.com/craigpeacock/CAN-Examples) ⭐ 124 | 🐛 1 | 🌐 C | 📅 2022-09-18 - Example C code for CAN Sockets on Linux.
* [socketcan-demo](https://github.com/zhanglongqi/socketcan-demo) ⭐ 9 | 🐛 0 | 🌐 C++ | 📅 2016-09-23 - Set of example programs which highlight how to make use of SocketCAN on Linux.

## CAN Database

### Formats (DBC, KCD)

#### DBC

DBC - The de facto standard for CAN databases is the DBC file format developed by Vector Informatik GmbH. It is a proprietary format in that no official public documentation or specification is available.

* [DBC Format Specification v1.0](http://read.pudn.com/downloads766/ebook/3041455/DBC_File_Format_Documentation.pdf) - Leaked DBC file format specification v1.0 (the obsolete specification).
* [DBC Format](http://socialledge.com/sjsu/index.php/DBC_Format) - Brief explanations about various sections, many examples and explains multiplexed signals well.
* [DBC File Explained](https://www.csselectronics.com/screen/page/can-dbc-file-database-intro/language/en) - A Simple Intro to DCB file format.
* [J1939 and DBC introduction](https://www.kvaser.com/developer-blog/an-introduction-j1939-and-dbc-files/) - An Introduction to J1939 and DBC files.
* 🔝[cabana](https://github.com/commaai/cabana) ⚠️ Archived - CAN visualizer and DBC maker (a tool developed to view raw CAN data; one use for this is creating and editing CAN Dictionaries (DBC files)).

#### KCD

* [KCD](https://github.com/julietkilo/kcd) ⭐ 84 | 🐛 0 | 📅 2023-03-03 - An open format to describe communication relationships in CAN. similar to DBC format but written in XML.

### Converters and Parsers

* 🔝[cantools by Erik Moqvist](https://github.com/eerimoq/cantools) ⭐ 2,272 | 🐛 128 | 🌐 Python | 📅 2026-08-21 - CAN tools in python for DBC, KCD, SYM, ARXML 4 and CDD file parsing.
* [canmatrix](https://github.com/ebroecker/canmatrix) ⭐ 1,086 | 🐛 20 | 🌐 Python | 📅 2026-08-17 - Converting CAN Database Formats .arxml .dbc .dbf .kcd.
* [CANBabel](https://github.com/julietkilo/CANBabel) ⭐ 171 | 🐛 2 | 🌐 Java | 📅 2025-04-13 - Translator for several CAN description formats (supports KCD r/w and DBC read).
* [cantools by Andreas Heitmann](https://github.com/aheit/cantools) ⭐ 68 | 🐛 3 | 🌐 C | 📅 2026-03-14 - A set of libraries and command line tools for handling ASC, BLF, CLG, VSB, MDF, and DBC files.
* [CanDB](https://github.com/skysky97/Candb) ⭐ 54 | 🐛 2 | 🌐 Python | 📅 2020-03-20 - Generate CAN dbc file with OEM defined CAN matrix (xls).

<!--lint disable double-link-->

* [can4python](https://github.com/caran/can4python) ⭐ 43 | 🐛 7 | 🌐 Python | 📅 2022-12-26 - A useful package for showing the contents of KCD files (also those converted from DBC files).

<!--lint enable double-link-->

* [dbcc](https://github.com/howerj/dbcc) ⭐ 455 | 🐛 1 | 🌐 C | 📅 2025-10-07 - DBC to C (and CSV, JSON and XML) compiler using the mpc parser combinator library.
* [convert\_dbc\_to\_cpp\_file](https://github.com/jobgeodev/convert_dbc_to_cpp_file) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2021-05-13 - Util for convert dbc (canbus) to cpp(cplusplus) function.

### DBC only

* [dbcppp](https://github.com/xR3b0rn/dbcppp) ⭐ 295 | 🐛 33 | 🌐 C++ | 📅 2025-07-09 - C/C++ DBC file parser/tool.
* [CANdb from GENIVI](https://github.com/GENIVI/CANdb) ⭐ 149 | 🐛 5 | 🌐 C++ | 📅 2021-06-25 - Library for parsing DBC - CAN bus database description formats.
* [can\_decoder](https://github.com/CSS-Electronics/can_decoder) ⭐ 85 | 🐛 4 | 🌐 Python | 📅 2024-11-14 - API module for decoding raw CAN bus data to physical values using a DBC CAN database.
* [pydbc](https://github.com/christoph2/pydbc) ⭐ 39 | 🐛 0 | 🌐 Python | 📅 2026-07-07 - Process vehicle network descriptions (CAN .dbc files).
* [Vector CANdb++ DBC file parser](https://github.com/kdschlosser/vector_dbc) ⭐ 25 | 🐛 1 | 🌐 Python | 📅 2023-08-13 - Modified version of the dbc file parser of eerimoq.
* [dbc-parser](https://github.com/msalau/dbc-parser) ⭐ 10 | 🐛 0 | 🌐 C | 📅 2022-05-09 - A Flex/Bison/Lemon parser/scanner for DBC files.
* [CAN\_BUS\_DBC\_VIEWER](https://github.com/akshaych92/CAN_BUS_DBC_VIEWER) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2023-02-27 - GUI based CAN bus dbc viewer.
* [dbcview](https://github.com/driftregion/dbcview) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2019-06-14 - DBC visualization tool - plots a graph of sending and receiving nodes linked by messages.
* [VectorDbcChecker](https://github.com/Golyshkin/VectorDbcChecker) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2025-12-04 - Vector DBC Checker a Python GUI application for checking DBC files for messages duplication, missed network nodes, signals overlap in message, etc.
* [pydbc](https://github.com/Sauci/pydbc) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2020-04-16 - AST generator for dbc format.
* [dbc\_reader](https://github.com/autti/dbc_reader) ⭐ 0 | 🐛 0 | 🌐 CMake | 📅 2018-07-10 - Virtual can bus reader from dbc file (python).
* [Vector DBC](https://bitbucket.org/tobylorenz/vector_dbc) - Library to access CAN Databases (aka CANdb, aka DBC files) from Vector Informatik.

## Hardware

All kind of HW like CAN bus USB2CAN dongles, loggers, sniffers, adapters, etc.

### ARM

* [FlexCAN](https://github.com/collin80/FlexCAN_Library) ⭐ 120 | 🐛 5 | 🌐 C | 📅 2021-07-23 - Arduino library for CAN on Teensy 3.1, 3.2, 3.5, and 3.6.
* [SuperCAN](https://github.com/jgressmann/supercan) ⭐ 103 | 🐛 1 | 🌐 C++ | 📅 2026-04-25 - An open source USB to CAN-FD protocol firmware (ATSAME51).
* [PiCCANTE](https://github.com/Alia5/PiCCANTE) ⭐ 91 | 🐛 12 | 🌐 C++ | 📅 2026-01-26 - Open-source CAN hacking tool based on Raspberry Pi Pico (1|2|W) - Up to 3x CAN interfaces, includes ELM327 emulator.
* [USB\_CAN-FD on ATSAME51](https://github.com/RudolphRiedel/USB_CAN-FD) ⭐ 84 | 🐛 0 | 📅 2025-11-28 - This is an Open Source Hardware USB to CAN-FD Interface (ATSAME51J).
* [CANBootloader](https://github.com/596142041/CANBootloader-Qt) ⭐ 69 | 🐛 1 | 🌐 C++ | 📅 2019-11-10 - GUI + CAN booloader protocol.
* [Open-OBD2-datalogger](https://github.com/arturlangner/Open-OBD2-datalogger) ⭐ 24 | 🐛 0 | 🌐 C | 📅 2018-02-25 - NXP Kinetis E datalogger that saves live engine data to SD card (Visualization is done with HTML5 and JavaScript).
* [ELM327](https://github.com/ObdDiag-Net/allpro) - Open-source ELM327 OBD adapter based on LPC1517JDB48.

#### STM32

* 🔝[panda](https://github.com/commaai/panda) ⭐ 1,696 | 🐛 65 | 🌐 C | 📅 2026-08-19 - It supports 3x CAN, 2x LIN, and 1x GMLAN (and it has J2534 over USB on host side). It uses an STM32F413 (Using a panda with cabana provides the best RE and development suites for CANBUS).
* 🔝[pcan\_pro\_x](https://github.com/moonglow/pcan_pro_x) ⭐ 346 | 🐛 13 | 🌐 C | 📅 2022-03-11 - PEAK PCAN PRO/PRO FD firmware for STM32F4 based boards.
* [Arduino-STM32-CAN](https://github.com/nopnop2002/Arduino-STM32-CAN) ⭐ 277 | 🐛 5 | 🌐 C++ | 📅 2026-03-10 - Can communication example for Arduino Core STM32.
* [eXoCAN](https://github.com/exothink/eXoCAN) ⭐ 86 | 🐛 5 | 🌐 C++ | 📅 2023-11-30 - CAN Library for the STM32F103 aka Blue Pill.
* [stm32-slcan](https://github.com/walmis/stm32-slcan) ⭐ 80 | 🐛 2 | 🌐 C | 📅 2022-03-02 - SLCAN compatible firmware for BluePill based on STM32f103C8T6.
* [cantact-pro-hw](https://github.com/linklayer/cantact-pro-hw) ⭐ 79 | 🐛 1 | 📅 2020-08-20 - Hardware for the CANtact Pro, use [cantact-pro-fw](https://github.com/linklayer/cantact-pro-fw) ⭐ 51 | 🐛 8 | 🌐 C | 📅 2023-03-17 as firmware.
* [vector\_can](https://github.com/moonglow/vector_can) ⭐ 64 | 🐛 4 | 📅 2022-07-28 - Vector VN1610 protocol implementation for cheap STM32F407/405 hardware (Two CAN channel).
* [CAN\_OMEGA](https://github.com/zjlywjh001/CAN_OMEGA) ⭐ 51 | 🐛 1 | 📅 2017-02-13 - Ultimate CAN Bus hardware for Car hacking based on STM32F411. Full Featured [firmware](https://github.com/zjlywjh001/CAN_Omega_Firmware) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2017-02-13 & [software](https://github.com/zjlywjh001/CAN_OMEGA_Tools) ⭐ 8 | 🐛 0 | 🌐 Java | 📅 2019-04-29.
* [stm32-CAN-bus-example-HAL-API](https://github.com/timsonater/stm32-CAN-bus-example-HAL-API) ⭐ 47 | 🐛 0 | 🌐 C | 📅 2019-01-11 - A simple example of CAN bus communications between two STM32 microcontrollers using the updated HAL API functions.
* [CAN-BUS-Man-In-The-Middle](https://github.com/damienmaguire/CAN-BUS-Man-In-The-Middle) ⭐ 41 | 🐛 1 | 🌐 C | 📅 2020-03-21 - Dual CAN MitM-device based on STM32F105.
* [zubax\_babel](https://github.com/Zubax/zubax_babel) ⭐ 41 | 🐛 4 | 🌐 C++ | 📅 2025-08-29 - High performance CAN-USB/CAN-UART adapter + UAVCAN devboard (STM32F37x).
* [CAN-USB-dongle-fw](https://github.com/cvra/CAN-USB-dongle-fw) ⭐ 37 | 🐛 0 | 🌐 C | 📅 2021-03-23 - A slcan firmware for the CVRA CAN to USB dongle (STM32F302).
* [hadoucan-fw on STM32H750](https://github.com/suburbanembedded/hadoucan-fw) ⭐ 27 | 🐛 14 | 🌐 C | 📅 2025-12-12 - Firmware for SM-1301 USB-CAN FD adapter based on.
* [Ethernet-CAN converter](https://github.com/MikhailBerezhanov/cncu-01) ⭐ 25 | 🐛 0 | 🌐 C | 📅 2022-04-22 - Based on STM32F407.
* [CAN-to-USB-lawicel-for-stm32](https://github.com/kolyandex/CAN-to-USB-lawicel-for-stm32) ⭐ 24 | 🐛 0 | 🌐 C | 📅 2019-06-18 - CAN to USB adapter using Lawicel/Canhacker protocol based on STM32F103.
* [CanDybugFW](https://github.com/IntergatedCircuits/CanDybugFW) ⭐ 22 | 🐛 0 | 🌐 C | 📅 2021-11-18 - Embedded firmware of the CanDybug, a CAN bus traffic analyzer which uses a custom protocol over a USB serial port emulation (STM32F302/STM32F042).
* [CANnon](https://github.com/mxcd/CANnon) ⭐ 21 | 🐛 0 | 🌐 C | 📅 2017-11-18 - A versatile CAN bootloader for the STM32 and friends.
* [CAN-Bus-Arduino\_Core\_STM32](https://github.com/seeers/CAN-Bus-Arduino_Core_STM32/blob/master/CanLowlevel.ino) ⭐ 13 | 🐛 2 | 🌐 C++ | 📅 2020-01-10 - Lowlevel CanBUS Example for Arduino Core STM32.
* 🔝[STM32duino\_CAN\_Library](https://github.com/adamczykpiotr/STM32duino_CAN_Library) ⭐ 10 | 🐛 0 | 🌐 C++ | 📅 2021-06-07 - CanBus library for STM32F103 running on STM32duino.
* [STM32-CAN-Busadapter](https://github.com/IvanDev2018/STM32-CAN-Busadapter) ⭐ 8 | 🐛 0 | 🌐 C | 📅 2020-01-01 - CAN adapter on MCU stm32f303cb.
* [CAN-RS485-adapter](https://github.com/YuriyLogvin/CAN-RS485-adapter) ⭐ 7 | 🐛 0 | 🌐 C | 📅 2026-08-19 - CAN-RS485 Adapter (STM32F103).
* [CANBUS\_UART](https://github.com/Oktay97/Canbus_Uart) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2021-03-07 - CANBUS to UART for STM32F1 (BluePill and Nucleo boards).
* [CANCAN](https://github.com/DDolphin/CANCAN) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2021-03-03 - CAN recorder based on STM32F407ZGTx.
* [BudgetCANv2](https://github.com/ryedwards/budgetcan_fw) - FW for use on STM32 microcontroller to implement FDCAN and USB using the STM32 HAL. Tested on [BudgetCANv2-HW](https://github.com/ryedwards/BUDGETCANFD_G0-Hardware).

#### STM32F0x2 based HW

* [candleLight\_fw](https://github.com/candle-usb/candleLight_fw) ⭐ 936 | 🐛 33 | 🌐 C | 📅 2026-07-17 - Compatible firmware for candleLight, cantact, canable, CANAlyze, VulCAN.
* [pcan\_cantact](https://github.com/moonglow/pcan_cantact) ⭐ 434 | 🐛 3 | 🌐 C | 📅 2022-07-28 - XCAN firmware for CANtact ( CANable ) or any other similar boards based on STM32F042.
* [cantact-hw](https://github.com/linklayer/cantact-hw) ⭐ 403 | 🐛 6 | 🌐 KiCad | 📅 2021-11-08 - Hardware design files for the CANtact tool, use [cantact-fw](https://github.com/linklayer/cantact-fw) ⭐ 280 | 🐛 16 | 🌐 C | 📅 2023-06-30 as firmware source.
* [candleLight](https://github.com/HubertD/candleLight) ⭐ 391 | 🐛 1 | 🌐 KiCad | 📅 2022-07-28 - KiCAD project of usb-can adapter based on STM32F0.
* [CANAlyze](https://kkuchera.github.io/canalyze/) - An open source, native CAN interface for Linux that can be built entirely using open source tools, use [canalyze-fw](https://github.com/kkuchera/canalyze-fw) ⭐ 73 | 🐛 9 | 🌐 C | 📅 2023-11-14 as firmware source.
* [cantact](https://github.com/linklayer/cantact/) ⭐ 57 | 🐛 0 | 🌐 Rust | 📅 2024-08-26 - Drivers and Command Line Interface for CANtact tools.
* [kvaser\_cantact](https://github.com/moonglow/kvaser_cantact) ⭐ 55 | 🐛 0 | 🌐 C | 📅 2022-03-09 - Xvaser LL v2 firmware for CANtact/CANable or any other similar boards based on STM32F042.
* [USB2CAN](https://github.com/roboterclubaachen/usb2can) ⭐ 52 | 🐛 2 | 🌐 Eagle | 📅 2019-10-29 - Compact and isolated USB-to-CAN Adapter.
* [OBD2CAN](https://github.com/autosportlabs/OBD2CAN) ⭐ 46 | 🐛 0 | 🌐 C | 📅 2019-12-12 - Bridge between any OBD2 compliant vehicle and the CAN bus interface (firmware is targeted for the STM32F072, and uses ChibiOS as a RTOS).
* [CANsniffer on STM32F042](https://github.com/majbthrd/CANsniffer) ⭐ 33 | 🐛 0 | 🌐 C | 📅 2017-11-09 - CANbus sniffer less complicated than existing commercial products.
* [Cantact FW](https://github.com/x893/cantact-fw) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2015-11-21 - Cantact FirmWare by x893.
* [ELM329](https://github.com/ObdDiag-Net/elm329) - Open-source ELM329 OBD adapter based on STM32F042.

### Arduino

* 🔝[arduino-canhacker](https://github.com/autowp/arduino-canhacker) ⭐ 477 | 🐛 12 | 🌐 C++ | 📅 2024-01-19 - CanHacker (lawicel) CAN adapter on Arduino + MCP2515.
* [Arduino-canbus-monitor](https://github.com/latonita/arduino-canbus-monitor) ⭐ 336 | 🐛 4 | 🌐 C++ | 📅 2025-10-22 - Can bus monitoring tool based on arduino and can bus shield. Implements CAN ASCII/SLCAN protocol compatible with Lawicel CAN232/CANUSB.
* [W203-canbus](https://github.com/rnd-ash/W203-canbus) ⭐ 167 | 🐛 3 | 🌐 C++ | 📅 2020-08-07 - Arduino project for W211/W219 W203/W209 Mercedes (bluetooth audio control and more).
* [open-usb-can from Fabio Baltieri](https://github.com/fabiobaltieri/open-usb-can) ⚠️ Archived - CAN-to-USB dongle based on ATMega32U and MCP2515.
* [Arduino-psa-comfort-can-adapter](https://github.com/ludwig-v/arduino-psa-comfort-can-adapter) ⭐ 71 | 🐛 2 | 🌐 C++ | 📅 2025-07-09 - Arduino sketch to operate new PSA (Peugeot, Citroen, DS, Opel) comfort devices (CAN2010) on old BSI CAN-BUS (CAN2004).
* [CANBus-Triple](https://github.com/CANBus-Triple/CANBus-Triple-Hardware) ⭐ 59 | 🐛 1 | 🌐 Eagle | 📅 2017-06-21 - The car hacking platform based on AVR and MCP2515 works with [this firmware](https://github.com/CANBus-Triple/CANBus-Triple) ⭐ 354 | 🐛 11 | 🌐 C | 📅 2019-11-11.
* [Arduino-CAN-bus-SD-logger](https://github.com/DieselDuz42/Arduino-CAN-bus-SD-logger) ⚠️ Archived - Arduino script to log CAN bus information to SD card. Mainly focused on J1939.
* [epasuino](https://github.com/srenner/epasuino) ⭐ 5 | 🐛 0 | 🌐 C++ | 📅 2019-02-19 - Arduino based Speed sensitive electric power steering for automobiles  Speed sensitive electric power steering for automobiles.
* [carfuino](https://github.com/srenner/carfuino) ⭐ 5 | 🐛 0 | 🌐 C++ | 📅 2018-08-20 - Arduino based Automotive performance computer with Megasquirt integration.

<!--lint disable double-link-->

* [GVRET](https://github.com/collin80/GVRET) ⭐ 112 | 🐛 10 | 🌐 C++ | 📅 2018-10-16 - Generalized Electric Vehicle Reverse Engineering Tool (Arduino FW).

<!--lint enable double-link-->

* [arduino-mcp2515](https://github.com/autowp/arduino-mcp2515) ⭐ 1,025 | 🐛 64 | 🌐 C++ | 📅 2026-02-27 - Arduino MCP2515 CAN interface library.
* [arduino-OBD2](https://github.com/sandeepmistry/arduino-OBD2) ⭐ 567 | 🐛 15 | 🌐 C++ | 📅 2022-12-29 - Arduino library for reading OBD-II data from your car over CAN bus.
* [slcanuino](https://github.com/kahiroka/slcanuino) ⭐ 140 | 🐛 6 | 🌐 C | 📅 2021-11-17 - USB-CAN (SocketCAN) sketch for Arduino CAN-BUS shield.
* [arduino-ecu-logger](https://github.com/ihaque/arduino-ecu-logger) ⭐ 39 | 🐛 0 | 🌐 Python | 📅 2016-01-17 - Arduino-based OBD2 engine monitor and data logger.
* [CITM02](https://github.com/BXProject/CITM02) ⭐ 9 | 🐛 0 | 🌐 C++ | 📅 2021-01-23 - CAN In The Middle (CITM) the Dual channel CANBUS adapter built around Arduino.
* [open-source-can-bridge](https://bitbucket.org/emile_nijssen/open-source-can-bridge) - Gateway with several CAN interfaces based on Xmega.

### Espressif Systems (ESP8266, ESP32)

* [ESP-IDF-CANBus-Monitor](https://github.com/nopnop2002/esp-idf-CANBus-Monitor) ⭐ 138 | 🐛 0 | 🌐 C | 📅 2026-06-09 - Monitor Canbus traffic ESP32.
* [PSASteeringWheelAdapter](https://github.com/morcibacsi/PSASteeringWheelAdapter) ⭐ 38 | 🐛 0 | 🌐 C++ | 📅 2020-02-29 - ESP32 based steering wheel adapter for Peugeot and Citroen cars.
* [connected-car](https://github.com/marmotton/connected-car) ⭐ 12 | 🐛 0 | 🌐 C++ | 📅 2021-04-25 - Connecting a Nissan e-NV200 (or Leaf) to MQTT.

<!--lint disable double-link-->

* [esp32-slcan](https://github.com/mintynet/esp32-slcan) ⭐ 109 | 🐛 0 | 🌐 C++ | 📅 2026-02-23 - ESP32 slcan compatible device.
* [esp32s3-slcan](https://github.com/Pacerino/TWAI_SLCAN) ⭐ 9 | 🐛 1 | 🌐 C++ | 📅 2024-03-18 - SLCAN implementation for ESP32-S3 (based on [esp32-slcan](https://github.com/mintynet/esp32-slcan) ⭐ 109 | 🐛 0 | 🌐 C++ | 📅 2026-02-23).

<!--lint enable double-link-->

* [RejsaCAN-ESP32](https://github.com/MagnusThome/RejsaCAN-ESP32) ⭐ 782 | 🐛 1 | 🌐 C++ | 📅 2026-07-26 - ESP32-S3 board with CAN interface.
* [RejsaCAN-ESP32-C6](https://github.com/MagnusThome/RejsaCAN-ESP32/tree/main/Code%20Examples/RejsaCAN%20v6.x%20-%20ESP32-C6%20-%20DUAL%20CAN%20self%20test) ⭐ 782 | 🐛 1 | 🌐 C++ | 📅 2026-07-26 - Example code that is tested and runs on the new ESP32-C6 that has TWO built in CAN controllers.
* [esp32-obd2-emulator](https://github.com/limiter121/esp32-obd2-emulator) ⚠️ Archived - Open-source OBD-II emulator based on an ESP32 + CAN transceiver IC, controllable via WiFi through a simple web UI (or via API).
* [ESP32RET](https://github.com/collin80/ESP32RET) ⭐ 403 | 🐛 46 | 🌐 C++ | 📅 2026-01-15 - CAN Reverse engineering tool for ESP32 based boards (unmaintained).
* [ESP32-Arduino-CAN](https://github.com/miwagner/ESP32-Arduino-CAN) ⭐ 390 | 🐛 33 | 🌐 C | 📅 2024-07-29 - Arduino CAN-Bus library for ESP32.
* [esp32\_obd2](https://github.com/MagnusThome/esp32_obd2) ⭐ 72 | 🐛 0 | 🌐 C++ | 📅 2023-12-23 - Simplified OBD2 layer to run on top of the esp32\_can library that supports the newer ESP32-S3 (Arduino library).
* [ESP32\_CAN\_Interface](https://github.com/PhilippFux/ESP32_CAN_Interface) ⭐ 62 | 🐛 1 | 🌐 C++ | 📅 2021-03-10 - Wireless CAN-Interface for the ESP32 which uses the cannelloni protocol to send CAN-Frames via UDP over an Wi-Fi tunnel.
* [esp-idf-can2http](https://github.com/nopnop2002/esp-idf-can2http) ⭐ 49 | 🐛 1 | 🌐 C | 📅 2026-06-08 -  CANbus to http bridge using ESP32.
* [CAN-wizard](https://github.com/okhsunrog/can_wizard) ⭐ 39 | 🐛 1 | 🌐 C | 📅 2025-11-07 - CAN bus sniffer on esp32/esp32-c3 + SN65HVD230. Is developed using ESP-IDF and implement serial control console.
* 🔝[ESP32\_CANViewer](https://github.com/Cellgalvano/ESP32_CANViewer) ⭐ 27 | 🐛 0 | 🌐 C++ | 📅 2021-03-08 -  ESP32 based CAN interface for your webbrowser.
* [esp32\_canbus\_gateway](https://github.com/vigoballak/esp32_canbus_gateway) ⭐ 21 | 🐛 1 | 🌐 Python | 📅 2021-05-06 - CAN module on esp32 + tja1050 coded on micropython.
* [ESP32\_OBD2\_Emulator](https://github.com/MagnusThome/ESP32_OBD2_Emulator) ⭐ 16 | 🐛 0 | 🌐 C++ | 📅 2023-12-10 - Simple OBD2 car emulator which runs on ESP32-S3 (replies to all OBD2 requests with dummy data).
* [ESP32S3RET](https://github.com/MagnusThome/ESP32S3RET) ⭐ 15 | 🐛 0 | 🌐 C++ | 📅 2023-12-14 - CAN Reverse engineering tool for ESP32-S3 based boards.
* [esp32-cantroller](https://github.com/neg2led/esp32-cantroller) ⭐ 13 | 🐛 1 | 🌐 KiCad Layout | 📅 2022-11-22 - ESP32-S2-WROVER/WROOM based CANBUS controller thingy.
* [esp32-canbus-logger](https://github.com/scipioni/esp32-canbus-logger) ⭐ 6 | 🐛 0 | 🌐 C++ | 📅 2021-06-09 - CAN bus logger on uSD-card based on ESP32.

### SBC

**SBC** - Single Board Computers.

* [rpi-can-logger](https://github.com/JonnoFTW/rpi-can-logger) ⭐ 157 | 🐛 2 | 🌐 Python | 📅 2021-03-14 - Project to log CAN bus data from a PiCAN2 and a GPS module.
* [CANoPi](https://github.com/SushiBits/CANoPi) ⭐ 13 | 🐛 0 | 🌐 Eagle | 📅 2017-08-26 - CAN interface for Raspberry Pi Zero.
* [beaglebone\_black\_socketcan](https://github.com/BlueAndi/beaglebone_black_socketcan) ⭐ 5 | 🐛 0 | 📅 2018-03-19 - How to get access to the CAN bus on a BeagleBone Black via socketcan interface.

### IP cores for ASIC and FPGA

* [CAN](https://opencores.org/projects/can) - IP core for classic CAN Protocol Controller (VHDL).
* [CTU-CAN-FD](https://github.com/Logic-Design-Services/CTU-CAN-FD) ⭐ 70 | 🐛 13 | 🌐 VHDL | 📅 2026-08-17 - CAN FD IP Core, ISO 11898-1:2015 compliant (VHDL).

### Others HW

* [Microchip CAN BUS Analyzer on PIC18F2550/PIC18F2680 Driver](https://github.com/rkollataj/mcba_usb) ⭐ 50 | 🐛 2 | 🌐 C | 📅 2017-07-13 - Linux kernel driver for Microchip CAN BUS Analyzer Tool.
* [elm327\_clone](https://github.com/darkspr1te/elm327_clone) ⭐ 48 | 🐛 0 | 🌐 C | 📅 2018-01-11 - ELM327 firmware for pic18f25k80 chip from china clone OBD2.
* [Microchip CAN BUS Analyzer on PIC18F2550/PIC18F2680 Firmware](https://github.com/rkollataj/mcba_firmware) ⭐ 22 | 🐛 1 | 🌐 C | 📅 2016-10-14 - Microchip CAN BUS Analyzer firmware.
* [BB-to-STM32](https://github.com/mvollrath/canbus_bbone_stm32) ⭐ 13 | 🐛 0 | 🌐 C | 📅 2017-02-03 - LED sync between BeagleBone Black and STM32F4 Discovery Board.

### Hardware related tools

* [CAN Bus Bit Timing Calculator](https://www.kvaser.com/support/calculators/bit-timing-calculator/) - Online tool for obsolete SJA1000 and MCP2510 (probably it works for MCP2515).
* [Bit Timing Calculator for CAN FD](https://kvaser.com/support/calculators/can-fd-bit-timing-calculator/) - Online tool to calculate detailed bit timing parameters for general CAN FD devices.
* [STM8S208 CAN Speed Calculator](https://github.com/iDoka/STM8S208-CAN-Speed-Calculator) ⭐ 6 | 🐛 0 | 🌐 C++ | 📅 2017-02-14 - CAN Speed Calculator for STM8 (perhaps it also works for STM32 family).
* [STMG431 FDCAN SOLVER](https://phryniszak.github.io/stm32g-fdcan/) - Online tool to calculate bit timing parameters for STM32G4 (likely compatible with STM32G0).

***

## Contributing

* Your contributions are always welcome! Please read the [contribution guidelines](contributing.md) first.

## Footnotes

<!--lint disable double-link-->

1. Please follow [this](https://github.com/iDoka/awesome-canbus) ⭐ 3,429 | 🐛 6 | 📅 2026-08-07 root-repo for lastest updates.
2. The another awesome list :arrow\_forward: [CAN ID collections](https://github.com/iDoka/awesome-automotive-can-id) ⭐ 978 | 🐛 0 | 📅 2026-08-12 :arrow\_backward: also might be useful.
3. Also might be useful [this curated list](https://github.com/iDoka/awesome-linbus) ⭐ 245 | 🐛 1 | 📅 2023-09-06 of awesome tools and resources for LIN bus reverse engineering, LIN hardware development and debugging.

<!--lint enable double-link-->

<!--
## Tags

#awesome
#awesome-list
#can
#can-bus
#canbus
#canfd
#can-fd
#logger
#sniffer
#slcan
#socketcan
#car-hacking
#bus-monitoring
#lawicel
#elm327
#obd2
#canutils
#automotive
#embedded
#arduino
#rpi
#raspberry-pi
#sae
#uds
#j1962
#j1939
#j1979
#j2534
#lin
#lin-bus
#local-interconnect-network
#flexray
#obd-ii
#slcan-protocol
#usbtin
#usb2can
#iso11898
#iso11565
#iso11765
#iso14229
#dbc
#odb
#ldf
#electric-vehicles
#vehicular-networks
#python
#automotive-security
-->

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-22._
