# quiz_app
letは変数といい、値の入れ物のことをさす。
<br>
関数の最初の行 (上のコードの 2行目) で、userGuess という変数を宣言して、現在のテキストフィールドに入力された値をセットしています。そして、組み込みの Number() 関数を呼び出して、テキストフィールドに入力された値が間違いなく数値であることも確認しています。
<br>
次に、初めて条件分岐を伴うコードブロックが出てきます 
<br>
(3行目～5行目)。条件分岐は、条件の判定結果が真 (true) であるかどうかによって、次に実行するコードが変わります。
<br>
見た目が少しだけ関数に似ていますが、違うものです。
<br>
条件分岐の最も単純な書き方は if キーワードから始まり、括弧が続き、中括弧が続きます。
<br>
括弧の中には分岐する条件を書きます。条件が true となれば、中括弧の中にあるコードが実行されます。
<br>
条件が true にならなければ、中括弧の次のコードまで移動します。
<br>
今回の条件は guessCount 変数が 1 であるかどうかを判定しています。
(つまり、プレイヤーの初回の予想かどうかを判定しているのです。)