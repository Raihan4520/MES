# Microprocessor and Embedded Systems (MES) Repository

This repository contains the final project for the **Microprocessor and Embedded Systems** course at **American International University - Bangladesh (AIUB)**. The project simulates a water quality monitoring system using Arduino and several sensors to measure important water parameters such as pH, temperature, turbidity, and dissolved oxygen. The project is implemented in a software simulation environment.

### Course Information
For more details on the course, refer to the [AIUB Undergraduate Course Catalog](https://www.aiub.edu/faculties/fst/ug-course-catalog).  
*Note: Search for "Microprocessor and Embedded Systems" for specific course information.*

## Water Monitoring System Using Arduino - Final Project (Simulation)

### Project Overview

The project focuses on designing a low-cost, real-time water quality monitoring system using Arduino. It measures key parameters that determine the quality of water, which can help in preventing pollution in remote lakes, rivers, and coastal areas. This system uses various sensors to monitor pH, temperature, turbidity, and dissolved oxygen levels.

### Key Features:
- **Microcontroller**: Arduino Uno
- **Sensors Used**: pH sensor, temperature sensor (DS18S20), turbidity sensor, dissolved oxygen sensor
- **Display**: 16x2 LCD
- **Monitoring Parameters**:
  - pH Level: Determines the acidity or alkalinity of water.
  - Temperature: Monitors the water temperature.
  - Turbidity: Measures the cloudiness or clarity of water.
  - Dissolved Oxygen (DO): Determines the amount of oxygen dissolved in water.

## Simulation Details

This project is fully implemented using Arduino simulation. The code reads the sensor data, processes it, and outputs the water quality conditions based on predefined safe ranges.

- **pH Range**: 6.5 - 8.5 (Safe)
- **Temperature Range**: 18°C - 35°C (Safe)
- **Turbidity Range**: 0 NTU - 5 NTU (Safe)
- **Dissolved Oxygen**: 6 mg/L - 9 mg/L (Safe)

If the values exceed or fall below the safe ranges, the LCD screen displays corresponding warnings.

## Project Components

1. **Arduino Uno**: The microcontroller used to interface with the sensors and LCD.
2. **Sensors**:
   - **pH Sensor**: Measures the pH level of the water.
   - **Temperature Sensor (DS18S20)**: Measures the water temperature.
   - **Turbidity Sensor**: Measures the clarity of the water.
   - **Dissolved Oxygen Sensor**: Measures the oxygen content in the water.
3. **16x2 LCD Display**: Displays real-time water quality data.

## How to Run the Simulation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Raihan4520/MES.git
2. Install Required Software:
   - Install Arduino IDE for code simulation.
   - Install Proteus for circuit simulation (optional, if circuit simulation is needed).
3. Load the Project:
   - Open the Arduino IDE and load the .ino file provided in the /src directory.
   - Connect the virtual sensors in the simulation software (e.g., Proteus) to simulate real-time data.
4. Run the Simulation:
   - Upload the code to the virtual Arduino board in the simulation environment.
   - Observe the results on the LCD screen as per the conditions of the sensors.

## Conclusion

This project demonstrates a practical water quality monitoring system, which can be used in various real-world scenarios with minor modifications. The simulation-based approach makes it accessible for further experimentation and testing.

## Contact

If you have any questions or suggestions, feel free to reach out through the repository's issues or contact me directly.
