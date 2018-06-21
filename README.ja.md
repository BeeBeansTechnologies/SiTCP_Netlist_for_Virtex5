Read this in other languages: [English](README.md), [日本語](README.ja.md)

# SiTCP Netlist for Virtex5

Xilinx Virtex 5用のSiTCP Netlist File(ngc file)です。


## SiTCP とは

物理学実験での大容量データ転送を目的としてFPGA（Field Programmable Gate Array）上に実装されたシンプルなTCP/IPです。

* SiTCPについては、[SiTCPライブラリページ](https://www.bbtech.co.jp/products/sitcp-library/)を参照してください。
* その他の関連プロジェクトは、[こちら](https://github.com/BeeBeansTechnologies)を参照してください。

![SiTCP](sitcp.png)


## 履歴

2012-11-22 Ver.6.0
* SiTCPのクライアントモードを追加しました。

2014-03-28 Ver.8.0
* 受信時のACK応答方式の拡張を行いました。IPGの最小値を3～15の範囲で設定可能にしました。

2017-04-21 Ver.10.0
* MACアドレス表示ポートを追加しました。受信時のバグを修正しました。

2017-05-29 Ver.11.0
* IEEE802.3xフローコントロール（PAUSE）に対応しました。
* クライアントモードでのARPリクエスト機能を追加しました。
* SiTCP_RSTのタイミングを変更しました（EEPROM設定値の転送完了まで延長）。
* データ受信時のACK送信形式を変更しました。
* MIF初期化機能を設定可能にしました。
