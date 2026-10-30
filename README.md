# SORTMARK Bus Servo Mechanism (3D Smart Actuator)

<p align="center">
  <a href="#-english">English</a> | <a href="#-中文说明">简体中文</a> | <a href="#-日本語">日本語</a> | <a href="https://sortmark.com">Official Portal 官网</a>
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License" /></a>
  <a href="https://threejs.org/"><img src="https://img.shields.io/badge/Render-WebGL%20Three.js-amber.svg" alt="WebGL" /></a>
  <a href="https://sortmark.com"><img src="https://img.shields.io/badge/Crafted%20by-SORTMARK-white.svg" alt="Brand" /></a>
</p>

---

## 🌐 English

An interactive, high-fidelity **3D Smart Bus Servo Actuator & Straddle Mount Dual-Shaft Mechanism** laboratory. Features internal metal gear train cutaways, U-bracket simply supported beam mechanics, and axial exploded views. Runs natively in-browser using local system fonts.

Crafted by the **[SORTMARK Lab Team](https://sortmark.com)**.

### 🌟 Key Features
* **Dual-Shaft Straddle Mount Mechanics**:
  * Eliminates traditional cantilever bending failure by supporting both active output spline and coaxial passive rear bearing.
  * Increases structural torsional stiffness by up to 400% under heavy robotic payloads.
* **4-Stage Metal Gear Train & Internal Cutaway**:
  * Precision powder metallurgy alloy gears and coreless motor cavity visualization.
  * Sweep motion angle simulation and dynamic component inspection.
* **Local System Fonts & Air-Gapped Ready**:
  * Native system font stack, zero tracking, instant zero-lag rendering.

### 🚀 Quick Start
```bash
git clone https://github.com/sortmark-lab/bus-servo-mechanism.git
cd bus-servo-mechanism
npx serve -l 3000 .
```

---

## 🇨🇳 中文说明

高拟真交互式 **3D 智能串行总线舵机与 U 型双臂简支梁机构** 仿真实验室。展示 4 级全金属齿轮箱透视、U 型支架简支梁受力抗弯矩特性与轴向爆炸分解图。纯浏览器运行，零外部网络依赖。

由 **[SORTMARK Lab Team](https://sortmark.com)** 研发打造。

### 🌟 核心特性
* **双轴支承简支梁抗弯架构**:
  * 主动力输出轴与副轴同轴支撑，将传统单轴“悬臂梁”受力转变为高刚性“简支梁”受力。
  * 在机器人关节重载摆动场景下，经力学模型对比，结构抗弯扭刚度可显著提升约 400%，有效降低重载工况下的扫齿与卡死风险。
* **4 级粉末冶金全金属齿轮箱透视**:
  * 真实展示空心杯/无刷电机齿轮输入级至主减速齿轮副的啮合传动链路。
  * 动态角度往复摆动与各零部件装配间隙观察。
* **纯本地系统字体与工业可靠性**:
  * 原生字体栈秒开渲染，零网络请求，适配各类工业与创客现场调试设备。

### 🚀 快速启动
```bash
git clone https://github.com/sortmark-lab/bus-servo-mechanism.git
cd bus-servo-mechanism
npx serve -l 3000 .
```

---

## 🇯🇵 日本語

高精度・対話型 **3D スマートシリアルバスサーボ＆U字両持ち支持機構** シミュレーションラボ。4段全金属ギヤトレインの内部透視、両持ち支持梁（Straddle Mount）による曲げモーメント分散効果、分解アセンブリを直感的に体験できます。

開発: **[SORTMARK Lab Team](https://sortmark.com)**

### 🌟 主な機能
* **U字ブラケット両持ち支持（簡支梁）剛性構造**:
  * 主出力軸と同軸の従動ベアリング軸を両側から挟み込み、従来の「片持ち梁（カンチレバー）」構造の曲げ荷重集中を解消。
  * ロボット脚部やマニピュレータの高トルク旋回時において、構造剛性を最大400%向上させ、ギヤの破損・偏摩耗を防止。
* **4段粉末冶金オールメタルギヤボックス透视**:
  * コアレスモータのピニオンギヤから最終出力ギヤまでの減速伝達レイアウトを視覚化。
  * スイング動作シミュレーションと各パーツの軸方向分解検査に対応。
* **オフライン対応＆ローカルフォントレンダリング**:
  * クラウド通信や外部フォントCDNを一切使用せず、即座にスムーズな60fpsレンダリングを実現。

### 🚀 クイックスタート
```bash
git clone https://github.com/sortmark-lab/bus-servo-mechanism.git
cd bus-servo-mechanism
npx serve -l 3000 .
```

---

---

## 🔬 Project Status, Evaluation Disclaimer & Feedback / 项目状态、免责声明与反馈

### 🌐 English
> ⚠️ **Evaluation Prototype Notice (Not Intended for Critical or Production Control)**:  
> This open-source repository is an experimental educational and simulation preview under active development. It is provided strictly **"AS IS"** for educational inspection, kinematics/mechanics study, and technical evaluation. It is **not certified for physical safety-critical machinery, high-voltage industrial automation, or direct production deployment**. We make no commercial promises or operational warranties. We warmly welcome community feedback, pull requests, and suggestions to help us refine and improve!  
> 📬 *Community Contact & Feedback*: [`contact@sortmark.com`](mailto:contact@sortmark.com)

### 🇨🇳 简体中文
> ⚠️ **评估原型免责声明（仅用于技术验证与教育交流，不建议直接用于生产工控）**:  
> 本开源项目属于处于持续迭代完善中的实验性技术演示与评估原型，按“现状（AS IS）”提供。**仅供机构原理教学、算法仿真验证与离线学习参考，未经工业安全与关键任务控制认证，不建议也不承诺直接应用于物理实体机电设备或工业生产控制**。本团队不作任何商业承诺或可用性担保。热忱欢迎广大开发者、机器人与语言学爱好者提出宝贵的改进建议与 Issue 反馈！  
> 📬 *交流与反馈渠道*: [`contact@sortmark.com`](mailto:contact@sortmark.com)

### 🇯🇵 日本語
> ⚠️ **評価用プロトタイプに関する免責事項（教育・研究評価用・重要制御への投入非推奨）**:  
> 本オープンソースプロジェクトは、現在も継続的な改良を行っている実験的な教育・シミュレーション用プレビューです。機構原理の学習、アルゴリズムの動作検証、概念実証を目的として現状有姿（AS IS）で公開されており、**物理的な実機機械の保安制御や産業生産現場への直接投入は推奨しておらず、一切の商用保証を行いません**。機能向上や品質改善に向けたコミュニティからのご意見・改善提案・Issue報告を心より歓迎いたします！  
> 📬 *フィードバック窓口*: [`contact@sortmark.com`](mailto:contact@sortmark.com)

## 📄 License
Released under the [MIT License](LICENSE).
