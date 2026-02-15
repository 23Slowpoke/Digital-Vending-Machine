# Digital-Vending-Machine

### 🛠️ Technologies
**Tool:** NI Multisim  
**Concepts:** Digital Logic Design, Sequential Logic, Two's Complement, Multiplexers (MUX).
### 📋 Project Overview
This project simulates the digital control logic of a Vending Machine. It handles product selection, payment validation, and change calculation using purely hardware logic gates (no software code).

**Key Engineering Features:**
* **Dynamic Selection:** Used **Multiplexers (MUX)** to route user inputs based on product choice.
* **Arithmetic Unit:** Implemented **Two's Complement logic** to perform binary subtraction (Input - Price) for calculating change.
* **Synchronous Logic:** Utilized clock cycles to manage the state of the transaction and validate inputs sequentially.
* **Validation:** The system prevents dispensing if funds are insufficient.
