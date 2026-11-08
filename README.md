# 🏢 Enterprise Office Network & CCTV Infrastructure Design

[📄 Download Full Technical Report (PDF)](./Office-Security-System%5F20261109%5F1.pdf)

---

## 📌 Project Overview
This project presents a complete **Wi-Fi 5GHz Heatmap Optimization**, **CCTV Security Surveillance Design**, and **Structured Cabling Topology** for a modern office layout. The entire architecture is designed using the **Reyee / Ruijie Ecosystem** to ensure 100% 5GHz signal coverage and zero camera blind spots.

---

## 🛠️ Hardware Bill of Materials (BOM)

| Device Type | Model Name | Quantity | Role / Purpose |
| :--- | :--- | :---: | :--- |
| **Wi-Fi 6 AP** | Reyee RG-RAP2260(G) | 1 | High-density Central Open Workspace |
| **Wi-Fi 5 AP** | Reyee RG-RAP2200(E) | 5 | Conference Room, Executive Cabins, Lounge |
| **PoE Switch** | Reyee RG-NBS3100-24GT4SFP-P-V2 | 1 | 24-Port Managed PoE+ Switch (Server Room) |
| **Bullet CCTV**| 4MP Outdoor/Entrance IP Camera | 2 | Main Entrance & Elevator Lobby (Facial Capture) |
| **Dome CCTV**  | 4MP/2MP Indoor Dome IP Camera | 9 | Open Desks, Conference, Server Room, Corridor |
| **Network Cable**| Cat6 UTP Cable | 2 Boxes | Overhead Structured Cabling for 17 Endpoints |

---

## 📡 5 GHz Wi-Fi Heatmap Optimization
- **Total AP Count:** 6 Units.
- **Strategy:** APs are placed inside key enclosed rooms to prevent 5GHz attenuation through concrete/partition walls.
- **Result:** Achieved **100% Uniform Green Coverage** across the entire floor plan.

![Wi-Fi 5GHz Heatmap](./Screenshot%202026-11-09%20021833.png)

---

## 📹 CCTV Surveillance Layout
- **Total Cameras:** 11 Units (2 Bullet + 9 Dome).
- **Key Coverage:** Main entrance (Facial Recognition), open workspace corners (Cross-angle), conference room, corridors, and central server rack.

![CCTV Layout](./Screenshot%202026-11-09%20021853.png)

---

## 🔌 Structured Cabling & Switch Topology
- **Cable Routing:** All 17 PoE endpoints (6 APs + 11 Cameras) route via overhead ceiling conduits directly to the central rack in the Server Room.
- **Switch Capacity:** The **RG-NBS3100-24GT4SFP-P-V2 (24-Port PoE+)** switch handles all 17 PoE devices while leaving **7 spare ports** for NVR, Router Gateway, and future expansion.

![Structured Cabling Topology](./Screenshot%202026-11-09%20021904.png)

---

### 👨‍💻 Project Author
- **Designed & Created by:** Mahir Shahrier Mugdho
- **Tools Used:** Ruijie / Reyee Cloud Planner
