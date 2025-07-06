# mayan.sync.kuch

This repository stores the locked MIDI endpoints schema for the Terra Universalis system, used by the `mayan.sync` module to ensure consistent MIDI mapping across devices.

## 🔒 Purpose
The `endpoints_midi_lock.json` file contains a fixed list of recognized MIDI input/output ports. It is referenced by PowerShell tools, DJ Pro mappings, and other systems for ensuring synchronized operation.

## 🌐 Structure
- `endpoints_midi_lock.json`: Primary JSON file containing locked endpoint definitions.
- Future expansion: support for profile loading, MIDI routing schemas, and advanced validation.

## 📍 Location in System
This repo is synchronized with the Terra Universalis endpoint manager:
```
C:\Users\alfon\OneDrive - Terrauniversalis\#terrasarchivum\#systemas\#mayansync\#endpoints
```

## 📘 Related Modules
- `mayan.sync`: Synchronization core.
- `mayan.mapper`: Visual and indexed system map.
- `mayan.tuukul`: MIDI master control.

## 📤 Sync & Usage
Use `git pull` or integrate into your pipeline to always refer to the latest locked configuration.

---


### español 🇪🇸
Este repositorio guarda el esquema bloqueado de endpoints MIDI para el sistema Terra Universalis, utilizado por el módulo `mayan.sync` para asegurar una sincronización uniforme entre dispositivos.

- Archivo principal: `endpoints_midi_lock.json`.
- Utilizado por sistemas de mapeo MIDI y herramientas de automatización PowerShell.
- Ruta en sistema: `#mayansync\#endpoints`.

### inglés 🇺🇸
This repository stores the locked MIDI endpoints schema for Terra Universalis, used by the `mayan.sync` module to ensure uniform synchronization across devices.

- Main file: `endpoints_midi_lock.json`.
- Used by MIDI mapping systems and PowerShell automation tools.
- System path: `#mayansync\#endpoints`.

### chino 🇨🇳
此仓库存储 Terra Universalis 的锁定 MIDI 端点架构，由 `mayan.sync` 模块使用，以确保设备之间的同步一致性。

- 主要文件：`endpoints_midi_lock.json`
- 适用于 MIDI 映射系统和 PowerShell 自动化工具
- 系统路径：`#mayansync\#endpoints`

### ruso 🇷🇺
Этот репозиторий хранит схему заблокированных MIDI-эндпоинтов для Terra Universalis, используемую модулем `mayan.sync` для обеспечения синхронной работы устройств.

- Основной файл: `endpoints_midi_lock.json`
- Используется в системах миди-маппинга и автоматизации PowerShell
- Системный путь: `#mayansync\#endpoints`

### árabe 🇸🇦
يخزن هذا المستودع مخطط نقاط النهاية المقفلة لـ MIDI في نظام Terra Universalis، ويُستخدم بواسطة وحدة `mayan.sync` لضمان التزامن الموحد بين الأجهزة.

- الملف الرئيسي: `endpoints_midi_lock.json`
- يُستخدم في أنظمة تعيين MIDI وأدوات PowerShell الآلية
- المسار في النظام: `#mayansync\#endpoints`
