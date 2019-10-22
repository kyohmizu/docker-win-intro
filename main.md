class: center, middle, inverse
## Windowsコンテナ入門

---
### whoami

.left-small[
    ![image](https://pbs.twimg.com/profile_images/994762110792953856/EheEvqBY_400x400.jpg)
]

.right-large[
- Kyohei Mizumoto(@kyohmizu)

- C# Software Engineer

- Interests
    - Docker/Kubernetes
    - Go
    - Security
]

---
### 今日話すこと

- コンテナの基本
- Windowsコンテナ
  - 概要
  - デモ（時間があれば）

---
class: center, middle, blue
## コンテナの基本

---
### コンテナとは

- 仮想化技術の一つ(コンテナ型仮想化)  
  ⇔ 仮想マシン(VM)
- 1つのホスト上に複数の分離空間を実現
  - それぞれの分離空間では異なるOSを実行可能
- ホストOSのリソースを共有
- Dockerコンテナが主流

---
.left-half[
  仮想マシン
  <img src="https://docs.microsoft.com/ja-jp/dotnet/architecture/microservices/container-docker-introduction/media/image3.png" width=84%>
]

.right-half[
  コンテナ
  <img src="https://docs.microsoft.com/ja-jp/dotnet/architecture/microservices/container-docker-introduction/media/image4.png" width=84%>
]

.zoom0[
  <u><https://docs.microsoft.com/ja-jp/dotnet/architecture/microservices/container-docker-introduction/docker-defined></u>
]

---
### コンテナの特徴

仮想マシンとの相違

- 軽量(オーバーヘッドが少ない)
- 起動が高速
- 仮想マシンに比べ分離レベルは低い
  - セキュリティリスクに注意

---
### コンテナを支える技術

.half[
- namespace
]

- cgroups

---
### Windowsでのコンテナ利用

.half[
- Docker Desktop for Windows
  - 仮想マシン上でコンテナ実行を実行
  - Hyper-Vを使用  
  <u><https://docs.docker.com/docker-for-windows/></u>
]

- Docker Toolbox
  - レガシーなデスクトッププログラム
  - Oracle VM VirtualBoxを使用  
  <u><https://docs.docker.com/toolbox/></u>

---
class: center, middle, blue
## Windowsコンテナ

---
### Windowsコンテナ

- Docker Desktop for Windowsのみ実行可能

---
### コンテナタイプ

---
### ベースイメージ

---
### 実行環境

---
class: center, middle, blue
## デモ<br/>（時間があれば）

---
### 参考

.zoom1[
Docker実践ガイド第2版  
<u><https://book.impress.co.jp/books/1118101052></u>

Microsoftドキュメント  
<u><https://docs.microsoft.com/ja-jp/virtualization/windowscontainers/></u>
]

---
class: center, middle, blue
## 宣伝

---
<u><https://cloudnativedays.jp/cndk2019/></u>

---
class: center, middle, blue
### ありがとうございました！