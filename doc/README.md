ツッコミのできるWeb日記システム
=================

tDiaryでできること
------------

tDiaryは、いわゆるWeb日記を支援するシステムです。tDiaryには以下の特徴があります。

### 更新や設定までブラウザからできる

日記の参照だけでなく、日記の更新、設定までもWebブラウザから実行できます。ブラウザさえあれば面倒なメンテナンスは不要。手軽に使えて、長く続けられます。

### 「ツッコミ」が入れられる

日記の読者が、日記に「ツッコミ」を入れられます。ようするに、日付ごとに掲示板がついています。これを通じて、読者とのコミュニケーションが生まれます。 ツッコミがあったことを著者にメールで知らせる機能もあります。

### 「本日のリンク元」(Referer)機能

他の日記等からリンクされると、Refererヘッダを見てそのURLを表示します。どこかで自分の日記が話題にされていることがすぐにわかるように、従来のWeb日記コミュニケーションで使われている手法をわかりやすくサポートしています。

### 携帯端末対応

iモードに限らず、ほとんどの携帯電話やPalm・ザウルスなどの携帯端末からも日記を参照できます。専用の特別なURLは必要なく、自動認識して最適なページを生成します。通信料金のシビアな端末向けには無駄を省いた小さなページを送るようになっています。

### CSSを使ったテーマ機能

スタイルシートを使って見た目をがらりを変えることができます。これは「テーマ」と呼ばれ、別パッケージとして配布されているテーマ集には、100を越えるテーマが収録されています。もちろん自分で作ることも可能です。テーマは設定画面で簡単に切り替えることができます。

### プラグインによる機能追加

プラグインというモジュールを追加することで、日記の機能を増やしたり変更したりすることが可能です。詳しくは[HOWTO-use-plugin.html](HOWTO-use-plugin.html)(使い方)・[HOWTO-make-plugin.html](HOWTO-make-plugin.html)(作り方)を参照してください。

### 記述形式や保存形式を変更できる

日記を記述する形式(スタイル機能)や、データの保存形式(IO機能)が選択可能です。スタイルはmisc/styleの下に複数収められています。IOは現在、1.4系までの旧tDiary互換のPStoreIOと、2.0系以降の新しいテキスト形式であるDefaultIOがあります。詳しくは[HOWTO-make-io.rd](HOWTO-make-io.rd)を参照してください。

### Rubyで書かれている

重要なポイントでしょう:-)??実行にはruby 1.9.1-p378またはruby 1.8.7-p249以上が必要です。

セクション(段落)アンカーや過去の日記の参照など、一般的なWeb日記システムの持つ機能は基本的にサポートしています。

tDiaryのインストールと設定
----------------

[INSTALL.html](INSTALL.html)を参照してください。

著作権、サポートなど
----------

tDiary本体は、原作者であるただただし(t@tdtds.jp)が、GPL2の元で配布、改変を許可するフリーソフトウェアです。

また、tDiaryフルセットに付属するテーマ、プラグインはすべて、それぞれの原作者が著作権を有します。ライセンス等に関しては個々のファイルを参照してください。

tDiaryは[http://www.tdiary.org/](http://www.tdiary.org/)でサポートを行っています。ご意見・ご要望はこちらへどうぞ。パッチ歓迎です。
