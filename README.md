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

| Product | Pricing | Free Tier / Limits | Description |
| :--- | :--- | :--- | :--- |
| **[NVIDIA GR00T-WBC](https://nvidia-isaac.github.io/GR00T-WholeBodyControl/)** | Hardware Cost (Jetson) | **Free for Individuals** | Foundation models and Isaac Sim/Lab are free for researchers and small teams. |
| **[OpenLoong (Dyn-Control)](https://openloong.org.cn/)** | **Free** (Apache 2.0) | **Unlimited** | Open-source control stack for the Qinglong humanoid series. |
| **[Unitree SDK (EDU)](https://www.unitree.com/)** | **$43,900 – $73,900** | **None** | Required for low-level whole-body control on G1 and H1 humanoids. |
| **[Spot SDK (Boston Dynamics)](https://bostondynamics.com/)** | **$75,000+** | **None** | Advanced API for balance and locomotion; requires enterprise license. |
| **[Flowstate (Intrinsic)](https://intrinsic.ai/)** | **Contact for Quote** | **Demo by request** | Alphabet's AI-enabled motion planning and whole-body force control platform. |

### Advanced Tools

**Other notable mentions**: Commercial extensions of Pinocchio and various vendor-specific WBC stacks from companies like PAL Robotics (TALOS/REEM-C) and Agility Robotics (Digit).

## Open-Source GitHub Projects

### Dedicated Whole-Body Control Frameworks

- **[Pinocchio](https://github.com/stack-of-tasks/pinocchio)**  
  Fast and efficient rigid body dynamics library with state-of-the-art whole-body control algorithms. Widely used as the foundation for humanoid control stacks.

- **[Crocoddyl](https://github.com/loco-3d/crocoddyl)**  
  Optimal control library for complex robotics tasks with excellent support for whole-body control, trajectory optimization, and contact-rich scenarios.

- **[RBDL (Rigid Body Dynamics Library)](https://github.com/rbdl/rbdl)**  
  Highly efficient C++ library for rigid body dynamics with strong whole-body control applications.

- **[qpOASES](https://github.com/coin-or/qpOASES)**  
  Reliable and fast quadratic programming solver widely used in real-time whole-body control implementations.

- **[eiquadprog](https://github.com/eiquadprog/eiquadprog)**  
  Efficient C++ quadratic programming solver optimized for whole-body control and constrained optimization.

- **[Pink](https://github.com/stack-of-tasks/pink)**  
  Python library for inverse kinematics and whole-body control built on top of Pinocchio.

- **[ARC-OPT WBC](https://github.com/search?q=arc-opt+wbc)**  
  Open-source whole-body control solver with advanced optimization capabilities.

- **[OpenWBT](https://github.com/search?q=openwbt)**  
  Open Whole-Body Toolbox for humanoid control with modular architecture.

- **[KungfuBot / PBHC (Priority-Based Hierarchical Control)](https://github.com/search?q=pbhc+humanoid)**  
  Priority-based hierarchical whole-body control frameworks for dynamic humanoid locomotion.

- **[OCS2 (ETH Zürich)](https://github.com/leggedrobotics/ocs2)**  
  Open-source Control Software 2 — a powerful toolbox for optimal control and whole-body control of legged robots.

### Additional Strong Open-Source Options

- **[raisim](https://github.com/leggedrobotics/raisim)** — High-performance physics engine with WBC examples.
- **[Drake](https://github.com/RobotLocomotion/drake)** — Model-based design and control toolbox with strong robotics support.
- **[MuJoCo](https://github.com/google-deepmind/mujoco)** — Advanced physics simulator with whole-body control research examples.
- **[Cartpole / Humanoid WBC benchmarks](https://github.com/search?q=humanoid+wbc+benchmark)** — Many community repositories.
- **Stack-of-Tasks** ecosystem (Pinocchio + Pink + TSID) for hierarchical control.

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