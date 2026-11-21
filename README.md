# NEXTRACE — Network Intelligence

NEXTRACE is a network monitoring and analysis dashboard for inspecting traffic on interfaces you are authorized to monitor. It uses the locally installed Wireshark/TShark tools for live capture.

This repository contains the project's downloadable reports and academic deliverables. The runnable application source code is maintained in the [NEXTRACE source repository](https://github.com/ShreyanshRaaJ/nextrace).

## Project documents

- [Project report](Project_Report.pdf)
- [Project output](Project_Output.pdf)
- [Classroom work](Classroom_Work.pdf)

## What the application does

- Displays live packet metadata, protocol summaries, and traffic statistics.
- Provides IP analysis and host observations from captured traffic.
- Includes packet exploration and analytics views.
- Shows local Windows Defender Firewall status as read-only information.
- Offers clearly labeled demo data for exploring the dashboard without capturing traffic.

## Run the application

The code is in the [NEXTRACE source repository](https://github.com/ShreyanshRaaJ/nextrace). On Windows, install Python 3.10 or newer and Wireshark with TShark/Npcap, then follow the source repository's README and launch instructions. The app is designed to run locally at `http://127.0.0.1:5000`.

## Responsible use and data handling

- Capture only traffic you are authorized to inspect.
- Live analysis uses packet metadata; the app does not retain packet payload bytes.
- Demo traffic is synthetic and labeled as demo data; it is not live captured traffic.
- Firewall information is read-only; NEXTRACE does not change system firewall rules.
- The project does not perform credential interception, decryption, spoofing, or man-in-the-middle attacks.
