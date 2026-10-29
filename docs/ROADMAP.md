# OpenGH5 roadmap

This roadmap expresses research priorities, **not confirmed GH5 capabilities**.

## Phase 0 — Foundations
- [x] Create a public, unofficial project with license and publication safeguards.
- [ ] Record hardware and firmware version for repeatable tests.
- [ ] Establish evidence standards and a public research log.

## Phase 1 — Protocol discovery (read-only first)
- [ ] Inventory documented GH5 Wi-Fi, USB and Bluetooth interfaces.
- [ ] Reproduce safe, non-persistent queries on a DC-GH5.
- [ ] Document API behavior, connection modes and compatibility limitations.
- [ ] Write isolated protocol tests with synthetic fixtures.

## Phase 2 — Firmware analysis (offline)
- [ ] Catalog vendor-distributed update versions and official source releases.
- [ ] Identify image format and architecture using authorized local samples.
- [ ] Publish original high-level findings without uploading vendor binaries.
- [ ] Investigate feature flags and extension mechanisms as hypotheses, not releases.

## Phase 3 — Control API and dashboard
- [ ] Implement local connection/service layer with explicit permissions.
- [ ] Expose typed read-only state and opt-in camera commands.
- [ ] Build a responsive web dashboard for desktop and mobile.
- [ ] Test reconnection, network loss and safe command sequencing.

## Phase 4 — Experimental extensions (only if supported by evidence)
- [ ] Evaluate feasibility, recovery strategy and device-specific risk.
- [ ] Seek independent validation before any hardware-modifying release.
- [ ] Publish only material we own or are licensed to distribute.

No custom firmware, unlock or patch is currently available.
