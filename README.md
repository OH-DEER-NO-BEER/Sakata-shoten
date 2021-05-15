# Sakata-shoten

## Overview

坂田商店の電子化を進める．
ユーザは Android, iOS, Web 上で動作する決済サービスを利用できる．
加えて，管理者は商品登録，棚卸，集金を本システム上で一括して行うことができる．

## 要件定義

-   開発環境

    -   Docker 
    -   IDE は自由
    -   Git

-   開発言語／ツール
    -   View: Kotlin(iOS, Android Native), React(TypeScript)
    -   Backend: Go lang 

-   関連モジュール
    - [内部処理](https://github.com/OH-DEER-NO-BEER/sakata-shoten-common)
## 実装の手法

## Description

## Demo

## Requirement

## Usage

First, copy files and folders written below.  
`$ git clone https://github.com/OH-DEER-NO-BEER/Sakata-shoten.git`  
`$ cd Sakata-shoten`  
Then, start containers by using following command  
`$ docker-compose up -d`  
or here (with building).  
`$ docker-compose up -d --build`  
If you want to enter running container, write below (web)  
`$ docker exec -it sakata-shoten_web_1 bash`  
or here (mysql).  
`$ docker exec -it sakata-shoten_mysql_1 bash`

## Install

## Contribution

## Author

Kaito YOKORO, Ryosuke MIYAWAKI, Koki MIYAZAKI, Hiroto OSHIMI
