# Small Hospital Network Setup

This repository contains a Cisco Packet Tracer network topology design for a small hospital environment. The project simulates network connectivity across multiple hospital departments to ensure secure and efficient data communication.

## 📊 Network Topology Diagram

![Hospital Network Topology](topology.png)
*(Note to user: Replace 'topology.png' with your actual screenshot filename once uploaded)*

## 🏢 Hospital Departments & Devices

The network is segmented into distinct logical zones representing the hospital infrastructure:

*   **Reception (Pink Zone):** 
    *   2 Desktop PCs (`PC0`, `PC1`) managing patient check-ins and administrative tasks.
*   **Doctor 1 (Magenta Zone):** 
    *   1 Laptop (`Laptop0`) and 1 Network Printer (`Printer0`) for medical records and prescriptions.
*   **Doctor 2 (Brown Zone):** 
    *   1 Laptop (`Laptop1`) and 1 Network Printer (`Printer1`) for medical records and prescriptions.
*   **Clinic (Blue Zone):** 
    *   2 Desktop PCs (`PC2`, `PC3`) dedicated to clinical operations and patient data access.
*   **Server Room (Yellow Zone / Core):**
    *   **1 Central Switch (Cisco 2960):** Acts as the central connection point linking all departments together.
    *   **1 Router (Cisco 2911):** Handles routing for external connectivity and inter-department communication.
    *   **1 Local Server:** Provides centralized services (e.g., DNS, DHCP, or Web Services) across the hospital.

## 🛠️ Core Features Implemented

*   **Centralized Connectivity:** All department endpoints converge at a central Layer 2 switch.
*   **Gateway Routing:** A Cisco 2911 router is configured to manage network boundaries and traffic routing.
*   **Shared Resources:** Shared printers and a central server are accessible by authorized hospital staff.
*   **Visual Segmentation:** Clear color-coded areas isolate and identify distinct functional departments.

## 🚀 How to Run the Project

1. Download and install **Cisco Packet Tracer**.
2. Download the `.pkt` file from this repository: `Small Hospital Network Setup.pkt`.
3. Open Packet Tracer, go to `File > Open`, and select the downloaded file.
4. Use the **Simulation** or **Realtime** tabs to test ping connectivity between the PCs, Laptops, and Servers.
