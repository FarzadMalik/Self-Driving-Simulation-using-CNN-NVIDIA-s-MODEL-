# Self-Driving Car Simulation using CNN NVIDIA's Model and TensorFlow

## Overview

This repository contains code and resources for a self-driving car simulation using the Convolutional Neural Network (CNN) NVIDIA's Model architecture. The simulation is implemented using TensorFlow and communicates with a simulator to control the car autonomously.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Directory Structure](#directory-structure)
- [Files](#files)
- [Model](#model)
- [Simulation](#simulation)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before running the simulation, you need to have the following software and resources installed:

- Python (3.x recommended)
- TensorFlow
- OpenCV
- Eventlet
- SocketIO
- Flask
- Simulator (e.g., the Udacity Self-Driving Car Simulator)

## Getting Started

1. Clone this repository to your local machine.
2. Install the required Python packages using `pip install -r requirements.txt`.

## Usage

1. Launch the simulator in autonomous mode.
2. Run the `Testing.py` script to start the self-driving simulation.

## Directory Structure

```
|-- simulator_data/                  # Data directory
|   |-- IMG/                          # Image data
|   |-- driving_log.csv               # Log file
|-- model.h5                          # Trained CNN NVIDIA's Model
|-- Testing.py                        # Main script to run the simulation
|-- utils.py                          # Utility functions
|-- README.md                         # This README file
|-- requirements.txt                  # Required Python packages
```

## Files

- `trainingsimulation.py`: Contains code related to training the CNN NVIDIA's Model.
- `utilis.py`: Provides utility functions for data processing and augmentation.
- `Testing.py`: Main script to run the self-driving simulation.

## Model

The CNN NVIDIA's Model architecture is used for autonomous driving. The model has been trained on a dataset of images and corresponding steering angles.

## Simulation

The self-driving simulation connects with the simulator, processes incoming images, and uses the trained model to predict steering angles. The simulator receives these predictions and controls the car accordingly.

## Contributing

Contributions are welcome! If you find any issues or want to enhance the project, feel free to create pull requests.

## License

This project is licensed under the [MIT License](LICENSE).
```

