# Smart City Planner 🏙️

A web-based Smart City Planner that uses C++ algorithms and interactive maps to support smart facility placement, route optimization, and emergency and disaster planning.

## 📌 Project Overview

Smart City Planner is an academic project designed to demonstrate how Data Structures and Algorithms can solve real-world urban planning problems. It combines a web-based interface with a C++ algorithm engine and interactive OpenStreetMap visualization.

## 🚀 Main Modules

### 1. Smart Facility Placement
- Identify suitable locations for hospitals, schools, fire stations, and other public facilities.
- Evaluate candidate locations based on demand, accessibility, and distance.
- Rank and recommend suitable facility locations.

### 2. Smart Route Optimizer
- Find efficient routes between selected city locations.
- Calculate shortest paths using Dijkstra's algorithm.
- Handle road closures and recalculate alternative routes.

### 3. Emergency & Disaster Planner
- Manage incidents and identify risk zones.
- Prioritize emergencies based on severity and affected population.
- Plan evacuation routes to safe destinations while avoiding blocked roads.

## 🛠️ Technology Stack

- **Frontend:** HTML, CSS, JavaScript
- **Map Library:** Leaflet
- **Map Data:** OpenStreetMap
- **Backend:** C++17
- **Build System:** CMake
- **API Framework:** Crow
- **Data Storage:** JSON / CSV
- **Version Control:** Git & GitHub

## 🧠 Data Structures & Algorithms

- Graphs (Adjacency List)
- Dijkstra's Algorithm
- BFS and DFS
- Priority Queue
- Greedy Algorithms
- Sorting and Searching
- Hash Maps
- Vectors and Queues

## 🏗️ System Architecture

The project uses a web interface connected to a C++ algorithm engine through a lightweight HTTP API.

JavaScript sends requests to the C++ backend, which processes them using the implemented algorithms and returns results in JSON format. Leaflet displays routes, facilities, incidents, and other geographic information on the map.

## 📂 Project Structure

```text
SmartCityPlanner/
│
├── frontend/
│   ├── index.html
│   ├── css/
│   └── js/
│
├── backend/
│   ├── CMakeLists.txt
│   └── src/
│
├── core/
│   ├── graph/
│   ├── algorithms/
│   ├── models/
│   └── modules/
│
├── data/
│   ├── locations.json
│   ├── roads.json
│   ├── facilities.json
│   └── incidents.json
│
└── tests/
```

## 🎯 Project Objectives

- Apply Data Structures and Algorithms to real-world problems.
- Develop an interactive city-planning interface.
- Optimize routes using graph algorithms.
- Support facility placement and emergency planning.
- Integrate C++ algorithms with web technologies.

## ⚠️ Project Scope

This project is an academic prototype designed for demonstration and decision-support purposes. It does not provide live traffic information or replace professional emergency services.

---

**Smart City Planner | C++ | DSA | Web Development | Interactive Maps**
