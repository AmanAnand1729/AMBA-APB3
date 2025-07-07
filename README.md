# AMBA-APB3
RTL design for AMBA APB3 bus in Verilog with configurable master, multiple slaves, and testbench.

# AMBA APB3 Bus — Verilog Implementation

This repository provides a simple and clear Verilog implementation of the **AMBA APB3 (Advanced Peripheral Bus version 3)** protocol.  
It includes a basic APB3 master, multiple slaves with address decoding, byte strobes, protection control, and a self-checking testbench.

---

## 📌 Features

- ✅ **Conforms to AMBA 3 APB3 Specification**
- ✅ Supports `PSTRB` (byte lane strobe) for partial writes
- ✅ Supports `PPROT` protection signals
- ✅ Single-cycle ready signaling
- ✅ Multiple slaves with simple address decoder
- ✅ Error flagging via `PSLVERR`
- ✅ Clean, parameterizable Verilog code
- ✅ Self-checking testbench with read/write transactions and error check

---
## 📖 References

- **AMBA 3 APB Protocol Specification:** [ARM IHI 0024B](https://developer.arm.com/documentation/ihi0024/latest)
- For more details on APB3 signals and timing, refer to the official ARM documentation.
