# FPGA-Accelerated CNN Inference

## Overview
This project explores accelerating Convolutional Neural Network (CNN) inference on embedded edge devices using FPGA-based hardware acceleration. A lightweight CNN is first implemented and benchmarked on an ARM CPU, followed by an HLS-based accelerator targeting Xilinx Zynq platforms.

## Objectives
- Implement a lightweight CNN for image classification
- Measure inference latency on CPU (software-only)
- Design a CNN accelerator using Vitis HLS
- Compare CPU vs FPGA performance

## Technology Stack
- Python (CNN training and CPU inference)
- OpenCV (image preprocessing)
- Vitis HLS (hardware accelerator)
- C/C++ (hardware and host code)

## Project Status
- Initial setup completed  
- CNN software baseline in progress
