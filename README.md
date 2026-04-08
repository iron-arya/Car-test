# Car Crash Simulation 🚗💥

## Overview
This project is a simple physics-based car crash simulation built using **p5.js** and **p5.play**. The simulation demonstrates how vehicle damage depends on factors like speed and weight when a collision occurs.

The project visually represents the severity of damage using color changes after impact.

## Features
- Random car speed generation
- Random vehicle weight simulation
- Collision detection between car and wall
- Damage calculation using physics formula
- Visual damage indication using colors:
  - Red → Severe damage
  - Yellow → Moderate damage
  - Green → Minor damage

## Technologies Used
- JavaScript
- p5.js
- p5.play library
- HTML
- CSS

## How It Works
The car moves toward a wall with randomly generated speed and weight values. When the collision occurs, deformation is calculated using the formula:

Deformation = (0.5 × weight × speed²) / constant

Based on the deformation value, the car changes color to indicate the severity of the crash.

## Project Structure
