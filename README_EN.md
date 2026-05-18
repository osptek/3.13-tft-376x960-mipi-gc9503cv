# 3.13" 376×960 TFT MIPI module (GC9503CV) — documentation & samples

**简体中文：** [`README.md`](README.md)

---

> This repository provides **sample projects** for this module, together with datasheets, specifications, and interface / bring-up documentation for selection reference and integration.

## Product overview

| Item | Description |
|:--|:--|
| Module | 3.13-inch **TFT** panel, **376×960** resolution |
| Interface | **MIPI** |
| Driver IC | **GC9503CV** |
| Spec ID | **`3.13-tft-376x960-mipi-gc9503cv`** is the common product designation in documentation |

---

## Repository layout

### Top-level

| Path | Contents |
|:--|:--|
| `docs/` | Datasheets, specifications, initialization documentation |
| `examples/` | **Sample projects** |

### `examples/` layout

| Location | Description (internal package folder) |
|:--|:--|
| `examples/` root | **esp-idf代码** (MIPI DSI + LVGL) |

### Sample project paths

| Description | Path |
|:--|:--|
| GC9503CV MIPI DSI + LVGL | `examples/esp32p4-idf5_gc9503cv-mipi-dsi/` |
