# BoatRaceDataStorager

## 何をするツールなのか
BoatRaceDataCollector から入手した競争成績データは txt ファイルなので、データ分析に使いにくいです。
それを SQL 形式のデータとして扱えるようにテキストファイルをパースして、データを格納するツールです。

## 環境について
・python 3.x 系の環境で動作します。
・MySQL を導入する必要があります。

## 使い方
1. CREATE_TABLE_COMMAND.txt 内の SQL 文を実行してテーブルを作成します
2. PREPARE_DATA.txt を実行して場内データ等を追加します
3. main.py と同じ階層に、「RaceResult」フォルダを作成します
4. 「RaceResult」 フォルダに BoatRaceDataCollector から入手した競争成績データを全ていれます。
5. main.py を実行します
