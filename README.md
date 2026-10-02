# Orchard Irrigation Controller Animal Intrusion Alarm

Build a smart agriculture prototype that uses capacitive soil sensor, solar charger to detect and report animal movement. Include setup instructions, a circuit diagram, tested firmware, and sample output.

## Project details

| Field | Value |
| --- | --- |
| Roadmap ID | 138 |
| Category | Smart Agriculture |
| Platform | STM32 |
| Difficulty | Beginner |
| Estimated build time | 16 hours |
| Connectivity | GSM |
| Core components | capacitive soil sensor, solar charger |
| Control mode | threshold alert |

## Repository layout

- `firmware/orchard-irrigation-controller-animal-intrusion-alarm/orchard-irrigation-controller-animal-intrusion-alarm.ino`: runnable firmware or application
- `docs/wiring.md`: suggested low-voltage wiring plan
- `docs/architecture.md`: system data flow
- `docs/test-plan.md`: repeatable verification steps
- `sample-data/example.json`: example telemetry record
- `tools/validate.py`: dependency-free repository validation

## Quick start

1. Open `firmware/orchard-irrigation-controller-animal-intrusion-alarm/orchard-irrigation-controller-animal-intrusion-alarm.ino` in Arduino IDE or Arduino CLI.
2. Select the board matching **STM32**.
3. Compile and upload, then open the serial monitor at 115200 baud.

## Expected behavior

Animal Intrusion Alarm demonstration with repeatable test steps. The default implementation supports simulated or generic analog inputs so the control path can be exercised before hardware-specific drivers are added.

## Hardware adaptation

The included code is a safe reference implementation. Update pin assignments and sensor conversions from the exact component datasheets, then repeat the test plan before connecting actuators.

## License

MIT
