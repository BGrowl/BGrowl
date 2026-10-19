<p align="center">
  <img src="https://raw.githubusercontent.com/BGrowl/BGrowl/main/banner.svg" width="100%" alt="BGrowl — Building systems, from signals to software." />
</p>

### 把想法做成系统，把系统打磨到能用。

我是 **BGrowl**，南方科技大学在读学生。关注 **嵌入式系统、机器人控制、信号处理与工程自动化**，喜欢从真实问题出发，把传感器、算法、固件、界面和部署连成一条完整的工程链路。

从让双轮小车保持平衡，到从脉搏波中提取有效信息，再到让数据持续采集、更新和触达用户——我关心每一层实现，也关心它们协同工作后的实际效果。

**Embedded Systems · Robotics & Control · Signal Processing · Data Products**

---

### 精选项目

#### [STM32 双轮自平衡与视觉寻球](https://github.com/BGrowl/STM32F767-balance-car)

**从底层闭环控制，到视觉驱动的任务执行。**

基于 STM32F767、MPU6050 与编码器构建平衡控制，结合 K230 视觉模块完成红球识别、搜索、对准与推球。将直立 PD、速度 PI、转向控制、串口协议和任务状态机接入同一套系统，配套硬件接线、参数调试与复现文档。

`C / C++` `STM32 HAL` `MPU6050` `K230` `闭环控制` `状态机`

#### [PPG 外周循环监测原型](https://github.com/BGrowl/ST_Project)

**先判断信号是否可信，再讨论指标意味着什么。**

围绕 MAX30102 指尖脉搏波，串联信号采集、心率、短时 HRV 估计、灌注指数与实时可视化。通过 Checking / Weak Signal / Motion / Good 四态质量判定处理接触与运动干扰，使用 PyQt6 和 pyqtgraph 展示波形及指标，并以 IEEE 会议模板整理课程报告。

`Python` `Arduino` `PPG` `PyQt6` `pyqtgraph` `LaTeX`

#### [跨商家卡券规格级比价](https://github.com/BGrowl/kaquan-bijia)

**把分散的商品信息，变成可以直接比较的决策入口。**

打通数据采集、规格归一、跨商家比价、商品直链和静态站点发布；通过 GitHub Actions 按每 6 小时的计划更新。项目数据快照覆盖 **38 家商家、6,180 个规格**，同时针对移动端优化首屏请求、数据加载与列表渲染。

`Python` `JavaScript` `数据归一化` `GitHub Actions` `前端性能`

#### [顺风车车源看板](https://github.com/BGrowl/zuche-hitch-board)

**让持续变化的信息，按需要筛选、排序并主动送达。**

构建车源采集、车型评分、城市与日期筛选、网页看板和微信通知的完整流程。后端使用 Python 标准库，加入后台刷新、通知去重与采集失败时保留上次有效数据的机制，兼顾日常使用与运行维护。

`Python` `数据管线` `Web Dashboard` `消息推送` `故障恢复`

#### [Android 定时触控与诊断实验](https://github.com/BGrowl/shangou-android)

探索手机独立运行、时间校准、定时触控与现场诊断，保留 **63 项回归测试**、开发逻辑及实测记录。该方向目前因时间原因暂时搁置，后续优化空间与当前实测边界均记录在仓库中。

`JavaScript` `AutoX.js` `时间校准` `回归测试` `诊断日志`

---

### 技术栈与工程实践

| 方向 | 项目中使用的技术与方法 |
| --- | --- |
| 嵌入式与控制 | C / C++ · STM32 · Arduino · 传感器采集 · 闭环控制 · 串口通信 |
| 信号与可视化 | Python · PPG 特征提取 · 信号质量判定 · PyQt6 · pyqtgraph |
| 数据与应用 | 数据采集与归一化 · 评分与筛选 · HTML / CSS / JavaScript · 消息推送 |
| 交付与复现 | Git · GitHub Actions · Linux · 回归测试 · 运行诊断 · LaTeX · 中文技术文档 |

### 我的工程习惯

- **沿着完整链路定位问题。** 从传感器、时序和通信，一直看到算法输出与用户界面。
- **让测量支撑优化。** 用波形、日志、实测记录和回归检查解释系统行为。
- **把复现也当成交付。** 记录接线、参数、协议、运行方式与已知边界，让下一次迭代有据可依。

欢迎围绕嵌入式、机器人、信号处理和实用工具交流。可以在[相关项目](https://github.com/BGrowl?tab=repositories)的 Issues 中讨论具体问题。

**Build with curiosity. Refine with evidence.**
