# 🧩 题目：日志分析与统计

## 背景：
你有一个简单的日志文件 access.log，每一行的格式如下：

```
2025-10-31 13:20:45 [INFO] user=john action=login duration=1.23
2025-10-31 13:21:02 [INFO] user=alice action=download duration=4.56
2025-10-31 13:21:15 [ERROR] user=bob action=upload duration=0.98
```

请编写一个 Python 程序，完成以下任务：

- 从文件中读取日志数据。

- 测试文件为 `test1-3.log`

- 统计每个用户的平均 duration。

- 输出一个字典或表格，按平均耗时从大到小排序。

- 额外挑战（可选）：打印出所有发生 ERROR 的日志行。

## 要求：

- 代码结构清晰，函数化；

- 不使用 pandas；

- 能在 25 分钟内写完并跑通。

