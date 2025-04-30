# Light Scheduler

A smart web-based tool to automate and control light schedules using WebSocket, MQTT, and Arduino — ideal for smart homes and IoT systems.

## Features

- Schedule ON and OFF times for lights through a clean web interface
- Real-time updates via WebSocket communication
- Seamless MQTT support for Internet of Things (IoT) integration
- Arduino-compatible for direct physical device control

[UI Diagram](./image.png)  
[Terminal running](./terminal.png)

## Setup Instructions

### Prerequisites

- Python 3.7 or higher
- Node.js (used for hosting the frontend)
- Mosquitto MQTT broker
- Arduino IDE (to program your Arduino board)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/PRINCESS-N/light_controller.git
   cd light-controller
