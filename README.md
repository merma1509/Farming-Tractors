# Farming Tractors - Digital Twin Simulation

[![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![Pygame](https://img.shields.io/badge/Pygame-2.6.0-green.svg)](https://www.pygame.org/)
[![License](https://img.shields.io/badge/License-Educational-yellow.svg)](LICENSE)

## Project Overview

Welcome to the Farming Tractors project! This interactive educational simulation teaches programming concepts through the development of a **Digital Twin** for autonomous farming equipment in the fictional region of Maji Ndogo. The project combines practical Python programming with agricultural automation concepts, making learning both engaging and relevant to real-world applications.

## Learning Objectives

This project helps students master fundamental programming concepts including:

- **Data Structures** - Lists, dictionaries, and nested data representations
- **Control Flow** - Loops, conditionals, and logical decision-making
- **Functions** - Modular code design and parameter handling
- **Algorithmic Thinking** - Path planning and optimization strategies
- **Problem Solving** - Translating real-world scenarios into code

## What You'll Build

- **Virtual Fields** - Grid-based representations of agricultural land
- **Autonomous Tractors** - Programmable vehicles that navigate and plough fields
- **Movement Algorithms** - Efficient pathfinding patterns for field coverage
- **Interactive Simulations** - Visual feedback using Pygame graphics

## Project Structure

```bash
Farming-Tractors/
├── README.md                          # This file
├── Code_challenge_loops_logic_functions_notebook.ipynb  # Main simulation notebook
├── GCC-Data-structures-types_model_solution.ipynb      # Data structures exercises
└── assets/                            # Visual assets and graphics
    ├── *_tractor_12x12.png           # Colored tractor sprites
    ├── free.png                      # Tileset for field rendering
    ├── soil_tile_darker.png          # Ploughed soil texture
    └── EAI_Blue_Dark.png             # Educational branding
```

## Getting Started

### Prerequisites

- Python 3.11 or higher
- Pygame 2.6.0 or higher

### Installation

1. **Clone or download** this project to your local machine
2. **Install Pygame** if not already installed:

   ```bash
   pip install pygame
   ```

3. **Open the main notebook**:

   ```bash
   jupyter notebook "Code_challenge_loops_logic_functions_notebook.ipynb"
   ```

### Quick Start

1. Run the first few cells to set up the simulation environment
2. Configure your field parameters:

   ```python
   field_height = 10  # Minimum 1
   field_width = 5    # Minimum 1
   simulation_speed = 40
   tractor_colour = 'blue'  # Options: blue, green, orange, pink, purple, red
   ```

3. Execute the main simulation cell to launch the interactive window
4. Click "Start" to watch your autonomous tractor in action!

## Interactive Features

### Simulation Controls

- **Start Button** - Begin the tractor simulation
- **Stop Button** - End the simulation
- **Real-time Scoring** - Track efficiency and movement penalties

### Customization Options

- **Field Dimensions** - Adjust size (minimum 1x1, recommended 20x25)
- **Simulation Speed** - Control animation speed (lower = faster)
- **Tractor Colors** - Choose from 6 different tractor colors
- **Movement Patterns** - Program different ploughing strategies

## Coding Challenges

### Challenge 1: Basic Field Coverage

Write a function to make the tractor plough the entire field row by row.

### Challenge 2: List Manipulation

Create functions to reverse lists and handle directional changes.

### Challenge 3: Optimal Path Planning

Implement realistic tractor movements that alternate directions to minimize penalties.

### Challenge 4: Data Structures

Represent farm equipment and fields using dictionaries and lists.

## Educational Context

This project is designed for students learning programming through practical applications. The farming theme provides:

- **Real-world relevance** - Agriculture automation is a growing field
- **Visual feedback** - See your code come to life through graphics
- **Progressive complexity** - Start simple and build to advanced concepts
- **Problem-based learning** - Solve authentic agricultural challenges

## Visual Assets

The project includes:

- **Tractor Sprites** - 6 different colored tractors (12x12 pixels)
- **Field Tiles** - Various soil textures and ploughed states
- **UI Elements** - Buttons and branding materials
- **Tilesets** - Comprehensive graphics for field rendering

## Technical Details

### Core Classes

- **Field** - Manages the virtual field layout and state
- **Tractor** - Handles tractor positioning and rendering
- **Button** - Interactive UI elements for simulation control

### Key Functions

- **student_function()** - Main function for implementing movement algorithms
- **render_tile()** - Graphics rendering for field elements
- **plough_field()** - Updates field state when tractor passes

### Simulation Parameters

```python
TILE_SIZE = 16          # Pixel size of each field tile
TRACTOR_SIZE = 12       # Pixel size of tractor sprite
UI_WIDTH = 200          # Width of control panel
```

## Learning Progression

1. **Introduction** - Understand the digital twin concept
2. **Setup** - Configure the simulation environment
3. **Basic Programming** - Simple loops and functions
4. **Advanced Logic** - Conditional movements and optimization
5. **Data Structures** - Complex data representation
6. **Project Integration** - Combine all concepts

## Contributing

This is an educational project designed for learning. Feel free to:

- Report issues or bugs
- Suggest improvements to exercises
- Share your solutions and approaches
- Contribute additional challenges

## License

This project is provided for educational purposes. Please use it responsibly to learn programming concepts.

## Acknowledgments

- **Explore AI** - Educational framework and methodology
- **Pygame** - Graphics and simulation engine
- **Maji Ndogo** - Fictional setting for agricultural challenges

---

## Ready to Start?

**Dive into the notebooks and begin your journey into autonomous farming!**

Remember: Every expert was once a beginner. Start with the basics, experiment with the code, and watch as your virtual farm comes to life through programming.

Happy coding, and may your fields be ever productive!
