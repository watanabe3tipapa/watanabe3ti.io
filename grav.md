---
description: Grav-markdown-syntax
---

# 🔍 Grav



## Grav-マークダウン構文

Markdown構文は、読みやすく、書きやすい形式でプレーンテキストを記述することとして定義され、後でHTMLコードに変換されます。 （\*）や（ \`）などの記号は、マークダウン構文で使用されます。 これらのシンボルは、ヘッダーを作成して太字にし、コンテンツを整理するために使用されます。

Markdown構文を使用するには、 **user/pages/02.mypage** フォルダーに.mdファイルを作成する必要があります。 **\ user \ config \ system.yaml** 構成ファイルでマークダウン構文を有効にします。

[Grav Markdown構文](https://www.finddevguides.com/index.php?title=%E7%89%B9%E5%88%A5:%E3%82%A2%E3%83%83%E3%83%97%E3%83%AD%E3%83%BC%E3%83%89\&wpDestFile=/grav/grav-markdown-syntax/grav-markdown-syntax-image1%EF%BC%88a%EF%BC%89.jpg)

Markdown構文を使用することには多くの利点がありますが、その一部は次のとおりです。

* 簡単に習得でき、最小限のキャラクターしかありません。
* マークダウンを使用すると、エラーが発生する可能性はほとんどありません。
* 有効なXHTML出力。
* コンテンツと視覚表示は別々に保持されるため、Webサイトの外観に影響を与えません。
* 任意のテキストエディターまたはマークダウンアプリケーションを使用できます。

次のセクションでは、マークダウンで使用されるHTMLの主要な要素について説明します。

### 見出し

各見出しタグは、見出しごとに＃で作成されます。つまり、h1からh6まで、＃の数は図のように増加します。

```
    #my new Heading
    ##my new Heading
    ###my new Heading
    ####my new Heading
    #####my new Heading
    ######my new Heading
```

Copy

ブラウザで\_.md\_ファイルを **localhost/Grav/mypage;** として開きます。次の結果が表示されます-

[Grav Markdown構文](https://www.finddevguides.com/index.php?title=%E7%89%B9%E5%88%A5:%E3%82%A2%E3%83%83%E3%83%97%E3%83%AD%E3%83%BC%E3%83%89\&wpDestFile=/grav/grav-markdown-syntax/grav-markdown-syntax-image1.jpg)

### コメント

次の形式でコメントを書くことができます。

```
<!—
   This is my new comment
