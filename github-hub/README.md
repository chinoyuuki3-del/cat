# PixelCat GitHub Hub

PixelCat v1.1 が読み込む軽量データHubです。

固定URL:
`https://raw.githubusercontent.com/chinoyuuki3-del/cat/main/github-hub/...`

## data
- `status.txt` サーバー状態
- `notice.txt` アプリ内お知らせ
- `config.json` デイリーボーナス・交換レート・セール設定
- `shop.json` 通常ショップ商品 (`items`)
- `cats.json` 猫カタログ (`cats`)
- `clothes.json` 服カタログ (`clothes`)
- `roulette.json` ルーレット報酬 (`rewards`)
- `events.json` 散歩イベント (`events`)
- `regions.json` 地域判定 (`regions`)
- `souvenirs.json` おみやげ (`souvenirs`)
- `gifts.json` ギフト配信 (`gifts`)
- `prepaid_test.json` CAT Payテストカード
- `version.json` Hub / アプリ互換情報

## regions
- `tokyo.json`
- `osaka.json`
- `hokkaido.json`
- `okinawa.json`

地域ショップはすべて `items` 配列で配信します。

## users
CAT PayカードIDごとのクラウドセーブ:
`users/CATCARD-XXXX.json`

公開リポジトリなので、個人情報・本物の秘密情報・アクセストークンは保存しないでください。
管理者HTMLのGitHub tokenは sessionStorage のみで扱います。
