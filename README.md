# Disagreement-Aware Variable Impedance (DAVI) controller

If you found this repo useful for your research, please cite it as:

```
@inproceedings{spaa2022disagreement,
  title={Disagreement-Aware Variable Impedance Control for Online Learning of Physical Human-Robot Cooperation Tasks},
  author={Spaa, Linda van der and Franzese, Giovanni and Kober, Jens and Gienger, Michael},
  booktitle={ICRA 2022 full day workshop - Shared Autonomy in Physical Human-Robot Interaction: Adaptability and Trust},
  year={2022}
}

```
This repo uses Franka Human Friendly Controllers (https://github.com/franzesegiovanni/franka_human_friendly_controllers) to interface with a Franka Emika Panda robot. 
Please first follow the installation instructions in that repo to set up both Franka ROS and the Human Friendly controller.

## Demo

To run the demo of teaching the robot where and how to place a paper cup:
- Clone this repository
- Open a new terminal in: ```DAVI_controller/python```
- Do not forget to: ```source <catkin_ws>/devel/setup.bash```
- Run the main file: ```python3 main.py```

The robot will move to make the gripper face down, and then switch to gravity compensation. The robot can now be moved to the desired initial end-effector position. Upon pressing enter, the model is further initialized and the Episodes can be started and quit via the keyboard.

Watch our demo here: https://youtu.be/toIUuFguFgM
