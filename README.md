### 実装したコード集

ご覧いただきありがとうございます。
下記はPublic repositoryです。
PyTorchによるニューラルネットワーク構築から、画像認識/自然言語処理の実装まで経験しております。

### 【画像認識】
#### 1. YOLOv7とWEBカメラを使用した物体検知アプリ
今年リリースされたYOLOv7を使用して、object detectionを実装。
WEBカメラを通じて人を検知し、特定の領域内に人が入ったときに枠線の色が変わる簡単なアプリを作成しました。

#### 2. Semantic Segmentationを行うためのU-Net実装
自己研鑽を目的として、U-Netを実装しました。

### 【決定木による分類】
#### 2. アヤメの花弁の長さから、種を推定するアプリ
言わずと知れたアヤメの花の分類です。
花弁の長さをスライダーで指定することで、種の分類結果を返してくれます。
streamlitの練習も兼ねています。

### 【探索的データ分析の効率化 (アプリ化)】
#### 3. csv可視化アプリ (streamlit)
KaggleやSIGNATE等では、まずは`df.info()`や`df.describe()`等でデータの全体像を把握するかと思います。
ただ、毎度やる操作で、もう少し効率化したいものです。
そこで、csvをアップロードして、そのcsvデータを自動的にヒストグラムで表示 + 相関係数分析 + 重回帰分析まで実施してくれる
アプリをstreamlitで簡単に作成しました。

詳しい解説は[こちら](https://qiita.com/wgsbt4859/items/071de4b8cb4306c8ceec)に掲載しています。



<!--
**wgsbt4859/wgsbt4859** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
