# iOS PiP System Monitor (Dynamic Island Style)

[![Swift](https://img.shields.io/badge/Swift-5.10+-orange.svg)](https://swift.org)
[![iOS](https://img.shields.io/badge/iOS-16.0+-blue.svg)](https://developer.apple.com/ios/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A lightweight and elegant iOS utility built with SwiftUI, demonstrating how to leverage the Apple Picture-in-Picture (PiP) API to display real-time system metrics (CPU, RAM, Disk, Network) with a pixel-perfect, highly-synchronized in-app Dynamic Island live preview.

> **⚠️ DISCLAIMER / 免責聲明**
> 
> **English:** This project is for **educational, research, and personal use only**. It serves as a technical demonstration of iOS background PiP rendering and sandbox cache tracking. Use at your own risk.
> 
> **中文：** 本專案僅供**學術研究、個人學習與技術分享**使用。主要展示 iOS 畫中畫（PiP）背景渲染技術與沙盒快取追蹤管理。請勿用於任何商業用途，使用者須自行承擔相關風險。

---

## Features / 專案特點

* **Real-Time PiP Monitoring:** Continuously displays CPU usage, RAM utilization, Disk space, and Network speed over any app or on the home screen.
* **Dual-Metric Layouts:** Supports side-by-side combined metrics (e.g., CPU/RAM or Net/Disk) aligned perfectly across a clean double-line interface.
* **Dynamic In-App Preview:** Features an exact SwiftUI replica of the PiP capsule frame with pixel-perfect alignment and responsive two-line text support.
* **Intelligent Threshold Alerts:** High-performance hardware icons dynamically switch colors (Green/Yellow/Red) based on active usage levels and thermal states.
* **Cache Monitor & Utility:** Includes a built-in sandbox cache manager with real-time size computation and one-tap cleanup alerts.

## Technical Stack / 技術棧

* **UI Framework:** SwiftUI
* **Rendering Engine:** AVKit & CoreGraphics (`UIGraphicsImageRenderer` for PiP buffer generation)
* **System Metrics:** Kernel & Task APIs (Mach kernel tasks, VM statistics)

---

## Requirements / 運行環境

* iOS 16.0+
* Xcode 15.0+
* Swift 5.10+

---

## Setup Instructions / 如何在本地運行

To run this project on your personal iOS device, you must configure the background capabilities manually in Xcode:

1. Clone this repository to your local machine.
2. Open the project in Xcode.
3. Select your project target, go to **Signing & Capabilities**.
4. Click **+ Capability** and add **Background Modes**.
5. Check the box for **Audio, AirPlay, and Picture in Picture** (Required for continuous PiP updates).
6. Connect your iPhone, select your development team, and press **Run (Cmd + R)**.

---

## License / 授權條款

This project is open-sourced under the [MIT License](LICENSE).
