# NEC Electrical Calculator

A single-file, offline-capable field calculator for electricians based on the **NFPA 70 National Electrical Code (NEC), 2023 Edition**.

Designed for use on phones, tablets, and laptops — no internet connection or installation required.

---

## Features

### Conduit Fill
- EMT, RMC, and PVC conduit types
- Trade sizes ½" through 6"
- THHN, THWN-2, XHHW, RHH/RHW, and bare conductors
- NEC Chapter 9, Tables 1, 4, and 5

### Wire Ampacity
- Copper and aluminum conductors, 14 AWG – 750 kcmil
- 60/75/90°C insulation and terminal ratings (NEC 110.14(C))
- Ambient temperature correction — NEC Table 310.15(B)(1)(1)
- CCC bundle derating — NEC Table 310.15(C)(1)
- Parallel conductor sets (NEC 310.10(H))
- Exportable PDF report

### Voltage Drop
- Single-phase and three-phase circuits
- Copper and aluminum conductors
- Target voltage drop percentage (1–5%)
- Minimum conductor size recommendation

### Generator Sizing
- Single-phase and three-phase generators
- NEC 445.13 terminal conductor sizing (115% nameplate)
- Downstream OCPD override — NEC 240.4 (all standard sizes 15A–1200A)
- Full ambient temp derating and CCC bundle derating
- Automatic parallel conductor solver (up to 6 sets, NEC 310.10(H))
- Exportable PDF report

### Grounding
**EGC — NEC 250.122**
- Equipment Grounding Conductor sizing by OCPD rating
- Proportional upsizing per NEC 250.122(B)

**GEC — NEC 250.66**
- Grounding Electrode Conductor sizing by largest service-entrance conductor
- Size caps for concrete-encased electrodes (250.66(B)), ground rings (250.66(C)), and rod/pipe/plate electrodes (250.66(A))

### Reference Tables
- NEC Table 310.12 ampacity tables
- NEC 240.6(A) standard OCPD sizes
- Conduit fill reference

---

## Usage

1. Download `nec-electrical-calculator.html`
2. Open it in any modern browser (Chrome, Safari, Firefox, Edge)
3. No server, no install, no internet required
4. Use **Export PDF** on any tab to print or save a report

---

## NEC Code References

| Section | Topic |
|---|---|
| NEC 445.13 | Generator terminal conductor ampacity |
| NEC 240.4 / 240.6(A) | Conductor protection / Standard OCPD sizes |
| NEC 310.10(H) | Parallel conductors — min 1/0 AWG |
| NEC Table 310.12 | Conductor ampacity |
| NEC Table 310.15(B)(1)(1) | Ambient temp correction factors |
| NEC Table 310.15(C)(1) | CCC bundle adjustment factors |
| NEC 110.14(C) | Terminal temperature limitations |
| NEC 250.122 / Table 250.122 | Equipment Grounding Conductor sizing |
| NEC 250.66 / Table 250.66 | Grounding Electrode Conductor sizing |
| NEC Chapter 9 | Conduit fill calculations |

---

## Disclaimer

This tool is intended as a field reference aid. All calculations should be verified by a licensed electrician or engineer. Local amendments to the NEC may apply. The authors assume no liability for errors or omissions.

---

## License

MIT License — free to use, modify, and distribute.
