# Basic AI Agent for RF PCB Design

**Automated RF filter design from specification to manufacturing.**

This system transforms natural-language prompts into complete, manufacturable RF PCB designs. Describe what you need in plain text, and get back a fully simulated, optimized, and DRC-validated KiCad project with manufacturing files.

## Example

**Input:**
```
4th-order Chebyshev LPF at 100 MHz, 0.5 dB ripple, ≥40 dB @ 300 MHz, 50 Ω, 0805
```

**Output:**
- Optimized RF circuit (L/C values)
- S-parameter plots and simulation data
- KiCad schematic & PCB layout
- Gerbers, drill files, BOM, pick-and-place
- Validation report with pass/fail metrics

## Features

- **Filter types:** Low-pass (Butterworth, Chebyshev). 
- **Frequency range:** 10-200 MHz
- **Orders:** 3, 4, or 5
- **PCB:** 2-layer FR-4, 0805/1206 components
- **Automation:** Full pipeline from text → simulation → KiCad → manufacturing files


## License
MIT