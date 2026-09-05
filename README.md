# Balloon Mooring Safety Analyzer

An interactive physics dashboard designed to calculate peak kinetic impact forces on hot air balloon mooring systems and quick releases. 

## The "Tight Rope" Rule
When a mooring line has slack, a wind gust allows the balloon system to accelerate. This tool demonstrates the catastrophic force multipliers created when a 3-ton inertial mass hits the end of a slack line. 
*   **Tight Rope (0 m/s):** Zero impact force. The anchor only supports static lift.
*   **Slack Rope (> 0 m/s):** The mass kinetic energy is converted into elastic potential energy, causing a violent shock proportional to the rope's stiffness.

## Core Features
*   **Real-Time Physics Engine:** Calculates equivalent mass (including hydrodynamic added mass), centrifugal force, and elastic impact.
*   **Hardware Presets:** Compare elastic nylon, standard tether ropes, and rigid steel cables.
*   **Safety Limits Tracking:** Instantly cross-references applied tension with Minimum Breaking Load (MBL) and Safe Working Load (SWL, Safety Factor 5).
*   **No Server Required:** Runs entirely client-side using a single HTML file and Chart.js.

## Usage Guide
1. Clone this repository or download the source code file.
2. Open the `.html` file directly in any modern web browser (Chrome, Firefox, Safari).
3. Adjust the system mass, drift speed, and hardware stiffness to visualize the structural failure thresholds.

