# real-time-stock-ticker-1
1.Project Setup:
•	Initialize project repository.
•	Configure development environment.
•	Set up necessary dependencies (e.g., WebSocket libraries).
•	Establish basic project structure for ticker components.

2. Project Report:
Objective:
Create a scalable system that streams live stock updates to clients, demonstrating event-driven, non-blocking communication.
System Overview:
Architecture:
•	[Client Browser] ⇄ [Express Server + Socket.IO] ⇄ [MongoDB]
•	Stocks are stored in MongoDB with symbol, price, and timestamp.
•	Prices update every few seconds (via simulation or API).
•	Server pushes changes to clients using WebSocket events.

