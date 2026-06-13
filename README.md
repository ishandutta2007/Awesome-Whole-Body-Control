# Awesome-Whole-Body-Control
## Top Whole-Body Control Softwares for Humanoid Robots Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Whole-Body Control, Dynamics & Locomotion for Humanoids*  
**Last updated: March 2026**

This repository tracks notable **platforms** and **open-source projects** for **Whole-Body Control (WBC)** in humanoid robots. These tools solve the complex problem of coordinating all joints simultaneously to achieve balanced, dynamic, and compliant locomotion, manipulation, and interaction in real-world environments.

**Examples** include Pinocchio, RBDL, NVIDIA GR00T-WholeBodyControl, OpenLoong (Dyn-Control), ARC-OPT WBC, qpOASES, eiquadprog, Pink, Crocoddyl, OCS2, KungfuBot / PBHC, and OpenWBT (the category leaders). Tools listed here emphasize **real-time performance**, quadratic programming solvers, hierarchical control, and integration with modern simulators.

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, local development, full customization, and research reproducibility — ideal for robotics researchers, humanoid developers, and open-source contributors.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Proprietary / Commercial Tools](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Proprietary / Commercial Tools

This section lists commercial platforms and SDKs that provide advanced whole-body control capabilities, often integrated with specific hardware.

| Product | Company Size (Valuation) | Pricing | Free Tier / Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[NVIDIA GR00T-WBC](https://nvidia-isaac.github.io/GR00T-WholeBodyControl/)** | **~$3.5 Trillion** | Hardware Cost (Jetson) | **Free for Individuals** | Foundation models and Isaac Sim/Lab are free for researchers and small teams. |
| **[Flowstate (Intrinsic)](https://intrinsic.ai/)** | **~$2.1 Trillion** (Alphabet) | **Contact for Quote** | **Demo by request** | Alphabet's AI-enabled motion planning and whole-body force control platform. |
| **[Spot SDK (Boston Dynamics)](https://bostondynamics.com/)** | **~$25 Billion** (Est.) | **$75,000+** | **None** | Advanced API for balance and locomotion; requires enterprise license. |
| **[Unitree SDK (EDU)](https://www.unitree.com/)** | **~$1.5 Billion** | **$43,900 – $73,900** | **None** | Required for low-level whole-body control on G1 and H1 humanoids. |
| **[OpenLoong (Dyn-Control)](https://openloong.org.cn/)** | **~$140 Million** (Reg. Cap) | **Free** (Apache 2.0) | **Unlimited** | Open-source control stack for the Qinglong humanoid series. |

### Advanced Tools

**Other notable mentions**: Commercial extensions of Pinocchio and various vendor-specific WBC stacks from companies like PAL Robotics (TALOS/REEM-C) and Agility Robotics (Digit).

## Open-Source GitHub Projects

This section lists the most active and widely used open-source projects for whole-body control, dynamics, and simulation, sorted by GitHub popularity.

- **[MuJoCo](https://github.com/google-deepmind/mujoco)** ![GitHub stars](https://img.shields.io/github/stars/google-deepmind/mujoco?style=flat-square)  
  Advanced physics simulator with state-of-the-art contact dynamics, widely used for training whole-body control policies via reinforcement learning.

- **[Drake](https://github.com/RobotLocomotion/drake)** ![GitHub stars](https://img.shields.io/github/stars/RobotLocomotion/drake?style=flat-square)  
  A C++ toolbox for model-based design and optimization, providing industry-grade tools for control, estimation, and motion planning.

- **[Pinocchio](https://github.com/stack-of-tasks/pinocchio)** ![GitHub stars](https://img.shields.io/github/stars/stack-of-tasks/pinocchio?style=flat-square)  
  The industry-standard rigid body dynamics library. Fast, efficient, and the foundation for many humanoid whole-body control stacks.

- **[OCS2](https://github.com/leggedrobotics/ocs2)** ![GitHub stars](https://img.shields.io/github/stars/leggedrobotics/ocs2?style=flat-square)  
  Open-source Control Software 2 — a powerful toolbox for optimal control and whole-body control of legged robots (ETH Zürich).

- **[Crocoddyl](https://github.com/loco-3d/crocoddyl)** ![GitHub stars](https://img.shields.io/github/stars/loco-3d/crocoddyl?style=flat-square)  
  Optimal control library for complex robotics tasks with excellent support for trajectory optimization and contact-rich scenarios.

- **[Pink](https://github.com/stephane-caron/pink)** ![GitHub stars](https://img.shields.io/github/stars/stephane-caron/pink?style=flat-square)  
  A Python library for inverse kinematics and whole-body control built on top of Pinocchio, designed for rapid prototyping.

- **[RBDL (Rigid Body Dynamics Library)](https://github.com/rbdl/rbdl)** ![GitHub stars](https://img.shields.io/github/stars/rbdl/rbdl?style=flat-square)  
  Highly efficient C++ library for rigid body dynamics calculations, optimized for real-time control.

- **[qpOASES](https://github.com/coin-or/qpOASES)** ![GitHub stars](https://img.shields.io/github/stars/coin-or/qpOASES?style=flat-square)  
  Reliable and fast quadratic programming solver widely used in real-time whole-body control implementations.

- **[RaiSim](https://github.com/raisimTech/raisimLib)** ![GitHub stars](https://img.shields.io/github/stars/raisimTech/raisimLib?style=flat-square)  
  High-performance physics engine optimized for legged robot simulation and whole-body control research.

- **[eiquadprog](https://github.com/stack-of-tasks/eiquadprog)** ![GitHub stars](https://img.shields.io/github/stars/stack-of-tasks/eiquadprog?style=flat-square)  
  Efficient C++ quadratic programming solver optimized for hierarchical whole-body control.

- **[ARC-OPT WBC](https://github.com/search?q=arc-opt+wbc)**  
  Open-source whole-body control solver with advanced optimization capabilities.

- **[OpenWBT](https://github.com/search?q=openwbt)**  
  Open Whole-Body Toolbox for humanoid control with modular architecture.

- **[KungfuBot / PBHC](https://github.com/search?q=pbhc+humanoid)**  
  Priority-based hierarchical whole-body control frameworks for dynamic humanoid locomotion.

**Frameworks for building custom WBC systems**: Combine **Pinocchio** + **Crocoddyl** + **qpOASES** with **ROS2** and simulators (MuJoCo, Isaac Gym) for full humanoid whole-body control stacks.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Whole-body control for physical robots requires careful safety validation and testing in simulation before real hardware deployment.
- Performance depends heavily on hardware, solver tuning, and specific robot model.

---

**Made for robotics researchers, humanoid developers, and control engineers.**  
Let's make whole-body control more accessible, efficient, and open.