# 正負出力電源装置

## 概要

DC 9 ~ 12V を入力すると，正負出力に変換する電源回路です  
実装する定電圧レギュレータにより出力電圧が異なります

| 正側レギュレータ（U2）の種類 | 出力電圧 | 負側レギュレータ（U3）の種類 | 出力電圧 |
|:----:|----:|:----:|----:|
| NJM7812 | 12V | NJM7912 | -12V |
| NJM7809 | 9V | NJM7909 | -9V |
| NJM7805 | 5V | NJM7905 | -5V |

## 回路図

<div align="center"><img src="./img/Schematic.png" width="75%"></div>

## 設計イメージ図

<div align="center"><img src="./img/PCB_CAD.png" width="75%"></div>

## 3D イメージ図

<div align="center"><img src="./img/3D_Image_f.png" width="75%"></div>

# LICENSE

[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.ja) で公開します．ただし，営利目的で利用したい場合はその旨を `tatarariku(at)gmail.com` にてご相談ください