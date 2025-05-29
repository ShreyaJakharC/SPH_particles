# SPH-JS: Interactive Fluid Simulation

## Overview

We have shown the SPH motion, and implemented it using Javascript.

The particles are dropped from the top and they fall under the force of gravity. Once they fall, they arrange themselves at the bottom of the canvas.

In our project we have 3 main features:

1. There are three sliders to make changes in the orientation of the particles and the speed at which they fall. The three sliders are: gravity, Gas Constant, and Visc Constant. You can change them to see changes in the motion.

2. There is another feature where you can add additional particles by double clicking any where on the canvas.

3. Additionally we have another feature where by holding the cursor close to the particles, the particles move away from it.

This project is made by Helios Hu, Sophie Murthy, and Shreya Jakhar Choudhary.

I tackled this fluid simulation in my Numerical Computing course, and it was a blast to see theory come alive on the screen. Diving into SPH algorithms and tweaking them in real time gave me a whole new appreciation for how math and code blend to create interactive visuals. It was both challenging and incredibly fun!

## Features

- **Adjustable Physics:**
  - **Gravity**, **Gas Constant**, and **Viscosity** sliders let you instantly dial in different fluid behaviors.
- **Dynamic Spawning:**
  - **Double-click** anywhere to spray a burst of new particles into the simulation.
- **Cursor Repulsion:**
  - **Hold** your mouse near particles to push them away and create ripples.
- **Boundary Handling:**
  - Particles bounce off canvas edges with a damping effect to keep the fluid contained.
- **Optimized Grid:**
  - A simple spatial grid partitions neighbors for efficient density and force calculations.

## Tech & Tools

- **Language & Libraries:**
  - JavaScript (ES6), p5.js for rendering and input
- **Physics Engine:**
  - Custom SPH implementation in `SPH.js` (density, pressure, viscosity, gravity)
- **Application Logic:**
  - `sketch.js` initializes the canvas, handles UI, and runs the main simulation loop
- **Markup & Styling:**
  - `index.html` and `style.css` for page layout and slider styling
- **Version Control:**
  - Git & GitHub

## Results & Key Takeaways

- **Browser-based Fluid:** Achieved smooth, water-like motion at ~60 FPS with hundreds of particles.
- **Hands-On Learning:** Instant feedback from sliders deepened my understanding of SPH parameters.
- **Interactive Sandbox:** Double-click & cursor repulsion transformed a static demo into a playful exploration.
- **Performance Gains:** Learned to balance physical accuracy with real-time responsiveness.
- **Video of the stimulation:**
![SPH Simulation Demo](assets/video.gif)






## Skills Gained

SPH Fundamentals, JavaScript Animation, UI Integration, and Spatial Partitioning.

## Quick Start

1. **Clone the repo**
   ```bash
   git clone https://github.com/yourusername/SPH-JS.git
   cd SPH-JS
   ```
