
<p align="center">
  <img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/Logo%20with%20text%20for%20GitHub%20Top.png" alt="人間のためのPythonGUI ">
  <h2 align="center">人間のためにPythonのGUIです</h2>
</p>

tkinter、Qt、WxPython、およびレミ(ブラウザベースの)GUIフレームワークを、よりシンプルなインタフェースに変換します。 ウィンドウ定義は、初心者が理解する Python コア データ型 (リストと辞書) を使用して簡略化されます。コールバック ベースのモデルからメッセージを渡すモデルにイベント処理を変更することで、さらに単純化が行われます。 

コードは、より多くのユーザーがパッケージを使用できるようにするオブジェクト指向アーキテクチャを持つため、_required_ではありません。アーキテクチャは理解しやすいものですが、必ずしも*単純な問題だけに制限されるわけではありません。

ただし、一部のプログラムはPySimpleGUIには適していません。 定義上、PySimpleGUI は、基盤となる GUI フレームワークの機能のサブセットを実装します。 どのプログラムが PySimpleGUIに適していて、どのプログラムが適していないのかを正確に定義するのは難しいです。 プログラムの詳細によって異なります。エクセル を詳細に複製することは、PySimpleGUI に適していないものの例PySimpleGUIです。

<hr>

# 統計 :chart_with_upwards_trend:

## PyPI インストール

<p align="center">
tkinter <img src="http://pepy.tech/badge/pysimplegui?color=blue&style=for-the-badge" width="100px"  align="center">
tkinter 2.7 <img src="https://pepy.tech/badge/pysimplegui27?color=blue&style=for-the-badge"  align="center"><br>
Qt <img src="https://pepy.tech/badge/pysimpleguiqt?color=blue&style=for-the-badge"  align="center">
WxPython<img src="https://pepy.tech/badge/pysimpleguiwx?color=blue&style=for-the-badge"  align="center">
Web (Remi) <img src="https://pepy.tech/badge/pysimpleguiweb?color=blue&style=for-the-badge"  align="center">
</p>


## GitHub

<p align="center">
<a href=""><img src="https://img.shields.io/github/issues-raw/PySimpleGUI/PySimpleGUI?color=blue&style=for-the-badge" alt="img" width="180px"></a>
<a href=""><img src="https://img.shields.io/github/issues-closed-raw/PySimpleGUI/PySimpleGUI?color=blue&style=for-the-badge" alt="img"  width="200px"></a>
<a href=""><img src="https://img.shields.io/github/commit-activity/m/PySimpleGUI/PySimpleGUI.svg?color=blue&style=for-the-badge" alt="img"  width="260px"></a>
<a href=""><img src="https://img.shields.io/github/last-commit/PySimpleGUI/PySimpleGUI.svg?color=blue&style=for-the-badge" alt="img"width="200px"></a>
<a href=""><img src="http://ForTheBadge.com/images/badges/makes-people-smile.svg" alt="img"width="190px"></a>
<a href=""><img src="https://img.shields.io/github/stars/PySimpleGUI/PySimpleGUI.svg?style=social&label=Star&maxAge=2592000" alt="img"width="140x"></a>
</p>


<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/?username=PySimpleGUI&bg_color=3e7bac&title_color=ffdd55&icon_color=ffdd55&text_color=ffdd55&show_icons=true&count_private=true">
</p>

## 最新の PyPI バージョン


<p align="center">
tkinter
<a href="pypi tkinter"><img src="https://img.shields.io/pypi/v/pysimplegui.svg?style=for-the-badge&color=red" alt="img" align="center" width="150px"></a>
Qt
<a href="https://img.shields.io/pypi/v/pysimpleguiqt.svg?style=for-the-badge"><img src="https://img.shields.io/pypi/v/pysimpleguiqt.svg?style=for-the-badge"  alt="img" align="center" width="150px"></a>
Web
<a href="https://img.shields.io/pypi/v/pysimpleguiweb.svg?style=for-the-badge"><img src="https://img.shields.io/pypi/v/pysimpleguiweb.svg?style=for-the-badge"  alt="img" align="center" width="150px"></a>
WxPython
<a href="https://img.shields.io/pypi/v/pysimpleguiwx.svg?style=for-the-badge"><img src="https://img.shields.io/pypi/v/pysimpleguiwx.svg?style=for-the-badge"  alt="img" align="center" width="150px"></a>
</p>

<hr>

# PySimpleGUIとは何ですか:question:

PySimpleGUIは、すべてのレベルの Python プログラマが GUI を作成できるようにする Python パッケージです。 ウィジェットを含む 「レイアウト」を使用して GUI ウィンドウを指定します (PySimpleGUI では「要素」と呼PySimpleGUIばれます)。 レイアウトを使用して、4 つのサポートされているフレームワークのいずれかを使用してウィンドウを表示し、ウィンドウと対話します。 サポートされるフレームワークには、tkinter、Qt、WxPython、WxPythonまたはレミが含まれます。このようなパッケージには「ラッパー」という用語が使われることがあります。

PySimpleGUI コードは、基本フレームワークを直接使用して記述するよりも簡単で短く、短いコードです。 さらに、インターフェイスは、必要な結果を得るためにできるだけ少ないコードを必要とするように簡略化されます。 使用するプログラムとフレームワークによっては、PySimpleGUI プログラムで、フレームワークの 1 つを直接使用して同じウィンドウを作成するために 1/2 ~ 1/10 分の 10 分の 1 のコードが必要になる場合があります。

