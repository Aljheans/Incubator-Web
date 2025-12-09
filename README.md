**IoT Incubator Monitor**
A lightweight real-time monitoring web dashboard for your IoT Incubator. Built using HTML, CSS, and JavaScript with WebSocket communication to display live sensor data and camera feed from an ESP32-CAM device.


**Features**
    Real-time updates via WebSocket
    Displays temperature, humidity, and water level readings
    Shows live camera image feed from ESP32-CAM
    Auto reconnects when connection is lost
    Displays last updated time for all readings


**System Overview**
    1. ESP32-CAM + Sensors → WebSocket Server → Web Dashboard
    2. The ESP32-CAM reads sensor data (temperature, humidity, water level).
    3. It sends JSON data through WebSocket.
    4. The Web Dashboard and Mobile Application listens for updates and displays them live.
