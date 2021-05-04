# Misoton-ReVIEW-Template
サークル「味噌とんトロ定食」用　Re;Viewテンプレートです。

[TechBoosterさんのリポジトリ](https://github.com/TechBooster/ReVIEW-Template)をカスタマイズして使っています。

# 使い方
## Docker環境を整える
1. Docker IDを作成する
 [こちら](https://hub.docker.com/signup)


### Windowsの場合
1. インストーラーをダウンロードする
2. Dockerをインストールする


## このリポジトリをダウンロードする
[こちら](https://github.com/Shuichiro-T/Misoton-ReVIEW-Template/archive/master.zip)

## PDFを作成する
 以下のコマンドを実行する

```sh
docker run --rm -v `pwd`:/work vvakame/review /bin/sh -c "cd /work/articles ; review-pdfmaker config.yml"
```

## articlesディレクトリにPDFが作成されている
