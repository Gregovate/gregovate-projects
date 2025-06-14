# Gregovate Project Index

This is the central hub for all projects developed under the **Gregovate** profile. Projects are grouped by functional area to support hardware automation, Home Assistant integrations, sensor platforms, and open-source utility builds.

---

## 🔖 Badge Key

### Status

* ![stable](https://img.shields.io/badge/status-stable-brightgreen): Fully deployed and field-tested
* ![active](https://img.shields.io/badge/status-active-brightgreen): Actively maintained and updated
* ![in\_testing](https://img.shields.io/badge/status-in_testing-yellow): Working implementation undergoing validation
* ![experimental](https://img.shields.io/badge/status-experimental-orange): Proof-of-concept or prototype in early testing
* ![archived](https://img.shields.io/badge/status-archived-lightgrey): Inactive, superseded, or preserved for reference

### Platform

* ![ESPHome](https://img.shields.io/badge/platform-ESPHome-blue): ESPHome-based automation
* ![ESP32](https://img.shields.io/badge/platform-ESP32-blue): Custom ESP32 firmware
* ![ESP8266](https://img.shields.io/badge/platform-ESP8266-blue): Custom ESP8266 firmware
* ![Home Assistant](https://img.shields.io/badge/platform-Home_Assistant-blue): Home Assistant configuration and automations
* ![Manual](https://img.shields.io/badge/platform-Manual-grey): No firmware or software

### Other

* ![Power Optimized](https://img.shields.io/badge/power_optimized-yes-brightgreen): Designed for energy efficiency
* ![Secrets Managed](https://img.shields.io/badge/secrets-managed-lightgrey): Uses structured secret handling
* ![Storage](https://img.shields.io/badge/storage-LittleFS-lightgrey): Filesystem-based data persistence
* ![Storage](https://img.shields.io/badge/storage-SQLite-lightgrey): Relational storage using embedded SQLite database
* ![Language](https://img.shields.io/badge/language-Python-blue): Primary scripting language


\--- for all projects developed under the **Gregovate** profile. Projects are grouped by functional area to support hardware automation, Home Assistant integrations, sensor platforms, and open-source utility builds.

---

## 🧠 Making Spirits Bright (MSB)

### [MSB-Production-Database-Project](https://github.com/Gregovate/MSB-Production-Database-Project)
![Status](https://img.shields.io/badge/status-active-brightgreen) ![Platform](https://img.shields.io/badge/platform-Home_Assistant-blue) ![Language](https://img.shields.io/badge/language-Python-blue) ![Storage](https://img.shields.io/badge/storage-SQLite-lightgrey)
A database-driven project for managing light show sequencing, prop data, and show setup logistics in the Making Spirits Bright event.

 
A database-driven project for managing light show sequencing, prop data, and show setup logistics in the Making Spirits Bright event.

### [MSB-Gate-Counter](https://github.com/Gregovate/msb-gate-counter)

![Status](https://img.shields.io/badge/status-stable-brightgreen) ![Platform](https://img.shields.io/badge/platform-ESP32-blue)
Gate counter system used at Making Spirits Bright, utilizing beam sensors and magnetic detection for accurate visitor tracking.

### [MSB-Car-Counter](https://github.com/Gregovate/msb-car-counter)

![Status](https://img.shields.io/badge/status-stable-brightgreen) ![Platform](https://img.shields.io/badge/platform-ESP32-blue) ![Storage](https://img.shields.io/badge/storage-LittleFS-lightgrey)
Standalone vehicle counting system leveraging ESP32, MQTT reporting, and backup storage using LittleFS.

---

## 📸 Camera Panning Projects

### [cam-panner-manual](https://github.com/Gregovate/cam-panner-manual)

![Status](https://img.shields.io/badge/status-archived-lightgrey) ![Platform](https://img.shields.io/badge/platform-Manual-grey)
Manual servo mount for controlling a lightweight security camera with physical joystick control.

### [cam-panner-servo](https://github.com/Gregovate/cam-panner-servo)

![Status](https://img.shields.io/badge/status-experimental-orange) ![Platform](https://img.shields.io/badge/platform-ESP8266-blue)
ESP-based pan/tilt system for automating camera angles. Supports Home Assistant and MQTT.

---

## 🚐 RV Automation Projects


![Status](https://img.shields.io/badge/status-in_testing-yellow) ![Platform](https://img.shields.io/badge/platform-ESPHome-blue) ![Power Optimized](https://img.shields.io/badge/power_optimized-yes-brightgreen)
Dual-fan PWM-based airflow control system for RV refrigerators. ESPHome-controlled, with freeze protection and energy efficiency.

### [rv-ha-config](https://github.com/Gregovate/rv-ha-config)

![Status](https://img.shields.io/badge/status-active-brightgreen) ![Platform](https://img.shields.io/badge/platform-Home_Assistant-blue) ![Secrets Managed](https://img.shields.io/badge/secrets-managed-lightgrey)
Version-controlled Home Assistant configuration with Git integration, secrets management, and organized package-based structure.

### rv-power-monitor *(planned)*

Victron Energy + MQTT dashboard sensor aggregation, template power metrics, and inverter/charger monitoring.

### rv-generator-control *(planned)*

Smart generator automation system for RV use with quiet hour control, load triggers, and Home Assistant integration.

---

## 🧰 Utilities & Shared Assets

### esphome-components-gregovate *(planned)*

Reusable ESPHome YAML components and logic blocks for sensors and automation.

### rv-3d-printed-parts *(planned)*

Custom housings, ducts, and mounts used across RV projects (STL-based).

### rv-pcb-designs *(planned)*

PCB layout and designs for D1 Mini breakouts, sensor shields, and power boards.

---

## How to Use This Repo

Each project is independently versioned and documented. This index helps:

* Navigate subprojects by focus area
* Discover build details, schematics, and YAML examples
* Track development status (e.g., live, planned, in-testing)

> Contributions, forks, or feedback welcome.

---

## 🛡️ Monetization & Source Control Strategy

Some projects in this collection may evolve into monetized or semi-commercial offerings. To balance transparency and control:

### Public Repos Include:

* Compiled YAML examples (no sensitive config)
* STL file previews or printable versions (not editable source)
* Output wiring diagrams (not source schematics)
* Partial documentation for DIY builds

### Private Assets (Held for Future Release or Sale):

* Full Fusion 360 files (`*.f3d`)
* Editable PCB designs and Gerbers
* YAML configuration templates with advanced logic
* Internal BOMs, pricing data, and scripts

### Licensing:

* Projects may be released under a restrictive open license (e.g. CC BY-NC 4.0)
* Source files marked as proprietary are not to be redistributed or resold without permission

### Distribution Options:

* STL/PCB access via Gumroad, Ko-fi, or GitHub Sponsors
* Kit hardware made available through Tindie or Etsy

This strategy preserves flexibility for open collaboration while allowing for commercial exploration in the future.
