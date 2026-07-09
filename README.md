## 📌 Simulation Note

Since Wokwi and Tinkercad do not provide a built-in pH sensor, a **potentiometer** is used to simulate pH values during testing.

The potentiometer acts as a virtual pH sensor, allowing users to manually adjust the pH value. The system interprets the potentiometer reading as the water's pH level.

### Simulation Behavior

- Users manually adjust the potentiometer to simulate different pH values.
- When the simulated pH value exceeds **8.5**, the system:
  - 🔴 Blinks the warning LED
  - 🔊 Activates the buzzer
- If the pH value remains within the safe range, the system continues normal monitoring.

### Additional Sensors

The complete Smart Water Monitor is designed to support multiple water quality parameters, including:

- 💧 pH Sensor (simulated using a potentiometer)
- 🌊 TDS Sensor
- 🌫 Turbidity Sensor
- 🌡 Water Temperature Sensor

> **Note:** In the simulation, only the pH sensor is demonstrated using a potentiometer due to the limited availability of water quality sensors in Wokwi and Tinkercad. The project architecture is designed to integrate real sensors in a physical prototype.
