# Misoton-ReVIEW-Template
サークル「味噌とんトロ定食」用　Re;Viewテンプレートです。

# 使い方
- Docker環境を整える
- 以下のコマンドを実行する

```sh
docker run --rm -v `pwd`:/work vvakame/review /bin/sh -c "cd /work/articles ; review-pdfmaker config.yml"
```

- articlesディレクトリにPDFが作成されている
