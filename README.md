Overview:

FlightDash V4 is a custom Lua telemetry widget designed for transmitters running EdgeTX 2.11+, optimized for radios such as the RadioMaster TX16S.

The widget provides a clean, real-time flight dashboard that displays critical telemetry and transmitter information in a single, easy-to-read layout. It combines telemetry data, system status, timers, and battery monitoring into a compact screen optimized for EdgeTX color displays.

FlightDash V4 automatically loads a model-specific image from the /IMAGES/ folder, allowing pilots to visually identify the active aircraft while monitoring telemetry during flight.

The layout is designed for quick readability during flight, using color indicators and status highlights to immediately show system health and aircraft state.


Features:

- Real-time telemetry dashboard for RSSI, Link Quality, RPM, Current, ESC temperature, BEC voltage, and cell count
- Clear ARM / DISARM and MOTOR ON / OFF status indicators
- Displays the current flight mode
- Intelligent receiver battery monitor with graphical battery icon and cell detection
- Transmitter battery voltage display with color-coded warnings
- Large flight timer display for easy in-flight monitoring
- Built-in date and time display
- Automatic model image loading from the /IMAGES folder
- Uses custom and EdgeTX color themes for improved readability
- Fully configurable telemetry sources through widget options
- Optimized for color radios like the RadioMaster TX16S running EdgeTX 2.11+

Installation:

- Download the ZIP file
- Extract the contents of the ZIP file
- Locate the last folder named fltDash4 (it contains main.lua)
- Copy this fltDash3 folder only
- Paste the folder into your SDCard/WIDGETS directory
