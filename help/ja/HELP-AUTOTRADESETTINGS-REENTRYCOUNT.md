# **再エントリー回数**

## 目的:

- この設定により、最終的に成行注文を出す前に、オフセット付きの指値注文を再試行する回数を調整できます。

## 例:

- 再試行回数が 1 の場合、シグナルは最初にシグナルで受信した価格で注文を約定しようとします。
- 約定しない場合は、再試行は 1 回のみ行われ (再試行回数の設定に基づき、変更可能)、買いシグナルの場合は Ask プラス オフセット、売りシグナルの場合は Bid マイナス オフセットが使用されます。
- 再試行回数が尽きると、成行注文が出されます。
