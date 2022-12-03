# PlayerSwapper
プレイヤーの位置を入れ替えるデータパック

> **対応バージョン**

**1.17～**

> **動作確認バージョン**

**1.19.x**


# ダウンロード方法
右側の[Releases]をクリックしMaki-PlayerSwapper.zipをダウンロードするだけ！

# データパックの導入方法
Maki-PlayerSwapper.zipを解凍し中にあるデータパックをworldフォルダのdatapacksに入れる

# データパックの使用方法
```mcfunction
# プレイヤーのインベントリをストレージに保存する
data modify storage storage_to_player: value set from entity <対象のプレイヤー> Inventory
# プレイヤーに装備させたいときにfunctionを実行する
execute as <対象のプレイヤー> run function storage_to_player:paste
```

# その他
バグ報告等は[@Having_harumaki](https://twitter.com/Having_harumaki)まで

