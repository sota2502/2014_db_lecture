2014 MySQL 講義資料
====

ごめんなさい、講義資料はまだコンフルから移動出来てません。
そのうち移動します。

ハンズオン
----

### インスタンス起動

+ RegionがTokyoになっている事を確認
+ EC2のAMIペインに移動
+ searchの条件をPublic imagesに変更
  + ami-11f08b10 を検索
+ それをベースにlaunch
  + m1.mediumを選択
  + 自分で外部からsshできるように
  + いちお外部に出る必要はないけど、ライブラリを追加する場合は必要
+ 起動したらmemcachedとmysqlが起動してるかいちお確認してください。
