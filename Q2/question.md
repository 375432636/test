# 🧩 题目：最短连续子数组的覆盖问题

## 题目描述：
给定一个字符串 s 和一个字符串数组 words，
要求找出字符串 s 中最短的连续子串，使得这个子串中包含了 words 中的所有单词（每个至少一次）。

如果不存在，返回空字符串 ""。

words 中的单词可能有重复。

单词顺序不要求一致。

示例：

```
s = "barfoothefoobarman"
words = ["foo", "bar"]
输出: "barfoo"   # 或 "foobar" 都可以
```
```
s = "lingmindraboofooowingdingbarrwingmonkeypoundcake"
words = ["fooo","barr","wing","ding","wing"]
输出: "foowingdingbarrwing"
```

## 要求：

时间复杂度尽量低于 O(n²)；

写出思路或注释；

不使用外部库（可以用 collections、Counter）。
