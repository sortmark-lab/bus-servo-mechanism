# 总线舵机机构原理与模型说明 (Bus Servo Principles & Model Architecture)

> **归属实验室**: SORTMARK Open-Source Lab (`sortmark-opensource-lab`)  
> **所属项目**: `bus-servo-mechanism`  
> **官方主页**: [https://sortmark.com](https://sortmark.com) | **商务咨询**: `contact@sortmark.com`

---

## 📌 1. 核心设计原则：纯 HTML 仿真，零外部 3D 模型依赖

本项目重点演示**4 级全金属齿轮箱传动比计算与 U 型双轴简支梁抗弯力学**，**不提供任何外部 3D CAD/STEP 模型文件**：

1. **工业制造 IP 保护**:
   - 商业级总线舵机的 CNC 铝合金中壳结构、粉末冶金齿轮模数及主副轴承装配属于商业机密，开源只做原理普及，不提供商业制造源文件。
2. **纯 HTML 原理仿真 (Zero-Dependency Mechanics Simulation)**:
   - 4 级金属齿轮的物理咬合传动比、单轴悬臂梁受力弯曲与双轴简支梁刚度对比，全部由纯 JavaScript 在 `index.html` 内 60FPS 实时渲染。
   - 打开即见，免去用户下载 3D 软件和庞大模型包的门槛。
3. **商业定制渠道**:
   - 12V/24V 高压无刷串口总线舵机（30kg·cm ~ 120kg·cm）、多圈绝对值磁编码器版本采购请联系 `contact@sortmark.com`。

---

## 🏭 2. AI 模型生产流水线：`model-builder` 与 `model-factory`

对于工业总线通信协议（如自定义半双工 UART 指令集、闭环反馈算法）的智能问答模型：

1. **微调与量化车间**:
   - 路径：`sortmark/sortmark-model-builder`
   - 执行工业总线协议与机械动力学问答语料的 QLoRA 训练与 GGUF 导出。
2. **Hugging Face 矩阵发布车间**:
   - 路径：`social_matrix/custom-model-factory`
   - 将模型权威文档与下载分发至 Hugging Face `sortmark/` 官方空间，注入品牌权重链接。
