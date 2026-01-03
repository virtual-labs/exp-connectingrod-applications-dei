<b style="font-size: 1.6em; color: black;">Connecting Rod Simulation - Documentation</b>

This directory contains the interactive simulation module for the **Connecting Rod Forming Process**.

### Overview
The simulation allows users to study the hot forging of manganese alloy steel maintained at 1250°C. It highlights material deformation, plastic flow, and equivalent strain distribution using a multi-step interactive interface.

### Folder Structure
* **index.html**: The main simulation page featuring vertical navigation buttons with "Call to Action" prompts to enhance user engagement.
* **css/main.css**: Stylesheet providing the layout for the vertical button stack, modern rounded UI elements, and the video section animations.
* **Simulation Videos**: Contains the four MP4 files demonstrating Setup and Strain analysis for Parts 1 and 2.

### Interactive Features
1. **Vertical Button Navigation**: Replaces the horizontal layout to improve mobile and desktop scannability.
2. **Dynamic Visibility**: Only the selected simulation and its corresponding description are visible at one time to prevent visual clutter.
3. **Engagement Prompts**: Each button is preceded by a short instruction (e.g., "Analyze the initial material deformation") to guide the user through the experiment steps.
4. **Auto-Management**: The system automatically pauses the current video when a different simulation is selected to conserve system resources and prevent overlapping audio.

### Technical Detail
The simulations demonstrate how a hydraulic press applies high force to deform a billet into the die impressions, resulting in a semi-finished connecting rod. Final mechanical properties such as fatigue resistance and strength are achieved through post-processing grain refinement.
