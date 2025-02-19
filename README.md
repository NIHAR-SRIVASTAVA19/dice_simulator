# dice_simulator

## Overview

This is a simple dice rolling simulation using Python and Tkinter. The application displays two dice images that change randomly upon clicking the "ROLL" button, simulating a real dice roll.

## Features

- Random dice face generation.
- Graphical user interface using Tkinter.
- Uses PIL (Pillow) for image handling.
- Simple and interactive button-based roll mechanism.

## Prerequisites

Ensure you have Python installed along with the required dependencies:

```bash
pip install pillow
```

## How to Run

1. Clone or download the repository.
2. Place six dice face images in the project directory with the names:
   - `dice-six-faces-one.png`
   - `dice-six-faces-two.png`
   - `dice-six-faces-three.png`
   - `dice-six-faces-four.png`
   - `dice-six-faces-five.png`
   - `dice-six-faces-six.png`
3. Run the script:

```bash
python simulator.py
```

## How It Works

- The application initializes with two random dice images.
- Clicking the "ROLL" button updates both dice with new random images.
- The images are selected from a predefined list of dice faces.

## Dependencies

- `tkinter` (built-in with Python)
- `PIL` (Pillow package for handling images)

## License

This project is open-source and free to use under the MIT License.

