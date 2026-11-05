# 周苓萱 · CanNyCat

**机器人软件 · 端侧 AI · 嵌入式 Linux**

重庆邮电大学 · 集成电路设计与集成系统 · **2028 届本科**  
地瓜机器人（D-Robotics）开发者生态部 · **RDK 生态开发实习生** · 2026.08–至今

从模型部署、传感器与执行器接入，到实机排障与开源交付。

[代表作品](#代表作品) · [工程竞赛](#工程竞赛) · [科研与荣誉](#科研与荣誉) · [技术与交流](#技术与交流)

## 代表作品

### [RDK X5 Duck｜机载机器人与开源复刻](https://github.com/CanNyCat17/rdk-x5-microduck)

<a href="https://github.com/CanNyCat17/rdk-x5-microduck/blob/main/docs/CURRENT_PROTOTYPE.md"><img src="assets/duck-single-power-20261030.png" width="640" alt="RDK X5 Duck 单电源机载样机，点击查看验证进度"></a>

- **我的贡献**：在团队支持下主导 15 轴整机集成、Linux/Python 控制、总线与 IMU 联调，开发 Web 调参、安全复位与分阶段颈部控制。
- **交付成果**：双电池全机载短距离前进；公开软件、机械资料、MuJoCo 教学仿真及 **24 章完整复刻手册**。
- **验证边界**：短距离成果采用目标序列与颈部时序控制；单电源已能站立，带载行走与 RL 实机闭环待验证。

[实机视频](https://github.com/CanNyCat17/rdk-x5-microduck/blob/main/media/20261023/onboard-short-walk.mp4) · [源码与 DEMO](https://github.com/CanNyCat17/rdk-x5-microduck/tree/main/software) · [复刻手册](https://github.com/CanNyCat17/rdk-x5-microduck/blob/main/docs/FULL_SOLUTION.md) · [地瓜社区](https://forum.d-robotics.cc/t/topic/35728/1)

### [Roboto Origin｜S600 多模态部署](https://github.com/CanNyCat17/roboto-origin-rdk-x5-s100)

<a href="https://github.com/CanNyCat17/roboto-origin-rdk-x5-s100/tree/main/apps/s600_coprocessor"><img src="assets/s600-deployment-preview.svg?v=2" width="640" alt="S600 多模态部署流程示意，点击查看源码"></a>

- **我的贡献**：负责算法适配与板端部署，联调相机、雷达、麦克风，完成 ONNX 数值校验、S600 BPU 推理及 X5/S100 离线适配。
- **交付成果**：YOLO 分割、Qwen3-VL 图片问答与 Whisper 转写演示；两分钟真实相机分割约 **19.2 FPS**。
- **验证边界**：基于公司团队的机器人底座开展感知演示，自主导航与整机运动闭环尚未验收。

[源码与复现](https://github.com/CanNyCat17/roboto-origin-rdk-x5-s100/tree/main/apps/s600_coprocessor) · [验证报告](https://github.com/CanNyCat17/roboto-origin-rdk-x5-s100/blob/main/docs/S600_COPROCESSOR_DEMO.md)

**开发者生态贡献** · 交付双语课程与实板样例，S100 第 11–13 课与 X5/S100 CAN 合计新增 10 条成片；复现设备与推理问题、分析日志并提供公开诊断建议。[课程贡献](https://github.com/D-Robotics/rdk-course-demos/commit/0ce864e93e8eaed061cebff69023e732961ea03e) · [技术答复](https://forum.d-robotics.cc/t/topic/35643/6)

## 工程竞赛

**全国一等奖 1 项 · 全国二等奖 2 项 · 全国三等奖 1 项**；4 项队长，负责核心软件开发与算法实现。

- **[双 RDK X5 材料 AI 与具身实验助理](https://github.com/CanNyCat17/dual-rdk-x5-materials-ai-robot-lab)**  
  2026 全国大学生嵌入式芯片与系统设计竞赛 **全国二等奖**。队长，负责材料分析、CPU/BPU 部署与 ROS 2 多机双臂软件联调。
- **[RootScope｜根区灌溉舱](https://github.com/CanNyCat17/RootScope-AdventureX2026)**  
  AdventureX 2026 **地瓜机器人赛道二等奖（第 2 名）· superun.ai 赛道三等奖**。队长，负责视觉模型与 X5→STM32 探针/水泵联调。
- **[Lab-Sentinel｜烧结安全哨兵](https://github.com/CanNyCat17/Lab-Sentinel-CIMC2026)**  
  2026 CIMC“西门子杯”中国智能制造挑战赛 **全国二等奖**。队长，负责 GD32H759、FreeRTOS/LVGL 软件与 MCU 边缘推理优化。
- **[存储芯片 ATE/PAT 平台](https://github.com/CanNyCat17/memory-ate-pat-platform)**  
  2026 全国大学生集成电路创新创业大赛 **全国一等奖**。软件与 PAT 算法负责人，开发 I²C/SPI 向量算法与 Electron 流式生成平台。
- **[自主散料搬运机器人](https://github.com/CanNyCat17/intelligent-vision-logistics-crane-2026)**  
  2026 中国大学生机械工程创新创意大赛物流技术创意赛 **全国三等奖**。队长，负责 Jetson 视觉、ROS 2 导航及串口联调。

## 科研与荣誉

- **SCI 论文共同作者 2 篇**：*Ceramics International*；*Journal of Luminescence*。
- **重庆市级大学生创新创业训练计划项目**：第一负责人。
- **美国大学生数学建模竞赛**：M 奖。
- **国际大学生物理竞赛金奖** · 2025 University Physics Competition · Gold Medal。Sasando 数字谐振器项目负责人，Team 112 / Problem A。[项目源码](https://github.com/CanNyCat17/sasando-digital-resonator) · [官方获奖论文](https://www.uphysicsc.com/2025-GM-A-112.pdf)
- **全国大学生机械创新设计大赛重庆赛区二等奖**。

## 技术与交流

**软件与系统**　C/C++ · Python · Linux · Git · Docker  
**端侧 AI**　PyTorch · ONNX · OpenCV · OpenExplorer · RDK CPU/BPU 部署  
**机器人与嵌入式**　ROS 2 · Nav2/SLAM · STM32/GD32 · FreeRTOS/LVGL · UART/I²C/SPI/CAN

**项目合作**：欢迎机器人、嵌入式与端侧 AI 共建，期待机械、硬件电控及运动控制方向伙伴。  
**实习招聘**：关注嵌入式 Linux、端侧 AI 部署与机器人软件岗位；可通过邮件索取最新版简历。

**[3773318175@qq.com](mailto:3773318175@qq.com)** · 项目使用问题与改进建议欢迎提交对应仓库 Issue。

<details>
<summary>更多探索与项目来源</summary>

- Duck 基于 [Pollen Robotics MicroDuck](https://github.com/pollen-robotics/microduck) 与[社区飞特结构](https://github.com/fanhao375/microduck-replica-cad)。同项目陆吾 XGO-Duck 副线完成 15 轴标定与官方策略短程复现，直线保持待验证。
- [南瓜鸭](https://github.com/CanNyCat17/rdk-x5-microduck/tree/main/projects/pumpkin-duck)：2026-10-30 结项，保留外观设计与 Web/UE5 展示；视觉、语音及完整实体互动未完成。
- [RDK Frontier Lab](https://github.com/CanNyCat17/rdk-frontier-lab)：个人扩展部署探索，首版完成，当前未持续维护。

</details>

<sub>更新于 2026-11-05 · 实机阶段与验证范围详见各项目仓库。</sub>
