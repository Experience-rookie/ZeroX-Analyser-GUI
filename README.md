# ZeroX Analyser — GUI

Browser-based interface for ZeroX Analyser, a static security 
analysis tool for PHP e-commerce applications.

The GUI wraps the CLI scanner in a React + MUI frontend with 
three result views: raw output, vulnerability summary, and 
detailed findings. Each view supports PDF export.

## Setup

# Terminal 1 — Flask backend
cd server
pip install flask flask-cors fpdf2
python3 app.py

# Terminal 2 — React frontend  
cd client
npm install
npm start

Then open http://localhost:3000

## CLI tool
The command-line version is here:
https://github.com/Experience-rookie/ZeroX-Analyser.V2.0

## Paper
Preprint: [link coming soon — will update after arXiv submission]
