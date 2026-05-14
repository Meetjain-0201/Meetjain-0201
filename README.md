<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=800&size=28&pause=1000&color=00FFB2&center=true&vCenter=true&width=700&lines=Hi%2C+I'm+Meet+Jain+%F0%9F%A4%96;Robotics+%26+AI+Engineer;Humanoid+Manipulation+%7C+Sim-to-Real;Physical+AI+%E2%80%94+making+robots+work+IRL" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-meetjain0201-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/meetjain0201)
[![Gmail](https://img.shields.io/badge/Gmail-meetjain0201-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:meetjain0201@gmail.com)
[![Scholar](https://img.shields.io/badge/Research-2×_Published-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white)](https://www.sciencedirect.com/science/article/pii/S2772503024000641)
[![GitHub](https://img.shields.io/badge/GitHub-Meetjain--0201-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Meetjain-0201)

</div>

---

```bash
meet@robotics:~$ whoami
> MS AI (Robotics) @ Northeastern University  |  GPA: 3.96  |  Boston, MA
> BTech Mechatronics & Robotics @ Manipal Institute of Technology
> Published researcher · surgical robotics · SLAM · humanoid control · physical AI
```

---

## 🔥 What I'm Building Right Now

<div align="center">

| 🤖 Humanoid RL Platform | ⚡ Asset Pipeline | 🎮 8-Skill Library |
|:---:|:---:|:---:|
| PPO on Unitree G1 (29-DOF) | 1,000+ 3D scans → MJCF/USD | walk · pick · place · press |
| 4,096 parallel envs on GCP | 30 min **→** < 60 sec/asset | turn · open · close · stack |
| Newton + MuJoCo-Warp | Polyhaven · SAM-3D · Meshy AI | FastAPI · React · Supabase |

</div>

---

## 🚀 Projects

### 🦾 Humanoid Robot Programming Platform &nbsp; `Mar 2026 – Present`
> PPO reinforcement learning for Unitree G1 full-body manipulation

- 29-DOF pick-and-place · **4,096 parallel envs** · 351-dim stacked observation with target-relative encoding
- Dual-simulator pipeline (MuJoCo + Isaac Lab) ingesting **1,000+ real-world 3D scans** with auto CoACD collision-hull generation
- GLB → USD/MJCF conversion slashed per-asset onboarding from **30+ min → < 60 sec**
- 8-skill manipulation library shipped on **FastAPI / React / Supabase** · multi-VM GCP infra (A100, L4)

![MuJoCo](https://img.shields.io/badge/MuJoCo-FF6B35?style=flat-square)
![Newton RL](https://img.shields.io/badge/Newton_RL-00D4FF?style=flat-square)
![Isaac Lab](https://img.shields.io/badge/Isaac_Lab-76B900?style=flat-square&logo=nvidia&logoColor=white)
![PPO](https://img.shields.io/badge/PPO-8B5CF6?style=flat-square)
![GCP](https://img.shields.io/badge/GCP_A100/L4-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Unitree G1](https://img.shields.io/badge/Unitree_G1-1A1A2E?style=flat-square)

---

### 🖐 Real-Time Bimanual Hand Teleoperation &nbsp; `Feb – Mar 2026`
> Hand gestures → 7-DOF Franka Panda arm, live

- MediaPipe landmarks (30 fps) → differential IK via **PhysX Jacobians** in NVIDIA Isaac Sim 5.1
- UDP bridge between **ROS2 ↔ Isaac Sim** · DLS damping (λ=0.05) + velocity clamping across all 7 joints
- Validated in MuJoCo before porting to Isaac Lab · achieved pick-and-place + stacking in sim

![Isaac Sim](https://img.shields.io/badge/Isaac_Sim_5.1-76B900?style=flat-square&logo=nvidia&logoColor=white)
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square)
![MuJoCo](https://img.shields.io/badge/MuJoCo-FF6B35?style=flat-square)
![Franka Panda](https://img.shields.io/badge/Franka_Panda-E63946?style=flat-square)

---

### 🗺 Autonomous Navigation Stack &nbsp; `2025`
> Three-phase full-stack autonomy — sensor fusion → SLAM → planning

- **Phase 1** · IMU + LiDAR EKF sensor fusion &nbsp;|&nbsp; **Phase 2** · ORB-SLAM3 localization & mapping &nbsp;|&nbsp; **Phase 3** · A\* + DWA planning

![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo-FF6600?style=flat-square)
![ORB-SLAM3](https://img.shields.io/badge/ORB--SLAM3-1B1F23?style=flat-square)
![EKF](https://img.shields.io/badge/EKF-8B5CF6?style=flat-square)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)

---

### 👁 Visual SLAM &nbsp;|&nbsp; 🐦 BEV Perception &nbsp;|&nbsp; ✨ 3D Gaussian Splatting &nbsp; `2025`

| Project | Stack | Highlight |
|---|---|---|
| **Visual SLAM** | ORB-SLAM3 · ROS2 Humble · Foxglove | Mono + stereo SLAM with live 3D map · APE/RPE eval |
| **BEV Perception** | PyTorch · nuScenes · LSS | IPM baseline vs Lift-Splat-Shoot · full mIoU benchmark |
| **3D Gaussian Splatting** | Python · COLMAP · CUDA | COLMAP SfM → Gaussian init → differentiable rasterization |

---

### 🚗 XAV · Explainable AV Trust Calibration &nbsp; `2024 – 2025`
> Do LLM explanations actually help humans trust self-driving cars?

- GPT-4o VLM on live **CARLA 0.9.15** · YOLOv8 perception · audio narration pipeline
- Williams Latin Square study design · **Next.js + Supabase** live results dashboard

![CARLA](https://img.shields.io/badge/CARLA_0.9.15-1A1A2E?style=flat-square)
![GPT-4o](https://img.shields.io/badge/GPT--4o-412991?style=flat-square&logo=openai&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-00FFFF?style=flat-square)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)

---

## 🏆 Experience

```
🔴 Autonomous Navigation Lead  ·  Mars Rover Manipal                           [2020 – 2023]
   └─ $20K UGV · ROS · YOLOv7 (94% mAP@0.5) · A* + DWA · Kalman filter
   └─ 95% path-planning accuracy · international competition placements

🟡 Robotics Intern  ·  Articulus Surgical, IIT Kharagpur                       [Dec 2022 – Jan 2023]
   └─ 7-DOF surgical arm (da Vinci) · PID + IK · ~1 cm positional accuracy
   └─ STM32 + IMU via UART/I2C/SPI at 100k Hz · real-time bilateral teleoperation

🟢 Research Intern  ·  ARTPARK / IISc Bangalore
   └─ SLAM-based autonomous docking
```

---

## 🛠 Tech Stack

**Robotics & Simulation**

![ROS2](https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![MuJoCo](https://img.shields.io/badge/MuJoCo-FF6B35?style=for-the-badge)
![Isaac Lab](https://img.shields.io/badge/Isaac_Lab-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Isaac Sim](https://img.shields.io/badge/Isaac_Sim-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo-FF6600?style=for-the-badge)
![CARLA](https://img.shields.io/badge/CARLA-1A1A2E?style=for-the-badge)
![Foxglove](https://img.shields.io/badge/Foxglove-8B5CF6?style=for-the-badge)

**Perception & CV**

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv7/v8-00FFFF?style=for-the-badge)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge)
![ORB-SLAM3](https://img.shields.io/badge/ORB--SLAM3-1B1F23?style=for-the-badge)
![3DGS](https://img.shields.io/badge/3D_Gaussian_Splatting-6C3483?style=for-the-badge)

**ML & RL**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PPO](https://img.shields.io/badge/PPO_RL-8B5CF6?style=for-the-badge)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

**Languages & Infra**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## 📄 Publications

```bib
@article{jain2025mav,
  title   = "Adaptive control strategies for button motor actuated insect-scale
             flapping wing MAV mechanisms",
  journal = "Scientific Reports (Nature Portfolio)",
  year    = 2025
}

@article{jain2024iot,
  title   = "Empowering Pandemic Resilience: Simulation of Integrating IoT
             Innovation to Curtail Mortality",
  journal = "Journal of Telematics and Informatics Reports",
  note    = "Presented @ ICCMEH 2023, Malaysia",
  year    = 2024
}
```

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Meetjain-0201&show_icons=true&theme=github_dark&hide_border=true&title_color=00FFB2&icon_color=00FFB2&text_color=c9d1d9&bg_color=0d1117" width="47%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Meetjain-0201&theme=github-dark-blue&hide_border=true&ring=00FFB2&fire=00FFB2&currStreakLabel=00FFB2" width="47%" />

<br/><br/>

![Profile Views](https://komarev.com/ghpvc/?username=Meetjain-0201&label=Profile+Views&color=00FFB2&style=flat-square)

</div>
