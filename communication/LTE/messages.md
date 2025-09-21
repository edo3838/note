# PSS (Primary Syncronization Signal)
## 役割
サブフレームの0と5のOFDM信号の最後から２番目のOFDM信号
つまり、10msごとに2回送信される。
- Cell ID（PCI）の３通りを通知
- 時間同期(サブフレーム１ms)

# SSS (Secondary Syncronization Signal) 
サブフレームの0と5のOFDM信号の最後のOFDM信号
- Cell ID (PCI)の168通りを通知
- 時間同期（フレーム10ms）

# MIB (Master Information Block)
- System Bandwidth（システム帯域幅、例：1.4 / 3 / 5 / 10 / 15 / 20 MHz）
- PHICH設定（PHICHの長さとリソース数）
- System Frame Number (SFN) の上位8ビット

物理チャネルはPBCH。３層ま
サブフレーム0で毎フレーム送信される。ただし、40msごとにSFNが変わる