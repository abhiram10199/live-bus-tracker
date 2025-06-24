# Bus tracking web app (Flask + WebSockets + Leaflet)

A real-time web app that fetches live bus data from the liverpool area (functionality to add custom busses still to come!).

Right now its very bare-bones, you open the app, it shows you a map with all the bus services in the area through a blue marker. Updated every 10 seconds (although some buses have inconsistencies with how often they update their data so certain markers may be totally still).

API - https://github.com/LemarTokham/bus-stop-api/tree/Abhi's-branch

## Setup
```bash
git clone https://github.com/LemarTokham/live-bus-tracker.git
cd live-bus-tracker
python -m venv env
source env/bin/activate  # or .\env\Scripts\activate on Windows
pip install -r requirements.txt
python app.py
```
To open, visit http://localhost:3000 on your machine

As you first load up the app, give it 10 seconds for the first set of bus data to come in.
