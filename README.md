Features
1.Visits all 28 state capitals exactly once

2.Calculates and returns to the starting city

Shows:

 Ordered list of cities visited

 Total distance (km)

 Total cost (₹1 per km)

🔧 Prerequisites

Node.js & npm installed

Vite globally (optional)

Backend Setup (Express)
bash
Copy
Edit
cd tsp-india-tour/server
npm init -y
npm install express cors
node index.js
✅ Server will run at: http://localhost:5000

Frontend Setup (React + Vite)
bash
Copy
Edit
cd tsp-india-tour/client
npm create vite@latest . -- --template react
npm install
npm install axios
🔁 Replace the src/App.jsx and src/App.css with the provided files.

bash
Copy
Edit
npm run dev
✅ App will run at: http://localhost:5173

