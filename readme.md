This project demonstrates how to control **four relays** using an **ESP8266 (NodeMCU)** and the **Arduino IoT Cloud**. Relays can be toggled **locally** via physical switches or **remotely** through a cloud-based dashboard.



- 🛠️ **Local Control**: Toggle relays with connected switches.
- 🌐 **Remote Control**: Use the Arduino IoT Cloud dashboard to manage relays online.
- 📶 **WiFi Feedback**: An LED indicates WiFi connectivity status.
- 🔄 **Synchronized State**: Updates from manual and remote operations are always in sync.

---

## 🛒 **Hardware Requirements**
1. **ESP8266 (NodeMCU)**
2. **4-Channel Relay Module**
3. **Push Buttons or Toggle Switches**
4. **Power Supply**
5. **Connecting Wires**

---

## 🖼️ **Circuit Diagram**
![alt_text, width="200"](/image/CircuitDiagram.JPG)
![alt_text, width="100"](/image/Circuit_Diagram2.JPG)
![alt_text, width="100"](/image/PCB_3d.JPG)

### 🧩 **Connections**
- **Relays**:
  - Relay 1: GPIO 5 (D1)
  - Relay 2: GPIO 4 (D2)
  - Relay 3: GPIO 15 (D8)
  - Relay 4: GPIO 13 (D7)
- **Switches**:
  - Switch 1: GPIO 0 (D3)
  - Switch 2: GPIO 2 (D4)
  - Switch 3: GPIO 14 (D5)
  - Switch 4: GPIO 12 (D6)

