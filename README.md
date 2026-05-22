# 📝 谷歌云学习与量化交易笔记

这是一个用于同步和备份我在 Google Colab 上学习记录的仓库。内容涵盖了深度学习、金融数据分析以及自动化脚本的实践。

## 🚀 项目概览

- **核心内容**: 基于 LSTM 的股票价格预测模型、数据抓取自动化。
- **主要工具**: Python, TensorFlow/Keras, yfinance, Pandas, Matplotlib。
- **自动同步**: 使用 Colab 脚本定期将 Google Drive 中的 `.ipynb` 笔记同步至此仓库。

## 文件夹说明

- `data/`: 存放从 yfinance 或 AkShare 获取的股票历史数据（CSV）。
- `models/`: 训练好的 `.keras` 格式 LSTM 模型文件。
- `charts/`: 预测结果的可视化图表。
- `*.ipynb`: 各个阶段的学习笔记与实验代码。

## 📅 最近进展

- [x] 解决 AkShare 连接中断问题，切换至 `yfinance` 数据源。
- [x] 实现多支股票的批量训练与 10 日趋势预测。
- [x] 修复 Matplotlib 中文显示与数据对齐问题。
- [ ] 待办：引入更多特征（如技术指标指标融合）优化模型准确率。