# Changelog

All notable changes, features, and architectural capabilities of this project are documented in this file.

---

## [1.0.0] - GeoFS V4.0 Release

### Changed

- Promote the existing GeoFS V4.0 standalone script to version 1.0.0.
- Align the release documentation and userscript metadata with the V4.0 ecosystem.

---

## [Unreleased]

### Fixed

- **Control Synchronization**: Standardized parking brake toggling to use GeoFS V4 control setters (`controls.setters?.toggleParkingBrake?.set`) and respected aircraft profile flap limits (`checklist-system_standalone.user.js`).

---

## [0.1.1] - V4 Integration Update

- Resolves aircraft profiles dynamically and falls back to the aircraft definition for its name.
- Fix aircraft detection when loading a profile.
- Live GeoFS V4 validation is pending.

## [0.1.0] - V4 Compatibility Fixes

- Waits for the shared HUD, uses V4 foundation dependencies and flight-control setters, and guards aircraft transitions.

## [4.0.0] - GeoFS 4.0 Port & Unified V3.9 Design

- Ported to GeoFS 4.0 ecosystem with dual-host support (`beta.geo-fs.com` and `www.geo-fs.com`).
- Enforced native minimalist styling matching GeoFS-V3.9 HUD conventions.
- Integrated into GeoFS-V4.0 Core Library and Design System lifecycle.
