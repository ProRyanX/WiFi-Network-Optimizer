# Campus Wi-Fi Network Optimizer  
*A Graph-Based Network Design & Optimization Tool*

---

## 📌 Overview
The **Campus Wi-Fi Network Optimizer** is a graph-based system designed to analyze, optimize, and visualize campus Wi-Fi infrastructure. It ensures reliable connectivity using classical **Data Structures & Algorithms (DSA)**, including:

- **Kruskal’s & Prim’s Algorithms** → Minimum Spanning Tree (MST)  
- **Dijkstra’s Algorithm** → Shortest latency path  
- **BFS & DFS** → Connectivity and fault tolerance  

The **backend is implemented in C**, while the **frontend uses HTML, CSS, and JavaScript**, replacing the earlier Tkinter-based GUI.

---

## 🎯 Key Features

### 🔹 Algorithmic Optimization
- MST construction using Kruskal and Prim  
- Shortest path calculation using Dijkstra  
- Connectivity verification via BFS and DFS  

### 🔹 Network Design Insights
- Total cabling & installation cost estimation  
- Optimized network topology visualization  
- Fault tolerance and connectivity check  
- Tested using real-world campus layout data  

### 🔹 Modern Frontend
- Web-based GUI built using:
  - **HTML** (structure)
  - **CSS** (styling)
  - **JavaScript** (logic + graph visualization)
- Displays:
  - Raw graph  
  - MST  
  - Shortest path  
  - Node/edge weights  

### 🔹 Backend
- C implementation for:
  - Graph creation using adjacency lists  
  - Weighted edge insertion  
  - MST algorithms  
  - Shortest path algorithms  
  - Connectivity algorithms  
  - User authentication via text file  

---

## 🛠️ Technologies Used

### Backend
- C (Algorithms & DS)
- File handling for authentication + graph inputs  
- Adjacency list graph implementation  

### Frontend (Updated)
- HTML  
- CSS  
- JavaScript  
- Canvas/SVG for graph rendering  

---

## 🚀 How It Works

### 1️⃣ Data Input
- User enters buildings, distances, cable costs, and connections via the GUI.
- Data is sent to the C backend for processing.

### 2️⃣ Graph Construction
- Backend builds a weighted adjacency list representing the campus layout.

### 3️⃣ Algorithm Execution
- **MST** → Minimum cabling cost  
- **Dijkstra** → Optimal latency path  
- **BFS/DFS** → Connectivity verification  

### 4️⃣ Output & Visualization
- Frontend receives results and displays:
  - Raw input graph  
  - MST  
  - Shortest path  
  - Connectivity results  

---

## 📊 Real-World Testing Dataset
The project was tested using a real campus environment, including buildings such as:

- CSIT Block  
- B-Tech Block  
- Civil Block  
- Library  
- Admin Block  
- Auditorium  
- Main Gate  
- Cafeteria  
- Architecture Block  
- Law Block  
- Basketball Court  

Data included realistic **distances**, **cable costs**, and **signal-related parameters**.

---

## 🔥 Major Achievements

- Graph input system fully functional  
- MST (Kruskal) implemented and validated  
- Shortest path using Dijkstra  
- Connectivity verification using BFS/DFS  
- Graph visualization integrated with frontend  
- User authentication module completed  
- Web-based GUI integrated with backend  
- Full system tested with real campus data  

---

## 📦 Deliverables

- Fully working Wi-Fi network optimizer application  
- Browser-based GUI (HTML/CSS/JS)  
- C backend for all algorithmic computations  
- Visualization of MST, shortest path, and raw graph  
- Documentation and project report  
- Sample demo outputs and screenshots  

---
---

## Contributor

**Vrunda Kamboj**  
- Implemented BFS-based connectivity checking between campus nodes  
- Developed Dijkstra’s shortest path logic for optimized routing  
- Worked on graph representation and algorithm integration  
- Collaborated via GitHub in a team-based development environment



## License

This project is academic and intended for educational use only.
