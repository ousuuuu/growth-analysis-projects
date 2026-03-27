# Shopee 漏斗分析流程图

```mermaid
flowchart TD
    A[访问用户 1000] --> B[注册用户 600]
    B --> C[浏览用户 500]
    C --> D[加购用户 200]
    D --> E[下单用户 120]
