# Hi, I'm Honglin Zeng · 曾弘霖

**C++ · Python · JavaScript | Scientific Computing · Engineering Software · 3D Visualization**

我是一名具有力学与工程背景的软件开发者，现于**东南大学攻读力学硕士**。掌握 **C++、Python、JavaScript**，具备模块化编程、数值计算、工程数据处理与交互可视化能力，能够将力学模型和工程分析需求实现为可运行、可验证的应用。

I develop engineering applications with **C++17, Python, and JavaScript**, combining computational mechanics, numerical computation, data processing, and interactive visualization. My project experience includes a native Windows fracture-mechanics application and a collaborative structural-monitoring analysis workbench.

## Programming & Development

| 技术 | 能力与项目实践 |
| :--- | :--- |
| **C++ / C++17** | 模块化程序设计、数值计算与原生桌面应用开发；分离计算核心与界面，处理单位换算、输入校验、浮点异常与临界状态判定。 |
| **Python** | 工程文件解析、Excel 数据处理、规则计算与分析应用集成；使用 openpyxl、Decimal、Streamlit 组织数据读取、温度修正、应力换算与异常处理。 |
| **JavaScript / ES6+** | 三维可视化与浏览器交互开发；使用 Three.js、Canvas 实现构件拾取、实例化绘制、剖切、时程曲线、联动游标与 CSV 导出。 |
| **Engineering Software** | 掌握 Abaqus、Ansys；具备结构建模、非线性与损伤分析、网格敏感性检查、收敛检查及结果后处理经验。 |

我的开发实践覆盖**计算模型 → 程序实现 → 参数与数据校验 → 交互展示 → 结果验证**，重视模块边界、异常输入处理和计算结果的可靠性。

## Featured Projects

### [Griffith Energy Balance · 能量平衡计算与可视化](https://github.com/zenghl84/griffith-energy-balance)

**C++17 · Win32 · GDI+ · Numerical Computation**  
**独立开发 | 2026.09**

面向线弹性断裂力学的原生 Windows 应用，将 Griffith 能量平衡模型、参数交互和图表分析集成在同一界面。

- **计算实现：**针对无限大板中心贯穿裂纹，实现平面应力 / 平面应变下的能量释放率、I 型应力强度因子、临界应力及临界裂纹半长计算。
- **数值可靠性：**统一 SI 单位，采用 `long double` 中间量与相对容差判定，处理溢出、下溢、零应力和非法参数等边界。
- **应用开发：**分离计算核心与 Win32 界面，实现交互式模型示意、能量曲线、参数扫描和 CSV 导出。
- **验证记录：**完成 **93 项计算与输入检查、39 项界面检查**，覆盖物理关系、临界状态、异常输入与交互功能。

### [SteelSafety · 钢结构监测与三维可视化工作台](https://github.com/zenghl84/SteelSafety)

**Python · JavaScript · Three.js · Canvas · Streamlit · openpyxl**  
**协作开发 | 2026.08–2026.10**

面向钢结构历史监测数据复核，将结构模型、监测记录、应力参考计算与三维定位整合为浏览器工作台。

- **Python 数据处理：**解析 MGT 结构模型与 Excel 历史监测数据，实现单位统一、温度修正、应力换算、分段参考评分与测点映射校验。
- **JavaScript 三维交互：**基于 Three.js 实现构件拾取、高亮、隐藏、剖切与静态应力云图；采用 `InstancedMesh` 批量绘制杆件和节点，并通过按需重绘组织渲染。
- **数据可视化：**结合 Canvas、Streamlit 实现多测点时程曲线、时间筛选、联动游标、三维构件定位与 CSV 导出。
- **异常与来源处理：**区分缺测、设备故障和应力复核项，保留数据来源，将异常记录关联到相应构件，支持复核与追溯。

## Technical Focus

**C++ 科学计算与工程软件开发 · Python 工程数据分析 · JavaScript 三维交互 · 计算力学与有限元分析**

我关注如何把力学问题转化为清晰的计算模型，把计算模型实现为可靠的程序，并通过数据与可视化让结果更容易分析和验证。

## Contact

- **Email:** [zenghl84@163.com](mailto:zenghl84@163.com)
- **GitHub:** [@zenghl84](https://github.com/zenghl84)
