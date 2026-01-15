# URDF file of Sainsmart 6dof Arm
An urdf file of six dof arm for sainsmart

<img width="794" height="632" alt="Screenshot from 2026-01-14 21-29-53" src="https://github.com/user-attachments/assets/39ce6364-c8d3-4247-bf0f-481dc9e2f05b" />


https://github.com/user-attachments/assets/0a5c15a7-8e43-44e0-8157-e4ffdeb356b1


## 概要
Sainsmart 6dof Arm 用 URDF(Unified Robot Description Format) ファイルを作成しました。

![Sainsmart6dofARM](https://github.com/wedesoft/arduino-sainsmart/raw/master/6axis-size.jpg)

## Elbow Joint について
Elbow Joint は、実機ではリンクを介して駆動していますが、この URDF では、都合で省略しております。

## 調整
URDF 上では、各リンクは薄い色のボックスで覆われていますが、Unity などで Joint が衝突しないようにしたい場合は、ボックスは取り除いてください。Moveit! でも、Collision を起こす個所はあるので、適程調整して使用しております。

## サーボモーター
標準仕様では、サーボモータは、MG996R と SG90G の組み合わせとなっておりますが、私の都合で、SG90G を、MG90S と MG90D に換装した URDF となっております。


**以上**
