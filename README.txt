■ PDFの差し替え方法
1. pdf フォルダの中のファイルを、同じ名前の新しいPDFで上書きする
   - 役割表           → pdf/yakuwari.pdf
   - タイムスケジュール → pdf/schedule.pdf
2. index.html の  var V="1";  の数字を1つ上げる（"2"、"3"…）
   ※スマホが古いPDFを覚えていて、差し替え前のものが出るのを防ぐため
3. フォルダごとサーバー（GitHub Pages など）にアップロードし直す

■ ボタンを増やす方法
index.html の <a href="pdf/○○.pdf" data-pdf>ボタン名</a> を1行コピーして書き換え、
pdf フォルダに同じ名前のPDFを入れる。
