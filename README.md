# IslandX

[![Swift](https://img.shields.io/badge/Swift-5.10+-orange.svg)](https://swift.org)
[![iOS](https://img.shields.io/badge/iOS-16.0+-blue.svg)](https://developer.apple.com/ios/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 🌐 Introduction / 專案簡介 / 项目简介 / はじめに

* **English:** A lightweight iOS utility built with SwiftUI, demonstrating how to leverage the Apple Picture-in-Picture (PiP) API to display real-time system metrics (CPU, RAM, Disk, Network) with a pixel-perfect, highly-synchronized in-app Dynamic Island live preview.
* **繁體中文:** 一款基於 SwiftUI 的 iOS 系統監控工具，展示如何利用畫中畫（PiP）API 在背景或主畫面即時顯示核心系統數據，並在 App 內嵌入高度同步、像素級還原的「動態島風格」預覽介面。
* **简体中文:** 一款基于 SwiftUI 的 iOS 系统监控工具，展示如何利用画中画（PiP）API 在后台或主屏幕实时显示核心系统数据，并在 App 内嵌入高度同步、像素级还原的“动态岛风格”预览界面。
* **日本語:** SwiftUI で構築された軽量な iOS システムモニター工具です。Apple のピクチャ・イン・ピクチャ（PiP）API を活用して、CPU、RAM、ディスク、ネットワークの状況をリアルタイムで表示し、アプリ内には完全に同期された「Dynamic Island スタイル」のライブプレビューを実装しています。

---

## ⚠️ DISCLAIMER / 免責聲明 / 免責事項

* **English:** This project is for **educational and research purposes only**. It serves as a technical demonstration of iOS background PiP rendering and sandbox cache tracking. Use at your own risk.
* **繁體中文：** 本專案僅供**學術研究與個人學習**使用，主要展示 iOS 畫中畫（PiP）背景渲染技術與沙盒快取追蹤管理。請勿用於任何商業用途，使用者須自行承擔相關風險。
* **简体中文：** 本项目仅供**学术研究与个人学习**使用，主要展示 iOS 画中画（PiP）后台渲染技术与沙盒缓存追踪管理。请勿用于任何商业用途，用户须自行承担相关风险。
* **日本語：** 本プロジェクトは**教育および研究目的のみ**の概念実証です。iOS バックグラウンド PiP レンダリング技術およびサンドボックスキャッシュ追跡管理の技術デモであり、ご利用は自己責任でお願いします。

---

## 🚀 Features / 專案特點 / 项目特点 / 主な機能

### English
* **Real-Time PiP Monitor:** Displays CPU, RAM, Disk, and Network speed continuously over any app or on the home screen.
* **Dual-Metric Layouts:** Supports side-by-side combined metrics perfectly aligned across a clean double-line interface.
* **Dynamic In-App Preview:** Exact SwiftUI replica of the PiP capsule frame with responsive text and geometry alignment.
* **Intelligent Threshold Alerts:** Icons dynamically switch colors (Green/Yellow/Red) based on performance loads and thermal states.
* **Cache Utility:** Sandbox cache manager with real-time size computation and one-tap cleanup alerts.

### 繁體中文
* **即時畫中畫監控：** 在主畫面或其他 App 上方持續顯示 CPU、RAM、磁碟容量與網路速度。
* **雙重指標佈局：** 支援並排組合數據（如 CPU/RAM），在乾淨的雙行介面中完美對齊顯示。
* **動態 App 內預覽：** 完美復刻實體 PiP 的 SwiftUI 膠囊元件，具備動態文字與進度條響應。
* **智慧門檻警示：** 系統圖示根據當前硬體負載與發熱狀態（Thermal State）自動切換綠/黃/紅燈。
* **快取管理工具：** 內建沙盒快取即時大小計算，並提供一鍵清理的互動式確認彈窗。

### 简体中文
* **实时画中画监控：** 在主屏幕或其他 App 上方持续显示 CPU、RAM、磁盘容量与网络速度。
* **双重指标布局：** 支持并排组合数据（如 CPU/RAM），在干净的双行界面中完美对齐显示。
* **动态 App 内预览：** 完美复刻实体 PiP 的 SwiftUI 胶囊组件，具备动态文字与进度条响应。
* **智能门槛警示：** 系统图标根据当前硬件负载与发热状态（Thermal State）自动切换绿/黄/红灯。
* **缓存管理工具：** 内置沙盒缓存实时大小计算，并提供一键清理的交互式确认弹窗。

### 日本語
* **リアルタイム PiP モニター：** 他のアプリの上やホーム画面で、CPU、RAM、ディスク、ネットワーク速度を継続的に表示。
* **デュアルメトリクス表示：** 2 つの指標（例：CPU/RAM）を並列させ、クリーンな 2 行のインターフェースに美しく配置。
* **アプリ内ライブプレビュー：** 実際の PiP 形状を再現した SwiftUI カプセルビューで、文字やゲージの位置を完全同期。
* **スマート警告アラート：** ハードウェアの負荷やサーマルステート（発熱状況）に応じて、アイコンの色が動的に変化（緑/黄/赤）。
* **キャッシュクリーナー：** サンドボックス内のキャッシュ容量をリアルタイム計算し、ワンタップで削除できる確認アラートを搭載。

---

## 📄 License / 授權條款 / 授权条款 / ライセンス

* **English:** This project is open-sourced under the [MIT License](LICENSE).
* **繁體中文：** 本專案採用 [MIT 授權條款](LICENSE) 開源。
* **简体中文：** 本项目采用 [MIT 授权条款](LICENSE) 开源。
* **日本語：** 本プロジェクトは [MIT ライセンス](LICENSE) のもとでオープンソースとして公開されています。
