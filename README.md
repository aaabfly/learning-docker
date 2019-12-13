# learning-docker: Dockerの練習

## ミニレポート

### Q1-1: 同じ `docker container run` コマンドを2回実行すると、1回目と2回目で違いはありますか？どう違いますか？

【二回目はhello-worldとだけしか出力されない】

### Q1-2: なぜ違いますか？

【ubuntuのイメージがすでにダウンロードされてる違い】

### Q1-3: `docker container ls` と `docker container ls -a` はどう違いますか？

【docker container lsは起動中のcontainerを表示して`docker container ls -a`はcontainerの履歴と詳細な情報を表示する違い】

### Q1-4: `docker image ls` と `docker container ls -a` はどう違いますか？（間違ってもいいので、自分の考えを述べてください）

【`docker image ls`はimageの一覧を表示する。
  `docker container ls -a`はすべてのdockerのcontainerの履歴を表示する】

### Q1-5: `ubuntu` イメージでの `cat /etc/issue` の結果をペーストしてください

【Debian GNU/Linux 10 \n \l】

### Q1-6: `docker image ls` と `docker container ls -a` はどう変化しましたか？

【nginxの情報が追加された】

### Q2-1: `-d` (デタッチド・モード) でコンテナを起動すると、どのような状態になりましたか？

【a8ccb538a41125a8668f71f7f193eee2e0199a83297517ccb2cc9b198ac60ae4
  よくわからん数列が出力された】

### Q2-2: http://localhost/ をブラウザで開くと、何が表示されましたか？

【Welcom to nginx! と表示された】

### Q3-1: `docker build -t sample-image .` 実行時に表示されている `building...` は、Dockerfileのどの行から実行されましたか？

【RUN echo "building...】

### Q3-2: `docker run sample-image` を実行すると、どうなりましたか？

【サンプルイメージが作られた】
