# 1/Nオクターブ解析プロジェクト

## 注意
次の場所で指定されたコマンドを実行してください: `~/.../lib/python3.8/site-packages/pyfilterbank`

```
gcc -c -std=c99 -O3 sosfilt.c
gcc -shared -o sosfilt.so sosfilt.o
```

### コマンドの説明

**gcc -c -std=c99 -O3 sosfilt.c:**
- `gcc`: GNU Compiler Collection。C言語のコードをコンパイルするために使われるプログラム。
- `-c`: ソースファイルをコンパイルしてオブジェクトファイルを生成しますが、リンクは行いません。
- `-std=c99`: C言語の規格としてC99を使用します。
- `-O3`: 最適化レベルを指定します。`O3`は高度な最適化を行います。
- `sosfilt.c`: コンパイルするソースファイル。

**gcc -shared -o sosfilt.so sosfilt.o:**
- `-shared`: 共有オブジェクト（`.so`ファイル）を生成します。
- `-o sosfilt.so`: 出力ファイル名を指定します。
- `sosfilt.o`: 入力となるオブジェクトファイル。
