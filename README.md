# SmartRide
🚖 SmartRide: Next-Gen Intelligent Cab Sharing
SmartRide is an advanced cab-sharing system that leverages graph algorithms for optimized routing, intelligent ride matching, and customizable fare splitting. It is built with scalability in mind and is designed to provide a smart, cost-effective, and efficient transportation solution.


🎯 Objective
To build an intelligent ride-sharing system that:
Calculates the shortest path between pickup and drop locations.
Matches riders based on proximity to optimize shared rides.
Splits fares dynamically based on ride distance.
Lays the foundation for a full-stack application with React and Node.js integration.


🛠 Technology Stack
Layer	Technology
Backend	TypeScript
Frontend	React.js (Planned) + Tailwind CSS
Middleware	Node.js (Planned)
Data APIs	Placeholder for Mapbox/OpenTraffic (Planned)


🚀 Features
Graph Optimization:
Implemented Dijkstra’s algorithm in TypeScript to compute shortest paths in a city graph.
Ride Matching:
CLI-based prototype that matches ride requests based on source and destination proximity.
Fare Splitting:
Console application to dynamically calculate fare based on shared ride distance.
Modular Design:
Backend logic is modular and structured for easy integration with a frontend interface.


📊 Technical Progress
✅ Dijkstra’s Algorithm – Fully functional in TypeScript.
✅ Graph Creation – City modeled using adjacency lists.
✅ Ride Matching Logic – Proximity-based matching working in CLI.
✅ Fare Splitting Logic – Working fare calculator (console-based).
✅ GitHub Setup – Repository structured with modular commits.
🟡 React UI – In progress (to display ride inputs/output visually).
🟡 Node.js Middleware – Planned for backend–frontend communication.
❌ Traffic API Integration – Not yet implemented; placeholders added for future Mapbox or OpenTraffic support.


📁 Repository Structure
bash
Copy
Edit
SmartRide/
├── src/
│   ├── graph.ts            # Graph and Dijkstra’s logic
│   ├── ride-matching.ts    # Ride matching logic
│   ├── fare-calculator.ts  # Fare calculation logic
│   └── main.ts             # Entry point
├── README.md
├── package.json
└── ... (other config files)


📌 Future Enhancements
✅ React.js user interface
✅ Node.js API middleware
✅ Real-time traffic data integration
✅ Unit testing and performance profiling


🙏 Thank You!
SmartRide is a work in progress and open to collaboration! Contributions, feedback, and suggestions are welcome

