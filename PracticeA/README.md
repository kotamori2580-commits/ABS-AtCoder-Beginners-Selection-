# [問題ID] PracticeA - Welcome to AtCoder
## 🔗 問題リンク
https://atcoder.jp/contests/abs/tasks

## 💡 アプローチ・考察
- mapの使い方を学んだ
- 代入した数字はint化しておく

## 🛠 実装 (Python)
```python
# ここにコードを貼り付ける
a = int(input())
b, c = map(int, input().split())
s = input()
print(f"{a+b+c} {s}")
