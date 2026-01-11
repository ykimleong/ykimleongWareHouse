# Ykimleong Warehouse

A personal utility hub containing engineering and physics calculators.

## Overview
This project is a web-based collection of utility tools designed for quick and easy calculations. It features a modern, responsive interface built with HTML, CSS, and vanilla JavaScript.

## Tools

### 1. Speed Calculation (`speed-calc.html`)
**Speed vs Time Calculator & Plotter**
- Calculates the total travel time for an object given its maximum speed, acceleration, and total distance.
- Generates a real-time "Speed vs Time" chart using Chart.js.
- Visualizes the acceleration, cruise (if applicable), and deceleration phases.

### 2. Pump Flow Range (`pump-flow.html`)
**Pour Capability Calculator (ISO / POL)**
- Computes flow rates (g/s) for chemical pump systems (ISO and POL sides).
- Inputs include Pump Size (cc), Motor Pole, Variable %, and Specific Gravity (SG).
- valid frequency range analysis to ensure pump limits are respecting the mixing ratio.
- Detailed output table showing Min/Max Hz and Total Flow (g/s).

### 3. Cycle Time (`cycle-time.html`)
**Plant & Production Calculator**
- Calculates plant configuration and production output based on 4 modes:
  1. **Yearly Requirement**: Input target pieces/year → calculates required cycle time.
  2. **Plant Size**: Input number of stations → calculates achievable cycle time.
  3. **Cycle Time per Round**: Input total round time → calculates plant size.
  4. **Cycle Time per Station**: Input station time → calculates total output.
- Features a responsive layout (1-3 columns) for easy data viewing on all devices.

## Usage
Simply open `index.html` in your web browser to access the main hub. From there, you can navigate to the specific tools.

## Technologies
- **Frontend**: HTML5, CSS3 (variables, flexbox/grid), JavaScript (ES6+)
- **Libraries**: [Chart.js](https://www.chartjs.org/) (for plotting)
- **Fonts**: Inter (Google Fonts)
