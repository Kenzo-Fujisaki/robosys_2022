# robosys_2022
ロボットシステム学の練習リポジトリ

  * このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
  * このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです．
      * [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)
  * © 2022 Kenzo Fujisaki

# plusコマンド
![test](https://github.com/Kenzo-Fujisaki/robosys_2022/actions/workflows/test.yml/badge.svg)

標準入力から読み込んだ数字を足す。
例
```
seq 5 | ./plus
```

実行結果
```
15
```

## 必要なソフトウェア
* Python
  * テスト済み: 3.7~3.10

## テスト環境
* Ubuntu 20.04

# calcコマンド
![test](https://github.com/Kenzo-Fujisaki/robosys_2022/actions/workflows/test_calc.yml/badge.svg)


標準入力で読み込んだ数を四則演算していくプログラム
例
```
echo -e '1\n+\n3\n=' | ./calc
```
実行結果
```
4.0
```

## 必要なソフトウェア
* Python
  * テスト済み: 3.7~3.10

## テスト環境
* Ubuntu 20.04
