# Pilot Insight

Pilot Insight evaluates flight data based on FAA regulations. This website allows users to upload a flight file (.kml) and view it visually. The site segments the flight maneuvers performed during the flight, displaying them in different colors. These segments are scored, and the score is visible to the user upon visualization. Users can either upload their own flight file or use one of our provided demo files.

## Segmentation Completed
- Takeoff
- Landing
- Turns Around a Point
- Slow Flight
- Touch & Go

## Overview

- `/docs` contains our Landing Page.
- `/project` contains our project files.

## File Specifics

- **index.js**: Runs the Node.js / Express server.
- **parseKML.py**: Computes the backend segmentation and scoring, which is then sent to the Node.js server.
- **cesiumScript.js**: Uses the CesiumJS plugin to display the flight and segmentation visually on the web server.

## Running Pilot Insight

To run the site, make sure to have **NodeJS** and **Python3** installed on your computer.

1. [Install NodeJS](https://nodejs.org/en/download)
2. Open your terminal and navigate to the project directory:
   ```sh
   cd project
   ```
3. Install the necessary Python dependencies:
   ```sh
   pip3 install -r requirements.txt
   ```
4. Install the necessary NodeJS dependencies:
   ```sh
   npm install
   ```
5. Start the server:
   ```sh
   npm start
   ```
6. Open the localhost link provided in the console.

## Branch Details

- **main**: Complete Project

Contributors: Adnan Shaker, Viraj Prakash, Ben Chapman
