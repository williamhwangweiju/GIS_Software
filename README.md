# Swift Map

Swift Map is an interactive Geographic Information System built in C++ for **ECE297: Software Design and Communication** at the University of Toronto, Winter 2024.

The project brings together geographic data processing, interactive map visualization, driving directions, and courier route optimization. It was developed across five milestones, progressing from development tools and data queries to a complete mapping application.

## Features

### Geographic Data and Search
- Loads city datasets derived from OpenStreetMap through course-provided database APIs.
- Supports queries about streets, intersections, points of interest, and geographic features.
- Finds intersections from street names, including partial-name searches.
- Computes geographic distances, street lengths, and estimated travel times.

### Interactive Map Visualization
- Displays streets, buildings, parks, waterways, and points of interest.
- Supports panning, zooming, and selecting intersections to view location information.
- Distinguishes major and minor roads and indicates one-way street directions.
- Loads different supported city maps without recompilation.

### Driving Routes and Directions
- Finds routes between intersections selected through street-name searches or mouse clicks.
- Minimizes modeled travel time while respecting one-way streets and accounting for speed limits and turn penalties.
- Highlights the selected route and provides step-by-step driving directions.
- Gives feedback for invalid searches and unavailable routes.

### Courier Delivery Planning
- Plans routes containing multiple pickup and drop-off locations.
- Ensures each package is collected before it is delivered.
- Starts and finishes at the same courier depot.
- Uses heuristic optimization to balance route quality with computation time.

## Project Milestones

| Milestone | Focus |
| --- | --- |
| **0 — Development Tools** | C++ development, Git collaboration, debugging, and memory-error detection. |
| **1 — Geographic Data APIs** | Efficient map queries, geographic calculations, and functional and performance testing. |
| **2 — Interactive Visualization** | Map rendering, location search, and interface design. |
| **3 — Pathfinding and Directions** | Travel-time routing, route visualization, and driving directions. |
| **4 — Traveling Courier** | Delivery sequencing and route optimization under pickup, drop-off, and depot constraints. |

## Technologies and Development

**Language:** C++  
**Graphics:** EZGL  
**Map data:** OpenStreetMap through course-provided APIs  
**Development environment:** Linux, Git, GDB, and Valgrind

Development combined incremental feature integration, automated correctness and performance tests, memory debugging, and interface demonstrations. A multithreaded rendering pipeline improved interface responsiveness.

## Source Code Availability

Source code and detailed implementation materials are not publicly available. The course prohibits sharing these materials to prevent plagiarism and protect the integrity of future students’ assignments.

This repository provides a high-level portfolio overview of the project’s functionality, scope, and development process.
