# Status-Hub-GUI
The Official GUI for the PC Status Hub GUI by Lofink Labs. 

www.LofinkLabs.com

Mini Status Hub – Desktop GUI

-----------------------------------------------------------------------------------------------------------------------------------------------------------


Mini Status Hub is a lightweight Windows companion app for a USB-connected external status display.
It transforms raw system telemetry into clear, glanceable system health indicators — without overlays, dashboards, or constant attention.

This GUI pairs with the Mini Status Hub hardware device currently under development.

-----------------------------------------------------------------------------------------------------------------------------------------------------------

 	
What It Does

Reads live system metrics via LibreHardwareMonitor

Sends customized, formatted data to an external display

Runs quietly in the background (system tray)

-----------------------------------------------------------------------------------------------------------------------------------------------------------

Key Features

Slot-based layout
Map individual sensors to display slots with labels

Semantic color alerts
Optional rule-based coloring (green / yellow / red) for quick-glance awareness

Cosmetic customization
Font size, rotation, alignment, and per-slot colors

Profiles & persistence
Save layouts, sensors, and alert rules per profile

Hardware-first design
All logic runs on the PC — firmware stays simple and stable

Headless-friendly
Configure once, then run unattended on headless or tucked-away systems

-----------------------------------------------------------------------------------------------------------------------------------------------------------

Typical Use Cases

Workstations and render machines

Streaming or capture PCs

Home servers or NAS boxes (Windows-based)

PCs located under desks or in closets

Anyone who wants ambient system awareness

-----------------------------------------------------------------------------------------------------------------------------------------------------------

Requirements

Windows 10 / 11

LibreHardwareMonitor
Download from the official GitHub:
https://github.com/LibreHardwareMonitor/LibreHardwareMonitor

Mini Status Hub USB device

⚠️ Some antivirus products (notably AVG / Avast) may flag LibreHardwareMonitor due to its low-level hardware access.
This is a known false positive.

-----------------------------------------------------------------------------------------------------------------------------------------------------------

Installation (Quick Start)

Install and run LibreHardwareMonitor

Start up the built in local Libre server

Ensure sensor web access is enabled

Connect the Mini Status Hub device via USB

Launch the Mini Status Hub GUI

Configure slots, colors, and alert rules

-----------------------------------------------------------------------------------------------------------------------------------------------------------

Privacy & Security

No cloud services

No telemetry or analytics

No accounts

USB-only device communication

All processing is local

-----------------------------------------------------------------------------------------------------------------------------------------------------------

Relationship to LibreHardwareMonitor

This project:

Is not endorsed byh LibreHardwareMonitor

Does not modify LibreHardwareMonitor

Does not redistribute LibreHardwareMonitor

Uses sensor data exposed via Libre’s public interface

LibreHardwareMonitor remains the authoritative sensor provider.

-----------------------------------------------------------------------------------------------------------------------------------------------------------


License

© 2025 Lofink Labs
All rights reserved.

This software is distributed as a binary-only companion application.
See the LICENSE file for details.

Project Status

Actively developed.
Designed as a long-term, low-distraction system utility — not a demo or overlay.
