# Risk-A-Lab-Visualization
本仓库存储了系列讲座第二讲“多源数据分析与可视化”中所涉及代码、数据、课件及参考资料。以下为文件目录：

- `/data`: 代码所使用数据及编码手册
  - `/large_file`: 原始数据
    - `/congress_tweets`: 第117届美国国会议员推特文本数据切片（原始来源：(https://zenodo.org/records/20150481)[https://zenodo.org/records/20150481]）
    - `/natural_earth_boundaries`: 世界地图Shapefile数据（来源：(https://zenodo.org/records/20150481)[https://www.naturalearthdata.com/downloads/110m-cultural-vectors/]）
    - `/UCDP_GED`: 乌普萨拉冲突事件地理数据集及编码手册（来源：(https://zenodo.org/records/20150481)[https://ucdp.uu.se/downloads/]）
    - `/PRIO_GRID`: 奥斯陆和平研究所0.5°×0.5°地理参考网格及分网格数据（来源：(https://zenodo.org/records/20150481)[https://grid.prio.org/]）
  - `/clean`: 部分持久化的清洗后数据
- `/docs`: 课件和参考资料
  - `课件：多源数据分析与可视化.pdf`：课件
  - `附件1：常见可视化图表类型整理.pdf`：数据结构、制图目的与可选图表映射表
  - `附件2：Matplotlib Cheat Sheet.pdf`：Matplotlib官方“一页纸摘要”
- `/scripts`: 代码部分
  - `Examples.ipynb`: 常见图表（折线图、热图、直方图和核密度图、网络图、风险地图）演示代码
  - `Replication.ipynb`: 大语言模型辅助绘图示例代码（Lobbyview原交互式图表URL：(https://zenodo.org/records/20150481)[https://www.lobbyview.org/visualizations?vizTab=industryLevelAnalysis]）
