# 3-Floor Elevator Controller (Digital Logic Design)

This project simulates a 3-floor elevator system using digital logic gates and components in Logisim. It models the elevator's floor selection, movement logic, and display outputs for an embedded systems or computer organization course.

## 🛠 Features
- Floor selection logic from Ground (00) to 3rd Floor (11)
- Up, Down, and Stop control mechanism
- Binary to decimal conversion for floor display
- Two elevator circuits for bidirectional or redundant control
- Visual output via 7-segment displays showing current floor

## 🧩 Components Used
- Logic gates: AND, OR, NOT, XOR
- Decoders and Multiplexers
- Binary comparators
- Flip-flops (optional for future memory handling)
- 7-segment display decoders
- Custom control logic for elevator direction

## 🚀 How It Works
- The elevator receives a 2-bit binary input representing the requested floor.
- Decoders and logic gates determine movement direction (Up/Down).
- Displays show the current floor in decimal format using 7-segment modules.
- Additional logic handles Stop conditions and input overrides.

## 📷 Preview
![Elevator Circuit Diagram](./Screenshot.png)  
> Screenshot of the full elevator logic circuit in Logisim

## 🧪 How to Run
1. Open the `.circ` file in [Logisim](http://www.cburch.com/logisim/) or your preferred digital logic simulator.
2. Use the input pins to simulate floor requests.
3. Observe the 7-segment displays and control LEDs (Up, Stop, Down).
4. Test each floor selection and ensure the circuit behaves as expected.

## 🧠 Concepts Applied
- Digital circuit design
- Combinational logic
- Floor-level encoding/decoding
- Control logic and state transitions
- Binary conversion

## 📜 License
This project is for academic and learning purposes. You’re free to use or modify it with credit.

---


