# PIC18 Autoclave Cycle Controller

Finite-state-machine that manages a sterilization cycle on the **PIC18F45K22**, handling pressure, temperature ramps, and safety interlocks.

## Key points for hiring managers
- **Safety-critical FSM** with timed ramps and alarm thresholds.
- **Compact codebase** - easily extensible for additional sensors.
- **Reference documentation** in `docs/Evaluacion 3.pdf`.

## How to run
```bash
git clone https://github.com/Alexis-c-d/pic18-autoclave-fsm.git
cd pic18-autoclave-fsm/src
# Compile and flash; monitor status via UART.
```

🗂️ **Docs** - cycle specifications in `docs/Evaluacion 3.pdf`.

---

## Repository layout
```
pic18-autoclave-fsm/
├─ src/        # Source code
├─ sim/        # Simulation files
└─ docs/       # Evaluacion 3.pdf (project report)
```

## License
MIT - feel free to use or adapt for medical/industrial control systems.
