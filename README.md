# Sensors Final Assignment: Group 101 Sensors Track B

## Resources
The goal of this project was to create a simulation of a UR3 robotic arm, that with the use of sensors could detect an object on a table top, plan an approach, and execute using IBVS.

## Group information
Group 101:
William Peirce, Jason Bean, Shujay Vijaygiri, Anthony Zappia

## Install info
First follow the [Installation Guide](https://github.com/IZapYou/Sensors_Final_Assessment/blob/main/Sensors-and-Controls-Final-Project--Code/Installation%20Guide.pdf). This is the basic installation guide for getting python ready. Once that is done,
```bash
pip install mujoco numpy scipy opencv-python matplotlib
```

## Run commands
To run the main simulation which then runs all the sections together, enter the line below in the terminal:
```bash
cd Sensors-and-Controls-Final-Project--Code/Sensors_Start
python main_pick.py
```
Note: To disable the added noise, go into config.py and edit CAMERA_NOISE = False

For original repo with code commits: https://github.com/SkyyWP/Sensors-and-Controls-Final-Project-/tree/main
