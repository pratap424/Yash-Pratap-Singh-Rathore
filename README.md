# Yash Pratap Singh Rathore

M.Tech (Research) in Robotics, IIT Mandi — Centre for AI and Robotics.

I work on semantic perception for autonomous UAVs under edge compute constraints. The
recurring result across my projects is that on constrained hardware the useful operating
metric is not per-frame accuracy but **calibrated confidence**: small models are reliable
inside a measured competence region, and the final decision belongs in code rather than in
the network.

Most of my systems run on an 8GB Jetson Orin Nano that is shared with a real-time flight
control loop, which sets the budget for everything else.

**Interests:** edge inference and model optimization · vision-language models ·
out-of-distribution and anomaly detection · visual SLAM and monocular depth · UAV autonomy

---

## Publications

| Work | Venue | Role |
|---|---|---|
| AerialGuard: Edge-Deployed Zero-Shot Visual Anomaly Detection for Autonomous UAV Patrol | IEEE CASE 2026 — accepted | First author |
| FastSpatial: Real-Time Spatial Reasoning for Edge-Deployed Autonomous Drones | IEEE RA-L — in preparation | First author |
| AMORE: Adaptive Multi-objective Reward Engineering for Socratic Math Tutoring with Small Language Models | ICANN 2026, Springer LNCS | Co-author |
| Towards Blind and Low-Vision Accessibility of Lightweight VLMs and Custom LLM-Evals | MMLoSo 2025, ACL Workshop | Co-author |

Indian patent granted (2024) — AI-integrated multi-sensor assistive navigation and health
monitoring for visually impaired individuals.

---

## Selected repositories

**[pseudo_rgbd_slam](https://github.com/pratap424/pseudo_rgbd_slam)** — Replaces a depth
sensor with a monocular metric depth network and feeds the prediction into ORB-SLAM3. ROS 2,
with the SLAM wrapper written in C++. Trajectory error stays within 1.3x of a real Kinect;
an ablation shows that masking 0.2% of pixels at depth boundaries accounts for a 26.9x
difference in that error.

**[visdrone_mot](https://github.com/pratap424/visdrone_mot)** — Person detection and
multi-object tracking for aerial video, with camera-motion compensation for drone ego-motion.
74.3% MOTA and 76.9% IDF1 on VisDrone-MOT-val, and a measured TensorRT deployment path on
Jetson Orin Nano. Includes a component-by-component ablation.

**[freuid-challenge-2026](https://github.com/pratap424/freuid-challenge-2026)** —
Identity-document fraud detection for the FREUID Challenge 2026 (IJCAI-ECAI). ConvNeXt and
EVA02 ensemble with TTA, roughly 60 GPU-hours, plus an auditable code-freeze trail.

**[AeroGemma](https://github.com/pratap424/AeroGemma)** — Fully offline search-and-rescue
drone running a multimodal model on-device: visual triage, Hindi speech in and out with no
ASR stage, and a live dashboard, all over MAVLink to a PX4 autopilot.

**[Towards-Blind-and-Low-Vision-Accessibility-of-Lightweight-VLMs-and-Custom-LLM-Evals](https://github.com/pratap424/Towards-Blind-and-Low-Vision-Accessibility-of-Lightweight-VLMs-and-Custom-LLM-Evals)**
— Prompting pipelines and two accessibility evaluation frameworks for lightweight
vision-language models, with a local open-LLM judge.

**[AerialGuard](https://github.com/pratap424/AerialGuard)** — Flight footage and figures for
the CASE 2026 paper. Source is held back pending publication.

---

## Awards

- Winner, Robotics Competition, ICSR 2024 — Odense, Denmark
- Winner, Zentej Hackathon, IIT Mandi, 2025

---

## Contact

[yashpratap424@gmail.com](mailto:yashpratap424@gmail.com) ·
[LinkedIn](https://www.linkedin.com/in/ypsrathore/)