-->
```

Copy

ブラウザで\_.md\_ファイルを **localhost/Grav/mypage;** として開きます。次の結果が表示されます-

[Grav Markdown構文](https://www.finddevguides.com/index.php?title=%E7%89%B9%E5%88%A5:%E3%82%A2%E3%83%83%E3%83%97%E3%83%AD%E3%83%BC%E3%83%89\&wpDestFile=/grav/grav-markdown-syntax/grav-markdown-syntax-image2.jpg)

### 横罫線

水平方向の規則は、段落間のテーマ別の区切りを作成するために使用されます。 次のいずれかの方法を使用して、段落間に区切りを作成できます。

* _**\_**_ -3つのアンダースコア
* **---** − 3つのダッシュ
* **\***-3つのアスタリスク

ブラウザで\_md\_ファイルを **localhost/Grav/mypage;** として開きます。次の結果が表示されます-

[Grav Markdown構文](https://www.finddevguides.com/index.php?title=%E7%89%B9%E5%88%A5:%E3%82%A2%E3%83%83%E3%83%97%E3%83%AD%E3%83%BC%E3%83%89\&wpDestFile=/grav/grav-markdown-syntax/grav-markdown-syntax-image3.jpg)

### ボディコピー

**本文コピー\*は、マークダウン構文で通常の形式でテキストを書き込むこととして定義できます。**（p）\*タグは使用されません

#### 例

```
It is a way of writing your plain text in an easy to read and write format,
which later gets converted into HTML code.
```

Copy

ブラウザで\_.md\_ファイルを **localhost/Grav/mypage;** として開きます。次の結果が表示されます-

[Grav Markdown構文](https://www.finddevguides.com/index.php?title=%E7%89%B9%E5%88%A5:%E3%82%A2%E3%83%83%E3%83%97%E3%83%AD%E3%83%BC%E3%83%89\&wpDestFile=/grav/grav-markdown-syntax/grav-markdown-syntax-image4.jpg)

### 強調

\_Emphasis\_は、テキストの一部を太字にしたり、斜体にしたり、取り消し線を引いたりするために使用されるマークダウン構文の記述形式です。 以下でそれらについて議論しましょう-

#### Bold

テキストの一部は、両側に2つの\*（\*\*）\*記号を使用して太字にすることができます。

* 例 \*

```
The newest articles from* *Advance Online Publication (AOP)** and the current issue.
```

Copy

この例では、\*「Advance Online Publication（AOP）」\*の単語を太字で表示する必要があります。

ブラウザで\_.md\_ファイルを **localhost/Grav/mypage** として開くと、次の結果が表示されます-

[Grav Markdown構文](https://www.finddevguides.com/index.php?title=%E7%89%B9%E5%88%A5:%E3%82%A2%E3%83%83%E3%83%97%E3%83%AD%E3%83%BC%E3%83%89\&wpDestFile=/grav/grav-markdown-syntax/grav-markdown-syntax-image5.jpg)

#### イタリック体

テキストをイタリック体にするには、単語の両側に\*“ \_” \*（アンダースコア）記号を使用します。

**例**

```
The newest articles from _Advance Online Publication_ (AOP) and the current issues.
```

Copy

この例では、**「Advance Online Publication」**（AOP）の単語を斜体にする必要があります。

ブラウザで\_.md\_ファイルを **localhost/Grav/mypage** として開きます。 これにより、次の結果が得られます-

[Grav Markdown構文](https://www.finddevguides.com/index.php?title=%E7%89%B9%E5%88%A5:%E3%82%A2%E3%83%83%E3%83%97%E3%83%AD%E3%83%BC%E3%83%89\&wpDestFile=/grav/grav-markdown-syntax/grav-markdown-syntax-image6.jpg)

#### 取り消し線

単語の両側に2つの **"\~\~"** （チルダ）を使用して、単語を取り消し線で囲みます。

**例**

```
The newest articles from ~~Advance Online Publication~~ (AOP) and the current issues.
```

Copy

この例では、「Advance Online Publication」（AOP）という言葉を打つ必要があります。

ブラウザで\_.md\_ファイルを **localhost/Grav/mypage** として開きます。 これにより、次の結果が得られます-

[Grav Markdown構文](https://www.finddevguides.com/index.php?title=%E7%89%B9%E5%88%A5:%E3%82%A2%E3%83%83%E3%83%97%E3%83%AD%E3%83%BC%E3%83%89\&wpDestFile=/grav/grav-markdown-syntax/grav-markdown-syntax-image7.jpg)

#### ブロッククォート

ブロック引用を作成するには、文または単語の前に\*> \*記号を追加する必要があります。

**例**

```
>The newest articles from Advance Online Publication (AOP) and the current issues.
```

Copy

この例では、文の前に>記号を使用しています。

ブラウザで\_.md\_ファイルを **localhost/Grav/mypage;** として開きます。次の結果が表示されます-

[Grav Markdown構文](https://www.finddevguides.com/index.php?title=%E7%89%B9%E5%88%A5:%E3%82%A2%E3%83%83%E3%83%97%E3%83%AD%E3%83%BC%E3%83%89\&wpDestFile=/grav/grav-markdown-syntax/grav-markdown-syntax-image8.jpg)

Blockquoteは次の方法でも使用できます-

```
>The newest articles from Advance Online Publication (AOP) and the current issues.
>>> The newest articles from Advance Online Publication (AOP) and the current issues.
```

Copy

ブラウザで\_.md\_ファイルを **localhost/Grav/mypage;** として開きます。次の結果が表示されます-

[Grav Markdown構文](https://www.finddevguides.com/index.php?title=%E7%89%B9%E5%88%A5:%E3%82%A2%E3%83%83%E3%83%97%E3%83%AD%E3%83%BC%E3%83%89\&wpDestFile=/grav/grav-markdown-syntax/grav-markdown-syntax-image9.jpg)

### お知らせ

通知を使用して、重要な情報を通知または通知できます。

通知には、黄色、赤、青、緑の4種類があります。

#### 黄

**！>> \*情報を説明する黄色の通知タイプの前に \*>>>** 記号を使用する必要があります。

**例**

```
>>>Neurotransmitter-gated ion channels of the Cys-loop receptor family are essential
mediators of fast neurotransmission throughout the nervous system and are implicated
in many neurological disorders.
```

Copy

#### Red

警告の赤い通知の前に4つの **>>>>** 記号を使用します。

**例**

```
>>>>Neurotransmitter-gated ion channels of the Cys-loop receptor family are essential
mediators of fast neurotransmission throughout the nervous system and are implicated
in many neurological disorders.
```

Copy

#### Blue

青の通知タイプには5つの **>>>>>** 記号を使用します。これはメモを表します。

**例**

```
>>>>>Neurotransmitter-gated ion channels of the Cys-loop receptor family are essential
mediators of fast neurotransmission throughout the nervous system and are implicated
in many neurological disorders.
```

Copy

#### 緑

緑の通知タイプの前に6つの **>>>>>>** 記号を使用します。これはヒントを説明しています。

**例**

```
>>>>>>Neurotransmitter-gated ion channels of the Cys-loop receptor family are essential
mediators of fast neurotransmission throughout the nervous system and are implicated
in many neurological disorders.
```

Copy

ブラウザでmdファイルを **localhost/Grav/mypage;** として開きます。次の結果が表示されます-

[Grav Markdown構文](https://www.finddevguides.com/index.php?title=%E7%89%B9%E5%88%A5:%E3%82%A2%E3%83%83%E3%83%97%E3%83%AD%E3%83%BC%E3%83%89\&wpDestFile=/grav/grav-markdown-syntax/grav-markdown-syntax-image10.jpg)

### リスト

このセクションでは、Gravで順序なしリストと順序付きリストがどのように機能するかを理解します。

#### 順不同

順不同リストでは、箇条書きが使用されます。 \*\*、-、+ \*を使用します。 箇条書きの記号。 テキストと箇条書きが表示される前に、スペースを含む記号を使用します。

* 例 \*

```
+ Bullet
+ Bullet
+ Bullet
   -Bullet
   -Bullet
   -Bullet
  * Bullet
