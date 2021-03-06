# ToDo操作について

後でやったことを思い出したい。そのためにToDoを記録する。

どこに、どう保存し、どう検索すればいいか？　要検討。

## 工程別

1. メモする
1. 優先順位をつける
1. やってみる（ToDo非表示/表示の切替）
1. やってみた結果を書く
    * URLを残す（参考、成果物）
    * 結果を分類する（解決した、解決せず、未実施）

### 1. メモする

忘れる前にメモできることが重要。

順番も内容もあとで精査すればいい。とにかく頭から消える前に残すことを最優先！

今までの状態も見ながらやらないと書けない。

```
$ todo
To
=====================
文脈A
    やること2
    やること3
文脈B
    やること
=====================
Doing
---------------------
文脈A
    やること1
        疑問
---------------------
Done 解決した
---------------------
文脈
    やること
        疑問
            調べたこと http://参考
                予想したこと
                    やったこと http://成果物
                        結果 http://成果物
---------------------
Done 解決せず
---------------------
文脈
    やること
        疑問
            調べたこと http://参考
                予想したこと
                    やったこと
                        問題点
---------------------
pending 保留した
---------------------
```

* To、Doのヘッダ部分は入力できないのが好ましい
* Toの優先度が高いものほど上に書く
* Doはできた順に書く

時間もメモできたほうがいいかもしれないが、自動計測が面倒そう。考えを整理している時間と、やってみた時間の分割がむずかしい。せいぜい、メモした時間、Doへ移動した時間、くらいか。

* ToDoの内容は1日でクリアする。00:00で確定。その日の成果状態として確定する。

### 2. 成果報告

完了: nnn

結果|件数
----|----
解決した|nnn
解決できず|nnn
未完|nnn

* 解決した
    * [やったこと](URL)  所要時間(メモから解決したに移動した時間)
    * [やったこと](URL)  所要時間(メモから解決したに移動した時間)
    * [やったこと](URL)  所要時間(メモから解決したに移動した時間)
* 解決できず
    * [やったこと](URL)  結果  所要時間(メモから解決せずに移動した時間)
    * [やったこと](URL)  結果  所要時間(メモから解決せずに移動した時間)
    * [やったこと](URL)  結果  所要時間(メモから解決せずに移動した時間)
* 未完
    * やること
    * やること
    * やること

### 3. 思い出す

* yyyyMMdd.log
* yyyyMMdd.log

