## LILYGO T-Circle-S3

T-Circle-S3 is a round-screen development board based on the ESP32S3 chip, featuring a 0.75-inch round TFT display, digital microphone, speaker, touch panel, and RGB LED.

Official GitHub: [T-Circle-S3](https://github.com/Xinyuan-LilyGO/T-Circle-S3)

## Version Information

| Version | Microphone | Interface Protocol | Description |
| --- | --- | --- | --- |
| T-Circle-S3_V1.0 | MSM261S4030H0R | I2S Standard Mode | Original version |
| T-Circle-S3_V1.1 | MP34DT05-A | PDM Mode | Microphone model changed |

## Configuration

**Set the compilation target to ESP32S3**

```bash
idf.py set-target esp32s3
```

**Open menuconfig**

```bash
idf.py menuconfig
```

**Select the board**

```
Xiaozhi Assistant -> Board Type -> LILYGO T-Circle-S3        (V1.0)
                               -> LILYGO T-Circle-S3_V1_1    (V1.1)
```

**Build**

```bash
idf.py build
```

<a href="https://github.com/Xinyuan-LilyGO/T-Circle-S3" target="_blank" title="LILYGO T-Circle-S3">LILYGO T-Circle-S3</a>
