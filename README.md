Next.js と FastAPI を組み合わせたサンプルアプリです。

フロントエンド（Next.js）: Home コンポーネントで GET / POST リクエストを送信
バックエンド（FastAPI）: 数値計算、文字列カウント、簡易メッセージAPI、CSV/画像処理などを提供

機能
フロントエンド
GETリクエスト送信（FastAPIからメッセージ取得）：数値を2倍 / 2で割る
POSTリクエスト送信（エコー）：文字数カウント

バックエンド
GET /api/hello : メッセージ返却
GET /api/multiply/{id} : 数値を2倍
GET /api/divided/{id} : 数値を2で割る
POST /api/echo : エコー
POST /api/count : 文字数カウント
