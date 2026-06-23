
# automatic-plant-irrigation-system

This project is a fully automatic plant irrigation system designed to water plants only when needed. The system continuously monitors soil moisture levels using a soil moisture sensor and automatically activates a DC water pump when the soil becomes dry.

| Component | Purpose | Qty | Cost (USD) | Distributor |
|-----------|---------|-----|------------|-------------|
| 10k Potentiometer | Adjusts sensitivity | 1 | $0.21 | Maker Bazar |
| IRFZ44N MOSFET | Switches the water pump on and off | 1 | $0.23 | Maker Bazar |
| 10k Through-Hole Resistor | Current limiting and biasing | 2 | $0.32 | Maker Bazar |
| 1N4007 Diode | Protects the circuit from reverse voltage and back EMF | 1 | $0.12 | Maker Bazar |
| 8-Pin IC Socket | Connects the IC to the PCB | 1 | $0.10 | Maker Bazar |
| LM358 IC | Amplifies and processes the sensor signal | 1 | $0.10 | Maker Bazar |
| 12V Water Pump | Pumps water to the plant | 1 | $1.90 | Maker Bazar |
| 2-Pin Screw Terminal Block | Connects external wires | 3 | $0.26 | Maker Bazar |
| Custom PCB | Connects all components together | 1 | $4.00 | JLCPCB |
| Delivery Charges | Shipping costs | 2 | $8.70 | Various |

Unlike many irrigation projects, this design does not use a microcontroller. Instead, it relies on an analog control circuit with a MOSFET for switching the pump, making the system simple, reliable, and power-efficient. The moisture threshold can be adjusted to suit different types of plants and soil conditions.

<img width="342" height="362" alt="Screenshot 2026-04-18 133606 - Copy" src="https://github.com/user-attachments/assets/fb812f92-c474-4378-ac0b-a390aa909d71" />
<img width="364" height="416" alt="Screenshot 2026-04-18 133546" src="https://github.com/user-attachments/assets/c4300346-5c1f-462e-8b4b-5448f7e6c3c4" />
<img width="383" height="203" alt="Screenshot 2026-04-18 133625" src="https://github.com/user-attachments/assets/3e4db158-0415-4038-8023-f46452e60d45" />
