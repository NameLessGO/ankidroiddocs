# インポート

Ankiのデータファイル(.apkg形式)は、AnkiDroidで直接インポートすることができます。それ以外の形式のファイルはAnkiDroidで直接インポートすることはできませんが、ほかの暗記カードソフトのデータの多くはAnkiでならインポートすることができ、それから[通常の操作でAnkiDroidに追加する](anki-desktop.md)ことが可能です。Ankiでのインポートについては、 [Ankiのマニュアルの「インポート」の節](http://wikiwiki.jp/rage2050/?2.0%2FImporting) を参照してください。

Ankiと同様に、AnkiDroidにおいても [二種類の.apkg形式ファイル](http://wikiwiki.jp/rage2050/?2.0%2FExporting#exporting-packaged-decks) を、ファイル名に基づき区別して扱っています。"collection.apkg"という名前であれば「コレクションパッケージ」と見なされ、AnkiDroidでインポートすると、**既に存在するすべてのデータを置きかえます。**"collection.apkg"**以外の**名前のapkgファイルはすべて「デッキパッケージ」として扱われ、AnkiDroidでインポートすると**既に存在するデータと合成されます。**

通常のAndroidの操作で.apkg形式のパッケージファイルを開くと、そのままAnkiDroidにインポートされます。あるいは、AnkiDroidの中で手動でインポート操作をすることもできます。

## パッケージファイルを開く

apkgファイルは自動的にAnkiDroidと関連づけられています。そこで、例えば自分宛てにapkgファイルを添付したメールを送ってその添付ファイルを開くと、AnkiDroidが自動的に起動し、インポートするか確認を求めてきます。「OK」を選ぶだけで、そのapkgファイルの内容がインポートされます。(訳注：ファイルマネージャーアプリの類を使っても便利だと思います)

## AnkiDroidで手動でファイルをインポートする

次のような手順で、手動でapkgファイルをインポートすることもできます。

 * 端末をUSBケーブルでPCに接続する
 * apkgファイルを、PCから端末のAnkiDroidフォルダにコピーする
 * AnkiDroidを起動する
 * デッキリスト画面のメニューから、「インポート」を選ぶ
 * コピーしたapkgファイルを選択する
 * 「OK」をタップ