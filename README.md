# Sanghoon Lee · ROSanghoon

**Postdoctoral Researcher at DGIST · ROS 2 middleware and reliable robotic systems**

I build tools for robot communication and middleware that helps learned controllers operate reliably. My research connects **ROS 2, DDS, and Zenoh** with **Cyber-Physical AI**: making intelligent systems work under real network and resource constraints.

[Website](https://hun0130.github.io/) · [Google Scholar](https://scholar.google.co.kr/citations?user=W2iqqvAAAAAJ&hl=en) · [LinkedIn](https://www.linkedin.com/in/sanghoon-lee-1b5929301) · [Email](mailto:leesh2913@dgist.ac.kr)

## Tools I work on

| Project | What you can do with it | Explore |
| --- | --- | --- |
| **[ros2probe](https://github.com/csi-dgist/ros2probe)** | Inspect ROS 2 middleware traffic, reconstruct the graph, and examine topic metrics through a CLI or desktop GUI. | [Demo & project page](https://csi-dgist.github.io/ros2probe-page/) · [Install](https://github.com/csi-dgist/ros2probe#install) |
| **[ROS 2 Harness Profile](https://github.com/csi-dgist/ros2-harness-profile)** | Constrain learned-controller outputs, reject stale commands, and switch to a fallback through ROS 2 interfaces. | [Project & experiments](https://csi-dgist.github.io/ros2-harness-profile/) · [Paper](https://arxiv.org/abs/2606.09416) |
| **[DDS Optimizer](https://github.com/csi-dgist/DDS-Optimizer-for-Wireless-Large-Payload-Transfer)** | Generate DDS XML profiles for large-payload communication over wireless networks. | [Code & usage](https://github.com/csi-dgist/DDS-Optimizer-for-Wireless-Large-Payload-Transfer) · [Paper](https://arxiv.org/abs/2508.11366) |
| **[QoS Guard](https://github.com/csi-dgist/QoS-Guard)** | Check ROS 2 QoS configurations for conflicts before deployment. | [Documentation](https://csi-dgist.github.io/QoS-Guard/) · [Paper](https://arxiv.org/abs/2509.03381) |
| **[LIMA](https://github.com/csi-dgist/LIMA)** | Coordinate dense multi-robot traffic using global routes and local intersection control; simulate and replay warehouse scenarios. | [Project page](https://csi-dgist.github.io/LIMA-page/) · [Code & usage](https://github.com/csi-dgist/LIMA) |

These projects are developed with collaborators at **[DGIST CSI Lab](https://github.com/csi-dgist)**. I am a **co-first author and project contact for ros2probe**, a **co-first author of LIMA**, and the **first author** of the Harness Engineering, wireless DDS optimization, and QoS Guard papers. The linked papers and project pages credit the full research teams.

<a href="https://csi-dgist.github.io/ros2probe-page/">
  <img src="https://raw.githubusercontent.com/csi-dgist/ros2probe/main/docs/demo-gui.gif" alt="ros2probe desktop demo showing the ROS graph, topic metrics, and recording" width="760">
</a>

## Recent public work

- **September 2026** — [ros2probe v0.2.1](https://github.com/csi-dgist/ros2probe/releases/tag/v0.2.1): CLI and desktop tools for ROS 2 middleware observability.
- **August 2026** — [ros2probe](https://arxiv.org/abs/2606.10746) and [Harness Engineering for Physical AI](https://arxiv.org/abs/2606.09416) accepted at ACM Middleware 2026. [Announcement](https://hun0130.github.io/#news)
- **August 2026** — The [QoS dependency analysis and QoS Guard paper](https://arxiv.org/abs/2509.03381) accepted to IEEE Internet of Things Journal. [Announcement](https://hun0130.github.io/#news)

## Papers with research code

| Research | Publication / status | Code & project |
| --- | --- | --- |
| [Harness Engineering for Physical AI: Robot Middleware Is the Harness Layer](https://arxiv.org/abs/2606.09416) | ACM Middleware 2026, Big Ideas · accepted | [ROS 2 Harness Profile](https://github.com/csi-dgist/ros2-harness-profile) · [Project & experiments](https://csi-dgist.github.io/ros2-harness-profile/) |
| [ros2probe: Non-intrusive, Kernel-selective Observability for Robot Operating System 2 Middleware](https://arxiv.org/abs/2606.10746) | ACM Middleware 2026 · accepted | [ros2probe](https://github.com/csi-dgist/ros2probe) · [Project & demo](https://csi-dgist.github.io/ros2probe-page/) |
| [Dependency Chain Analysis of ROS 2 DDS QoS Policies: From Lifecycle Tutorial to Static Verification](https://arxiv.org/abs/2509.03381) | IEEE Internet of Things Journal · accepted | [QoS Guard](https://github.com/csi-dgist/QoS-Guard) · [Documentation](https://csi-dgist.github.io/QoS-Guard/) |
| [Optimizing ROS 2 Communication for Wireless Robotic Systems](https://arxiv.org/abs/2508.11366) | Preprint, 2025 | [DDS Optimizer](https://github.com/csi-dgist/DDS-Optimizer-for-Wireless-Large-Payload-Transfer) · [Paper](https://arxiv.org/abs/2508.11366) |
| [LIMA: Local Intersection Marshalling Architecture for Scale-Independent Multi-Agent Path Finding in Dense Warehouses](https://csi-dgist.github.io/LIMA-page/) | Research manuscript | [Code](https://github.com/csi-dgist/LIMA) · [Project page](https://csi-dgist.github.io/LIMA-page/) · [Page source](https://github.com/csi-dgist/LIMA-page) |
| [Deep Reinforcement Learning-driven Scheduling in Multijob Serial Lines: A Case Study in Automotive Parts Assembly](https://ieeexplore.ieee.org/document/10210628) | IEEE Transactions on Industrial Informatics, 2024 | [PSE_DQN](https://github.com/Hun0130/PSE_DQN) |
| [Real-Time Controller Reconfiguration for Delay-Resilient Cyber-Physical Systems](https://ieeexplore.ieee.org/document/9896851) | IEEE Access, 2022 | [Dynamic-gain-for-delay](https://github.com/Hun0130/Dynamic-gain-for-delay) |

[Full publications, talks, and research background →](https://hun0130.github.io/)

I welcome discussions with developers and researchers working on robotic communication and dependable Physical AI. For tool questions and reproducible bugs, please use the relevant repository's issue tracker.

**Follow [@Hun0130](https://github.com/Hun0130) for ROS 2 middleware tools, reproducible experiments, and practical research notes.**
