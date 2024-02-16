# Dockerのハンズオンで出来た事  
 - このREAD.mdでは、課題⑦のハンズオン出来た事をまとめております。  
   今回参考にしたハンズオンは↓のURLになります。  
   https://github.com/raisetech-for-student/docker-mysql-hands-on

 ### 実行結果①
  - 実行結果①では、「　ls　」コマンドでdocker-mysql-hands-onのあるファイルを一覧表示しております。
  - docker-mysql-hands-onの中には  
    ①Dockerfile　　②RAEDME.md　　③conf　　④docker-compose.yml　　⑤renovate.json　　⑥sql　の  
    6つのファイルがある事になります。
    
 ![handson①](https://github.com/mizoguchi-kouichi/assignment7/assets/156568693/ffc5395c-3858-4eac-bee3-2ebda6283c47)
### 実行結果②
 - 実行結果②の線について説明します。
 - 赤線のコマンドでは、コンテナの起動をしております。
 - 水色のコマンドでは、現在起動しているプロセスを表示しております。
   緑色の箇所が、起動しているプロセス表示しており docker-mysql-hands-on　になっております。
   
![handson②](https://github.com/mizoguchi-kouichi/assignment7/assets/156568693/a9de1445-85ad-468a-ba7e-ccee357f446e)

### 実行結果③
 - 実行結果③の線について説明します。  
 - 赤線のコマンドでは、MySQLにログインしております。  
   今回は、赤線の箇所の最後に　「　-p 　」があるので、パスワード入力が必要になります。  
   ここでのパスワード入力は、打ったパスワードが画面には表示されないので、パスワードの間違いに気をつけてください。  
 - 水色のコマンドでは、データベースの一覧を表示しております。
   
![handson③](https://github.com/mizoguchi-kouichi/assignment7/assets/156568693/d7d73439-e884-4461-a375-75972b0cfa60)
