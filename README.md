# Exynos7870-Revived-Beta OTA Updates

Over-The-Air (OTA) update metadata for LineageOS 19.1 (Android 12L) devices powered by Samsung Exynos 7870.

## Supported Devices

| Device | Codename | OTA Metadata |
| :--- | :--- | :--- |
| Galaxy A3 (2017) | `a3y17lte` | [`a3y17lte.json`](./a3y17lte.json) |
| Galaxy J5 (2017) / Pro | `j5y17lte` | [`j5y17lte.json`](./j5y17lte.json) |
| Galaxy J6 (2018) | `j6lte` | [`j6lte.json`](./j6lte.json) |
| Galaxy J7 Neo / Core / Nxt | `j7velte` | [`j7velte.json`](./j7velte.json) |
| Galaxy J7 (2016) | `j7xelte` | [`j7xelte.json`](./j7xelte.json) |
| Galaxy J7 (2017) / Pro | `j7y17lte` | [`j7y17lte.json`](./j7y17lte.json) |
| Galaxy On7 (2016) / J7 Prime | `on7xelte` | [`on7xelte.json`](./on7xelte.json) |
| Galaxy On7 Prime (2018) / J7 Prime 2 | `on7xreflte` | [`on7xreflte.json`](./on7xreflte.json) |

## ROM Integration

Configured in `device/samsung/universal7870-common/device-common.mk`:
```make
PRODUCT_PROPERTY_OVERRIDES += \
    lineage.updater.uri=https://raw.githubusercontent.com/Exynos7870-Revived-Beta/OTA/main/{device}.json
```
