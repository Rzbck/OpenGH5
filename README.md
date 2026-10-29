# OpenGH5

**Unofficial open-source research and control tools for the Panasonic Lumix DC-GH5.**

> [!IMPORTANT]
> **Early-stage research.** OpenGH5 does not currently provide a custom GH5 firmware, a firmware patch, or a ready-to-use camera controller. This project is **not affiliated with, endorsed by, or supported by Panasonic**.

## Goals

- **Firmware research:** document the GH5 architecture, update formats, and verifiable findings without distributing proprietary firmware.
- **Camera connectivity:** study and implement supported Wi-Fi, USB and Bluetooth control protocols.
- **Control Center:** build a responsive local dashboard for camera settings, monitoring and automation.
- **Interoperability:** document reproducible experiments and encourage community contributions.

## Project status

| Workstream | Status |
| --- | --- |
| Firmware research | Planning |
| Wi-Fi / USB / Bluetooth protocol research | Planning |
| Local control API | Not started |
| Web dashboard | Not started |
| Custom firmware | **Not available** |

**Target hardware:** Panasonic Lumix **DC-GH5** (original GH5). Related models are not presumed compatible.

## Getting started

There is no software release yet. Start with [the roadmap](docs/ROADMAP.md) and [research methodology](docs/RESEARCH.md). Contributions are welcome via issues and pull requests; read [CONTRIBUTING.md](CONTRIBUTING.md) first.

## Safety and responsible publication

- No Panasonic proprietary firmware, dumped ROM/RAM, copyrighted disassembly, cryptographic keys, secrets, personal information or private network details belong in this public repository.
- Keep original firmware files, raw captures and private analysis artifacts **offline and outside Git**.
- Never flash experimental firmware or run unverified patches based on an issue or draft.
- Mark every claim as **verified**, **reproduced**, or **hypothesis**, with the exact camera/firmware version and evidence.
- Security-sensitive reports should follow [SECURITY.md](SECURITY.md), not public issues.

## License

Original code and documentation in this repository are licensed under the [MIT License](LICENSE) unless otherwise noted. Panasonic trademarks and proprietary software remain the property of their respective owners.
