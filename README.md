# parabolic

- パラボリックアルゴ.xlsx
パラボリック解析のアルゴリズムを流れ図に起こしてみました。(アルゴリズムの出典元：https://qiita.com/siruku6/items/76f4072c06a988dfe2cb)
処理の流れ図があれば、python,javascript等の言語に処理を落とし組むことができると思います。


- paraboric.xlsx
パラボリック解析をエクセル上で行っております。サンプルデータとして1570 日経レバのOHCLデータを使用しており、OHLCデータをエクセル上の所定の場所に配置すると
シート上に組み込んだ計算式により、パラボリック解析の数値結果をシート上に出力するようになっております。

- parabolic.ipynbと1570.csv
パラボリック解析をJupyter上で実行します。1570.csvは日経レバのOHCLサンプルデータです。Jupyter notebook 「parabolic.ipynb」と株価データ「1570.csv」を同一ディレクトリに配置したうえで
parabolic.ipynbを実してください。
