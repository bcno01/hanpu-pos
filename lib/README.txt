オフライン動作のため、外部CDNを使わずここに同梱している第三者ライブラリ(改変なし)。
npm レジストリの tarball を sha1 で照合して取得したもの。

- jsQR 1.4.0 (Apache-2.0)  https://github.com/cozmo/jsQR       -> jsQR.js(QRの読み取り)。ライセンス全文: LICENSE-jsQR.txt
- qrcode-generator 1.4.4 (MIT, Kazuhiko Arase)  https://github.com/kazuhikoarase/qrcode-generator -> qrcode.js(QRの生成)。ライセンスは qrcode.js 冒頭に記載

どちらも使う画面(スキャン開始 / QRシート表示)を開いたときに初めて読み込む。
