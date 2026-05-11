# P1AM PlatformIO

PlatformIO project template for the **P1AM-100** and **P1AM-200** automation controllers.

| Board | MCU | Flash | RAM |
|-------|-----|-------|-----|
| P1AM-100 | ATSAMD21G18A @ 48 MHz | 256 KB | 32 KB |
| P1AM-200 | ATSAMD51P20A @ 120 MHz | 1 MB | 256 KB |

---

## Requirements

Install these before starting:

- [VS Code](https://code.visualstudio.com/) + [PlatformIO IDE extension](https://marketplace.visualstudio.com/items?itemName=platformio.platformio-ide)
- [Git](https://git-scm.com/downloads)

---

## Setup

**1. Clone or download this repo.**

**2. Open the project folder in VS Code.** PlatformIO will detect it automatically.

**3. Build** — PlatformIO will fetch the FACTS board support packages automatically on first run:

```bash
pio run -e p1am_100    # P1AM-100
pio run -e p1am_200    # P1AM-200
```

**4. Upload:**

```bash
pio run -e p1am_100 -t upload
pio run -e p1am_200 -t upload
```

**5. Serial monitor** (115200 baud):

```bash
pio device monitor
```

---

## References

- [Buy on AutomationDirect](https://www.automationdirect.com/adc/shopping/catalog/programmable_controllers/productivity_open_(arduino-compatible))
- [P1AM Documentation](https://facts-engineering.github.io/)
- [P1AM Library](https://github.com/facts-engineering/P1AM)
- [P1AM-100 Hardware](https://facts-engineering.github.io/modules/P1AM-100/P1AM-100.html)
- [P1AM-200 Hardware](https://facts-engineering.github.io/modules/P1AM-200/P1AM-200.html)
