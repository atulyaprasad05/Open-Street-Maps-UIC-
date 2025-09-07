# 🗺️ OpenStreetMaps Pathfinding Project (CS 251 - Spring 2025)

This project builds a graph-based pathfinding application using real-world data from OpenStreetMaps (OSM). It parses JSON-formatted map data, constructs a weighted, undirected graph, and implements Dijkstra’s algorithm to compute shortest paths between buildings on the UIC campus.

## 🚀 Features

- Parses OSM data from JSON format
- Constructs a directed, weighted graph using adjacency lists
- Adds building nodes and connects them to nearby waypoints
- Implements Dijkstra’s algorithm with building avoidance
- Provides both terminal and web-based interfaces for pathfinding


## 🖥️ Running the Application

### 🔤 Text Interface
```bash
make osm_main
make run_main
```

### 🌐 Web Interface
```bash
make osm_server
make run_server
Navigate to http://localhost:8000 to visualize paths on a map.
```


## 📚 Dependencies
- nlohmann/json (header-only JSON parser)
- cpp-httplib (header-only HTTP server)


## 🛡️ Academic Integrity
This project is part of CS 251 at UIC and subject to academic integrity policies. Do not share or post solutions publicly.
