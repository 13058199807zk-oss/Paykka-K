# PayKKa余额预警阈值配置
```
BALANCE_THRESHOLDS = {
    # 机构名必须完全匹配：易宝, Currencycloud, 海云汇
    ("易宝", "USD"): 750000.00,
    ("易宝", "CNH"): 3550000.00,
    ("易宝", "HKD"): 10000.00,
    ("Currencycloud", "USD"): 10000.00,
    ("Currencycloud", "EUR"): 400000.00,
    ("Currencycloud", "GBP"): 100000.00,
    ("海云汇", "USD"): 1000.00,
    ("海云汇", "CNH"): 0.00,
    ("海云汇", "HKD"): 1000.00
}
```
# 注意：键是元组 (机构名, 币种)，值是阈值金额
