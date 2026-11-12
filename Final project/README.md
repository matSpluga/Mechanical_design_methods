# Mechanical Design Methods – Group 9

## Project Overview

This project presents the mechanical design of a customized gripper for lifting a **Rzeppa half-shaft constant-velocity (CV) joint** from a dedicated transport tray.

The proposed solution is based on the existing **Jodell gripper base frame** and is designed to handle half-shaft joints with graspable cylindrical sections ranging from **25 mm to 35 mm** in diameter. The design addresses the asymmetric mass distribution of the component, which can cause it to tilt during lifting.

The project focuses on the mechanical design, kinematic operation, component selection, assembly, and verification of the final gripper.

## Design Requirements

The design is developed around the following requirements:

- **Diameter adaptability:** accommodate graspable shaft sections between 25 mm and 35 mm.
- **Restricted contact areas:** the claws grip the intermediate non-threaded cylindrical section, while the buffer contacts the threaded section only along its axis.
- **Surface protection:** rubber layers are used at contact points to reduce wear and prevent slipping.
- **Load stability:** compensate for the gravity-induced moment caused by the offset centre of mass.
- **Jodell compatibility:** use the two existing linear sliders without adding further actuators.

## Final Design

The final mechanism consists of an **under-actuated, two-claw quadrilateral linkage** integrated with the Jodell gripper and a mechanical buffer.

The main elements are:

- **Claw base and slider:** connect the mechanism to the Jodell linear sliders.
- **Proximal link:** makes the first contact with the cylindrical shaft section.
- **Distal link:** guides the closing motion of the claw.
- **Triangular hugger:** completes the gripping structure and supports the shaft from below.
- **Return springs:** maintain the initial claw configuration and enable passive movement during gripping.
- **Mechanical buffer:** contacts the threaded section and generates a counter-moment to keep the half-shaft approximately horizontal.
- **Transport tray:** supports and positions the half-shaft before the gripping operation.

## Operating Principle

The gripping sequence is based on one actively driven prismatic motion followed by passive rotations in the linkage:

1. **Linear approach:** the Jodell sliders move the claw bases towards the half-shaft.
2. **Initial stabilization:** the rubber tip of the mechanical buffer contacts the threaded section first, helping counteract the moment caused by the offset centre of mass.
3. **First claw contact:** the proximal links touch the non-threaded cylindrical section.
4. **Passive closure:** continued slider motion compresses the springs and causes the distal links and triangular huggers to rotate around their revolute joints.
5. **Lifting:** the claws secure the shaft while the buffer helps maintain its horizontal orientation.

The claw kinematic chain is described as **P–R–R–R**: one prismatic pair, driven by the Jodell slider, and three revolute pairs. Only the initial translational motion is actively actuated; the remaining closing motion is passive and spring-assisted.

## Design Development

The report documents several discarded concepts, including a static claw and alternative linkage and arm configurations. These solutions were evaluated in terms of:

- Mechanical complexity
- Grip reliability
- Adaptability to different shaft diameters
- Ease of assembly and manufacturing

The final under-actuated design was selected as a compromise between adaptability, reliability, and manufacturing simplicity.

## Requirement Verification

The final design is assessed against the original requirements:

| Requirement | Design response |
|---|---|
| 25–35 mm graspable diameter range | The quadrilateral claws adapt to the required range through the slider stroke and linkage motion. |
| Restricted contact areas | The claws contact the non-threaded cylindrical section; the buffer contacts the threaded section axially. |
| Surface protection | Rubber material is applied to the claw and buffer contact points. |
| Load stability | The buffer generates a counter-moment to reduce gravity-induced tilting during lifting. |
| Compatibility with the Jodell base | The mechanism is driven by the existing two linear sliders, with no additional actuator. |

## CAD and Design Tools

The report describes the use of **Creo Parametric** for the CAD design, component modelling, mechanism views, and assembly presentation. The half-shaft CAD model was imported from SolidWorks.

The report includes component views, mechanism configurations, exploded assembly views, and a final CAD test of the gripper closing around the half-shaft.

## Repository Contents

This README summarizes the project described in the report. Refer to the project files for the detailed design documentation, drawings, CAD models, and assembly information, where available.

## Further Information

For a complete explanation of the design process, component dimensions, spring arrangement, mechanical buffer, kinematic closing sequence, assembly, and requirement verification, consult the project report:

**`MDM_report_group_9.pdf`**

## Authors

- Antonio Mazzotta
- Francesco Sisani
- Matteo Spluga

**Course:** Mechanical Design Methods  
**Academic Year:** 2025/2026  
**Group:** 9
