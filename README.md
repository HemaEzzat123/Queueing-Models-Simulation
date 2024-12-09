# Queueing System Simulation

A simulation project designed to model and analyze various queueing systems. This tool simulates real-world queueing scenarios, providing insights into system performance and customer behavior under different configurations.

### **Features**
- Simulation of common queueing models:
  - **MM1**: Single server, unlimited capacity.
  - **MM1K**: Single server, limited capacity.
  - **MMC**: Multiple servers, unlimited capacity.
  - **MMCK**: Multiple servers, limited capacity.
- Dynamic generation of:
  - **Interarrival Times** (based on exponential distribution).
  - **Service Times** (based on exponential distribution).
- Key performance metrics:
  - **L**: Average number of customers in the system.
  - **Lq**: Average number of customers in the queue.
  - **W**: Average time a customer spends in the system.
  - **Wq**: Average time a customer spends in the queue.
  - **Blocking Probability** (for limited-capacity systems).
- Visual representation of:
  - Customer arrivals and departures.
  - System state over time.

---

## **Getting Started**

Follow these instructions to set up and run the simulation locally.

### **Prerequisites**
- A modern web browser (e.g., Chrome, Firefox, Edge).
- (Optional) Node.js, if using advanced tools.

### **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Queueing-Simulation.git
   cd Queueing-Simulation
