# ><> standard library

## ><>ってなに？

- https://esolangs.org/wiki/Fish
- https://github.com/n4o847/esolangs/wiki/Fish


## ライブラリの使い方
コード全体を
```
関数1
v
関数2
v
...
v
関数n
\>;
```
のような構造にできるようにしています

## 小数点切り捨ての割り算
stackの上2つの切り捨て割り算をした値をpushする。
```
>:@$:@$%-$,\   [[[ floor_div(a, b) ]]]
/          /
```

## max, min
stackの上2つのmax, minをそれぞれpushする。
```
>:@$:@)?$~\   [[[ min(a, b) ]]]
/         /
```

```
>:@$:@(?$~\   [[[ max(a, b) ]]]
/         /
```