# esp32-homekit
This project is impemented Apple Homekit Accessory Protocol(HAP) to ESP32.

# 事前準備
- ESP-IDF開発ツールをインストール
https://qiita.com/SamAkada/items/67551f3e2ff6ac602215

# ダウンロード
```
$ git clone https://github.com/SamAkada/esp32-homekit.git
$ cd esp32-homekit
$ git submodule update --init --recursive
```

# WiFi設定
1. ソースコードを開く examples/M5StickC-led/main/main.c
2. EXAMPLE_ESP_WIFI_SSID と EXAMPLE_ESP_WIFI_PASS を変更する

```
#define EXAMPLE_ESP_WIFI_SSID "mywifi"
#define EXAMPLE_ESP_WIFI_SSID "mypassword"  
```

# ビルド
```
$ cd examples/M5StickC-led
$ make
$ make flash
```

# Setup Code
## **`111-22-333`**

# 謝辞
https://github.com/younghyunjo
