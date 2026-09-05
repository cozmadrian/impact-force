# Balloon Mooring Safety Simulator

A standalone, interactive physics dashboard designed to demonstrate the critical mechanical stresses applied to hot air balloon mooring systems and quick releases during the inflation and launch phases.

## The "Tight Rope" Rule
This tool exists to prove a single, vital physical reality to balloon pilots and safety committees: **slack in a mooring line creates lethal force multipliers.**

When a balloon system (often exceeding 3 tons of kinetic inertia due to hydrodynamic added mass) drifts on a slack line, the impact acts as a loaded spring. The resulting elastic rebound generates forces that easily exceed the Minimum Breaking Load (MBL) of standard hardware.
*   **Tight Rope (v = 0 m/s):** Zero impact force. The anchor only supports static lift.
*   **Slack Rope (v > 0 m/s):** The kinetic energy converts into elastic potential energy, causing a violent shock proportional to the rope's stiffness.

## Core Features
*   **Analytical Engine:** The simulation uses a pure harmonic oscillator function during the impact phase to guarantee that the real-time ECG oscilloscope matches the theoretical peak tension with absolute mathematical precision.
*   **Dynamic Added Mass:** Automatically calculates the hydrodynamic added mass (0.6 * Envelope Volume) based on the input system weight.
*   **Hardware Presets:** Instantly compare the elastic absorption of Nylon, standard tether ropes (e.g., Ultramagic), and the catastrophic rigidity of Steel Cables.
*   **Safety Limits Tracking:** Cross-references the applied peak tension against the Minimum Breaking Load (MBL) and Safe Working Load (SWL, using a standard aeronautical Safety Factor of 5).
*   **Zero Server Dependencies:** Runs entirely client-side using a single HTML file and Chart.js.

## Usage
1. Clone this repository or download the `securite_ballon.html` file.
2. Open the file directly in any modern web browser (Chrome, Safari, Firefox, Edge) on desktop or mobile.
3. Adjust the system mass, drift speed, and hardware stiffness to visualize the structural failure thresholds.

## ⚠️ LEGAL DISCLAIMER
**For educational and training demonstration purposes only.** 
This tool uses idealized physical models (linear elasticity, simplified pendulum kinematics) to demonstrate the physical dangers of slack lines. It **DOES NOT** replace certified aeronautical engineering analysis. Do not use this software to legally certify, validate, or dimension flight hardware. Always refer to your local Civil Aviation Authority regulations and the manufacturer's official equipment specifications.
