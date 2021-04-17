# covid_osaka
大阪の公開データの縦軸を対数にしてみました
奥村先生のコードを使わせていただいています。

[横軸が日付のグラフの書き方](https://oku.edu.mie-u.ac.jp/~okumura/python/COVID-tokyo.html)<br>
[matplotlibでの日本語表示](https://oku.edu.mie-u.ac.jp/~okumura/python/plot.html)

以下のような形で進めようと考えたが、万一環境を汚してしまうといけないのですべてコメントアウトしました。
また、年、月、日という日本語は削除しました。
もし日本語表示をしたい場合には適切な修正を行ってください。

Google Colabで修正してアップロードするとadd -> commit -> pushがされるのかと思ったらそういうわけではないのを
知りませんでした。なので履歴は残っていません。

当初想定していた方法
>from google.colab import filesが成功したらGoogle Colab上での実行と仮定
>失敗したらローカルなのでIPAexfontなど日本語環境が設定されていると仮定
>
>以下の部分はGoogle Colab上での実行の時のみ実行しているつもり<br>
>```python
>!pip install japanize_matplotlib
>import japanize_matplotlib
>```
