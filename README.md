# Setup

```bash
cd graftorio && \
  bash ./build.sh && \
  sudo chown -R 472 data/grafana && \
  sudo chown -R 65534 data/prometheus && \
  sudo chown -R 65534 data/prometheus.yml && \
  cd ../
mkdir -p factorio-mods
mv ./graftorio_1.0.19.zip -t factorio-mods --force
```

1. 出来上がった zip ファイルを自分のゲーム本体の方へもコピーする
1. `docker-compose up`
1. `localhost:34197`で接続
1. https://github.com/TheVirtualCrew/graftorio#installation の 5 以降を参考に色々やる
