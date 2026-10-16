# Firmware and devices

Optional home for ESP32, Arduino, microcontroller, sensor, and actuator code.

Document the board, toolchain, firmware flash steps, pin map, supply-voltage assumptions, serial settings, and safe test procedure. Keep secrets and real device identifiers out of the repository.

Suggested layout:

```text
firmware/
├── src/
├── include/
├── tests/
├── docs/       # wiring / pin map / calibration notes
└── README.md
```

For wiring images, save a readable diagram in `assets/diagrams/` and link it here. State clearly what is simulated versus connected to physical hardware.
