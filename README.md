# Smart Vision Robotic Car

An automated logistics and surveillance robotic car powered by a Raspberry Pi 3A. This robot features a dual-mode control system, allowing it to transition seamlessly between autonomous tracking and active remote piloting via a mobile application.

**Operational Modes**
1. **Autonomous Mode:** Line following and color/object tracking relying on onboard logic and sensor processing.
2. **Remote Mode:** Manual override and piloting via IoT mobile app connectivity, paired with active object avoidance.

**System Architecture & Hardware**
* **Compute:** Raspberry Pi 3A running Python-based control and vision scripts.
* **Vision & Sensors:** RPi Camera v1 for live video streaming, combined with IR and color sensors for navigation.
* **Actuation:** Motor driver (L298N) managing chassis movement.

**Impact & Metrics**
* Achieved 95% routing and path accuracy during automated logistics tasks.
* Maintained active IR object avoidance and low-latency live streaming across both operating modes.

**License**
Copyright (c) 2026 @glADIatorADI. All Rights Reserved. No permission is granted to use, copy, modify, or distribute this code.
