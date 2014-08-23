# Cyberduckを起動する

事前にDockに追加されている場合、DockのCyberduckアイコンをクリックします。

> SpotlightやFinderで「アプリケーション」フォルダの中のCyberduckをダブルクリックしてもかまいません。

![](2014-08-23_13.14.45.jpg)

起動時に、Cyberduckを標準のFTPクライアントに設定するか聞かれますが、これはキャンセルでかまいません。

「次回から確認しない」をクリックした後キャンセルすれば、次回から表示されなくなります。

![](2014-08-23_13.14.56.jpg)

起動したら、左上の「新規接続」ボタンをクリックします。

![](2014-08-23_13.15.08.jpg)

設定画面が開きますので、接続先になるFTPの情報を入力します。

- サーバー（ホスト名）
- ユーザー名（ID）
- パスワード（password）

![](2014-08-23_13.16.28.jpg)

もし、契約しているサーバーがFTPS（FTP SSL、FTP over TLS/SSL）をサポートしているのならば、プルダウンで変更し、FTPSで接続するのが良いでしょう。

![](2014-08-23_13.16.35.jpg)

「接続」ボタンを押すと接続を開始します。

![](2014-08-23_13.16.49.jpg)

FTPSの場合、証明書でエラーが表示される事があります。

![](2014-08-23_13.16.52.jpg)

「証明書を表示」ボタンを押し、問題がなさそうであれば「続ける」を押して下さい。

問題がないか判断できない場合には、レンタルサーバー業者へ確認が必要です。

> このスクリーンショットですと「*.xserver.jp」のドメインの証明書であることがわかり、このドメインは同一の業者だとわかりますので許可しました。

もし次以降もこのエラーを無視したい場合には「"○○○"への接続時に"○○○"を常に信頼」のチェックをオンにしてから続けるを押してください。

![](2014-08-23_13.16.53.jpg)

次以降もこのエラーを無視したい場合（確認のできない証明書を許可する場合）には、OSの（お使いのMacの）パスワード入力を求められますので入力してください。

![](2014-08-23_13.16.54.jpg)

接続が完了すると、ファイル一覧が表示されます。


![](2014-08-23_13.16.57.jpg)

契約しているサーバーの`htdocs`（DocumentRoot[ドキュメントルート]）に相当するディレクトリに移動します。どこがそれに相当するのかは契約しているサーバー業者のサポートページや、契約時などに送られてくる資料を確認してください。

今回は`/uzulla.xsrv.jp/public_html`が相当しますので、そちらに移動します。

![](2014-08-23_13.17.04.jpg)

ディレクトリ（フォルダ）をダブルクリックすることで、移動ができます。

![](2014-08-23_13.17.09.jpg)

現在のディレクトリは、ファイルリスト上のプルダウンに表示されます。これで移動を完了しました。

![](2014-08-23_13.17.29.jpg)

契約直後にあるファイルは不要なので削除します（または、後述のダウンロード方法を見てダウンロードしてください）、削除するファイルを選択し、右クリックから「削除」を選びます。

![](2014-08-23_13.17.47.jpg)

確認のダイアログが出ますので、問題がなければ「削除」ボタンを押すとファイルが削除されます。

![](2014-08-23_13.17.51.jpg)

このFTPサーバーへの接続をブックマークする事ができます。左上のブックマークボタン（新規接続の下の本のアイコン）をクリックします。

![](2014-08-23_13.18.00.jpg)

左下の「＋」ボタンをクリックします。

![](2014-08-23_13.18.02.jpg)

ダイアログが表示されますので、必要であればニックネームを修正した後、ダイアログの左上の閉じるボタンをクリックするとブックマークが保存されます。

![](2014-08-23_13.18.09.jpg)

ブックマークが保存されました。今後はブックマークボタンをおして表示されるブックマーク表示画面からダブルクリックするだけでFTPに接続する事ができます。

![](2014-08-23_13.18.20.jpg)