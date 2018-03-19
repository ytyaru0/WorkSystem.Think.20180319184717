# ToDo

## To

* テンプレ作成
    * y, pj, repoコマンドそれぞれ

## Do

### 解決できず

* ranger
    * ファイル選択時、実行とエディタ起動を使い分けたいが可能？
        * `:r`で実行方法を選べるが……
            * `*.py`ファイルを`python`で実行すると一瞬で画面が消えて見えない……
                * [こちら](http://malkalech.com/ranger_filer#less)の方法 `LESS="$LESS -+F -+X" ranger` でも同様

### 解決した

* push
    * .git既存時
        * user起動引数省略したら.gitのを使う

* ranger
    * highlight
        * venv
            * 別々のvenvを併用できるか？
                * 知らん。でも`$ bash --rcfile {sh_path}`でアクティベート＋起動させて解決した [※](https://github.com/ytyaru0/RaspberryPi.Home.Root.20180318143826/commit/e54c5b4d665d0015f17ae2663e8bde1acab9def6)
    * ファイルパスコピーしたいがどうやって？
        * `yp`, `yn`, `yd` [参考](http://malkalech.com/ranger_filer#i-2)
    * 自作コマンド実行したいができなかった。環境変数パス通っていない？
        * `:shell {command}`とすれば実行できる


