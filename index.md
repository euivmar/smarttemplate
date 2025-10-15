---
layout: page
title: MRI-Guided Robot-Assisted Prostate Biopsy with SmartTemplate
---

# MRI-Guided Robot-Assisted Prostate Biopsy with SmartTemplate

- Mariana Bernardes - Brigham and Women's Hospital and Harvard Medical School (mcostabernardesmatias@bwh.harvard.edu)
- Junichi Tokuda - Brigham and Women's Hospital and Harvard Medical School (tokuda@bwh.harvard.edu) 

This tutorial demonstrates how to integrate a virtual version of the **SmartTemplate** robotic system with **SlicerROS2** for planning and monitoring MRI-guided robot-assisted prostate biopsies.

## Table of Contents

1. [Prerequisites]({{ site.baseurl }}/prerequisites.html)
   - Required Files
   - Required Software
   - Hardware Requirements
   - Knowledge Prerequisites

2. [Overview]({{ site.baseurl }}/overview.html)
   - Clinical Context
   - Robot-Assisted Solution: SmartTemplate
   - What You'll Do in This Tutorial

3. [SmartTemplate Robot]({{ site.baseurl }}/robot.html)
   - Kinematic Chain
   - Joint Definitions

4. [SmartTemplate Description Package]({{ site.baseurl }}/description.html)
   - What is URDF?
   - Key URDF Files
   - Robot Registration

5. [SmartTemplate ROS2 Nodes]({{ site.baseurl }}/ros2_node.html)
   - Virtual Template
   - World Pose Listener


6. Tutorial Steps
   - [Step 0: Preparation - Launch SmartTemplate and 3D Slicer]({{ site.baseurl }}/0-preparation.html)
   - [Step 1: Load MR images and register ZFrame fiducials]({{ site.baseurl }}/1-load-images.html)
   - [Step 2: Load SmartTemplate robot in 3DSlicer]({{ site.baseurl }}/2-load-robot.html)
   - [Step 3: Register SmartTemplate to the scanner]({{ site.baseurl }}/3-register-smarttemplate.html)
   - [Step 4: Make a straight needle insertion using the robot GUI]({{ site.baseurl }}/4-straight-needle-insertion.html)
   - [Step 5: Make a targeted insertion using SlicerROS2 publishers]({{ site.baseurl }}/5-targeted-insertion.html)
   - [Step 6: Read needle position using SlicerROS2 subscriber]({{ site.baseurl }}/6-read-needle-position.html)
   - [Step 7: Send a robot command using SlicerROS2 publishers]({{ site.baseurl }}/7-send-robot-command.html)


