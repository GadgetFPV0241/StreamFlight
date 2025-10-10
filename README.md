✈️ Want to display live MSFS 2020/2024 flight data on your Twitch or YouTube stream?

I was constantly battling with my streaming overlay.  Either the app I used would crash mid-flight, the flight tracking software hid basic features behind a premium subscription, or the tools that did work were far too CPU-heavy for streaming, and if they didn’t hog resources, they forced me into using some generic, non-customizable overlay that just didn’t fit my stream look and feel.

That’s exactly why I created StreamFlight — a lightweight, reliable, and simple interface that updates your flight data in real time. No crashes. No hidden costs. No performance drag.

With StreamFlight, your stream looks polished and professional, and your viewers stay immersed in the flight — without you fighting your setup.

Here’s how to set it up:

1️⃣ Create Your Overlay
Use Photoshop (other graphics programs are available) to design an overlay with all your labels — Aircraft, CallSign, Altitude, Speed, Heading, ETE, ETA, Network, or anything else you want to share with your viewers. Keep it styled to match your stream’s look.

2️⃣ Set Up A Nested Scene In OBS
Open OBS and create a new Nested Scene — for example, call it “FlightData.”

Add your overlay image to this scene.  Then, for each flight data element you want (speed, altitude, etc.), add a Text Source in OBS.  Choose “Read from File” and point it to the corresponding text file that StreamFlight generates in the Output folder (you set this folder the first time you start StreamFlight).

3️⃣ Add To Your Main Scene
Now just drop the "FlightData" Nested Scene into your main streaming scene. Position the text elements exactly where you want them on your overlay.

4️⃣ Go live!
As soon as StreamFlight is connected to MSFS 2020/2024, the application will notify you of the connection status. It updates all files in real time. Your viewers will see smooth, live flight data — perfectly in sync with your flight.

💡 No complicated scripting. 💡 No clunky plugins. 💡 Just a clean, seamless solution that makes your stream stand out.

With StreamFlight, your cockpit becomes part of the show — giving your audience the immersive experience they’re looking for.

⚙️ Core Features

🧭 Real-Time Data Capture

Automatically generates live data files throughout your flight:

ETE (Estimated Time Enroute) – continuous time tracking
ETA (Estimated Time of Arrival, UTC) – precise arrival prediction
Altitude – live altitude updates
Headings – true, magnetic, and gyro
Speed – real-time ground speed monitoring
Distance to Waypoint (DTG) – GPS-based distance updates
Distance to Destination – true remaining distance
Outside Air Temperature (OAT) – live environmental monitoringAll data saved automatically in text files for easy access and integration.
🛫 Flight Planning Integration

SimBrief Sync or Manual Entry

Supports:
Aircraft Type
Callsign
Departure & Destination ICAO Codes
🌐 Flexible Network Connectivity

Choose how you fly:

📴 OFFLINE Mode
🌎 VATSIM
✈️ IVAO
🎧 PILOTEDGE
🚀 Smart Flight Phase Tracking
Automatic detection and logging of all major flight stages:

PREFLIGHT → TAXI → TAKEOFF → CLIMB → CRUISE → DESCENT → APPROACH → LANDING → TAXI
Provides complete situational awareness from gate to gate.

⏱️ Dynamic Time Calculation

ETA (UTC) and ETE continuously updated
Based on current speed and distance remaining
Ensures accurate arrival predictions under changing conditions
⚙️ Installation
Extract: Unzip the downloaded file to any directory, using a utility such 7-Zip, WinZip or whatever (e.g., G:\Flightsim Utillities\StreamFlight\)
Run: Double-click StreamFlight.exe to start the application

🛠️ Setup
Upon First Launch

StreamFlight will ask you to select an output folder for the data element text files, Browse to the directory of your choice.

✨ Usage

Enter the manual input requirements, which are, Aircraft Type, CallSign, Departure ICAO, Destination ICAO and Online Network (if flying offline, select "NONE"). Click "Save Manual Fields", this create the text files in the chosen output folder.  THATS IT!

All the other elements will be created once you are connected to the simulator and will be updated live during the flight.  When diconnected from the simulator you will see the updated connection staus in StreamFlight.  It will constantly look for a connection and change its status if the simulator reconnects.  In addition, all automatically updated text files will revert to either N/A or 00:00 when no simulator connection is present.

📚 Resource

Included in the ZIP file, is an "overlay_demo.png" to serve as a visual reference for understanding the overlay process. This example demonstrates the intended structure, placement, and styling approach. You may use the "overlay_demo.png" to familiarise yourself with the method, and once you are comfortable, you can proceed to create your own overlay following the same principles.

☎️ Support & Feedback
This is an initial release that I use myself, and to be honest works exactly how I need it to. Whilst there's no formal support, you can always pop into my stream to provide feedback. Don't forget to follow and Subscribe 🤣.

WANT TO SEE IT IN ACTION - https://www.twitch.tv/gadgetfpv

⚠️ License & Disclaimer
This free software is provided “as is,” without any warranty of any kind. It is intended solely for educational and entertainment purposes. By using this software, you accept full responsibility for compliance with all applicable rules, laws, and regulations, and you assume all associated risks.

This software makes use of SimConnect © Microsoft Corporation. All rights reserved.

This application is not affiliated with, endorsed by, or approved by OBS or its developers.

AFTER ALL THAT... ENJOY
