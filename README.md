# Verilog Temperature Alert System

This project implements a simple **temperature alert system** using Verilog. The system monitors an input temperature and triggers an alert when it crosses a threshold.

## Files

- `temp_alert.v` — RTL module that contains the temperature alert logic.
- `tb_temp_alert.v` — Testbench used to simulate and verify the design.
- `temp_out.unknown` — Output file (e.g., waveform or compiled result — clarify if needed).

## Features

- Compares input temperature to a preset threshold.
- Outputs an alert signal if the temperature exceeds the limit.
- Designed and tested using Verilog.

## How to Simulate

You can simulate the design using a Verilog simulator like:
- ModelSim
- Icarus Verilog (`iverilog`)
- XSIM (from Vivado)

### Example using Icarus Verilog:

```bash
iverilog -o temp_alert_sim temp_alert.v tb_temp_alert.v
vvp temp_alert_sim


Use GTKWave to view waveform output (if you generate .vcd).

Author
Avinash Kurella

GitHub: avinash-150

yaml
Copy
Edit

---

If you want to add simulation output or waveform images later, you can update the README with a screenshot using:

```markdown
![Waveform Output](path/to/image.png)
