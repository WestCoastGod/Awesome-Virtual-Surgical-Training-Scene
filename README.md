# Awesome-Virtual-Surgical-Training-Scene

A curated collection of simulation platforms, datasets, and papers related to virtual surgical training environments, with emphasis on robotics simulation and AI/AR-assisted surgical training. asdasd

## Contents

- [Simulation Platforms](#simulation-platforms)
  - [Isaac-based Frameworks](#isaac-based-frameworks)
  - [Unity-based Frameworks](#unity-based-frameworks)
- [AI/AR Assistance for Surgical Training](#aiar-assistance-for-surgical-training)
  - [Visual Feedback Systems](#visual-feedback-systems)
  - [Tool Localization](#tool-localization)
  - [Demonstration Data Generation](#demonstration-data-generation)
  - [3D Reconstruction](#3d-reconstruction)
  - [Visual Question Answering](#visual-question-answering)
  - [Low-Fidelity VR Training](#low-fidelity-vr-training)
- [Related Resources](#related-resources)

---

## Simulation Platforms

### Isaac-based Frameworks

Simulation platforms for surgical robotics, primarily focused on Reinforcement Learning applications.

| Platform           | Base Framework   | Key Features                                                                                   | Link                                      | Code |
| ------------------ | ---------------- | ---------------------------------------------------------------------------------------------- | ----------------------------------------- | ---- |
| **ORBIT**          | Nvidia Isaac Gym | Unified simulation framework for interactive robot learning environments (IsaacLab)            | -                                         | -    |
| **ORBIT-Surgical** | ORBIT            | Open-simulation framework for learning surgical augmented dexterity                            | -                                         | -    |
| **SUFIA**          | ORBIT-Surgical   | Language-guided augmented dexterity for robotic surgical assistants                            | -                                         | -    |
| **SUFIA-BC**       | ORBIT-Surgical   | Generating high-quality demonstration data for visuomotor policy learning in surgical subtasks | [Paper](https://arxiv.org/abs/2504.xxxxx) | -    |
| **SonoGym**        | -                | High-performance simulation for challenging surgical tasks with robotic ultrasound             | -                                         | -    |

### Unity-based Frameworks

Simulation platforms built on Unity engine for surgical training and VR applications.

| Platform                                 | Base Framework       | Key Features                                                                                                      | Link                                            | Code |
| ---------------------------------------- | -------------------- | ----------------------------------------------------------------------------------------------------------------- | ----------------------------------------------- | ---- |
| **Low-Fidelity VR Laparoscopic Trainer** | Unity + Meta Quest 2 | Cost-effective VR training for peg transfer tasks with AI-powered assessment (YOLOv8-based automated evaluation)  | [Paper](https://journals.sagepub.com/doi/xxxxx) | -    |
| **Learning Spatial Awareness System**    | Unity + Isaac Sim    | Dual visual training framework combining 2D endoscopic view with 3D MR feedback for laparoscopic surgery training | [Paper](https://arxiv.org/abs/xxxxx)            | -    |

---

## AI/AR Assistance for Surgical Training

### Visual Feedback Systems

| Title                                                                                | Year | Venue | Hardware                                                                                                                                                      | Link                                 | Code |
| ------------------------------------------------------------------------------------ | ---- | ----- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------ | ---- |
| Learning Spatial Awareness for Laparoscopic Surgery with AI Assisted Visual Feedback | 2025 | -     | **Simulation:** NVIDIA Isaac Sim<br>**MR Display:** Meta Quest 3<br>**Controllers:** Quest 3 hand controllers<br>**Compute:** High-performance PC workstation | [Paper](https://arxiv.org/abs/xxxxx) | -    |

### Tool Localization

| Title                                                                                   | Year | Venue        | Hardware                         | Link                                                | Code |
| --------------------------------------------------------------------------------------- | ---- | ------------ | -------------------------------- | --------------------------------------------------- | ---- |
| Real-Time Tool Localization for Laparoscopic Surgery Using Convolutional Neural Network | 2024 | MDPI Sensors | Standard surgical room computers | [Paper](https://www.mdpi.com/1424-8220/24/13/xxxxx) | -    |

### Demonstration Data Generation

| Title                                                                                                    | Year | Venue | Hardware | Link                                      | Code |
| -------------------------------------------------------------------------------------------------------- | ---- | ----- | -------- | ----------------------------------------- | ---- |
| SuFIA-BC: Generating High Quality Demonstration Data for Visuomotor Policy Learning in Surgical Subtasks | 2025 | -     | -        | [Paper](https://arxiv.org/abs/2504.xxxxx) | -    |

### 3D Reconstruction

| Title                                                                                                     | Year | Venue | Hardware | Link                                      | Code |
| --------------------------------------------------------------------------------------------------------- | ---- | ----- | -------- | ----------------------------------------- | ---- |
| EndoSfM3D: Learning to 3D Reconstruct Any Endoscopic Surgery Scene using Self-supervised Foundation Model | 2025 | -     | -        | [Paper](https://arxiv.org/abs/2510.xxxxx) | -    |

### Visual Question Answering

| Title                                                                                                                  | Year | Venue | Hardware                                                                                                                                                                  | Link                                      | Code |
| ---------------------------------------------------------------------------------------------------------------------- | ---- | ----- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------- | ---- |
| Surgical-LVLM: Learning to Adapt Large Vision-Language Model for Grounded Visual Question Answering in Robotic Surgery | 2025 | -     | **Training:** NVIDIA A100 GPU<br>**Framework:** PyTorch + Python<br>**Base:** Qwen-VL (Qwen-7B + Vision Transformer)<br>**Deployment:** High-performance compute required | [Paper](https://arxiv.org/abs/2503.xxxxx) | -    |

### Low-Fidelity VR Training

| Title                                                                                                                                                   | Year | Venue | Hardware                                                                                                                                                                                                                       | Link                                            | Code |
| ------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | ----- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------- | ---- |
| Validation of a novel, low-fidelity virtual reality simulator and an artificial intelligence assessment approach for peg transfer laparoscopic training | 2024 | -     | **VR Training:** Meta Quest 2 + 3D-printed physical accessories<br>**AI Assessment:** Intel Core i9-9900KF + NVIDIA RTX 2080 Ti<br>**Traditional Control:** FLS All-In-One Trainer System<br>**Data Capture:** Standard camera | [Paper](https://journals.sagepub.com/doi/xxxxx) | -    |

---

## Related Resources

### Surveys & Reviews

- [Surgical Scene Understanding in the Era of Foundation AI Models: A Comprehensive Review](https://arxiv.org/abs/xxxxx)
- [Deep-Learning-Assisted Analysis of Cataract Surgery Videos](https://arxiv.org/abs/xxxxx)

### Related Awesome Lists

- [Awesome-Surgical-Video-Understanding](https://github.com/isyangshu/Awesome-Surgical-Video-Understanding) - Comprehensive collection of surgical video understanding papers and datasets

---

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
