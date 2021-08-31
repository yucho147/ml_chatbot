# ml_chatbot
特定のtwitterアカウントのtweetをslackに投げるbot  
(私は)HEROKUでデプロイしています。

- `Procfile`
  - HEROKUで動かすためのファイル
- `main.py`
  - botのスクリプト
- `user_list.yaml`
  - twitterアカウント名を列挙すれば良い

最新技術や論文の要約をしたtweetなどをslackに投げることで、技術に接する機会を増やす目的で作成しました。  
接する機会を増やし、インターナルな環境での議論をしやすくすることで、グループ内の最新技術への精神的ハードルを下げる目論見です。  
もちろん同様のことができる外部のツールをslackに連携させる方が圧倒的に楽です。slack以外のチャットツールをご利用であったり、オレオレチューンした書き込みをしたい方が、本リポジトリのコードを編集して使っていただければと思います。  
ぜひ、技術へ触れるハードルを下げて、楽しい働く環境を作っていただけると幸いです!!

## Example
| slack画面(参考)                                                                   | Rocket.Chat画面(参考)                                                                       |
|-----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|
| ![slack](https://github.com/yucho147/ml_chatbot/blob/main/figs/slack_example.png) | ![rocketchat](https://github.com/yucho147/ml_chatbot/blob/main/figs/rocketchat_example.png) |


