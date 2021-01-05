# Compiler in Python

## A simple compiler written in python

- Currently, the following code can be compiled into assembly code.

```
5*(9-6) <= 15;
a = 1; b = 2; a + b == 3;
```

## How to use

`python main.py '<statement you want to compile>' >> tmp.s`<br>
`gcc -o tmp tmp.s`<br>

## Reference

- [低レイヤを知りたい人のための C コンパイラ作成入門](https://www.sigbus.info/compilerbook)