```

Copy

ブラウザで\_.md\_ファイルを **localhost/Grav/mypage;** として開きます。次の結果が表示されます-

[Grav Markdown構文](https://www.finddevguides.com/index.php?title=%E7%89%B9%E5%88%A5:%E3%82%A2%E3%83%83%E3%83%97%E3%83%AD%E3%83%BC%E3%83%89\&wpDestFile=/grav/grav-markdown-syntax/grav-markdown-syntax-image11.jpg)

#### 順序付けられました

何かをリストする前に番号を追加してください。

**例**

```
1. Coffee
2. Tea
3. Green Tea
```

Copy

ブラウザで\_.md\_ファイルを **localhost/Grav/mypage** として開きます。 これにより、次の結果が得られます-

[Grav Markdown構文](https://www.finddevguides.com/index.php?title=%E7%89%B9%E5%88%A5:%E3%82%A2%E3%83%83%E3%83%97%E3%83%AD%E3%83%BC%E3%83%89\&wpDestFile=/grav/grav-markdown-syntax/grav-markdown-syntax-image12.jpg)

### Code

このセクションでは、インラインコードとブロックコードの「フェンス」がGravでどのように機能するかを理解します。

#### インラインコード

マークダウンでコードを使用するために、\*（ \`）\*を使用してインラインコードを作成します。

**例**

```
In the given example, '<section></section>' must be converted into code.
```

Copy

ブラウザで\_.md\_ファイルを **localhost/Grav/mypage** として開くと、次の結果が表示されます-

[Grav Markdown構文](https://www.finddevguides.com/index.php?title=%E7%89%B9%E5%88%A5:%E3%82%A2%E3%83%83%E3%83%97%E3%83%AD%E3%83%BC%E3%83%89\&wpDestFile=/grav/grav-markdown-syntax/grav-markdown-syntax-image13.jpg)

#### ブロックコード「フェンス」

複数行のコードをブロックする場合は、\*（ \`\` \`）\*フェンスを使用します。

**例**

````
```
You’re Text Here

