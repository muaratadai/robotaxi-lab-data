# robotaxi-lab-data

ロボタクシー実践ラボ（ https://robotaxi-lab.com/ ）のデータとサイトのファイル。

- `zakkuri.json`：毎日ざっくりニュース（本番サイトが直接読み込む）
- `hojokin.json`：あなたが使える補助金（本番サイトが直接読み込む）
- `site/`：本番サイトのファイル。`main` に push すると、GitHub Actions がさくらのサーバー（ /home/colors2/www/robotaxi-lab ）へ自動で送る
