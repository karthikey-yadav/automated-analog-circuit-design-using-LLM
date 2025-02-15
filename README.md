# Automated Analog Circuit Design Using LLM

## Overview
This project leverages a Large Language Model (LLM) to automate the design and optimization of analog circuits. The system takes user-defined specifications and generates circuit schematics, component values, and performance estimations. It integrates AI-driven design strategies to streamline the traditionally complex and time-consuming analog circuit design process.

## Features
- **AI-Powered Circuit Synthesis**: Uses LLMs to generate circuit designs based on user specifications.
- **Optimization Algorithms**: Implements ML techniques to optimize circuit performance.
- **Simulation Integration**: Supports SPICE simulations for performance validation.
- **User-Friendly Interface**: Provides an interactive UI for easy parameter input and circuit visualization.
- **Multi-Objective Tuning**: Balances parameters like gain, bandwidth, power consumption, and noise.

## Technologies Used
- **LLM Framework**: OpenAI/GPT-based models for text-to-circuit generation.
- **Circuit Simulation**: SPICE, LTspice, Ngspice.
- **Programming Languages**: Python, VHDL/Verilog (for FPGA-based implementations).
- **Optimization Techniques**: Genetic Algorithms, Reinforcement Learning.
- **Web Interface**: Flask/Django for user interaction.

## Installation
1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-repo/automated-analog-circuit-design.git
   cd automated-analog-circuit-design
   ```
2. **Install Dependencies**
   ```sh
   pip install -r requirements.txt
   ```
3. **Run the Application**
   ```sh
   python main.py
   ```

## Usage
1. Input circuit parameters (e.g., frequency response, gain, power limits).
2. The LLM generates a proposed circuit topology and component values.
3. Run SPICE simulation to verify circuit performance.
4. Adjust constraints and re-run the optimization if needed.


## Future Enhancements
- **Integration with FPGA for real-time circuit prototyping**
- **Support for digital-analog hybrid circuit designs**
- **AI-driven fault detection and debugging**

## Contributors
- **Name** - karthikeyan yadav



