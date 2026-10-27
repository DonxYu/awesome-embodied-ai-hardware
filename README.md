# Awesome Embodied AI & Robotics Hardware / VLA Models (2026)

> **最后更新**：`2026-10-27` | **在线交互对比、价格库与 URDF 下载**：**[具身开发者社区 (https://robotics.hellobike.com)](https://robotics.hellobike.com)**

本项目面向机器人算法工程师、硬件研发与选型负责人，结构化整理全球主流 **人形机器人、四足机器狗、协作机械臂** 的核心工程参数、公开售价/日租行情、**URDF / MuJoCo (MJCF) / Isaac (USD)** 仿真模型直链，以及主流 **VLA 具身大模型** 与 **开源数据集**。

## 快速导航
- [在线 31 项参数并排对比工具 (Compare Tool)](https://robotics.hellobike.com/compare/)
- [163 款机器人公开售价与租赁价格表 (Pricing Directory)](https://robotics.hellobike.com/pricing/)
- [官方 URDF / MJCF / USD 仿真资产索引 (Sim Assets)](https://robotics.hellobike.com/sim-assets/)
- [VLA 具身大模型与微调指南 (Models Hub)](https://robotics.hellobike.com/models/)
- [真机调试与 ROS 2 排障问答库 (Pitfalls FAQ)](https://robotics.hellobike.com/pitfalls/)

---

## 一、主流人形与四足机器人核心参数及参考报价 (Top 60)

| 机型名称 | 品牌厂商 | 品类 | 自由度(DoF) | 重量(kg) | 负载(kg) | 续航(h) | 公开参考报价 | 仿真资产 | 完整规格与BOM |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **[IRB 1200-5/0.9 Gen2](https://robotics.hellobike.com/robots/abb-robotics-irb-1200-5-0-9-gen2)** | ABB机器人 | 机械臂 | 6 | — | 5.0 | — | ¥85,000 ~ ¥320,000 | URDF | [详情 & 对比](https://robotics.hellobike.com/robots/abb-robotics-irb-1200-5-0-9-gen2) |
| **[智元灵犀 X2](https://robotics.hellobike.com/robots/agibot-lingxi-x2)** | 智元机器人 | 人形机器人 | 31 | 39 | 3 | 2 | ¥98,000 起 | URDF/MJCF | [详情 & 对比](https://robotics.hellobike.com/robots/agibot-lingxi-x2) |
| **[松灵 PiPER](https://robotics.hellobike.com/robots/agilex-piper)** | 松灵机器人 | 机械臂 | 6 | 4.2 | 1.5 | — | $1,999 起 | URDF/MJCF | [详情 & 对比](https://robotics.hellobike.com/robots/agilex-piper) |
| **[Boston Dynamics Spot](https://robotics.hellobike.com/robots/boston-dynamics-spot)** | Boston Dynamics | 四足机器狗 | 12 | 32.7 | 14 | 1.5 | $74,500 起 | MJCF | [详情 & 对比](https://robotics.hellobike.com/robots/boston-dynamics-spot) |
| **[傅利叶 GR-2](https://robotics.hellobike.com/robots/fourier-gr-2)** | 傅利叶 | 人形机器人 | 41 | 63 | 3 | 2 | ¥350,000 ~ ¥550,000 | URDF | [详情 & 对比](https://robotics.hellobike.com/robots/fourier-gr-2) |
| **[傅利叶 GR-3](https://robotics.hellobike.com/robots/fourier-gr-3)** | 傅利叶 | 人形机器人 | 55 | 71 | 3 | 3 | ¥298,000 ~ ¥450,000 | URDF/MJCF | [详情 & 对比](https://robotics.hellobike.com/robots/fourier-gr-3) |
| **[Franka FR3](https://robotics.hellobike.com/robots/franka-research-3)** | Franka Robotics | 机械臂 | 7 | — | 3 | — | $28,500 ~ $35,000 | URDF/MJCF | [详情 & 对比](https://robotics.hellobike.com/robots/franka-research-3) |
| **[星海图 R1](https://robotics.hellobike.com/robots/galaxea-r1)** | 星海图 | 人形机器人 | 24 | 96 | 5 | — | ¥199,000 起 | URDF | [详情 & 对比](https://robotics.hellobike.com/robots/galaxea-r1) |
| **[R1 Lite](https://robotics.hellobike.com/robots/galaxea-r1-lite)** | 星海图 | mobile | 23 | — | 3.0 | — | ¥129,000 ~ ¥169,000 | URDF | [详情 & 对比](https://robotics.hellobike.com/robots/galaxea-r1-lite) |
| **[钢镚 L1](https://robotics.hellobike.com/robots/genisom-l1)** | 智身科技 | 四足机器狗 | 12 | 15.0 | 8.0 | 2.0 | ¥19,999 ~ ¥29,999 | URDF | [详情 & 对比](https://robotics.hellobike.com/robots/genisom-l1) |
| **[钢镚 L1 Maker](https://robotics.hellobike.com/robots/genisom-l1-maker)** | 智身科技 | 四足机器狗 | 12 | 15.0 | 8.0 | 2.0 | ¥19,999 ~ ¥29,999 | URDF | [详情 & 对比](https://robotics.hellobike.com/robots/genisom-l1-maker) |
| **[钢镚 L1-W](https://robotics.hellobike.com/robots/genisom-l1-w)** | 智身科技 | 四足机器狗 | 12 | 22.0 | 10.0 | 2.0 | ¥24,999 ~ ¥34,999 | URDF | [详情 & 对比](https://robotics.hellobike.com/robots/genisom-l1-w) |
| **[逐际动力 Oli](https://robotics.hellobike.com/robots/limx-dynamics-limx-oli)** | 逐际动力 | 人形机器人 | 33 | 55 | 3 | 1.5 | ¥158,000 起 | URDF/MJCF | [详情 & 对比](https://robotics.hellobike.com/robots/limx-dynamics-limx-oli) |
| **[OMY](https://robotics.hellobike.com/robots/robotis-omy)** | ROBOTIS | 机械臂 | 6 | — | — | — | $2,873.85 ~ $17,248.85 | URDF/MJCF | [详情 & 对比](https://robotics.hellobike.com/robots/robotis-omy) |
| **[宇树 A2](https://robotics.hellobike.com/robots/unitree-a2)** | 宇树科技 | 四足机器狗 | 12 | 42 | 25 | 3 | $100,000 起 | MJCF | [详情 & 对比](https://robotics.hellobike.com/robots/unitree-a2) |
| **[宇树 B2](https://robotics.hellobike.com/robots/unitree-b2)** | 宇树科技 | 四足机器狗 | 12 | 60 | 40 | 4 | $100,000 起 | URDF/MJCF | [详情 & 对比](https://robotics.hellobike.com/robots/unitree-b2) |
| **[宇树 G1](https://robotics.hellobike.com/robots/unitree-g1)** | 宇树科技 | 人形机器人 | 23 | 35 | 2 | 2 | $13,500 ~ $21,500 | URDF/MJCF | [详情 & 对比](https://robotics.hellobike.com/robots/unitree-g1) |
| **[宇树 Go2](https://robotics.hellobike.com/robots/unitree-go2)** | 宇树科技 | 四足机器狗 | 12 | 15 | 7 | 1 | $1,600 ~ $4,500 | URDF/MJCF | [详情 & 对比](https://robotics.hellobike.com/robots/unitree-go2) |
| **[宇树 Go2-W](https://robotics.hellobike.com/robots/unitree-go2-w)** | 宇树科技 | 四足机器狗 | 16 | 18 | 8 | 1.5 | $5,600 ~ $9,800 | URDF/MJCF | [详情 & 对比](https://robotics.hellobike.com/robots/unitree-go2-w) |
| **[宇树 H1](https://robotics.hellobike.com/robots/unitree-h1)** | 宇树科技 | 人形机器人 | 19 | 47 | — | — | $90,000 起 | URDF/MJCF | [详情 & 对比](https://robotics.hellobike.com/robots/unitree-h1) |
| **[宇树 H2](https://robotics.hellobike.com/robots/unitree-h2)** | 宇树科技 | 人形机器人 | 31 | 70 | 7 | 3 | $29,900 起 | URDF/MJCF | [详情 & 对比](https://robotics.hellobike.com/robots/unitree-h2) |
| **[宇树 R1](https://robotics.hellobike.com/robots/unitree-r1)** | 宇树科技 | 人形机器人 | 26 | 29 | 2 | 1 | $4,900 ~ $10,500 | URDF/MJCF | [详情 & 对比](https://robotics.hellobike.com/robots/unitree-r1) |
| **[宇树 Z1](https://robotics.hellobike.com/robots/unitree-z1)** | 宇树科技 | 机械臂 | 6 | 4.3 | 2 | — | $15,999 起 | MJCF | [详情 & 对比](https://robotics.hellobike.com/robots/unitree-z1) |
| **[Universal Robots UR10e](https://robotics.hellobike.com/robots/universal-robots-ur10e)** | Universal Robots | 机械臂 | 6 | 33.5 | 12.5 | — | $38,000 ~ $46,000 | URDF/MJCF | [详情 & 对比](https://robotics.hellobike.com/robots/universal-robots-ur10e) |
| **[Universal Robots UR5e](https://robotics.hellobike.com/robots/universal-robots-ur5e)** | Universal Robots | 机械臂 | 6 | 20.6 | 5 | — | $28,000 ~ $35,000 | URDF/MJCF | [详情 & 对比](https://robotics.hellobike.com/robots/universal-robots-ur5e) |
| **[IRB 1200-7/0.7 Gen2](https://robotics.hellobike.com/robots/abb-robotics-irb-1200-7-0-7-gen2)** | ABB机器人 | 机械臂 | — | — | 7.0 | — | ¥85,000 ~ ¥320,000 | URDF | [详情 & 对比](https://robotics.hellobike.com/robots/abb-robotics-irb-1200-7-0-7-gen2) |
| **[IRB 1600](https://robotics.hellobike.com/robots/abb-robotics-irb-1600)** | ABB机器人 | 机械臂 | — | — | 10.0 | — | ¥85,000 ~ ¥320,000 | URDF | [详情 & 对比](https://robotics.hellobike.com/robots/abb-robotics-irb-1600) |
| **[IRB 2600](https://robotics.hellobike.com/robots/abb-robotics-irb-2600)** | ABB机器人 | 机械臂 | — | — | 20.0 | — | ¥85,000 ~ ¥320,000 | URDF | [详情 & 对比](https://robotics.hellobike.com/robots/abb-robotics-irb-2600) |
| **[IRB 4400](https://robotics.hellobike.com/robots/abb-robotics-irb-4400)** | ABB机器人 | 机械臂 | — | — | 60.0 | — | ¥85,000 ~ ¥320,000 | URDF | [详情 & 对比](https://robotics.hellobike.com/robots/abb-robotics-irb-4400) |
| **[松灵 AgileX LIMO](https://robotics.hellobike.com/robots/agilex-limo)** | 松灵机器人 | mobile | — | 4.8 | 1 | 0.67 | ¥9,800 ~ ¥23,800 | URDF | [详情 & 对比](https://robotics.hellobike.com/robots/agilex-limo) |
| **[松灵 AgileX SCOUT 2.0](https://robotics.hellobike.com/robots/agilex-scout-2-0)** | 松灵机器人 | mobile | — | — | 50 | 3.5 | ¥42,000 ~ ¥58,000 | URDF | [详情 & 对比](https://robotics.hellobike.com/robots/agilex-scout-2-0) |
| **[FR3 Duo](https://robotics.hellobike.com/robots/franka-fr3-duo)** | Franka Robotics | 机械臂 | — | — | 3 | — | $58,000 ~ $70,000 | URDF | [详情 & 对比](https://robotics.hellobike.com/robots/franka-fr3-duo) |
| **[Stretch机器人](https://robotics.hellobike.com/robots/hello-robot-stretch-robots)** | Hello Robot | service | — | — | — | — | $24,950 起 | URDF/MJCF | [详情 & 对比](https://robotics.hellobike.com/robots/hello-robot-stretch-robots) |
| **[乐聚 KUAVO 5](https://robotics.hellobike.com/robots/leju-kuavo-5)** | 乐聚机器人 | 人形机器人 | — | — | 20.0 | — | ¥308,100 ~ ¥413,900 | URDF | [详情 & 对比](https://robotics.hellobike.com/robots/leju-kuavo-5) |
| **[逐际动力 TRON 1](https://robotics.hellobike.com/robots/limx-dynamics-tron-1)** | 逐际动力 | other | — | 20 | 10 | 2 | $15,000 ~ $25,000 | URDF/MJCF | [详情 & 对比](https://robotics.hellobike.com/robots/limx-dynamics-tron-1) |
| **[宇树 B2-W](https://robotics.hellobike.com/robots/unitree-b2-w)** | 宇树科技 | 四足机器狗 | — | 85 | 40 | — | $100,000 起 | URDF/MJCF | [详情 & 对比](https://robotics.hellobike.com/robots/unitree-b2-w) |
| **[IRB 1200 Hygienic](https://robotics.hellobike.com/robots/abb-robotics-irb-1200-hygienic)** | ABB机器人 | 机械臂 | 6 | — | 7.0 | — | ¥85,000 ~ ¥320,000 | — | [详情 & 对比](https://robotics.hellobike.com/robots/abb-robotics-irb-1200-hygienic) |
| **[IRB 1660ID](https://robotics.hellobike.com/robots/abb-robotics-irb-1660id)** | ABB机器人 | 机械臂 | 6 | — | 6.0 | — | ¥85,000 ~ ¥320,000 | — | [详情 & 对比](https://robotics.hellobike.com/robots/abb-robotics-irb-1660id) |
| **[IRB 460](https://robotics.hellobike.com/robots/abb-robotics-irb-460)** | ABB机器人 | 机械臂 | 4 | — | 110.0 | — | ¥85,000 ~ ¥320,000 | — | [详情 & 对比](https://robotics.hellobike.com/robots/abb-robotics-irb-460) |
| **[IRB 660](https://robotics.hellobike.com/robots/abb-robotics-irb-660)** | ABB机器人 | 机械臂 | 4 | — | 250.0 | — | ¥85,000 ~ ¥320,000 | — | [详情 & 对比](https://robotics.hellobike.com/robots/abb-robotics-irb-660) |
| **[IRB 760](https://robotics.hellobike.com/robots/abb-robotics-irb-760)** | ABB机器人 | 机械臂 | 4 | — | — | — | ¥85,000 ~ ¥320,000 | — | [详情 & 对比](https://robotics.hellobike.com/robots/abb-robotics-irb-760) |
| **[智元远征 A2](https://robotics.hellobike.com/robots/agibot-expedition-a2)** | 智元机器人 | 人形机器人 | 40 | 69 | 2 | 1.5 | ¥168,000 ~ ¥198,000 | — | [详情 & 对比](https://robotics.hellobike.com/robots/agibot-expedition-a2) |
| **[智元精灵 G2](https://robotics.hellobike.com/robots/agibot-genie-g2)** | 智元机器人 | 人形机器人 | 25 | 185 | 5 | 4 | ¥250,000 ~ ¥398,000 | — | [详情 & 对比](https://robotics.hellobike.com/robots/agibot-genie-g2) |
| **[智元 灵犀 X1](https://robotics.hellobike.com/robots/agibot-x1)** | 智元机器人 | 人形机器人 | 34 | 33 | 0.5 | 2 | ¥89,000 ~ ¥149,000 | — | [详情 & 对比](https://robotics.hellobike.com/robots/agibot-x1) |
| **[遨博 i5](https://robotics.hellobike.com/robots/aubo-i5)** | 遨博机器人 | 机械臂 | 6 | 24 | 5 | — | ¥48,000 ~ ¥68,000 | — | [详情 & 对比](https://robotics.hellobike.com/robots/aubo-i5) |
| **[众擎 PM01](https://robotics.hellobike.com/robots/engineai-pm01)** | 众擎机器人 | 人形机器人 | 24 | 44 | — | 2 | ¥88,000 ~ ¥188,000 | — | [详情 & 对比](https://robotics.hellobike.com/robots/engineai-pm01) |
| **[SA01](https://robotics.hellobike.com/robots/engineai-sa01)** | 众擎机器人 | 人形机器人 | 12 | 40.0 | — | — | ¥42,000 起 | — | [详情 & 对比](https://robotics.hellobike.com/robots/engineai-sa01) |
| **[众擎 SE01](https://robotics.hellobike.com/robots/engineai-se01)** | 众擎机器人 | 人形机器人 | 32 | — | — | 2 | ¥150,000 ~ ¥200,000 | — | [详情 & 对比](https://robotics.hellobike.com/robots/engineai-se01) |
| **[T800](https://robotics.hellobike.com/robots/engineai-t800)** | 众擎机器人 | 人形机器人 | 29 | 75.0 | 5.0 | 4.0 | ¥180,000 起 | — | [详情 & 对比](https://robotics.hellobike.com/robots/engineai-t800) |
| **[银河通用 Galbot G1](https://robotics.hellobike.com/robots/galbot-g1)** | 银河通用机器人 | 人形机器人 | 21 | 92.5 | 5 | 8 | ¥700,000 起 | — | [详情 & 对比](https://robotics.hellobike.com/robots/galbot-g1) |
| **[钢镚 L2](https://robotics.hellobike.com/robots/genisom-l2)** | 智身科技 | 四足机器狗 | 12 | 21.0 | 16.0 | 5.5 | ¥39,999 起 | — | [详情 & 对比](https://robotics.hellobike.com/robots/genisom-l2) |
| **[钢镚 L2-W](https://robotics.hellobike.com/robots/genisom-l2-w)** | 智身科技 | 四足机器狗 | 12 | 27.0 | 16.0 | 5.5 | ¥39,999 起 | — | [详情 & 对比](https://robotics.hellobike.com/robots/genisom-l2-w) |
| **[钢镚 L2-W Ultra](https://robotics.hellobike.com/robots/genisom-l2-w-ultra)** | 智身科技 | 四足机器狗 | 12 | 27.0 | 16.0 | 4.5 | ¥39,999 起 | — | [详情 & 对比](https://robotics.hellobike.com/robots/genisom-l2-w-ultra) |
| **[铜锤 M1](https://robotics.hellobike.com/robots/genisom-m1)** | 智身科技 | 四足机器狗 | 12 | 41.0 | 30.0 | 5.0 | ¥128,000 ~ ¥198,000 | — | [详情 & 对比](https://robotics.hellobike.com/robots/genisom-m1) |
| **[铜锤 M1 Pro](https://robotics.hellobike.com/robots/genisom-m1-pro)** | 智身科技 | 四足机器狗 | 12 | 41.0 | 30.0 | 5.0 | ¥158,000 ~ ¥238,000 | — | [详情 & 对比](https://robotics.hellobike.com/robots/genisom-m1-pro) |
| **[铜锤 M1 Ultra](https://robotics.hellobike.com/robots/genisom-m1-ultra)** | 智身科技 | 四足机器狗 | 12 | 41.0 | 30.0 | 5.0 | ¥198,000 ~ ¥288,000 | — | [详情 & 对比](https://robotics.hellobike.com/robots/genisom-m1-ultra) |
| **[银毅 NE01](https://robotics.hellobike.com/robots/genisom-ne01)** | 智身科技 | 人形机器人 | 24 | 37.0 | 2.0 | 2.0 | ¥39,999 ~ ¥59,999 | — | [详情 & 对比](https://robotics.hellobike.com/robots/genisom-ne01) |
| **[银毅 NE01 Pro](https://robotics.hellobike.com/robots/genisom-ne01-pro)** | 智身科技 | 人形机器人 | 24 | 37.0 | 2.0 | 2.0 | ¥59,999 ~ ¥89,999 | — | [详情 & 对比](https://robotics.hellobike.com/robots/genisom-ne01-pro) |
| **[银毅 NE01 Ultra](https://robotics.hellobike.com/robots/genisom-ne01-ultra)** | 智身科技 | 人形机器人 | 28 | 38.0 | 3.0 | 2.0 | ¥89,999 ~ ¥129,999 | — | [详情 & 对比](https://robotics.hellobike.com/robots/genisom-ne01-ultra) |
| **[KUKA ready2_arc 奥太](https://robotics.hellobike.com/robots/kuka-ready2-arc-aotai)** | 库卡 | 机械臂 | 6 | — | 10.0 | — | ¥85,000 ~ ¥320,000 | — | [详情 & 对比](https://robotics.hellobike.com/robots/kuka-ready2-arc-aotai) |

> 查看全部 **212 款** 机器人参数或并排比对：[点击进入在线对比工作台 →](https://robotics.hellobike.com/compare/)

---

## 二、核心具身大模型 / VLA 模型架构与开源权重 (Top 40)

| 模型名称 | 家族 | 参数量 | 主干架构 | 许可协议 | 核心概述 | 部署与微调指南 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **[smolvla_base](https://robotics.hellobike.com/models/lerobot-smolvla-base)** | vla | 450M | SmolVLA (SmolVLM2 + Flow Matching Action Expert) | apache-2.0 | lerobot 在 Hugging Face 发布的机器人模型，架构为 SmolVLA (SmolVLM2 + Flow Matching  | [模型卡](https://robotics.hellobike.com/models/lerobot-smolvla-base) |
| **[Alpamayo-R1-10B](https://robotics.hellobike.com/models/nvidia-alpamayo-r1-10b)** | other | 11.1B | AlpamayoR1 | openmdw-1.1 | nvidia 在 Hugging Face 发布的机器人模型，架构为 AlpamayoR1，参数规模 11.1B，训练数据包含 nvidia | [模型卡](https://robotics.hellobike.com/models/nvidia-alpamayo-r1-10b) |
| **[Magma-8B](https://robotics.hellobike.com/models/microsoft-magma-8b)** | other | 8.9B | MagmaForCausalLM | mit | microsoft 在 Hugging Face 发布的机器人模型，架构为 MagmaForCausalLM，参数规模 8.9B。 | [模型卡](https://robotics.hellobike.com/models/microsoft-magma-8b) |
| **[GR00T-N1-2B](https://robotics.hellobike.com/models/nvidia-gr00t-n1-2b)** | vla | 2.2B | GR00T_N1 | Apache-2.0 | nvidia 在 Hugging Face 发布的机器人模型，架构为 GR00T_N1，参数规模 2.2B，训练数据包含 nvidia/Ph | [模型卡](https://robotics.hellobike.com/models/nvidia-gr00t-n1-2b) |
| **[pi0_old](https://robotics.hellobike.com/models/lerobot-pi0-old)** | vla | 3.5B | π0 (PaliGemma VLM + Flow Matching Action Expert) | apache-2.0 | lerobot 在 Hugging Face 发布的机器人模型，架构为 π0 (PaliGemma VLM + Flow Matching  | [模型卡](https://robotics.hellobike.com/models/lerobot-pi0-old) |
| **[openvla-7b](https://robotics.hellobike.com/models/openvla-openvla-7b)** | vla | 7.5B | OpenVLA (Prismatic VLM 7B + Action Tokenizer) | mit | openvla 在 Hugging Face 发布的机器人模型，架构为 OpenVLA (Prismatic VLM 7B + Action | [模型卡](https://robotics.hellobike.com/models/openvla-openvla-7b) |
| **[GR00T-N1.5-3B](https://robotics.hellobike.com/models/nvidia-gr00t-n1-5-3b)** | vla | 2.7B | NVIDIA Isaac GR00T N1.5 (Eagle VLM + DiT Action Head) | Apache-2.0 | nvidia 在 Hugging Face 发布的机器人模型，架构为 NVIDIA Isaac GR00T N1.5 (Eagle VLM  | [模型卡](https://robotics.hellobike.com/models/nvidia-gr00t-n1-5-3b) |
| **[MiniCPM-RobotManip](https://robotics.hellobike.com/models/openbmb-minicpm-robotmanip)** | vla | 1.5B | MiniCPMV_VLA | apache-2.0 | openbmb 在 Hugging Face 发布的机器人模型，架构为 MiniCPMV_VLA，参数规模 1.5B。 | [模型卡](https://robotics.hellobike.com/models/openbmb-minicpm-robotmanip) |
| **[GR00T-N1.7-3B](https://robotics.hellobike.com/models/nvidia-gr00t-n1-7-3b)** | vla | 3.1B | NVIDIA Isaac GR00T N1.7 (VLM + Diffusion Action Transformer) | Apache-2.0 | nvidia 在 Hugging Face 发布的机器人模型，架构为 NVIDIA Isaac GR00T N1.7 (VLM + Diff | [模型卡](https://robotics.hellobike.com/models/nvidia-gr00t-n1-7-3b) |
| **[flux-3-action-base](https://robotics.hellobike.com/models/black-forest-labs-flux-3-action-base)** | world_model | 80M | Flow Matching World-Action Model (Flux) | other | black-forest-labs 在 Hugging Face 发布的机器人模型，架构为 Flow Matching World-Acti | [模型卡](https://robotics.hellobike.com/models/black-forest-labs-flux-3-action-base) |
| **[Alpamayo2-Super](https://robotics.hellobike.com/models/nvidia-alpamayo2-super)** | world_model | 35.8B | Alpamayo2Super | openmdw-1.1 | nvidia 在 Hugging Face 发布的机器人模型，架构为 Alpamayo2Super，参数规模 35.8B，训练数据包含 nv | [模型卡](https://robotics.hellobike.com/models/nvidia-alpamayo2-super) |
| **[MiniCPM-RobotTrack](https://robotics.hellobike.com/models/openbmb-minicpm-robottrack)** | other | 450M | MiniCPMRobotTrackModel | apache-2.0 | openbmb 在 Hugging Face 发布的机器人模型，架构为 MiniCPMRobotTrackModel，参数规模 450M。 | [模型卡](https://robotics.hellobike.com/models/openbmb-minicpm-robottrack) |
| **[Alpamayo-1.5-10B](https://robotics.hellobike.com/models/nvidia-alpamayo-1-5-10b)** | world_model | 11.1B | Alpamayo1_5 | openmdw-1.1 | nvidia 在 Hugging Face 发布的机器人模型，架构为 Alpamayo1_5，参数规模 11.1B，训练数据包含 nvidi | [模型卡](https://robotics.hellobike.com/models/nvidia-alpamayo-1-5-10b) |
| **[RoboBrain2.0-7B](https://robotics.hellobike.com/models/baai-robobrain2-0-7b)** | vla | 8.3B | Qwen2_5_VLForConditionalGeneration | apache-2.0 | BAAI 在 Hugging Face 发布的机器人模型，架构为 Qwen2_5_VLForConditionalGeneration，参数 | [模型卡](https://robotics.hellobike.com/models/baai-robobrain2-0-7b) |
| **[pi05_base](https://robotics.hellobike.com/models/lerobot-pi05-base)** | vla | 3.6B | π0.5 (PaliGemma VLM + Flow Matching Action Expert) | gemma | lerobot 在 Hugging Face 发布的机器人模型，架构为 π0.5 (PaliGemma VLM + Flow Matchin | [模型卡](https://robotics.hellobike.com/models/lerobot-pi05-base) |
| **[rdt-1b](https://robotics.hellobike.com/models/robotics-diffusion-transformer-rdt-1b)** | vla | 1B | Diffusion Policy (CNN / Transformer UNet) | mit | robotics-diffusion-transformer 在 Hugging Face 发布的机器人模型，架构为 Diffusion P | [模型卡](https://robotics.hellobike.com/models/robotics-diffusion-transformer-rdt-1b) |
| **[JEV-9B](https://robotics.hellobike.com/models/autotrust-jev-9b)** | other | 9B | Qwen3_5ForCausalLM | apache-2.0 | autotrust 在 Hugging Face 发布的机器人模型，架构为 Qwen3_5ForCausalLM，参数规模 9B，训练数据包 | [模型卡](https://robotics.hellobike.com/models/autotrust-jev-9b) |
| **[GR00T-N1.6-3B](https://robotics.hellobike.com/models/nvidia-gr00t-n1-6-3b)** | vla | 3.3B | NVIDIA Isaac GR00T N1.6 (VLM + Diffusion Action Transformer) | Apache-2.0 | nvidia 在 Hugging Face 发布的机器人模型，架构为 NVIDIA Isaac GR00T N1.6 (VLM + Diff | [模型卡](https://robotics.hellobike.com/models/nvidia-gr00t-n1-6-3b) |
| **[dobb-e](https://robotics.hellobike.com/models/notmahi-dobb-e)** | other | 21M | LeRobot / PyTorch Policy Network | mit | notmahi 在 Hugging Face 发布的机器人模型，基于 timm，参数规模 21M。 | [模型卡](https://robotics.hellobike.com/models/notmahi-dobb-e) |
| **[GEAR-SONIC](https://robotics.hellobike.com/models/nvidia-gear-sonic)** | other | 80M | MLP Actor-Critic Policy (RL Locomotion) | other | nvidia 在 Hugging Face 发布的机器人模型，架构为 MLP Actor-Critic Policy (RL Locomot | [模型卡](https://robotics.hellobike.com/models/nvidia-gear-sonic) |
| **[diffusion_pusht](https://robotics.hellobike.com/models/lerobot-diffusion-pusht)** | policy | 263M | Diffusion Policy (CNN / Transformer UNet) | apache-2.0 | lerobot 在 Hugging Face 发布的机器人模型，架构为 Diffusion Policy (CNN / Transforme | [模型卡](https://robotics.hellobike.com/models/lerobot-diffusion-pusht) |
| **[flux-3-action-so101](https://robotics.hellobike.com/models/black-forest-labs-flux-3-action-so101)** | world_model | 6.9B | Flow Matching World-Action Model (Flux) | other | black-forest-labs 在 Hugging Face 发布的机器人模型，架构为 Flow Matching World-Acti | [模型卡](https://robotics.hellobike.com/models/black-forest-labs-flux-3-action-so101) |
| **[Isaac-0.5](https://robotics.hellobike.com/models/perceptronai-isaac-0-5)** | other | 35.7B | Isaac05ForConditionalGeneration | apache-2.0 | PerceptronAI 在 Hugging Face 发布的机器人模型，架构为 Isaac05ForConditionalGenerati | [模型卡](https://robotics.hellobike.com/models/perceptronai-isaac-0-5) |
| **[MolmoAct-7B-D-0812](https://robotics.hellobike.com/models/allenai-molmoact-7b-d-0812)** | vla | 8.1B | MolmoAct (Molmo VLM + Action Reasoning) | apache-2.0 | allenai 在 Hugging Face 发布的机器人模型，架构为 MolmoAct (Molmo VLM + Action Reaso | [模型卡](https://robotics.hellobike.com/models/allenai-molmoact-7b-d-0812) |
| **[lingbot-vla-v2-6b](https://robotics.hellobike.com/models/robbyant-lingbot-vla-v2-6b)** | vla | 6.4B | LeRobot / PyTorch Policy Network | Apache-2.0 | robbyant 在 Hugging Face 发布的机器人模型，参数规模 6.4B。 | [模型卡](https://robotics.hellobike.com/models/robbyant-lingbot-vla-v2-6b) |
| **[InternVLA-N1-wo-dagger](https://robotics.hellobike.com/models/internrobotics-internvla-n1-wo-dagger)** | vla | 8.4B | InternVLAN1ForCausalLM | cc-by-nc-sa-4.0 | InternRobotics 在 Hugging Face 发布的机器人模型，架构为 InternVLAN1ForCausalLM，参数规模 | [模型卡](https://robotics.hellobike.com/models/internrobotics-internvla-n1-wo-dagger) |
| **[Miril-Drone-2B-1](https://robotics.hellobike.com/models/mirilai-miril-drone-2b-1)** | other | 5.1B | Gemma4ForConditionalGeneration | apache-2.0 | MirilAI 在 Hugging Face 发布的机器人模型，架构为 Gemma4ForConditionalGeneration，参数规 | [模型卡](https://robotics.hellobike.com/models/mirilai-miril-drone-2b-1) |
| **[RoboBrain2.0-32B](https://robotics.hellobike.com/models/baai-robobrain2-0-32b)** | vla | 33.5B | Qwen2_5_VLForConditionalGeneration | apache-2.0 | BAAI 在 Hugging Face 发布的机器人模型，架构为 Qwen2_5_VLForConditionalGeneration，参数 | [模型卡](https://robotics.hellobike.com/models/baai-robobrain2-0-32b) |
| **[VLAC](https://robotics.hellobike.com/models/internrobotics-vlac)** | other | 2.2B | InternVLChatModel | cc-by-nc-sa-4.0 | InternRobotics 在 Hugging Face 发布的机器人模型，架构为 InternVLChatModel，参数规模 2.2B | [模型卡](https://robotics.hellobike.com/models/internrobotics-vlac) |
| **[InternVLA-A1-3B](https://robotics.hellobike.com/models/internrobotics-internvla-a1-3b)** | vla | 3.2B | Transformer (Qwen/Qwen3-VL-2B-Instruct) | cc-by-nc-sa-4.0 | InternRobotics 在 Hugging Face 发布的机器人模型，架构为 Transformer (Qwen/Qwen3-VL- | [模型卡](https://robotics.hellobike.com/models/internrobotics-internvla-a1-3b) |
| **[flux-3-action-droid](https://robotics.hellobike.com/models/black-forest-labs-flux-3-action-droid)** | world_model | 6.9B | Flow Matching World-Action Model (Flux) | other | black-forest-labs 在 Hugging Face 发布的机器人模型，架构为 Flow Matching World-Acti | [模型卡](https://robotics.hellobike.com/models/black-forest-labs-flux-3-action-droid) |
| **[openpie-0.6](https://robotics.hellobike.com/models/exla-ai-openpie-0-6)** | vla | 3.3B | π0 (PaliGemma VLM + Flow Matching Action Expert) | apache-2.0 | exla-ai 在 Hugging Face 发布的机器人模型，架构为 π0 (PaliGemma VLM + Flow Matching  | [模型卡](https://robotics.hellobike.com/models/exla-ai-openpie-0-6) |
| **[DreamZero-DROID](https://robotics.hellobike.com/models/gear-dreams-dreamzero-droid)** | world_model | 22.9B | VLA | cc-by-nc-4.0 | GEAR-Dreams 在 Hugging Face 发布的机器人模型，架构为 VLA，参数规模 22.9B，训练数据包含 GEAR-Dre | [模型卡](https://robotics.hellobike.com/models/gear-dreams-dreamzero-droid) |
| **[act_aloha_sim_transfer_cube_human](https://robotics.hellobike.com/models/lerobot-act-aloha-sim-transfer-cube-human)** | policy | 52M | ACT (Action Chunking Transformer) | apache-2.0 | lerobot 在 Hugging Face 发布的机器人模型，架构为 ACT (Action Chunking Transformer)  | [模型卡](https://robotics.hellobike.com/models/lerobot-act-aloha-sim-transfer-cube-human) |
| **[LabVLA-5B-Base](https://robotics.hellobike.com/models/zjunlp-labvla-5b-base)** | vla | 4.7B | LeRobot / PyTorch Policy Network | mit | zjunlp 在 Hugging Face 发布的机器人模型，参数规模 4.7B。 | [模型卡](https://robotics.hellobike.com/models/zjunlp-labvla-5b-base) |
| **[microduck-flamingo-cycle](https://robotics.hellobike.com/models/remifabre-microduck-flamingo-cycle)** | policy | 0.18M | MLP Actor-Critic Policy (RL Locomotion) | apache-2.0 | RemiFabre 在 Hugging Face 发布的机器人模型，架构为 MLP Actor-Critic Policy (RL Loco | [模型卡](https://robotics.hellobike.com/models/remifabre-microduck-flamingo-cycle) |
| **[lingbot-vla-4b](https://robotics.hellobike.com/models/robbyant-lingbot-vla-4b)** | vla | 4.2B | LeRobot / PyTorch Policy Network | Apache-2.0 | robbyant 在 Hugging Face 发布的机器人模型，参数规模 4.2B。 | [模型卡](https://robotics.hellobike.com/models/robbyant-lingbot-vla-4b) |
| **[F1-VLA](https://robotics.hellobike.com/models/internrobotics-f1-vla)** | vla | 4.2B | MWMForConditionalGeneration | cc-by-nc-sa-4.0 | InternRobotics 在 Hugging Face 发布的机器人模型，架构为 MWMForConditionalGeneration | [模型卡](https://robotics.hellobike.com/models/internrobotics-f1-vla) |
| **[LightNav-0](https://robotics.hellobike.com/models/lightoriginshq-lightnav-0)** | other | 4.8B | Qwen3VLForConditionalGeneration | apache-2.0 | LightOriginsHQ 在 Hugging Face 发布的机器人模型，架构为 Qwen3VLForConditionalGenera | [模型卡](https://robotics.hellobike.com/models/lightoriginshq-lightnav-0) |
| **[microduck-policies](https://robotics.hellobike.com/models/pollen-robotics-microduck-policies)** | other | 80M | MLP Actor-Critic Policy (RL Locomotion) | apache-2.0 | pollen-robotics 在 Hugging Face 发布的机器人模型，架构为 MLP Actor-Critic Policy (R | [模型卡](https://robotics.hellobike.com/models/pollen-robotics-microduck-policies) |

---

## 三、具身智能高下载开源数据集 (Top 30)

| 数据集名称 | 采集方式 | 时长(h) | 轨迹数(Episodes) | 格式 | 详情与下载 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[PhysicalAI-Robotics-GR00T-X-Embodiment-Sim](https://robotics.hellobike.com/datasets/nvidia-physicalai-robotics-gr00t-x-embodiment-sim)** | sim | — | 102 | Parquet | [数据集详情](https://robotics.hellobike.com/datasets/nvidia-physicalai-robotics-gr00t-x-embodiment-sim) |
| **[Gen-HumanEgo](https://robotics.hellobike.com/datasets/genrobot2025-gen-humanego)** | human_video | — | — | Parquet | [数据集详情](https://robotics.hellobike.com/datasets/genrobot2025-gen-humanego) |
| **[autodex-gallery](https://robotics.hellobike.com/datasets/willi19-autodex-gallery)** | teleop | — | 2610 | Parquet | [数据集详情](https://robotics.hellobike.com/datasets/willi19-autodex-gallery) |
| **[10Kh-RealOmin-OpenData](https://robotics.hellobike.com/datasets/genrobot2025-10kh-realomin-opendata)** | teleop | — | — | Parquet | [数据集详情](https://robotics.hellobike.com/datasets/genrobot2025-10kh-realomin-opendata) |
| **[ABC-130k](https://robotics.hellobike.com/datasets/xdof-abc-130k)** | teleop | — | — | Parquet | [数据集详情](https://robotics.hellobike.com/datasets/xdof-abc-130k) |
| **[droid_1.0.1](https://robotics.hellobike.com/datasets/cadene-droid-1-0-1)** | teleop | 511.34 | 95600 | LeRobot | [数据集详情](https://robotics.hellobike.com/datasets/cadene-droid-1-0-1) |
| **[OmniAction](https://robotics.hellobike.com/datasets/openmoss-team-omniaction)** | teleop | — | 141162 | Parquet | [数据集详情](https://robotics.hellobike.com/datasets/openmoss-team-omniaction) |
| **[language_table_lerobot](https://robotics.hellobike.com/datasets/ipec-community-language-table-lerobot)** | teleop | 195.71 | 442226 | LeRobot | [数据集详情](https://robotics.hellobike.com/datasets/ipec-community-language-table-lerobot) |
| **[AgiBotWorld2026](https://robotics.hellobike.com/datasets/agibot-world-agibotworld2026)** | teleop | — | — | Parquet | [数据集详情](https://robotics.hellobike.com/datasets/agibot-world-agibotworld2026) |
| **[droid_lerobot](https://robotics.hellobike.com/datasets/ipec-community-droid-lerobot)** | teleop | 500.82 | 92233 | LeRobot | [数据集详情](https://robotics.hellobike.com/datasets/ipec-community-droid-lerobot) |
| **[HiFi-UMI-2K](https://robotics.hellobike.com/datasets/simple-world-lab-hifi-umi-2k)** | teleop | 2000 | — | LeRobot/parquet | [数据集详情](https://robotics.hellobike.com/datasets/simple-world-lab-hifi-umi-2k) |
| **[PhysicalAI-Robotics-Open-H-Embodiment](https://robotics.hellobike.com/datasets/nvidia-physicalai-robotics-open-h-embodiment)** | teleop | 750 | — | Parquet | [数据集详情](https://robotics.hellobike.com/datasets/nvidia-physicalai-robotics-open-h-embodiment) |
| **[grand_tour_dataset](https://robotics.hellobike.com/datasets/leggedrobotics-grand-tour-dataset)** | teleop | — | — | Parquet | [数据集详情](https://robotics.hellobike.com/datasets/leggedrobotics-grand-tour-dataset) |
| **[Egocentric-100K](https://robotics.hellobike.com/datasets/builddotai-egocentric-100k)** | human_video | — | — | webdataset | [数据集详情](https://robotics.hellobike.com/datasets/builddotai-egocentric-100k) |
| **[2025-challenge-demos](https://robotics.hellobike.com/datasets/behavior-1k-2025-challenge-demos)** | teleop | 1102.73 | 10000 | LeRobot | [数据集详情](https://robotics.hellobike.com/datasets/behavior-1k-2025-challenge-demos) |
| **[UrbanVerse-Assets-Sim-ready](https://robotics.hellobike.com/datasets/ucla-vail-urbanverse-assets-sim-ready)** | sim | — | — | Parquet | [数据集详情](https://robotics.hellobike.com/datasets/ucla-vail-urbanverse-assets-sim-ready) |
| **[kuka_lerobot](https://robotics.hellobike.com/datasets/ipec-community-kuka-lerobot)** | teleop | 68.22 | 209880 | LeRobot | [数据集详情](https://robotics.hellobike.com/datasets/ipec-community-kuka-lerobot) |
| **[PhysicalAI-Robotics-Manipulation-Kitchen-Demos](https://robotics.hellobike.com/datasets/nvidia-physicalai-robotics-manipulation-kitchen-demos)** | teleop | 600 | 55000 | Parquet | [数据集详情](https://robotics.hellobike.com/datasets/nvidia-physicalai-robotics-manipulation-kitchen-demos) |
| **[SharpaDex-v1.0](https://robotics.hellobike.com/datasets/sharpa-robotics-sharpadex-v1-0)** | teleop | 300.0 | 28993 | Parquet | [数据集详情](https://robotics.hellobike.com/datasets/sharpa-robotics-sharpadex-v1-0) |
| **[exp-bucket](https://robotics.hellobike.com/datasets/mh-hf-exp-bucket)** | teleop | 2312.4 | 292198 | Parquet | [数据集详情](https://robotics.hellobike.com/datasets/mh-hf-exp-bucket) |
| **[bridge_orig_lerobot](https://robotics.hellobike.com/datasets/ipec-community-bridge-orig-lerobot)** | teleop | 105.17 | 53192 | LeRobot | [数据集详情](https://robotics.hellobike.com/datasets/ipec-community-bridge-orig-lerobot) |
| **[FastUMI_100k_lerobot](https://robotics.hellobike.com/datasets/ipec-community-fastumi-100k-lerobot)** | teleop | — | — | Parquet | [数据集详情](https://robotics.hellobike.com/datasets/ipec-community-fastumi-100k-lerobot) |
| **[tracker-pov](https://robotics.hellobike.com/datasets/eidon-ai-tracker-pov)** | human_video | 1273.8 | 13451 | Parquet | [数据集详情](https://robotics.hellobike.com/datasets/eidon-ai-tracker-pov) |
| **[AgiBotWorld-Beta](https://robotics.hellobike.com/datasets/agibot-world-agibotworld-beta)** | teleop | — | — | webdataset | [数据集详情](https://robotics.hellobike.com/datasets/agibot-world-agibotworld-beta) |
| **[HABIT](https://robotics.hellobike.com/datasets/configinc-habit)** | teleop | 164.19 | 10563 | LeRobot/parquet | [数据集详情](https://robotics.hellobike.com/datasets/configinc-habit) |
| **[nuReasoning](https://robotics.hellobike.com/datasets/nureasoning-nureasoning)** | teleop | — | — | Parquet | [数据集详情](https://robotics.hellobike.com/datasets/nureasoning-nureasoning) |
| **[droid](https://robotics.hellobike.com/datasets/cadene-droid)** | teleop | 500.82 | 92233 | LeRobot | [数据集详情](https://robotics.hellobike.com/datasets/cadene-droid) |
| **[roboverse_data](https://robotics.hellobike.com/datasets/roboverseorg-roboverse-data)** | teleop | — | — | Parquet | [数据集详情](https://robotics.hellobike.com/datasets/roboverseorg-roboverse-data) |
| **[L2D](https://robotics.hellobike.com/datasets/yaak-ai-l2d)** | teleop | 735.19 | 100000 | LeRobot/parquet | [数据集详情](https://robotics.hellobike.com/datasets/yaak-ai-l2d) |
| **[fractal20220817_data_lerobot](https://robotics.hellobike.com/datasets/ipec-community-fractal20220817-data-lerobot)** | teleop | 350.59 | 87212 | LeRobot | [数据集详情](https://robotics.hellobike.com/datasets/ipec-community-fractal20220817-data-lerobot) |

---

## 四、精选硬核深度解读与选型路线

- [π0 到 π0.5 演进拆解：Flow Matching 动作专家与开放世界泛化边界](https://robotics.hellobike.com/explainers/openpi-pi0-pi05-flow-matching-vla)
- [NVIDIA GR00T N1.5 / N1.7 与 Cosmos 世界模型全栈解析](https://robotics.hellobike.com/explainers/nvidia-gr00t-n1-5-n1-7-cosmos-stack)
- [宇树 G1 / H2 强化学习全身运动控制（WBC）与 unitree_sdk2 软件栈拆解](https://robotics.hellobike.com/explainers/unitree-g1-h2-locomotion-rl-sdk2-stack)
- [163 款机器人公开售价与租赁价格拆解：从万元桌面臂到百万工业人形](https://robotics.hellobike.com/explainers/robot-pricing-and-rental-landscape)
- [具身智能 120 案拆解：亿元订单与 1250 工时背后的 POC 验收鸿沟](https://robotics.hellobike.com/explainers/humanoid-commercialization-tracker)
- [物理仿真器选型横评：Isaac Lab vs MuJoCo 3 vs Genesis vs Gazebo](https://robotics.hellobike.com/routes/simulator-comparison)

## 贡献与纠错
如发现机型参数、最新报价或开源仓库变更，欢迎直接在 [社区投稿与纠错页 (https://robotics.hellobike.com/submit/)](https://robotics.hellobike.com/submit/) 提交。
