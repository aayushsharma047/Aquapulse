# Aquapulse Smart Irrigation System

![Aquapulse Logo](/Screenshots/logo.png)

Aquapulse is an intelligent irrigation system designed to optimize water usage in agriculture. It utilizes Arduino and NodeMCU microcontrollers to collect and manage data efficiently.

## System Architecture

1. **Arduino Setup:**
   - Collects moisture levels from Soil Moisture Sensors.
   - Commands the irrigation pump based on moisture levels.
   - Transfers data through serial communication.

2. **NodeMCU Wireless Communication:**
   - Communicates wirelessly with Arduino.
   - Sends data to the BackEnd Flask server.

3. **BackEnd Flask Server:**
   - Receives and stores data in the database.
   - Handles user requests from the Front End portal.

4. **Database:**
   - Stores collected data for historical analysis.

5. **Front End User Portal (React):**
   - Developed using React for a user-friendly interface.
   - Displays real-time and historical data visualizations.
   - Allows users to reconfigure microcontroller operations.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/username/aquapulse.git

2. Setup Sensors and Arduino:
    Connect water pump, soil moisture sensors, transistor and then configure the Arduino Microcontroller.

3. Configure NodeMCU:
    Set up NodeMCU for wireless communication with the backend server.

4. Backend Setup:
    Install required dependencies and set up the Flask server.

5. Frontend Setup:
    Install dependencies for the React user portal

6. Run the System:
    Start Arduino, NodeMCU, Flask server, and React portal. Make sure the assembly is as given below

![Assembly](/Diagrams/Assembly Diagram.png)
