これは2009年に、[「Google日本語入力のヘルプフォーラム」に投稿された要望](https://productforums.google.com/forum/?hl=ja#!category-topic/ime-ja/LSB5bd2VHYA)により始まった「[Google日本語入力の和英辞書作成プロジェクト](https://code.google.com/archive/p/google-ime-user-dictionary-ja-en/)」をGoogleCodeのサービス廃止に伴い、公式に引き継いだプロジェクトのアーカイブです。

主に「カタカナ語英語辞書」の代替辞書作成を目的としています。(EDICT使用)

## プロジェクト概要

「Google日本語入力」の「カタカナ語→英単語」変換用の辞書を、みんなで作るプロジェクトです。

Jim Breen氏の日本語辞書プロジェクト"EDICT"により作成された、日本語－英語電子辞書ファイルをベースにしています。 主に「Microsoft IME カタカナ語英語辞書」の代替辞書を目的としていますが、ほとんど和英辞書になってしまいました。ごめんなさい。

## プロジェクトの期限

おそらく近いうちにGoogle TranslateやGoogle Dictionaryと連動するとは思うので、それまでのプロジェクトとします。 ぜひ、[Googleへ要望・提案](https://productforums.google.com/forum/?hl=ja#!category-topic/ime-ja/LSB5bd2VHYA)してください。

[https://productforums.google.com/forum/?hl=ja#!category-topic/ime-ja/LSB5bd2VHYA](https://productforums.google.com/forum/?hl=ja#!category-topic/ime-ja/LSB5bd2VHYA)

※ 追記 2012/06/25 : Google日本語入力で、主要のカタカナ語が使えるようになったようです。(Ver.1.5.1109 現在) プロジェクトとしては基本的に終了ですが、辞書作成は継続していきたいと思います。

※ 追記 2013/09/29 : [Googleのフォーラム](https://productforums.google.com/forum/?hl=ja#!category-topic/ime-ja/LSB5bd2VHYA)で、goldsさんが＊付きで変換できるファイルをアップしてくれています。[txtファイルへの直リン](https://14424878677811871143.googlegroups.com/attach/c4754b39c6bd65c1/%E5%92%8C%E8%8B%B1.txt?part=0.1&view=1&vt=ANaJVrFkDWsk3aW-5tYyT8aewSqjFMeIgfF8gOslm0IrSs0fOAqlBYy3gWfuPUzpx_jTOTgaQcMV3WSymN8vqp-0JfUbJWZ9A3QmBvVAKwq_26Dvee5EySc)

※ 追記 2016/12/23 : GitHubに以降後、放置していましたが、整備を行いました。


## 現在の収録単語数

約４万６千単語 (2009/12/11現在 45,989単語)

## 一括ダウンロード
下記は2016/12/23時点のアーカイブです。
[https://github.com/KEINOS/google-ime-user-dictionary-ja-en/archive/master.zip](https://github.com/KEINOS/google-ime-user-dictionary-ja-en/archive/master.zip)

最新のソースはGoogleDrive

※辞書の追加方法は下記「インストール方法」を参照

※単語の追加要望は下記「変更・更新・校正」を参照

## いささかウザイ件について

　複数ファイルにわかれているので、ダウンロードが面倒かもしれません。 Google日本語入力では１つのユーザー辞書は10,000行までしか読み込めないので、４万６千もの英単語を扱うには、複数ファイルに分ける必要がありました。ごめんなさい。

　また、作ったのはいいのですが、４万以上もあると必要以上に変換してしまうため、学習されるまでうざいと感じました。

　要望が多ければ「＊」を頭に付けて単語を入力すると変換する辞書も用意したいと思います。

例）＊らじお　→　radio

### インストール方法
ダウンロードしたTSVファイルを新規辞書としてインポートします。

  1. Google日本語辞書の「ツール」アイコンにある「辞書登録」から「Google日本語入力ツール」を開きます。
  2. 「管理」から「新規辞書にインポート」を選択します。
  3. 「ファイルを選択...」から「ファイルの種類」を「すべてのファイル(*)」にして、ダウンロードしたtsvファイルを選択して開きます。
  4. 辞書名をわかりやすい名前にします。(例：カタカナ辞書１) 
  5. 「インポート」ボタンを押してインポートします。 1. ダウンロードした辞書ファイルの分だけ(3)から繰り返します。

※ツールアイコンが選べない場合は、メモ帳などを開いて何か入力すると選べるようになります。

### 変更・更新・校正

辞書データは複数のGoogle Spreadsheetで管理し、管理方法はWikipediaと同じ概念を採用しています。

つまり、GMailやGoogleアカウントをお持ちであれば、誰でもダウンロード・追加・校正・バージョンバックなどの参加が可能です。

[https://goo.gl/VnfFLZ](https://goo.gl/VnfFLZ)


※ Googleアカウントの登録： [https://www.google.com/accounts/NewAccount?hl=ja](https://www.google.com/accounts/NewAccount?hl=ja)

※間違えて編集した場合： 該当するスプレッドシートの「ファイル」から「変更履歴を表示」で自分の編集より１つ前に戻し版を戻してください。

## ライセンス
この辞書のライセンスはEDICTファイル同様、下記クリエイティブ・コモンズにのっとります。

* http://creativecommons.org/licenses/by-sa/3.0/deed.ja
* http://creativecommons.org/licenses/by-sa/3.0/
* http://creativecommons.org/licenses/by-sa/3.0/legalcode

　また、上記は辞書に対してのライセンスであり、この辞書を利用するソフトウェアそのものには適用されません。 つまり、ソフトウェアそのものが同様のクリエイティブ・コモンズである必要はありませんが、標準でこの辞書を組み込んでいる場合や、この辞書を一部でもカスタマイズして利用している場合は、連絡の必要はありませんが、このオープンソース(ユーザー参加による辞書作成コミュニティ）の辞書を利用している旨、記載ください。

■ EDICT (Japanese-English Electronic DICTionary)

[http://www.csse.monash.edu.au/~jwb/edict.html](http://www.csse.monash.edu.au/~jwb/edict.html)
