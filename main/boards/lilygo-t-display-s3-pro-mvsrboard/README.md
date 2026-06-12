## LILYGO T-Display-S3-Pro-MVSRBoard

T-Display-S3-Pro-MVSRBoard 是一款基于 ESP32S3 芯片的开发板，配备 222x480 TFT 显示屏、数字麦克风、扬声器、触摸屏、电源管理芯片、SD 卡模块等。

官方 GitHub：[T-Display-S3-Pro](https://github.com/Xinyuan-LilyGO/T-Display-S3-Pro)

## 版本说明

| 版本 | 麦克风型号 | 接口协议 | 更新说明 |
| --- | --- | --- | --- |
| T-Display-S3-Pro-MVSRBoard_V1.0 | MSM261S4030H0R | I2S 标准模式 | 原始版本 |
| T-Display-S3-Pro-MVSRBoard_V1.1 | MP34DT05-A | PDM 模式 | 更换麦克风型号 |

## 编译配置

**配置编译目标为 ESP32S3：**

```bash
idf.py set-target esp32s3
```

**打开 menuconfig：**

```bash
idf.py menuconfig
```

**选择板子：**

```
Xiaozhi Assistant -> Board Type -> LILYGO T-Display-S3-Pro-MVSRBoard_V1_0    (V1.0)
                               -> LILYGO T-Display-S3-Pro-MVSRBoard_V1_1    (V1.1)
```

**编译：**

```bash
idf.py build
```

<a href="https://github.com/Xinyuan-LilyGO/T-Display-S3-Pro" target="_blank" title="LILYGO T-Display-S3-Pro">LILYGO T-Display-S3-Pro</a>
