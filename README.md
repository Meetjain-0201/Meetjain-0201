<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=20&pause=1000&color=00FFB2&center=true&vCenter=true&width=700&lines=Robotics+%26+AI+Engineer;Physical+AI+%7C+Embodied+Control+%7C+Sim-to-Real;Humanoid+manipulation+%7C+SLAM+%7C+BEV+Perception" />

[![LinkedIn](https://img.shields.io/badge/-meetjain0201-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/meetjain0201)
[![Email](https://img.shields.io/badge/-meetjain0201@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:meetjain0201@gmail.com)
[![Scholar](https://img.shields.io/badge/-Published_×2-4285F4?style=flat-square&logo=google-scholar&logoColor=white)](https://www.sciencedirect.com/science/article/pii/S2772503024000641)

</div>

---

```bash
meet@robotics:~$ whoami
```
```
Name    : Meet Jain
Role    : Robotics & AI Engineer
Focus   : Physical AI · Humanoid manipulation · Autonomous systems
Degree  : MS Artificial Intelligence (Robotics), Northeastern University  [GPA: 3.96]
          BTech Mechatronics & Robotics, Manipal Institute of Technology  [GPA: 8.17]
Location: Boston, MA
Status  : Open to robotics engineering roles
```

---

```bash
meet@robotics:~$ ls -lrt ~/projects/ | sort -k6 -r
```
```
drwxr-xr-x  humanoid-rl-platform/         Mar 2026 – present   [MuJoCo · Newton RL · PPO · GCP · Isaac Lab]
drwxr-xr-x  bimanual-teleoperation/        Feb – Mar 2026       [Isaac Sim 5.1 · ROS2 · MediaPipe · PhysX IK]
drwxr-xr-x  autonomous-nav-stack/          2025                 [ROS2 · Gazebo · ORB-SLAM3 · A* · DWA · EKF]
drwxr-xr-x  visual-slam/                   2025                 [ORB-SLAM3 · ROS2 Humble · Foxglove Studio]
drwxr-xr-x  bev-perception-ipm-vs-lss/     2025                 [PyTorch · nuScenes · Lift-Splat-Shoot]
drwxr-xr-x  3d-gaussian-splatting/         2025                 [Python · COLMAP · CUDA · 3DGS]
drwxr-xr-x  xav-explainable-av/            2024 – 2025          [CARLA 0.9.15 · GPT-4o · YOLOv8 · Next.js]
```

---

```bash
meet@robotics:~$ cat ~/projects/humanoid-rl-platform/README.md
```
```
[Humanoid Robot Programming Platform]  MuJoCo · Newton RL · NVIDIA Isaac Lab · GCP

  • PPO RL pipeline for Unitree G1 (29-DOF pick-and-place) on Newton + MuJoCo-Warp
    └─ 4,096 parallel envs · 351-dim stacked obs vector · target-relative encoding
    └─ Policy generalises across arbitrary scanned 3D objects

  • Dual-simulator 3D asset pipeline (MuJoCo + Isaac Lab)
    └─ 1,000+ real-world scans ingested from Polyhaven, SAM-3D, Blender-3D, Meshy AI
    └─ Automated CoACD collision-hull generation + physics inference (mass, friction, tags)
    └─ GLB → USD/MJCF conversion: 30+ min  →  < 60 sec per asset

  • 8-skill manipulation library: walk · pick · place · press · turn · open · close
    └─ FastAPI / React / Supabase stack with row-level security + versioned migrations
    └─ Multi-VM GPU infra on GCP (A100, L4) for parallel RL training + motion inference
```

---

```bash
meet@robotics:~$ cat ~/projects/bimanual-teleoperation/README.md
```
```
[Real-Time Bimanual Hand Teleoperation]  Isaac Sim 5.1 · ROS2 · MuJoCo · MediaPipe

  • MediaPipe hand landmarks (30 fps) → 7-DOF Franka Panda via differential IK
    └─ PhysX Jacobians in NVIDIA Isaac Sim 5.1
    └─ Validated in MuJoCo before porting to Isaac Lab

  • UDP socket bridge between ROS2 ↔ Isaac Sim
    └─ DLS damping (λ=0.05) + velocity clamping → stable IK across all 7 joints
    └─ Achieved pick-and-place and stacking in simulation
```

---

```bash
meet@robotics:~$ git log --oneline --graph ~/experience
```
```
* b3f2a1c  (HEAD)  Robotics Engineer – humanoid RL + teleoperation pipelines
* 7e91d4f  Autonomous Navigation Lead – Mars Rover Manipal
|           └ ROS · YOLOv7 (94% mAP@0.5) · A* + DWA · Kalman filter · $20K UGV
|           └ 95% path-planning accuracy · international competition placements
* 4c82b0e  Robotics Intern – Articulus Surgical (IIT Kharagpur)
|           └ 7-DOF surgical arm (da Vinci) · PID + IK · ~1 cm positional accuracy
|           └ STM32 + IMU via UART/I2C/SPI at 100k Hz · bilateral teleoperation
* 1fa55d9  Research Intern – ARTPARK / IISc Bangalore
            └ SLAM-based autonomous docking
```

---

```bash
meet@robotics:~$ ros2 pkg list | grep -E "active|installed"
```
```
[Robotics]   ROS2 · MuJoCo · Isaac Lab · Isaac Sim · Gazebo · CARLA · ORB-SLAM3 · Foxglove
[Perception] OpenCV · YOLOv7/v8 · MediaPipe · 3DGS · LSS · nuScenes · COLMAP
[ML/RL]      PyTorch · TensorFlow · PPO · Newton RL · HuggingFace · Transformers
[Languages]  Python · C++ · TypeScript · MATLAB · SQL
[AI]         GPT-4o · VLMs · LLM tool-use · FastAPI
[Hardware]   Unitree G1 · Franka Panda · STM32 · IMU · LiDAR
[Infra]      GCP (A100/L4) · Docker · AWS · CI/CD · Git
```

---

```bash
meet@robotics:~$ cat ~/.publications
```
```
[1] Meet Hitesh Jain. "Adaptive control strategies for button motor actuated
    insect-scale flapping wing MAV mechanisms."
    Scientific Reports – Nature Portfolio, 2025

[2] Meet Hitesh Jain. "Empowering Pandemic Resilience: Simulation of Integrating
    IoT Innovation to Curtail Mortality."
    Journal of Telematics and Informatics Reports, 2024
    Presented @ ICCMEH 2023, Malaysia
```

---

```bash
meet@robotics:~$ cat /proc/currently-building
```
```
  humanoid-rl-platform      [running]   PPO on Unitree G1 · 4096 envs on GCP
  3d-asset-pipeline         [running]   GLB → MJCF/USD at scale
  manipulation-skill-lib    [running]   8-skill workflow on FastAPI/Supabase
```

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Meetjain-0201&show_icons=true&theme=github_dark&hide_border=true&title_color=00FFB2&icon_color=00FFB2&text_color=c9d1d9&bg_color=0d1117" width="47%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Meetjain-0201&theme=github-dark-blue&hide_border=true&ring=00FFB2&fire=00FFB2&currStreakLabel=00FFB2" width="47%" />

</div>

---

```bash
meet@robotics:~$ echo "Open to robotics engineering roles · meetjain0201@gmail.com"
```
