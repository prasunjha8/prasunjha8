<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:07090d,55:0b2a33,100:00e5ff&height=200&section=header&text=Prasun%20Jha&fontSize=56&fontColor=e6edf3&animation=fadeIn&fontAlignY=36&desc=~/robotics%20%E2%80%A2%20robot%20learning%20%E2%80%A2%20autonomous%20navigation%20%E2%80%A2%20multi-robot%20systems&descSize=15&descAlignY=58" alt="Prasun Jha" width="100%"/>

<a href="https://prasunjha8.github.io/">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=19&duration=2800&pause=900&color=00E5FF&center=true&vCenter=true&width=760&lines=%24+ros2+launch+prasun+portfolio.launch.py;%3E+camera-only+socially+aware+navigation;%3E+explainable+multi-robot+task+allocation;%3E+RL+policies+in+sim+%E2%86%92+PID+loops+on+a+microcontroller;Build+it.+Simulate+it.+Measure+it.+Break+it.+Improve+it." alt="Typing animation"/>
</a>

<p>
<a href="https://prasunjha8.github.io/"><img src="https://img.shields.io/badge/portfolio-prasunjha8.github.io-00e5ff?style=for-the-badge&labelColor=0b0f16&logo=googlechrome&logoColor=00e5ff" alt="Portfolio"/></a>
<a href="https://www.linkedin.com/in/prasun-jha-703685216/"><img src="https://img.shields.io/badge/linkedin-prasun--jha-00e5ff?style=for-the-badge&labelColor=0b0f16&logo=linkedin&logoColor=00e5ff" alt="LinkedIn"/></a>
<a href="mailto:prasunjhaofficial@gmail.com"><img src="https://img.shields.io/badge/email-say_hello-ff5a1f?style=for-the-badge&labelColor=0b0f16&logo=gmail&logoColor=ff5a1f" alt="Email"/></a>
<a href="https://prasunjha8.github.io/Prasun_Jha_Resume.pdf"><img src="https://img.shields.io/badge/resume-pdf-ff5a1f?style=for-the-badge&labelColor=0b0f16&logo=readme&logoColor=ff5a1f" alt="Resume"/></a>
</p>

<img src="https://img.shields.io/badge/●_status-open_to_research_internships-3dfc8a?style=flat-square&labelColor=0b0f16" alt="status"/>

</div>

---

### `01.` about_me

```yaml
# prasun@robolab:~$ ros2 param dump /prasun_jha
name:       Prasun Jha
degree:     Integrated BS-MS, Mathematics & Computing
school:     BIT Mesra, Ranchi  (2024 – 2029)
role:       General Secretary, Robolution (Robotics Club)
focus:      [robot_learning, embodied_ai, autonomous_navigation, sim_to_real, multi_robot_systems, marl]
philosophy: "I care about the maths behind a working system, not only the fact that it runs."
aiming_for: graduate research in robot learning & embodied intelligence
```

I build robots that **perceive, decide and act**, from reinforcement-learning policies in simulation down to
Kalman-filtered PID loops on an ESP8266.

---

### `02.` research_&_projects

<table>
<tr>
<td width="50%" valign="top">

#### 🛰️ [Vision-Guided Socially Aware Navigation](https://github.com/prasunjha8/social-nav-research)
<sub>`● ongoing research` · 2026 – present</sub>

```bash
$ ros2 launch social_nav hospital_corridor.launch.py
```
Camera-only assistive navigation, with **no LiDAR and no depth**. ORCA (RVO2) crowds, an airport-terminal stress test, a PPO baseline,
and VLM-derived scene semantics for observations and reward shaping.

`ROS 2 Humble` `Gazebo Fortress` `PPO` `SB3` `OpenCV` `VLMs` `RVO2`

</td>
<td width="50%" valign="top">

#### 🤖 [Fuzzy Robot Coordinator](https://github.com/prasunjha8/fuzzy-robot-coordinator)
<sub>`● built` · 2026</sub>

```bash
$ python -m coordinator --sim mujoco --robots 3
```
Explainable multi-robot task allocation using **8 Sugeno fuzzy rules** and exact one-to-one assignment,
with battery-aware charging in a MuJoCo warehouse. Has 17 automated tests.

