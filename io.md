# 入力

## 文字列入力
stackの上(length)個に文字一つ一つのascii codeをpushする。
```
>i:a=?v\   [[[ input(), sep='\n' ]]]
\      /
/    ~/
```

```
>i:f2*2+=?v\   [[[ input(), sep=' ' ]]]
\          /
/        ~/
```

## 数字入力
stackの上に数字をpushする。

```
>0>i:a=?v4a*8+-$a*+\   [[[ int(input()), sep='\n' ]]]
  \                /
/      ~/
```

```
>0>i:f2*2+=?v4a*8+-$a*+\   [[[ int(input()), sep=' ' ]]]
  \                    /
/          ~/
```

```
v                         \   [[[ IN(vector<int>( pop_back()) ), sep=' ']]]
>0>i:f2*2+=?v4a*8+-$a*+\
  \                    /
/          ~/
>{1-:0=?v}                /
/      ~/
r
```