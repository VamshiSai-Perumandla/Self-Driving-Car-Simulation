# Self Driving Car Simulator

## Overview
This project leverages Artificial Intelligence alongside the Webots simulation environment to create an immersive Self Driving Car Simulator. It demonstrates the capabilities of autonomous vehicles to navigate complex driving scenarios, including dynamic obstacle avoidance and lane management.

## Features
- **Advanced Driving Controllers**: Includes `drive_controller` for the self-driving car and `EV_controller` for emergency vehicles, encompassing functionalities such as lane management, object recognition, and voice assistance.
- **Comprehensive Views Plugin**: Offers multiple perspectives with top, bottom, front, back, left, and right views to closely monitor the simulation.
- **Diverse Vehicle Prototypes**: Features a wide range of vehicle brands like Tesla, BMW, Lincoln, Range Rover, and Toyota, serving as dynamic obstacles in the simulation.
- **Realistic World Textures**: Enriches the simulation environment with detailed road lines, grass, trees, and flowers alongside the roads, enhancing the overall experience.

## Getting Started

### Prerequisites
- Ensure you have Webots app installed on your Windows machine. You can download it [here](https://www.cyberbotics.com/).

### Installation and Running the Simulation
1. **Clone the Repository**
    ```bash
    git clone URL_TO_THIS_REPOSITORY
    ```
2. **Navigate to the Project Directory**
    ```bash
    cd PATH_TO_PROJECT
    ```
3. **Explore the Folders**
    - **Controllers**: Contains driving conditions and behaviors.
    - **Plugins**: Views for the simulation.
    - **Protos**: Vehicle prototypes as obstacles.
    - **Worlds**: Environment textures and the main simulation file.

4. **Launch Webots and Open the Simulation**
    - Open Webots and navigate to the `Worlds` folder.
    - Open `highway_overtake.wbt` and run the simulation.

### Customization
- **Obstacle Management**: You can either modify the code to change obstacle positions or use the 3D view to drag obstacles to new locations.

## Contributing
Contributions to the Self Driving Car Simulator are welcome! Whether it's feature enhancement, bug fixing, or adding new vehicle prototypes, feel free to fork the repository and submit your pull requests.
