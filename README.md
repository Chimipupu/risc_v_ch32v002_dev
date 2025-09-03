# 15円 RISC-Vマイコン CH32V002評価F/W開発
WCH製 15円 RISC-Vマイコン CH32V002の評価F/W個人開発リポジトリ

## 開発環境

### H/W

- マイコン ... 型番:[CH32V002F4P6](https://www.wch-ic.com/downloads/CH32V002DS0_PDF.html)🔗
  - CPU ... [QingKeV2C (32bit RV32EmC RISC-V)]
  - ROM ... 16KB
  - RAM ... 4KB
  - Clock ... 48MHz
  - GPIO ... 18本
  - DMA ... x7ch
  - タイマー
    - ADTM ... 16bit高機能タイマー
    - GPTM ... 16bit汎用タイマー
  - WDT ... x2本(IWDG, WWDG)
  - SysTick ... 32bitタイマー
  - I2C ... x1ch
  - SPI ... x1ch
  - USART ... x1ch
  - ADC ... 12bit 3Msps SAR x8ch

### S/W

- IDE/SDK/コンパイラ
  - [MounRiver Studio (MRS) V2.2.0](https://www.mounriver.com/download)🔗

### デバッガ

- [WCH-LinkE Ver1.3](https://akizukidenshi.com/catalog/g/g118065)🔗

### デバッグ

#### SDI

- SDI ... WCHの1線式デバッグ

- [WCH-LinkE <--> 評価基板]
  - SWDIO <--> PD1ピン
  - GND <--> GND

#### UART

- [WCH-LinkE <--> 評価基板]
  - RX <--> PD5ピン(TX)
  - TX <--> PD6ピン(RX)
  - GND <--> GND
