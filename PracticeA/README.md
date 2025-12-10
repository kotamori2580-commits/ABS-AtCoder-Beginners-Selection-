# [問題ID] 問題タイトル
## 🔗 問題リンク
https://atcoder.jp/contests/abs/tasks/abc086a_a

## 💡 アプローチ・考察
- 入力値 a, b の積が偶数か奇数かを判定する。
- 実際に掛け算をして、2で割った余りを見る。
## 🛠 実装 (Python)
```python
# ここにコードを貼り付ける
a, b = map(int, input().split())

if (a * b) % 2 == 0:
    print("Even")
else:
    print("Odd")
