# Bus tracking web app (Flask + WebSockets + Leaflet)

A real-time web app that fetches live bus data from the liverpool area (functionality to add custom busses still to come!).

Right now its very bare-bones, you open the app, it shows you a map with all the bus services in the area through a blue marker. Updated every 10 seconds (although some buses have inconsistencies with how often they update their data so certain markers may be totally still).

## Setup
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
python -m venv env
source env/bin/activate  # or .\env\Scripts\activate on Windows
pip install -r requirements.txt
python app.py
```
To open, visit http://localhost:3000 on your machine

