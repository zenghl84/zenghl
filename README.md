# Hi, I'm Honglin Zeng · 曾弘霖

C++ · Python · JavaScript | Scientific Computing · Engineering Software · 3D Visualization

我是一名具有力学与工程背景的软件开发者，现于东南大学攻读力学硕士。掌握 C++、Python、JavaScript，具备模块化编程、数值计算、工程数据处理与交互可视化能力，能够将力学模型和工程分析需求实现为可运行、可验证的应用。

I develop engineering applications with C++17, Python, and JavaScript, combining computational mechanics, numerical computation, data processing, and interactive visualization. My project experience includes a native Windows fracture-mechanics application and a collaborative structural-monitoring analysis workbench.

## Programming & Development

| 技术 | 能力与项目实践 |
| :--- | :--- |
| C++ / C++17 | 模块化程序设计、数值计算与原生桌面应用开发；分离计算核心与界面，处理单位换算、输入校验、浮点异常与临界状态判定。 |
| Python | 工程文件解析、Excel 数据处理、规则计算与分析应用集成；使用 openpyxl、Decimal、Streamlit 组织数据读取、温度修正、应力换算与异常处理。 |
| JavaScript / ES6+ | 三维可视化与浏览器交互开发；使用 Three.js、Canvas 实现构件拾取、实例化绘制、剖切、时程曲线、联动游标与 CSV 导出。 |
| Engineering Software | 掌握 Abaqus、Ansys；具备结构建模、非线性与损伤分析、网格敏感性检查、收敛检查及结果后处理经验。 |

我的开发实践覆盖计算模型 → 程序实现 → 参数与数据校验 → 交互展示 → 结果验证，重视模块边界、异常输入处理和计算结果的可靠性。

## Featured Projects

### [Griffith Energy Balance · 能量平衡计算与可视化](https://github.com/zenghl84/griffith-energy-balance)

C++17 · Win32 · GDI+  
独立开发 | 2026.09

基于 Griffith 能量平衡模型的 Windows 断裂力学计算与可视化应用。

- 支持平面应力 / 应变，计算能量释放率、I 型应力强度因子、临界应力与临界裂纹半长。
- 统一 SI 单位，使用 `long double` 与相对容差，处理非法输入及数值边界。
- 分离计算核心与界面，提供模型交互、能量曲线、参数扫描与 CSV 导出。
- 验证记录：93 项计算与输入检查、39 项界面检查。

### [SteelSafety · 钢结构监测与三维可视化工作台](https://github.com/zenghl84/SteelSafety)

Python · JavaScript · Three.js · Canvas · Streamlit · openpyxl  
协作开发 | 2026.08–2026.10

整合结构模型、历史监测数据与三维定位的钢结构分析工作台。

- Python：解析 MGT 模型与 Excel 数据，完成单位统一、温度修正、应力换算与参考评分，校验测点映射并区分缺测和设备故障。
- JavaScript / Three.js：实现构件拾取、高亮、隐藏、剖切与静态应力云图，采用实例化绘制和按需重绘。
- Canvas / Streamlit：提供多测点曲线、时间筛选、联动游标、三维定位与 CSV 导出，支持异常记录及数据来源追溯。

## Technical Focus

C++ 科学计算与工程软件开发 · Python 工程数据分析 · JavaScript 三维交互 · 计算力学与有限元分析

我关注如何把力学问题转化为清晰的计算模型，把计算模型实现为可靠的程序，并通过数据与可视化让结果更容易分析和验证。

## Contact

- Email: [zenghl84@163.com](mailto:zenghl84@163.com)
- GitHub: [@zenghl84](https://github.com/zenghl84)