```
````

Copy

ブラウザで\_.md\_ファイルを **localhost/Grav/mypage;** として開きます。次の結果が表示されます-

[Grav Markdown構文](https://www.finddevguides.com/index.php?title=%E7%89%B9%E5%88%A5:%E3%82%A2%E3%83%83%E3%83%97%E3%83%AD%E3%83%BC%E3%83%89\&wpDestFile=/grav/grav-markdown-syntax/grav-markdown-syntax-image14.jpg)

### テーブル

Gravでは、ヘッダーセクションの下のパイプとダッシュを使用してテーブルが作成されます。 パイプを垂直方向に並べてはいけません。

#### 例

```
| Number  |    Points       |
| ------  | -----------     |
|   1     | Eve Jackson 94  |
|   2     | John Doe 80     |
|   3     | Adam Johnson 67 |
```

Copy

ブラウザで\_.md\_ファイルを **localhost/Grav/mypage;** として開きます。次の結果が表示されます-

[Grav Markdown構文](https://www.finddevguides.com/index.php?title=%E7%89%B9%E5%88%A5:%E3%82%A2%E3%83%83%E3%83%97%E3%83%AD%E3%83%BC%E3%83%89\&wpDestFile=/grav/grav-markdown-syntax/grav-markdown-syntax-image15.jpg)

#### 右揃えのテキスト

テーブルの内容を右側に表示するには、見出しの下のダッシュの右側にコロンを追加する必要があります。

```
| Number |     Points      |
| ------:| -----------:    |
|   1    | Eve Jackson 94  |
|   2    | John Doe 80     |
|   3    | Adam Johnson 67 |
```

Copy

ブラウザで\_.md\_ファイルを **localhost/Grav/mypage;** として開きます。次の結果が表示されます-

[Grav Markdown構文](https://www.finddevguides.com/index.php?title=%E7%89%B9%E5%88%A5:%E3%82%A2%E3%83%83%E3%83%97%E3%83%AD%E3%83%BC%E3%83%89\&wpDestFile=/grav/grav-markdown-syntax/grav-markdown-syntax-image15%EF%BC%88a%EF%BC%89.jpg)

### リンク集

このセクションでは、Gravでリンクがどのように機能するかを理解します。

#### 基本リンク

リンクは（\[]）角括弧と（（））括弧を使用して作成されます。 **\[]** 括弧内にコンテンツを記述し、\*（）\*内にドメイン名を記述する必要があります。

**例**

```
[Follow the Given link](http://www.google.com)
```

Copy

ブラウザで\_.md\_ファイルを **localhost/Grav/mypage;** として開きます。次の結果が表示されます-

[Grav Markdown構文](https://www.finddevguides.com/index.php?title=%E7%89%B9%E5%88%A5:%E3%82%A2%E3%83%83%E3%83%97%E3%83%AD%E3%83%BC%E3%83%89\&wpDestFile=/grav/grav-markdown-syntax/grav-markdown-syntax-image16.jpg)

#### タイトルを追加

このセクションでは、.mdファイルにタイトルを追加する方法を理解します。

**例**

```
[Google](https://www.gogle.com/google/"Visit Google!")
```

Copy

ブラウザで\_.md\_ファイルを **localhost/Grav/mypage;** として開きます。次の結果が表示されます-

[Grav Markdown構文](https://www.finddevguides.com/index.php?title=%E7%89%B9%E5%88%A5:%E3%82%A2%E3%83%83%E3%83%97%E3%83%AD%E3%83%BC%E3%83%89\&wpDestFile=/grav/grav-markdown-syntax/grav-markdown-syntax-image16%EF%BC%88a%EF%BC%89.jpg)

### 画像

画像はリンクに似ていますが、構文の先頭に感嘆符が付いています。

**例**

```
![Nature] (/Grav/images/Grav-images.jpg)
```

ブラウザで\_.md\_ファイルを **localhost/Grav/mypage** として開くと、次の結果が表示されます-



