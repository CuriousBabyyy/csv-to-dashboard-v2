# Plotline – CSV to Dashboard (Version 2.0)

## Overview
Plotline is a simple, locally hosted web application that converts CSV (Comma-Separated Values) files into visual dashboards. It helps users explore and visualize data without manually creating charts from scratch.

This is the first version of the application, offering basic dashboard functionality with limited interactivity. The project is still in its early stages, and future versions may include additional features and improvements.

## How to Start the Application

**Method 1: Using the BAT File (Recommended)**

1. Open the project folder.
2. Find the file named `start plotline.bat`.
3. Double-click it to start the application.
4. Wait for the server to launch. A terminal window will display the local URL.
5. Open the displayed URL in your web browser to access Plotline.

Keep the terminal window open while using the application.

**Method 2: Using the Terminal**

1. Open the project folder.
2. Click the folder's address bar, type `cmd`, and press Enter. Alternatively, open PowerShell or a terminal in the same folder.
3. Run the following command:

   `npm run dev`

4. Once the development server starts, copy the local URL displayed in the terminal (usually similar to `http://localhost:5173/`) and open it in your browser.

**Note:** If dependencies are missing, run `npm install` in the project folder before starting the application.

## Features and Limitations
- Basic CSV-to-dashboard conversion.
- Runs locally on your computer.
- Limited dashboard interactivity.
- No built-in user guide yet.

**Version:** 1.0 – Initial Release

Plotline provides a foundation for future improvements, including enhanced interactivity, additional visualizations, and a more user-friendly interface.
