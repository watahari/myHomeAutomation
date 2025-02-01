
env.
* Raspberry Pi OS ( Debian Bookworm 12 )
* aarch64

setup
* https://docs.docker.com/engine/install/debian/

manual deploy
```
docker compose up -d
```

features.
* 4時間空けなければいけない薬を服用したとき、amazon dash button によってそれを記録してメトリクス化し、Grafana上で「あと何時間で次の服用か」を表示する

ops.
* 系の監視のページングはDiscordに対して行なう
