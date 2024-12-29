here's the simulation: 
https://sanikakale.itch.io/solar-system

# Solar System Simulation

## Overview
The Solar System Simulation is an interactive 3D representation of our solar system, developed in Unity using C#. This project allows users to explore celestial bodies, observe their orbital movements, and learn about planetary characteristics.

---

## Features
- **Realistic Orbits:** Planets and moons follow accurate elliptical orbits.
- **Scalability:** Adjustable scales for planet sizes and orbital distances.
- **User Interaction:** Camera controls to navigate and zoom into celestial bodies.
- **Informational Panels:** Displays data about planets, including size, distance from the sun, and rotation period.
- **Dynamic Lighting:** Simulates sunlight and shadows across the solar system.

---

## Prerequisites
- Unity 2021.3.x or later.
- Basic knowledge of Unity and C#.

---

## Getting Started

### 1. Clone the Repository
```bash
git clone <repository-url>
```

### 2. Open the Project in Unity
1. Launch Unity Hub.
2. Click on **Open Project** and navigate to the cloned folder.

### 3. Play the Simulation
- Press the **Play** button in Unity to start the simulation.

---

## Controls
- **W/A/S/D or Arrow Keys:** Move the camera.
- **Mouse Scroll:** Zoom in/out.
- **Right Mouse Button + Drag:** Rotate the camera view.
- **Left Click on a Planet:** Display planet details.

---

## Project Structure
```
Assets/
├── Scripts/
│   ├── CelestialBodies/
│   │   ├── Planet.cs
│   │   ├── Moon.cs
│   ├── System/
│   │   ├── OrbitController.cs
│   │   ├── Sun.cs
│   ├── UI/
│       ├── InfoPanelController.cs
│       ├── CameraController.cs
├── Prefabs/
│   ├── Planet.prefab
│   ├── Moon.prefab
│   ├── Sun.prefab
├── Scenes/
│   ├── MainScene.unity
├── Materials/
│   ├── PlanetTextures/
│       ├── Earth.jpg
│       ├── Mars.jpg
│       ├── Jupiter.jpg
│       ├── ...
├── Audio/
│   ├── BackgroundMusic.mp3
│   ├── ClickSound.wav
```

---

## Simulation Mechanics

### 1. Celestial Bodies
- **Sun:** Center of the solar system, emits light.
- **Planets:** Move in elliptical orbits around the sun.
- **Moons:** Orbit their respective planets.

### 2. Orbits
- Orbits are controlled by the `OrbitController.cs` script, which calculates positions based on time and orbital parameters.

### 3. Interaction
- Clicking on a celestial body displays an informational panel with:
  - Name
  - Orbital distance
  - Size
  - Rotation period

### 4. Scaling
- Adjust scales for educational or visual purposes using Unity's Inspector panel.

---

## Customization
- Add new celestial bodies by creating prefabs and configuring their parameters in `OrbitController.cs`.
- Change textures or materials for planets and moons under the `Materials/PlanetTextures` directory.
- Modify camera behavior by editing the `CameraController.cs` script.

---
