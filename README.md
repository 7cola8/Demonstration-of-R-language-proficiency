# 家庭的月收入与支出建模分析

本项目旨在使用 R 语言对某家庭的月收入与支出进行建模分析，识别影响支出的主要因素，并建立合理的预测模型。

# 销售价格、购进价格与销售费用的关系建模分析

本项目通过 R 语言进行建模，旨在探索销售价格、购进价格与销售费用三者之间的定量关系，为企业经营决策提供数据支持。

## 📌 项目文件说明

- `家庭的月收入与支出建模分析.Rmd`：项目核心分析文档，包含数据处理、建模分析、可视化及结果解释等完整流程。
- `家庭的月收入与支出建模分析.html`：可将 `.Rmd` 渲染为 `.html` 以便查看格式化报告。
- `销售价格+购进价格+销售费用关系建模.Rmd`：本项目的核心分析脚本，包含完整的建模过程、数据可视化、回归分析等内容。
- `销售价格+购进价格+销售费用关系建模.html`：可将 `.Rmd` 渲染为 `.html` 以便查看格式化报告。

## 🔧 使用方法

1. 请确保已安装 R 和 RStudio。
2. 需加载的主要 R 包包括但不限于：
   - `ggplot2`
   - `dplyr`
   - `car`
   - `readr`
   - `lmtest`
   - `tidyverse`
3. 打开 `.Rmd` 文件，点击 RStudio 中的 "Knit" 按钮生成 HTML 格式的分析报告。

## 📊 分析内容摘要

- **数据预处理**：对原始数据进行清洗、标准化处理。
- **变量分析**：探索性数据分析，检验自变量与支出间的关系。
- **线性回归建模**：建立家庭支出预测模型，解释各变量对支出的影响。
- **模型优化与诊断**：残差分析、多重共线性检验、模型稳健性评估等。

## 💡 项目亮点

- 从数据探索到建模全流程完整记录。
- 使用多种图表（如散点图、残差图等）直观展现结果。
- 对影响支出的关键因子进行了系统性分析。
- 为企业在成本控制与定价策略方面提供数据支持；
- 通过回归模型量化不同成本因素对销售费用的影响；
- 演示了 R Markdown 在商业数据建模中的实际应用。
