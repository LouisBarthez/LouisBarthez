# Louis Barthez

Robotics engineering student at **Polytech Montpellier** (Microelectronics & Automation, robotics option), working on **robot learning for real-world manipulation**: imitation learning, VLAs and robot control.

📍 Montpellier, France · 🎯 Looking for a **6-month internship in Tokyo** (March – August 2027)

## Projects

### 🤖 Bimanual imitation learning on OpenArm — AIST Tokyo Waterfront (Apr–Jul 2026)
[hcp-ai-hub/openarm-box-sorting](https://github.com/hcp-ai-hub/openarm-box-sorting) · [Dataset & models on Hugging Face](https://huggingface.co/Louislerikiki)

- Brought a bimanual 7-DoF OpenArm from a bare kit to a full record → train → evaluate pipeline (CAN FD, leader–follower teleoperation with force feedback, 6 RGB-D streams on custom 3D-printed mounts).
- Collected 100 teleoperated episodes (~249k frames) and compared **ACT, Diffusion Policy, VQ-BeT and π0** on the real robot.
- Built an offline dry-run diagnostic to separate model failures from hardware issues.

*Commits for this project were pushed from a shared lab workstation, so they don't appear in my contribution graph.*

### 🦾 Franka Panda: ROS 2 control and digital twin — end-of-studies project with EuroDAO (2026–2027)
- ROS 2 + MoveIt 2 (C++) pipeline driving a real Panda, running a legacy libfranka 0.8.0 / ROS 2 Foxy stack in Docker to match the robot firmware.
- Cartesian impedance control validated in MuJoCo simulation (contour following on a 3D-printed part).
- Preparing an Isaac Sim digital twin to compare imitation learning and reinforcement learning.

## Stack
- **Robot learning:** PyTorch · LeRobot · ACT / Diffusion Policy / VQ-BeT / π0 · SAC / PPO
- **Robotics:** ROS 2 · MoveIt 2 · ros2_control · libfranka · MuJoCo · CAN FD
- **Languages & tools:** Python · C / C++ · Docker · CMake / colcon · Git

## Contact
[LinkedIn](https://www.linkedin.com/in/louis-barthez-29a476398/) · [Hugging Face](https://huggingface.co/Louislerikiki) · louis.barthez2206@gmail.com
