# 数当てゲーム(kazuate-game)  
数当てゲームは、ユーザーがランダムに生成された数字を当てるシンプルなPythonゲームです。      
`kazuate_gui.py`は、Tkinterを使ったGUIバージョンの数当てゲームです。  

## 概要  
- **ジャンル** :コマンドラインゲーム  
- **目的** :数字を予測して正解するまで何回でも挑戦できる！
- **機能** :
    1. ランダムな数を生成する  
    2. ユーザーの入力に応じてヒントを提供する
    3. 正解が出るとゲームが終了する

## 使用技術  
- **プログラミング言語**:Python
- **GUIライブラリ**:Tkinter
- ランダムな数字の生成:`random`モジュール

## 使い方  

### CLI版(kazuate_game.py)  
- コマンドラインでシンプルに遊べる。

### GUI版(kazuate_gui.py)  
1. **Pythonをインストール**
   [公式サイト](https://www.python.org/)からインストールしてください。
  
2. **クローンorダウンロード**
```
git clone https://github.com/cinamocha/kazuate-game
cd kazuate-game  
```
   
3. **実行**
```
Python kazuate_gui.py
```
  
GUI版では、ボタンをクリックして数字を予測する形式になっており、視覚的に楽しめます。  