`Fuzzy Logic` `MRTA` `Optimization` `MuJoCo` `Python`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🧭 [Nav2 Bring-up from Scratch · ERIC Robotics](https://github.com/prasunjha8/level01_ros_assignment-ERIC_Robotics)
<sub>`● built` · Oct 2026</sub>

Built map_server, AMCL and the Nav2 servers by hand and fixed 10 starter bugs, including a `/tf` flood
(~330 → 116 msg/s after the fix). AMCL error was **0.02–0.26 m**, and **7/8 goals** were reached within 0.21 m.

`Nav2` `AMCL` `Costmaps` `Cyclone DDS` `URDF`

</td>
<td width="50%" valign="top">

#### 🏍️ [RL Self-Balancing Motorcycle](https://github.com/prasunjha8/catkin_ws)
<sub>`● built` · Jun – Aug 2025</sub>

A **Soft Actor-Critic** agent keeps an unstable two-wheeler upright and drives it to waypoints.
It runs in Gazebo 11 through a custom Gym ↔ ROS bridge, in Docker.

`SAC` `ROS Noetic` `Gazebo` `Docker`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🐢 [TortoiseBot Navigation Stack](https://github.com/prasunjha8/tortoisewithself)
<sub>`● in progress` · 2026 – present</sub>

A Pi 4 edge node (micro-ROS, LiDAR, camera) talks to a Pi 5 Docker (Jazzy) compute node over DDS.
Includes a URDF/TF2 tree, SLAM Toolbox and Nav2.

`ROS 2 Jazzy` `Nav2` `SLAM` `micro-ROS`

</td>
<td width="50%" valign="top">

#### ✈️ [Flight Simulation Control](https://github.com/prasunjha8/jsbsim_droame)
<sub>`● in progress` · Apr 2026 – present</sub>

A JSBSim flight-dynamics model (Cessna 172P and custom RC planes) with FlightGear visuals and Python control over UDP.
PID loops are tuned for stable flight under disturbances.

`JSBSim` `FlightGear` `PID` `UDP`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### ⚖️ [Inverted Pendulum on a 4-Wheel Cart](https://github.com/prasunjha8/Inverted-Pendulum-on-a-4-wheel-Cart-)
<sub>`● built` · 2024</sub>

An ESP8266 with an MPU6050, a Kalman filter for angle fusion, and PID driving four DC motors through an L298N.
A Wi-Fi web UI tunes the gains live.

`ESP8266` `Kalman` `PID` `C++`

</td>
<td width="50%" valign="top">

#### 📐 [RL Notes · NPTEL (IIT Madras)](https://prasunjha8.github.io/nptelrl.github.io/index.html)
<sub>`● published` · 2026</sub>

Derivation-first notes on Prof. Ravindran's RL course. They cover Bellman optimality, TD(λ), LSTD,
fitted-Q/DQN, policy gradients and hierarchical RL.

`MDPs` `TD(λ)` `DQN` `Policy Gradient` `HRL`

</td>
</tr>
</table>

<details>
<summary><b><code>// side quests</code></b> (click to expand)</summary>

<br/>

| project | what it is | stack |
|---|---|---|
| [N-D Tic-Tac-Toe](https://github.com/prasunjha8/multidimension-tic-tac-toe-) · [play ↗](https://chah-gamma.vercel.app) | Tic-tac-toe from a 2D plane up to a 6D hypercube, using linear-algebra projections | `React` |
| [IPL Akinator](https://github.com/prasunjha8/ipl-Akinator) | Entropy-maximising questions, $\arg\max_q H(P) - \mathbb{E}[H(P \mid q)]$, over 788 players | `Python` |
| [AgentVerify](https://github.com/prasunjha8/Agentllmcode) | LLM code generation with a sandboxed test-and-self-correct loop | `Python` |
| [ProjectMemoryOS](https://github.com/prasunjha8/ProjectMemoryOS) · [live ↗](https://project-memory-os-chi.vercel.app) | Semantic engineering memory | `FastAPI` `Next.js` `pgvector` |
| [Robocon R1 Concept](https://github.com/prasunjha8/pratyunmish_robocon) | Mecanum-drive R1 CAD and mechanism animations | `CAD` |
| [MUN Ops](https://github.com/prasunjha8/mun-ops) · [live ↗](https://mun-ops.vercel.app) | Real-time event-staff command dashboard | `React` |

</details>

---

### `03.` tech_stack

```text
$ ros2 node list        # each node publishes into the next

/perception   ──▶  OpenCV · YOLOv8 · VLMs · ArUco
/learning     ──▶  PyTorch · Stable-Baselines3 · PPO · SAC · Q-learning · Gymnasium
/planning     ──▶  Nav2 · SLAM Toolbox · ORCA · Fuzzy (Sugeno) · Optimization
/control      ──▶  PID · Kalman Filtering · Task Allocation
/simulation   ──▶  Gazebo · MuJoCo · CoppeliaSim · JSBSim · Blender
/middleware   ──▶  ROS 2 · TF2 · micro-ROS · DDS · Docker · Linux
/hardware     ──▶  ESP32 · ESP8266 · Arduino · Raspberry Pi · Jetson Orin Nano
/languages    ──▶  Python · C++ · C · MATLAB
```

<div align="center">

<img src="https://img.shields.io/badge/ROS_2-0b0f16?style=for-the-badge&logo=ros&logoColor=00e5ff"/>
<img src="https://img.shields.io/badge/PyTorch-0b0f16?style=for-the-badge&logo=pytorch&logoColor=ff5a1f"/>
<img src="https://img.shields.io/badge/OpenCV-0b0f16?style=for-the-badge&logo=opencv&logoColor=00e5ff"/>
<img src="https://img.shields.io/badge/Python-0b0f16?style=for-the-badge&logo=python&logoColor=00e5ff"/>
<img src="https://img.shields.io/badge/C++-0b0f16?style=for-the-badge&logo=cplusplus&logoColor=00e5ff"/>
<img src="https://img.shields.io/badge/Docker-0b0f16?style=for-the-badge&logo=docker&logoColor=00e5ff"/>
<img src="https://img.shields.io/badge/Linux-0b0f16?style=for-the-badge&logo=linux&logoColor=ff5a1f"/>
<img src="https://img.shields.io/badge/Raspberry_Pi-0b0f16?style=for-the-badge&logo=raspberrypi&logoColor=ff5a1f"/>
<img src="https://img.shields.io/badge/Arduino-0b0f16?style=for-the-badge&logo=arduino&logoColor=00e5ff"/>
<img src="https://img.shields.io/badge/Blender-0b0f16?style=for-the-badge&logo=blender&logoColor=ff5a1f"/>

</div>

---

### `04.` mission_log

```diff
+ [leadership]   General Secretary · Robolution, Robotics Club, BIT Mesra   (May 2026 – present)
+ [open-source]  GSoC 2026 · two proposals to JdeRobot
! [achievement]  Zonal Runner-up · Ramakrishna Mission Innovation Challenge  (assistive smart glasses)
! [achievement]  Zonal Runner-up · Dassault Systèmes Innovation Program     (foldable 3D-printed helmet)
```

#### `> currently working on`

- [ ] Vision-language models as scene semantics for robot navigation
- [ ] Socially aware navigation for assistive mobility robots
- [ ] Multi-robot coordination and task allocation
- [ ] Reinforcement learning for physical systems
- [ ] Sim-to-real transfer

---

### `05.` telemetry

<div align="center">

<img src="https://streak-stats.demolab.com?user=prasunjha8&theme=dark&background=07090D&ring=00E5FF&fire=FF5A1F&currStreakNum=E6EDF3&sideNums=E6EDF3&currStreakLabel=00E5FF&sideLabels=8B98A5&dates=8B98A5&hide_border=true" alt="GitHub streak stats"/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/prasunjha8/prasunjha8/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/prasunjha8/prasunjha8/output/github-snake.svg" />
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/prasunjha8/prasunjha8/output/github-snake.svg" />
</picture>

</div>

---

<div align="center">

```text
prasun@robolab:~$ echo $MOTTO
Build it. Simulate it. Measure it. Break it. Improve it.
```

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00e5ff,45:0b2a33,100:07090d&height=110&section=footer" width="100%"/>

</div>
