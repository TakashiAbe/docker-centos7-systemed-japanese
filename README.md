## 概要

### CentOS7 Systemdインストールおよびベース日本語化対応

- Systemd導入
- Crond導入
- 日本語化
- タイムゾーンを東京へ変更
- gitインストール

## 使い方

```
docker run -d --privileged=true --name centos7 takashiabe/centos7-systemd-japanize
```

docker-compose で使う際も、privileged: true の指定を忘れずに入れてください。

## License
MIT