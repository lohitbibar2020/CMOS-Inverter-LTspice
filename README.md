# CMOS Inverter LTspice Simulation

## 📌 Project Description
This project demonstrates the **CMOS Inverter Circuit** simulation using **LTspice**. A CMOS inverter is a fundamental digital logic gate used in various electronics applications. The project includes **circuit schematics, SPICE netlist files, and simulation results**, showcasing the inverter's behavior.

## ⚡ Key Features
- ✅ **CMOS Technology**: Uses NMOS and PMOS transistors for switching.
- ✅ **Simulation in LTspice**: Provides `.asc` schematic and `.cir` netlist files.
- ✅ **Waveform Analysis**: Observes voltage transitions in an inverter circuit.
- ✅ **LTspice-Compatible Files**: Ready-to-run simulations for students and researchers.

## 🔧 Circuit Details
- **Components Used**: NMOS & PMOS transistors, power supply, load resistor.
- **Operating Voltage**: 5V DC.
- **Functionality**:
  - When **input = HIGH (1)** → Output = **LOW (0)**.
  - When **input = LOW (0)** → Output = **HIGH (1)**.
- **Applications**:  
  - Used in **logic circuits** for switching.
  - Basis for designing **logic gates and microprocessors**.

## 💻 How to Use the Files
1. **Download** the `.asc` schematic file from this repository.
2. Open the file in **LTspice**.
3. Run a **Transient Analysis** (`.tran 10u`) to observe the switching behavior.
4. View the waveform results showing **input-output transitions**.

## 📊 Simulation Results
- The output waveform shows the inverter behavior (**high input → low output** and vice versa).
- The simulation verifies **CMOS switching operation** under different voltage levels.
- **Example Output**:  
  ![Simulation Waveform](your-image-link)  *(Replace with the actual image link you uploaded on GitHub)*

## 📁 Files Included in the Repository
| File Name        | Description |
|-----------------|-------------|
| `cmos_inverter.asc` | LTspice schematic file |
| `cmos_inverter.cir` | Netlist file for SPICE simulation |
| `cmos_waveform.raw` | Output waveform file |
| `README.md` | Project documentation |

---

### 🎯 Conclusion
This project provides a **practical LTspice simulation** of a CMOS inverter, demonstrating its **digital logic switching characteristics**. It serves as a useful reference for **students, researchers, and engineers** interested in **CMOS logic design**. 🚀
