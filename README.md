# mcs-report.com（MCS-Japan Vietnam Report）

静的サイト（Cloudflare Pages）。AI社員が `data/` のJSONを毎日更新し、push すると自動で公開される。

| パス | 内容 | 更新 |
|---|---|---|
| `index.html` | 公開ページ（基本情報・地図・数字・現地探訪・月次レポートの要点・相談フォーム） | 手動 |
| `members/index.html` | 会員ページ（Cloudflare Access でメール確認） | 手動 |
| `data/digs.json` | 数字で深掘り（新しい順） | 毎日 AI |
| `data/news.json` | デイリーニュース（新しい順）※公開は法律確認後 | 毎朝 AI |
| `data/issues.json` | 月次レポートの公開部分（見出しと要点まで） | 毎月4日 AI |
| `members/data/issues.json` | 月次レポート全文（会員のみ） | 毎月4日 AI |
| `data/posts.json` | 駐在員の投稿（掲載分）※公開は法律確認後 | 毎日 朝・15時 AI |
| `data/explore.json` | 現地探訪 | 編集長 |
| `data/docs.json` / `members/data/docs.json` | 資料（会員版のみURLあり） | 手動 |

注意：編集長の実名など個人名は載せない。会員向けの本文・資料URLは `members/` 以下にだけ置く。
