# tou-skipper
東京通信大学のLMSシステム @ROOM の学習補助ユーザースクリプトです。  
# 使用する前に
使用には[TamperMonkey](https://www.tampermonkey.net)等のユーザースクリプト拡張機能が必要です。  
使用前に必ず下記設定を行って下さい。  
①@ROOMを開き、URL左側の🔒マークをクリックする  
![image](https://user-images.githubusercontent.com/25764819/165962441-74542861-924f-4932-8bf4-428fa6837660.png)  
②サイトの設定をクリックする  
![image](https://user-images.githubusercontent.com/25764819/165962664-5fc3d4b3-33d1-4721-abb7-b95322309722.png)  
③カメラとポップアップを許可する(ポップアップを許可しない場合、進捗が正しく取得できません)  
![image](https://user-images.githubusercontent.com/25764819/165962849-ea9a4f15-e6c5-4e02-98e3-fcc9d7aecec7.png)
# 主な機能
## トップ画面
各授業の進捗率を取得・表示することができます  
通常![image](https://user-images.githubusercontent.com/25764819/165965453-256d2ed6-c2be-4a02-af5f-aad826c61acd.png)
変更![image](https://user-images.githubusercontent.com/25764819/165965556-549bd5aa-bfbb-490a-8a03-850f0b5d0d02.png)  
進捗率を取得する場合は、@ROOMのロゴをクリックすると取得することができます。(必ずポップアップを許可して下さい)
## 授業視聴中
動画の残り時間・割合%をタブ名に表示します  
動画を開いた時、自動で再生を開始します  
動画を再生する時、音量を自動で指定した値に調整します  
動画の再生が完了した時、ブザー音で知らせます  
〃、次の授業を自動で再生します  
## 小テスト
回答をDBに記録し、次回以降の再回答時に正答を自動で選択・入力します  
(現時点では文字列を自動入力した後、問題を正しく処理できないバグがあります。自動入力後、適当にキーボードをinput内で押すと処理されるようです)  
## 記述問題
記述のC&P禁止を解除します  
## その他
色々追加予定です...
