# Robot Dog Preliminary Mechanical Design

## Overview

This project presents a simple preliminary mechanical design for a quadruped (four-legged) robot dog. The objective is to understand the basic mechanical concepts that enable a robot to stand, maintain balance, and perform simple walking motions.

This project focuses only on the mechanical design and does not include electronics, sensors, or programming.

---

## Mechanical Design

![Robot Dog Design](images/robot-dog-design.png)

---

## Project Objectives

The main objectives of this project are:

- Design a simple robot body structure.
- Design four mechanical legs.
- Determine the number of joints and degrees of freedom (DOF).
- Select suitable servo motors.
- Perform an initial torque calculation.
- Study robot stability and center of gravity.
- Suggest a simple walking method.
- Identify expected mechanical challenges.

---

# 1. Body Structure

The robot uses a simple rectangular body because it is easy to manufacture and provides enough space for batteries, electronics, and motors.

### Proposed Dimensions

- Length: 40 cm
- Width: 20 cm
- Height: 10 cm

### Suggested Materials

- Aluminum
- Acrylic
- 3D Printed Plastic

These materials are lightweight and provide sufficient mechanical strength.

---

# 2. Leg Design

The robot has four identical legs.

Each leg contains three joints:

- Hip Joint
- Knee Joint
- Ankle Joint

Total joints:

4 Legs × 3 Joints = **12 Joints**

---

# 3. Degrees of Freedom (DOF)

Each joint rotates around one axis.

Therefore:

- DOF per leg = 3
- Total DOF = 12

This allows the robot to perform basic walking movements while maintaining stability.

---

# 4. Motor Selection

Suggested servo motor:

- MG996R Servo Motor

Reasons for selection:

- Affordable
- Easy to control
- Suitable for educational robot projects
- Provides sufficient torque for a lightweight robot

---

# 5. Preliminary Torque Calculation

### Assumptions

- Robot mass = **3 kg**
- Gravity = **9.81 m/s²**
- Number of legs = **4**
- Distance from the joint to the foot = **0.1 m**

### Step 1: Calculate Weight

Force = Mass × Gravity

Force = 3 × 9.81

Force = **29.43 N**

### Step 2: Load on One Leg

29.43 ÷ 4 = **7.35 N**

### Step 3: Calculate Torque

Torque = Force × Distance

Torque = 7.35 × 0.1

Torque = **0.735 N·m**

### Result

A servo motor capable of producing at least **1 N·m** of torque is recommended to provide a safety margin.

---

# 6. Stability and Center of Gravity

The robot's center of gravity should remain close to the middle of the body and as low as possible.

This improves balance and reduces the risk of tipping over while standing or walking.

---

# 7. Proposed Walking Method

The proposed walking method is **Static Walk**.

Walking sequence:

1. Front Left Leg
2. Rear Right Leg
3. Front Right Leg
4. Rear Left Leg

Only one leg moves at a time while the other three remain on the ground, providing high stability.

---

# 8. Expected Mechanical Challenges

Possible challenges include:

- Robot imbalance
- Weak servo motors
- Joint friction
- Leg vibration
- Battery weight
- Mechanical wear
- Slipping on smooth surfaces

---

# Conclusion

This preliminary mechanical design demonstrates the basic principles required for a quadruped robot to stand and walk.

Although the design is simple, it introduces important engineering concepts such as body structure, leg design, degrees of freedom, torque calculation, stability, and walking strategy.

Future improvements may include sensors, advanced controllers, stronger motors, and optimized mechanical components.