目標は、上で実行している GUI フレームワークで使用される特定のオブジェクトとコードをカプセル化/非表示にすることですが、必要に応じて、フレームワークの依存ウィジェットやウィンドウに直接アクセスできます。設定または機能が、まだ公開されていない場合、またはPySimpleGUI API を使用してアクセス可能でない場合、フレームワークから壁に囲まれていません。PySimpleGUI パッケージ自体を直接変更することなく、機能を拡張できますPySimpleGUI。
## 「GUI ギャップ」のブリッジング

Python はプログラミング コミュニティに多くの人々を招いています。プログラムの数とそれが触れる領域の範囲は気が遠くなります。 しかし、多くの場合、これらの技術と技術は、一握りの人々以外の手の届かないところにあります。 Python プログラムの大半は"コマンドライン"ベースです。プログラマタイプでは、テキストインターフェイスを介してコンピュータとやり取りすることに慣れ、この問題はありません。 プログラマはコマンドラインインターフェイスに問題はありませんが、ほとんどの「普通の人」は問題を抱えています。 これにより、デジタル分割、「GUI ギャップ」が生み出されます。
プログラムに GUI を追加すると、そのプログラムが、より多くのユーザーに表示されます。それはより親しみやすくなる。GUI は、コマンド行インターフェースに慣れているプログラムであっても、一部のプログラムとの対話を容易にする場合もあります。 最後に、いくつかの問題はGUIを必要とします。   


<p align="center">
  <img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/GUI%20Gap%202020.png" width="600px">
</p>


<hr>

#私について :wave:
こんにちは！ 私はマイクです。 ここでは、PySimpleGUI  GitHubで、問題を解決し、PySimpleGUIを継続的に前進させますPySimpleGUI。 私はプロジェクトとPySimpleGUIユーザーに私の日、夜、週末を捧げましたPySimpleGUI。 私たちの成功は最終的に共有されます。 あなたが成功したとき、私は成功しています。

Pythonの相対的な新人ですが、私は70年代からソフトウェアを書いています。  私のキャリアの大半は 、シリコンバレーで製品を作成するために費やされました.私は 私 が開発した企業製品にしたのと同じプロフェッショナリズムと献身をPySimpleGUIにもたらします。あなたは今、私の顧客です。


## プロジェクトの目標 :goal_net:

PySimpleGUIプロジェクトの重要な目標の 2 つ:

*楽しみを持っている

