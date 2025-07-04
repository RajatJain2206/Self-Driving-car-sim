# 🚗 Self-Driving Car Simulation

This is a browser-based simulation of a self-driving car built **entirely from scratch** using **HTML, CSS, and vanilla JavaScript**, without any external frameworks or libraries.

The project implements basic AI behavior using a simple neural network, allowing cars to learn and adapt using a genetic algorithm-like selection and mutation process. It also features real-time physics, collision detection, and a fully interactive environment.

## 🔍 Features

- 🚘 Multiple AI-controlled cars with individual neural networks
- 🧠 Basic neural network logic and mutation-based learning (no ML libraries used)
- 🚧 Realistic road layout with lane guidance and traffic simulation
- ⚡ Real-time collision detection and dynamic rendering
- 🧪 Adjustable sensors and visual debugging tools
- 💡 Save and load best-performing brain from localStorage

## 🛠️ Technologies Used

- HTML5 Canvas for rendering
- Vanilla JavaScript for logic and interactivity
- CSS for layout and UI elements

## 📁 Project Structure

```plaintext
├── index.html          # Main HTML file
├── styles.css          # CSS for layout and visuals
├── main.js             # Core logic and animation loop
├── car.js              # Car object and movement logic
├── sensor.js           # Simulates the car's vision
├── controls.js         # User and AI control inputs
├── network.js          # Neural network logic
├── visualizer.js       # Draws the neural network (AI brain) in real-time
├── utils.js            # Utility functions

