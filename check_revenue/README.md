# 電商訂單對帳分析

##  分析概述

旨在比對第三方平台訂單和官網訂單，識別差異並找出不對稱金額原因及訂單。

## 主要流程

- **訂單導入**：支持載入不同來源的訂單報表
- **數據清理**：標準化日期格式，處理訂單號碼
- **差異檢測**：
  * 識別遺失訂單
  * 檢查金額不一致
  * 跨年度訂單比較
- **重複訂單處理**


##  環境需求

- Python 3.9+
- 必要套件：
  - pandas

## 安裝方式

```bash
pip install pandas
```

##  注意事項

- 僅供參考
