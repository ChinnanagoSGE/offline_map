# offline_map

## このオフラインマップシステムについて
　GPIOピンにGPSモジュールを接続したRaspberry Piで利用可能．マップデータをローカルファイルにダウンロードする必要がある．
 
## 環境
　動作に必要なライブラリを記す．バージョンは動作確認済みのもの．
 - Python 3.7
 - pySerial 3.0
 - websockets 8.1
 - micropyGPS
 
## 準備
　QJIS(3.16)を用いてマップタイル(png)を"./leaflet"にダウウンロード．（"qjis_download.pdf"参照）
 
## 使用方法
 1. "gps_server.py"を実行．
 2. "leaflet_offline.html"を開く．
