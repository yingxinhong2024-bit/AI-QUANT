# AI-QUANT

AI驱动的量化投资分析工具集

## 股票看板

| 股票 | 代码 | 数据区间 | 看板 |
|------|------|----------|------|
| 中际旭创 | 300308.SZ | 2025-07-04 ~ 2026-07-04 | [查看](https://yingxinhong2024-bit.github.io/AI-QUANT/) |

## 项目结构

```
├── index.html          # 主看板页面
├── data/               # 股票数据CSV
│   └── 300308_中际旭创_日线.csv
└── scripts/            # 生成脚本
    └── generate_dashboard.py
```

## 数据来源

数据通过 Tushare Pro API 获取，仅供参考研究，不构成投资建议。
