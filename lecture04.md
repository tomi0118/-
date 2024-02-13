# 第 4 回講義の課題

## 課題内容

1. VPCの作成
1. EC2の構築
1. RDSの構築
1. EC2からRDSへ接続
1. 学んだこと・苦労したこと

## 1.　VPCの作成

![VPC](image/lecture04-1(vpc).png)

## 2.　EC2の構築

![EC2](image/lecture04-2(inst1).png)

![EC2](image/lecture04-3(inst2).png)

![EC2](image/lecture04-4(inst3).png)

![EC2](image/lecture04-5(inst4).png)

## 3.　RDSの構築

![EC2](image/lecture04-6(RDS).png)

## 4.　EC2からRDSへ接続

![EC2](image/lecture04-7.png)

## 4.　学んだこと・苦労したこと

EC2やRDSのセキュリティーグループの作成に特に苦労しました。その設定を間違えていたために、EC2のSSH接続ができずかなり時間がかかってしまいました。
また、インスタンスのマシンイメージをAmazon Linux 2023に設定していたために、Mysqlがインストールできなかったりと、一つの設定が間違っているだけでエラーが発生してしまうことを実感しました。（このエラーはマシンイメージをAmazon Linux 2に変更することで解消できました。）ただ、エラー一つ一つを自分の力で調べながら解消できたことは今後に繋がるように感じました。



















