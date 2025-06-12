Smart Tissue Culture Lab - GUI Software

Frontend Framework: React.js

INSTRUCTIONS TO RUN:
---------------------
1. Ensure Node.js and npm are installed.
2. Navigate to the GUI folder:
   cd GUI
3. Install dependencies:
   npm install
4. Run the app locally:
   npm start


FEATURES:
---------
- Connects to broker.hivemq.com via MQTT.js
- Publishes control messages in JSON format (e.g., { fan: "on" })
- Displays LED status indicators based on topic messages
- Sends email alerts on motion detection using EmailJS

CODE STRUCTURE:
---------------
- App.js: Main entry point with UI and logic
- mqttService.js: Manages MQTT connection
- EmailAlert.js: Handles EmailJS integration
- components/: UI components (buttons, cards, etc.)