*あなたの成功
**Fun**深刻なプロジェクトの目標として奇妙に聞こえるが、それは深刻な目標です。私はこれらのGUIプログラムを書くことはとても楽しいと思います。その理由の 1 つは、完全なソリューションを作成するのにかかる時間が少なさです。私たちがプロセスを楽しんでいない場合、誰かがあきらめるつもりです。
**あなたの成功**は共通の目標です。 PySimpleGUI は開発者向けに構築されました。あなたは私の覗きです。ユーザーと PySimpleGUI の努力を組み合わせた結果を見るのは予想外の報酬でしたPySimpleGUI。アプリケーションの構築に役立つドキュメントや他の資料を使用します。 トラブルに遭遇した場合は、[PySimpleGUI GitHub の問題](http://Issues.PySimpleGUI.org)でヘルプを開いてヘルプを表示できます。 以下のサポートのセクションを見てください。

<hr>

# 教育リソース :books:

www.PySimpleGUI.orgは覚えやすく、ドキュメントが配置されている場所です。複数の異なるドキュメントを表すタブが上部に表示されます。ドキュメントは「ドキュメントを読む」に記載されているため、各ドキュメントの目次があり、検索が簡単です。

100 ページの文書と 100 ページのプログラム例を使用すると、迅速に効果を発揮できます。 単一の GUI パッケージを学習するために数日または数週間の投資を必要とするのではなく、PySimpleGUIを使用する場合、1 つの午後にプロジェクトを完了できる場合があります。


## 例 1 - ワンショットウィンドウ

このタイプのプログラムは、ウィンドウが 1 回表示され、収集された値が閉じられるため、「ワンショット」ウィンドウと呼ばれます。 ワード プロセッサのように長い間開いたままになっていません。
### 単純なPySimpleGUIプログラムの解剖学

PySimpleGUIプログラムには5つのセクションがあります



```python
import PySimpleGUI as sg                                 # パート 1 - インポート

# ウィンドウの内容を定義する
layout = [  [sg.Text("お名前は何ですか？")],     # パート 2 - レイアウト
            [sg.Input()],
            [sg.Button('はい')] ]
# ウィンドウを作成する
window = sg.Window('ウィンドウタイトル', layout)      # パート 3- ウィンドウ定義
                                                
#ウィンドウを表示し、対話
event, values = window.read()                   # パート 4- イベント ループまたは Window.read 呼び出し

#収集された情報で何かをする
print('ハロー ', values[0], "! PySimpleGUIを試してくれてありがとう")

#画面から削除して終了
window.close()                                  #パート 5 - ウィンドウを閉じる
```

コードは、このウィンドウを生成します

<p align="center">
  <img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/WhatsYourNameBlank1.jpg">
</p>


<hr>

## 例 2 - 対話型ウィンドウ

この例では、ユーザーがウィンドウを閉じるか、または [終了] ボタンをクリックするまで、ウィンドウは画面に残ります。 先ほど見たワンショットウィンドウとインタラクティブウィンドウの主な違いは、「イベントループ」の追加です。イベントループは、イベントと入力をウィンドウから読み込みます。 アプリケーションの中心は、イベント ループに入ります。

```python
import PySimpleGUI as sg

# ウィンドウの内容を定義する
layout = [[sg.Text("お名前は何ですか？")],
          [sg.Input(key='-入力-')],
          [sg.Text(size=(55,1), key='-出力-')],
          [sg.Button('はい'), sg.Button('終了')]]

# ウィンドウを作成する
window = sg.Window('ウィンドウタイトル',レイアウト)

#イベントループを使用してウィンドウを表示し、対話
while True:
    event, values = window.read()
#ユーザーが終了したいか、ウィンドウが閉じられたかどうかを確認してください
    if event == sg.WINDOW_CLOSED or event == '終了':
        break

    # Output a message to the window
    window['-出力-'].update('ハロー ' + values['-入力-'] + "! PySimpleGUI をお試しいただきありがとうございます")

#画面から削除して終了
window.close()
```

これは、例 2 が作成するウィンドウです。

<p align="center">
  <img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/WhatsYourNameBlank.jpg">
</p>



入力フィールドに値を入力して [OK] ボタンをクリックした後の表示は次のようになります。

<p align="center">
  <img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/HelloWorld1.jpg">
</p>


この例とワンショット ウィンドウの違いについて簡単に見てみましょう。
まず、レイアウトの違いに気づくでしょう。 特に2つの変更が重要です。 1つは'入力'要素と'テキスト'要素の1つに'キー'パラメータを追加することです。 「キー」は要素の名前のようなものです。 または、Pythonの言葉では、辞書キーのようなものです。 '入力' 要素のキーは、コードの後半で辞書キーとして使用されます。


もう 1 つの違いは、この 'テキスト' 要素の追加です:
```python
          [sg.Text(size=(40,1), key='-OUTPUT-')],
```

すでにカバーしている「キー」という2つのパラメータがあります。 'サイズ' パラメーターは、文字で要素のサイズを定義します。 この場合、この 'テキスト' 要素は、高さ 1 文字で 40文字の幅であることを示しています。 テキスト文字列が指定されていないので、空白になります。 作成されたウィンドウにこの空白行が簡単に表示されます。

また 、ボタンを追加しました, "終了".

イベントループには、おなじみのwindow.read()'呼び出しがあります。

次の read は、次の if ステートメントです。
```python
    if event == sg.WINDOW_CLOSED or event == '終了':
        break
```

このコードは、ユーザーが "X" をクリックしてウィンドウを閉じたか、または [終了] ボタンをクリックしたかどうかを確認します。 これらのいずれかが発生した場合、コードはイベント ループから抜け出します。

ウィンドウが閉じられず、[終了] ボタンがクリックされていない場合は、実行が続行されます。 起こりうる唯一の事は、ユーザーが「OK」ボタンをクリックしたことです。 イベントループの最後のステートメントは次のとおりです。




```python
    window['-OUTPUT-'].update('ハロー  ' + values['-INPUT-'] + "! PySimpleGUI をお試しいただきありがとうございます")
```

この文は、キー '-OUTPUT-' を持つ 'Text' 要素を文字列で更新します。 ''-OUTPUT-'''''''は キー'-OUTPUT-'を持つ要素を見つけます。 そのキーは、空白の 'Text' 要素に属します。 その要素が検索から返されると、その 'update' メソッドが呼び出されます。 ほとんどすべての要素は'update'メソッドを持っています。 このメソッドは、要素の値を変更したり、要素の構成を変更したりするために使用します。

テキストを黄色にしたい場合は、'text_color'パラメータを'update' メソッドに追加して、次のようにして処理します。
```python
    window['-出力-'].update('ハロー ' + values['-入力-'] + "! PySimpleGUI をお試しいただきありがとうございます", text_color='yellow')
```

'text_color' パラメータを追加すると、新しい結果ウィンドウになります:

<p align="center">
  <img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/HelloWorldYellow.jpg">
</p>


各要素で使用できるパラメータは、docstrings と同様に[呼び出しリファレンスドキュメント](http://calls.PySimpleGUI.org)に記載されています。  PySimpleGUIには、利用可能なすべてのオプションを理解するのに役立つ広範なドキュメントall ofが用意されています。 調べる'Text' 要素の 'update' メソッドを検索すると、呼び出しの定義が見つかります:

<p align="center">
  <img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/TextUpdate.jpg">
</p>


ご覧のように、いくつかのものは、'Text'要素に変更することができます。 呼び出しリファレンス ドキュメントは、PySimpleGUIでのプログラミングを簡単にする貴重なリソースです。

<hr>

##レイアウトは面白いです笑! :laughing:

ウィンドウのレイアウトは「リストのリスト」(LOL)です。 ウィンドウは"行"に分割されます。 ウィンドウの各行は、レイアウトのリストになります。 すべての リストを連結すると、レイアウトがあります。リストのリスト。

行の定義方法を簡単に確認できるように、各行に追加の 'Text' 要素を追加したレイアウトは、以前と同じです:

```python
layout = [  [sg.Text('ライン 1'), sg.Text("お名前は何ですか")],
            [sg.Text('ライン 2'), sg.Input()],
            [sg.Text('ライン 3'), sg.Button('はい')] ]
```

このレイアウトの各行は、ウィンドウのその行に表示される要素のリストです。


<p align="center">
  <img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/rows.jpg">
</p>



リストを使用して GUI を定義する場合、他のフレームワークを使用して GUI プログラミングを行う方法に対して大きな利点があります。 たとえば、Python のリストの理解を利用して、1 行のコードでボタンのグリッドを作成できます。

次の 3 行のコード:

```python
import PySimpleGUI as sg

layout = [[sg.Button(f'{row}, {col}') for col in range(4)] for row in range(4)]

event, values = sg.Window('List Comprehensions', layout).read(close=True)
```

ボタンの4 x 4グリッドを持つこのウィンドウを生成します:

<p align="center">
  <img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/4x4grid.jpg">
</p>

「楽しい」がプロジェクトの目標の1つであることを思い出してください。 Python の強力な基本機能を GUI の問題に直接適用するのは楽しいです。GUI を作成するコードのページの代わりに、数行 (または多くの場合 1 行) のコードです。

## コードの折りたたみ

ウィンドウのコードを 1 行のコードに縮小することができます。 レイアウト定義、ウィンドウ作成、表示、およびデータ収集はすべて、次のコード行に記述できます:
```python
event, values = sg.Window('Window Title', [[sg.Text("お名前は何ですか？")],[sg.Input()],[sg.Button('はい')]]).read(close=True)
```

<p align="center">
  <img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/WhatsYourName.jpg">
</p>


同じウィンドウが表示され、PySimpleGUIプログラムのセクションを示す例と同じ値が返されます。 非常に少ない量で多くのことを行うことができるため、Python コードに GUI をすばやく簡単に追加できます。 データを表示してユーザーから選択を得たい場合は、コードのページではなくコード行で行うことができます。

短い手のエイリアスを使用すると、使用する文字を減らすことでコードの領域を節約できます。  すべての 要素には、使用できる短い名前が 1 つ以上含まれています。 たとえば、'Text' 要素は単に 'T' として記述できます。'Input' 要素は 'I' と 'ボタン' として書き込むことができます。 したがって、単一行のウィンドウ コードは次のようになります:

```python
event, values = sg.Window('Window Title', [[sg.T("あなたの名前は何ですか?")],[sg.I()],[sg.B('はい')]]).read(close=True)
```


### コードの移植性

PySimpleGUIは現在、4 つの Python の GUI フレームワークで実行できます。 使用するフレームワークは、import ステートメントを使用して指定します。 インポートを変更すると、基になる GUI フレームワークが変更されます。 プログラムによっては、別の GUI フレームワークで実行するために import ステートメント以外の変更は必要ありません。 上記の例では、インポートを'PySimpleGUI'から 'PySimpleGUIQt''PySimpleGUIWx'、'PySimpleGUIWeb'PySimpleGUIWebに`, `変更すると、フレームワークが変更されます。

| ステートメントをインポート | 結果ウィンドウ |
|--|--|
| PySimpleGUI |  ![](https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/ex1-tkinter.jpg) |
| PySimpleGUIQt |  ![](https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/ex1-Qt.jpg) |
| PySimpleGUIWx |  ![](https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/ex1-WxPython.jpg) |
| PySimpleGUIWeb |  ![](https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/ex1-Remi.jpg) |



GUI コードをあるフレームワークから別のフレームワークに移植する (例えば、コードをtkinterからQt に移動する) には、通常、コードの書き換えが必要です。  PySimpleGUI は、フレームワーク間の簡単な移動を可能にするように設計されています。 場合によっては、いくつかの変更が必要ですが、目的は最小限の変更で非常に移植性の高いコードを持つ必要があります。 

システム トレイ アイコンなどの一部の機能は、すべてのポートで使用できない場合があります。 システムトレイアイコン機能は、QtおよびWxPythonポートで使用できます。 シミュレートされたバージョンは tkinter で使用できますtkinter。 システム トレイ アイコンは、PySimpleGUIWebポートではサポートされません。
##  ランタイム環境

|環境 |サポートされる |
|--|--|
|パイソン| Python  3.4+ |
|オペレーティング システム |ウィンドウズ, Linux, マック |
|ハードウェア |デスクトップ PC, ノートパソコン, ラズベリーパイ, PyDroid3 を実行しているアンドロイドデバイス |
|オンライン |repli.it、Trinket.com (どちらもブラウザで tkinterを実行) |
|GUI フレームワーク |tkinter, パイサイド2,  WxPython, レミ |


## 統合
200 以上の「デモ プログラム」の中には、多くの人気 Python パッケージを GUI に統合する方法の例が見つかります。

あなたのウィンドウにMatplotlib図面を埋め込みたいですか?  問題ありません、 デモコードをコピーし、即座にあなたの夢のMatplotlib図面をあなたのGUIに持っています。  

デモプログラムやデモレポが用意されている場合、これらのパッケージなどはGUIに入れる準備ができています:

パッケージ |説明 |
|--|--|
 マトプロプリブ |グラフやプロットの多くの種類 |
 オープンCV |コンピュータビジョン (AI でよく使用) |
 VLC |ビデオ再生 |
 ピムンク |物理エンジン|
 サイプチ |システム環境の統計 |
 エビ |レディット API |
json |PySimpleGUI は、「ユーザー設定」を格納する特別な API をラップします。 |
 天気 |天気アプリを作るためにいくつかの天気APIと統合 |
 ミド |MIDI 再生 |
 美しいスープ |ウェブスクレイピング (GitHub 問題ウォッチャーの例) |

<hr>

# インストール :floppy_disk:


PySimpleGUIをインストールする 2 つの一般的な方法:

1.PyPIからインストールする1ピップ
2. ファイルをダウンロードPySimpleGUI.py、アプリケーションのフォルダに配置します

### Pip インストールとアップグレード

'pip' コマンドを呼び出す現在提案されている方法は、Python を使ってモジュールとして実行することです。 以前は、コマンド 'pip' または 'pip3' はコマンドライン/シェルに直接ありました。 提案された方法

Windows の初期インストール:

' Python -m ピップインストール ピシンプルGUI'

Linux および MacOS の初期インストール:

`python3 -m pip install PySimpleGUI`

To upgrade using `pip` you simply 2 parameters to the line `--upgrade --no-cache-dir`.  

Windows のインストールをアップグレードします:

`python -m pip install --upgrade --no-cache-dir PySimpleGUI`

Linux および MacOS のアップグレード:

`python3 -m pip install --upgrade --no-cache-dir PySimpleGUI`


### 単一ファイルのインストール

PySimpleGUIは単一の .pyそれは、ラズベリーパイのようなインターネットに接続されていないシステムでも、それをインストールすることは非常に簡単であろうように、pyファイル。 これは、PySimpleGUI.pyファイルをインポートするアプリケーションと同じフォルダに配置するのと同じくらい簡単です。Python はインポートの実行時にローカル コピーを使用します。

を使用してインストールする場合は、 .pyファイルは、PyPIから入手するかPyPI、最新の未リリースバージョンを実行したい場合は、GitHubからダウンロードします。

PyPIからインストールするには、ホイールまたは .gz ファイルを解凍し、ファイルを解凍します。 名前を変更する場合は、 .whlファイルを.zipにすれば、通常のzipファイルと同じように開くことができます。 PySimpleGUI.pyファイルは、いずれかのフォルダに表示されます。 このファイルをアプリケーションのフォルダーにコピーすると、完了です。

TPySimpleGUIのtkinterバージョンの PyPI リンクは次のとおりです:
https://pypi.org/project/PySimpleGUI/#files

GitHub リポジトリの最新バージョンは、こちらで確認できます:
https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/PySimpleGUI.py


今、あなたの中には、「はい、しかし、待って、単一の巨大なソースファイルを持つことはひどい考えです」と考えている人もいます。 そして、はい、*時には*それはひどい考えかもしれません。 この場合、利点はマイナス面を大幅に上回りました。 コンピュータサイエンスの概念の多くは、トレードオフまたは主観的です。 一部の人が望むのと同じくらい、すべてが白黒ではありません。 質問に対する答えは「依存する」というものが多い。



## ギャラリー :art:

ユーザーが提出したGUIのより正式なギャラリーとGitHubで見つかったものの作業は進行中ですが、この執筆時点では完了していません。 現在、一元的な方法でいくつかのスクリーンショットを見るために行くことができる2つの場所があります。 うまくいけば、Wikiやその他のメカニズムがすぐにリリースされ、人々が作っている素晴らしい作品に正義を与えることができます。

### ユーザーが提出したギャラリー

1つ目は、GitHub にある[ユーザーがスクリーンショットを提出した 問題](https://github.com/PySimpleGUI/PySimpleGUI/issues/10)です。 これは、人々が彼らが作ったものを披露するための非公式な方法です。 それは理想的ではありませんが、それは始まりでした。

### 大規模な削り取られたGitHub画像

2つ目は、PySimpleGUIを使用していると伝えられているGitHubの1,000のプロジェクトから削られた[3,000以上の画像の大規模なギャラリー ](https://www.dropbox.com/sh/g67ms0darox0i2p/AAAMrkIM6C64nwHLDkboCWnaa?dl=0)です。 手でフィルタリングされておらず、初期のドキュメントで使用されていた古いスクリーンショットがたくさんあります。 しかし、あなたはそこにあなたの想像力を引き起こす何かを見つけるかもしれません。
<hr>

# PySimpleGUI の用途です :hammer:

次のセクションでは、PySimpleGUIの用途の一部を紹介します。 PySimpleGUI を使用する GitHub だけでも 1,000 以上のプロジェクトがありますPySimpleGUI。 それは本当に多くの人々のために開かれた可能性は本当に驚くべきことです。 多くのユーザーは、以前にPythonでGUIを作成しようとして失敗したが、彼らがPySimpleGUIを試してみたときに最終的に自分の夢を達成することについて話PySimpleGUIしました。

## あなたの最初のGUI

もちろん、PySimpleGUIの最も優れた用途の1つは、Pythonプロジェクト用のGUIを作ることです。 ファイル名を要求するサイズと同じくらい小さく開始できます。 このためには、「ポップアップ」と呼ばれる「ハイレベル関数」の1つを1回呼び出すだけで済みます。 ポップアップのすべての種類があり、一部は情報を収集します

' popup ' が、それ自体が情報を表示するウィンドウを作成します。 複数のパラメータを印刷と同様に渡すことができます。 情報を取得する場合は、'popup_get_'で始まる関数popup_get_filename呼び出します。
コマンドラインでファイル名を指定する代わりに、ファイル名を取得するために1行を追加すると、プログラムを「普通の人」が使い心地よく感じるものに変換できます。



```python
import PySimpleGUI as sg

filename = sg.popup_get_file('処理したいファイルを入力してください')
sg.popup('入力した', filename)
```


このコードは、2 つのポップアップ ウィンドウを表示します。 入力ボックスに参照したり貼り付けたりできるファイル名を取得するファイル名。  

<p align="center">
<a href="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/popupgetfilename.jpg"><img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/popupgetfilename.jpg"  alt="img" width="400px"></a>
</p>

もう一方のウィンドウは収集された内容を出力します。

<p align="center">
<a href="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/popupyouentered.jpg"><img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/popupyouentered.jpg"  alt="img" width="175px"></a>

</p>


<br>

## Rainmeter風スタイルウィンドウ

<a href="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/RainmeterStyleWidgets.jpg"><img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/RainmeterStyleWidgets.jpg"  alt="img" align="right" width="500px"></a>
GUIフレームワークのデフォルト設定では見栄えの良いウィンドウは作成できません。しかし細部に注意することでウィンドウを魅力的に見せるためにいくつかのことをおこなえます。 PySimpleGUIは、色やタイトルバーの削除などの機能をより簡単に操作できます。 その結果、典型的なtkinterのようには見えないウィンドウができます。

ここでは、典型的なtkinterのように見えないウィンドウをWindowsで作成する方法の例を紹介します。 この例ではウィンドウのタイトル バーが削除されています。その結果としてデスクトップウィジェットプログラムのRainmeterように見えるウィンドウができあがります。

<br><br>
ウィンドウの透明度も簡単に設定できます。 同じRainmeterスタイルのデスクトップウィジェットの他の例を紹介します。 半透明なので、薄暗く表示される場合もあります。
<a href="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/semi-transparent.jpg"><img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/semi-transparent.jpg"  alt="img" align="right" width="500px"></a>



タイトルバーの削除とウィンドウの半透明化の両方の効果はウィンドウを作成する際に2つのパラメータを設定することで実現しています。 これはPySimpleGUIがいかに機能に簡単にアクセスできるかを示す例です。 また、PySimpleGUI のコードはGUIフレームワーク間で移植可能なので、Qtのような他のポートでも同じパラメータで動作します。


例１のウィンドウ作成の呼び出しを以下のコードに変更すると同様の半透明のウィンドウが作成されます。
```python
window = sg.Window('My window', layout, no_titlebar=True, alpha_channel=0.5)
```

## ゲーム

ゲーム開発用の SDK としては特に記述されていませんが、PySimpleGUIはゲームの開発を非常に簡単にします。

<a href="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/Chess.png"><img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/Chess.png"  alt="img" align="right" width="500px"></a>
このチェスプログラムはチェスをするだけでなく、チェスAI「Stockfish」を統合します。
<br><br><br><br><br><br><br><br><br>
<a href="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/Minesweeper.gif"><img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/Minesweeper.gif"  alt="img" align="right" width="500px"></a>
マインスイーパのいくつかのバリエーションがユーザーによってリリースされました。

<br><br><br><br>
<br><br><br><br><br>

<a href="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/minesweeper_israel_dryer.png"><img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/minesweeper_israel_dryer.png"  alt="img" align="right" width="500px"></a>
<br><br><br><br><br><br><br><br><br><br>


<a href="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/Solitaire.gif"><img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/Solitaire.gif"  alt="img" align="right" width="500px"></a>
<br><br>

PySimpleGUIの`Graph`エレメントを使用すると画像の操作が簡単なので、カードゲームはPySimpleGUIを使用すると簡単です。

ゲーム開発用のSDKとして書かれたわけではありませんが、PySimpleGUIはゲームの開発を非常に簡単にします。<br><br>
<br><br>
<br><br><br>


## メディアのキャプチャと再生

<a href="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/OpenCV.jpg"><img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/OpenCV.jpg"  alt="img" align="right" width="400px"></a>


WEBカメラからビデオをキャプチャしてGUIで表示するのには、PySimpleGUIのコードでは4行でできます。 さらに印象的なのはこらの4行のコードが tkinter、Qt、および Web ポートで動作します。  tkinterを使用して画像を表示するのと同じコードを使用して、ブラウザでWebカメラをリアルタイムが表示できます。

また、VLCプレーヤーを使って、オーディオやビデオなどのメディア再生も可能です。デモアプリケーションが提供されているので実際の作業例が用意されています。このreadmeに記載されている内容は全て、あなた自身の創作の出発点として利用できます。
<br><br><br><br><br>
<br><br><br><br><br>
<br><br>
## 人工知能

<a href="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/YOLO_GIF.gif"><img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/YOLO_GIF.gif"  alt="img" align="right" width="500px"></a>



AIとPythonは長い間、この2つが組み合わされたときのスーパーパワーとして認識されてきました。しかし、多くの場合、ユーザーがGUIを使用してこれらのAIアルゴリズムを身近に操作する方法が欠けています。

これらのYOLOのデモは、GUIがAIアルゴリズムとの対話においていかに大きな違いをもたらすかの素晴らしい例です。 これらのウィンドウの下部にある2つのスライダーに注目してください。 この2つのスライダーは、YOLOアルゴリズムが使用するパラメータを変更します。 

コマンドラインのみを使用してYOLOデモをチューニングする場合は、アプリケーションを起動するときに、パラメーターを設定し、その実行方法を確認し、アプリケーションを停止し、パラメーターを変更し、最後に新しいパラメーターでアプリケーションを再起動する必要があります。
<br><br><br><br>

<a href="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/YOLO%20Object%20Detection.jpg"><img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/YOLO%20Object%20Detection.jpg"  alt="img" align="right" width="500px"></a>

これらのステップと、GUIを使用して実行できる操作と比較してみます。 GUIを使用すると、これらのパラメータをリアルタイムで変更できます。 アルゴリズムにどのような影響を与えているかについて、すぐにフィードバックを得られます。



<br><br><br><br><br>
<br><br>
<a href="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/Colorizer.jpg"><img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/Colorizer.jpg"  alt="img" align="right" width="500px"></a>


公開されているAIプログラムには、コマンドラインで動かすプログラムが非常に多く存在します。 これ自体は大きなハードルではありませんが、コマンドラインでカラーリングしたいファイル名を入力/貼り付け、プログラムを実行して、出力ファイルの結果をファイルビューアで開くには十分「面倒くさい」です。


GUI には、**ユーザーエクスペリエンスを変更する**を「GUIギャップ」に変化させる力があります。 このカラーライズの例では、ユーザーは画像が格納されてたフォルダを指定して、画像をクリックするだけでカラーリングと結果表示の両方を行えます。  
カラーライズを行うプログラム/アルゴリズムは自由に利用可能で、使用可能でした。 不足していたのはGUIがもたらす使いやすさです。


<hr>

## グラフ化

<a href="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/CPU%20Cores%20Dashboard%202.gif"><img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/CPU%20Cores%20Dashboard%202.gif"  alt="img" align="right" width="500px"></a>

Gui でデータを表示し、操作するのは、PySimpleGUIを使用して簡単です。 いくつかのオプションがあります。
組み込みの描画/グラフ作成機能を使用して、カスタムグラフを作成できます。 この CPU 使用率モニタは'グラフ' 要素を使用します
<br><br>
<br><br>
<br><br>

<a href="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/Matplotlib.jpg"><img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/Matplotlib.jpg"  alt="img" align="right" width="500px"></a>


Matplotlib は Python ユーザーに人気のある選択肢です。 PySimpleGUI を使用すると、MATPLOTLIB グラフを GUI ウィンドウに直接埋め込むことができます。 Matplotlib インタラクティブ機能を保持したい場合は、インタラクティブコントロールをウィンドウに埋め込むこともできます。

<br><br>
<br><br>
<br><br>
<br><br>

<a href="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/Matplotlib2.jpg"><img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/Matplotlib2.jpg"  alt="img" align="right" width="500px"></a>
PySimpleGUI のカラーテーマを使用すると、ほとんどの人が Matplotlib で作成するデフォルトのグラフの上にノッチを付けたグラフを作成できます。

<br><br>
<br><br>
<br><br>
<br><br>
<br><br>
<br><br>
<br><br>

<hr>

## フロントエンド


<a href="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/JumpCutter.png"><img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/JumpCutter.png"  alt="img" align="right" width="500px"></a>

前述の「GUI ギャップ」は、PySimpleGUIを使用して簡単に解決できます。 GUI を追加するプログラムにソースコードを用意する必要もありません。 "フロントエンド" GUI は、コマンド 行アプリケーションに渡される情報を収集する GUI です。
フロントエンド GUI は、プログラマが、コマンドライン インターフェイスを使用する場合に、ユーザーが以前使用することに消極的だったアプリケーションを配布する優れた方法です。 これらの GUI は、ソースコードにアクセスできないコマンドラインプログラムに対する唯一の選択肢です。
この例は、"ジャンプ カッター" というプログラムのフロントエンドです。 パラメーターは GUI を介して収集され、コマンド行はそれらのパラメーターを使用して構成され、コマンドは GUI インターフェースにルーティングされるコマンド行プログラムからの出力で実行されます。 この例では、実行されたコマンドを黄色で確認できます。
<br><br>
<hr>

## ラズベリーパイ

<a href="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/Raspberry%20Pi.jpg"><img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/Raspberry%20Pi.jpg"  alt="img" align="right" width="500px"></a>


PySimpleGUIはPython 3.4に対応しているため、ラズベリーパイプロジェクト用のGUIを作成することができます。 タッチスクリーンと組み合わせると特にうまく機能します。 モニターが接続されていない場合は、PySimpleGUIWeb を使用して Pi を制御することもできます。

<br><br>
<br><br>
<br><br>
<br><br><br>
<hr>


## 高度な機能への簡単なアクセス
<a href="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/Customized%20Titlebar.gif"><img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/Customized%20Titlebar.gif"  alt="img" align="right" width="500px"></a>


基礎となる GUI フレームワークの機能の多くは非常に簡単にアクセスできるため、GUI フレームワークを使用して直接作成されたものとまったく似たようなアプリケーションを作成する機能を組み合わせて作成できます。

たとえば、tkinterやその他の GUI パッケージを使用してタイトルバーの色/外観を変更することはできませんが、PySimpleGUI を使用すると、カスタムタイトルバーを持っているかのように表示されるウィンドウを簡単に作成できます。
<br><br><br>

<a href="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/Desktop%20Bouncing%20Balls.gif"><img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/Desktop%20Bouncing%20Balls.gif"  alt="img" align="right" width="500px"></a>

信じられないことに、このウィンドウは、スクリーンセーバーのようなものと思われるものを達成するためにtkinterを使用しています。

ウィンドウでは、tkinter はアプリケーションから背景を完全に削除できます。 繰り返しますが、PySimpleGUIはこれらの機能へのアクセスを簡単にします。 透明なウィンドウを作成するには、'Window' を作成する呼び出しに 1 つのパラメーターを追加する必要があります。 1 つのパラメータ変更により、次の効果を持つ単純なアプリケーションが発生する可能性があります:

デスクトップ上のすべてのものを操作し、フルスクリーンウィンドウをクリックすることができます。
<hr>

#テーマ

デフォルトのグレー GUI にうんざり?  PySimpleGUI は'テーマ'関数への単一の呼び出しを行うことによって、あなたのウィンドウが素敵に見えることを簡単にします。 150種類以上のカラーテーマを選択できます:
<p align="center">
<a href=""><img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/ThemePreview.jpg"  alt="img" width="900px"></a>
</p>


ほとんどの GUI フレームワークでは、作成するすべてのウィジェットの色を指定する必要があります。  PySimpleGUI は、あなたからこの雑用を取り、自動的に選択したテーマに合わせて要素を着色します。

テーマを使用するには、ウィンドウを作成する前にテーマ名を指定して 'テーマ' 関数を呼び出します。読みやすくするためにスペースを追加できます。 テーマを「ダークグレー9」に設定するには:
```python
import PySimpleGUI as sg

sg.theme('dark grey 9')
```

この 1 行のコードは、ウィンドウの外観を完全に変更します:
<p align="center">
<a href=""><img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/DarkGreyJapanese.jpg"  alt="img" width="400px"></a>
</p>


テーマは、背景、テキスト、入力背景、入力テキスト、およびボタンの色を変更しました。 このような配色を変更する他の GUI パッケージでは、各ウィジェットの色を個別に指定する必要があり、コードに多数の変更が必要になります。

<hr>

# サポート:muscle:

最初のストップは[ドキュメンテーション](http://www.PySimpleGUI.org)と[デモプログラム](http://Demos.PySimpleGUI.org)でなければなりません。 あなたはまだ質問があるか、助けが必要な場合. 大丈夫。。。ヘルプは無償で、あなたに利用可能です。PySimpleGUI GitHubリポジトリで[問題を提出PySimpleGUI](http://Issues.PySimpleGUI.org)するだけで、ヘルプが表示されます。

ほぼすべてのソフトウェア会社は、バグレポートに付随するフォームを持っています。 それは悪い貿易ではありません.フォームに記入し、フリーソフトウェアのサポートを受ける。 この情報は、効率的に回答を得るのに役立ちます。

PySimpleGUIのバージョン番号や基になる GUI フレームワークなどの情報を要求するだけでなく、問題の解決に役立つ項目のチェックリストも提供されます。

***フォームに記入してください 。*** それはあなたに無意味に感じるかもしれません。 ほんの少し時間が取っているにもかかわらず、それは痛みを感じるかもしれません。 ソリューションを迅速に入手できます。 迅速な返信と修正を得るのに役立つ情報が役に立たない場合は、入力を求められません。 「私があなたを助ける」。


# サポート	<a href="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/PSGSuperHero.png"><img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/PSGSuperHero.png"  alt="img"  width="90px"></a>

プロジェクトの財政的支援は非常に高く評価されています。 正直に言うと、経済的な援助が必要です。 ライトをつけ続けるだけで高価です。 ドメイン名登録、トリンケット、コンサルティングヘルプなどのサブスクリプションの長いリストは、すぐにかなりの繰り返しコストに加算されます。

PySimpleGUI は作成するのに安価ではありませんでした。愛の労働は、非常に面倒でした。ソフトウェアとドキュメントを現在のレベルに到達するには、週7日の作業に2年以上必要です。

PySimpleGUIにはオープンソースライセンスがあり、そのまま残ることができれば素晴らしいことです。 お客様またはお客様の会社 (特に企業でPySimpleGUIを使用している場合) が、PySimpleGUIを使用して経済的に利益を得ている場合は、プロジェクトの寿命を延長する機能を持ちます。

###コーヒーを買って

私にコーヒーを買うことは、開発者を公的にサポートするための素晴らしい方法です。 それは迅速で簡単で、あなたの貢献は、あなたがPySimpleGUIの支持者であることを他の人が見ることができるように記録されます。 寄付を非公開にすることもできます。

<a href="https://www.buymeacoffee.com/PySimpleGUI" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/arial-yellow.png" alt="Buy Me A Coffee" width="217px" ></a>



###GitHubスポンサー

<a href="https://github.com/sponsors/PySimpleGUI" target="_blank"><img src="https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&link=%3Curl%3E&color=f88379"></a>

[GitHub定期的なスポンサーシップ](https://github.com/sponsorsー/PySimpleGUI)は、継続的にさまざまなレベルのサポートでプロジェクトをスポンサーする方法です。これは、企業レベルのスポンサーシップを受けることができるオープンソースの開発者の数です。
プロジェクトに財政的に貢献するあなたの助けは非常に高く評価されます。オープンソース開発者であることは、財政的に困難です。YouTube 動画クリエイターは、動画を作成して生計を立てることができます。オープンソース開発者にとってはまだ簡単ではありません。
#貢献:construction_worker:

PySimpleGUI は現在、オープンソースライセンスでライセンスされていますが、プロジェクト自体は独自の製品のように構成されています。 プル要求は受け付けられません。

貢献する最も良い方法の 1 つは、アプリケーションの作成と公開です。 ユーザーは、他のユーザーが構築するものを見てインスピレーションを得ています。 GitHub リポジトリを作成し、コードを投稿し、リポジトリの Readme ファイルにスクリーンショットを含めます。  

必要な機能が不足している場合、または提案する機能が強化されている場合は、[問題を開く](https://github.com/PySimpleGUI/PySimpleGUI/issues/new?assignees=&labels=&template=issue-form---must-fill-in-this-form-with-every-new-issue-submitted.md&title=%5B+Enhancement%2FBug%2FQuestion%5D+My+problem+is.)) 


# 特別な感謝 :pray:


PySimpleGUIのreadmeのこのバージョンは、[@M4cs](https://github.com/M4cs)の助けを借りずに一緒に来なかったでしょう。彼は素晴らしい開発者であり、プロジェクトの立ち上げ以来PySimpleGUIサポーターです。  [@イスラエル-ドライヤー](https://github.com/israel-dryer)は、別の長期的なサポーターであり、パッケージの機能の封筒を押したいくつかのPySimpleGUIプログラムを書いています。 ボードの画像を使用するユニークな掃海艇は、イスラエルによって作成されました。 [@jason990420](https://github.com/jason990420)は、彼はあなたが上の写真だけでなく、PySimpleGUIで作られた最初の掃海ゲームを見てPySimpleGUI、PySimpleGUIを使用して最初のカードゲームを公開したときに多くの驚きました。

PySimpleGUIを使用する1,100以上のGitHubリポジトリは、このプロジェクトのエンジンを刺激するインスピレーションとなっているのはあなたのために、「ありがとう」を負っています。 一晩Twitterに投稿する海外ユーザーは、PySimpleGUIで一日の仕事を始める火花ですPySimpleGUI.開発エンジンを開始し、毎日実行する準備ができているポジティブなエネルギーの源となっています。 あなたは、オープンソース開発者が望むことができる最高のユーザーコミュニティでした。

&copy; Copyright 2020 PySimpleGUI.org 
