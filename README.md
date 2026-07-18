## アプリ概要
Next.jsとSupabaseを用いた単語帳アプリです。  

日本語学習者が「単語を覚えるだけで終わらず、実際に文章でアウトプットできる」ことを目的とした単語帳アプリです。
ユーザーは単語を選択して例文を作成し、生成AIによる添削を受けることで、自然な日本語表現を学習できます。

## サイトイメージ

![アプリ画面](https://github.com/sophie0938/PortfolioExample_WorX_ENGINEER-CLASS/blob/6ac43745f91a7b503ab76d1dd4329897898e2123/docs/%E3%83%A1%E3%82%A4%E3%83%B3%E3%83%9A%E3%83%BC%E3%82%B8.png?raw=true)

## サイトURL
https://japanese-learning-app-sophie.vercel.app


## 機能一覧

### 認証
- ユーザー登録
- ログイン
- ログアウト

### 学習機能
- 単語一覧表示
- 単語詳細表示
- 文章入力
- AI添削
- 添削結果の保存
- 学習履歴一覧
- 学習履歴編集

### マイページ
- 添削履歴確認

## 使用技術
- フロントエンド：Next.js
- バックエンド：Next.js
- データベース：Supabase
- AI：Gemini API
- デプロイ：Vercel
- バージョン管理：Git、GitHub
- テスト・デバッグ：DevTools
- CI/CD：GitHub Actions（ESLint）


## 設計ドキュメント
[要件定義・基本設計・詳細設計の一覧_Googleスプレッドシート](https://docs.google.com/spreadsheets/d/1CoT2IGuHdD216YW1eHGiQw6s_OzVstxDH-4IYs_Krp4/edit?usp=sharing)

詳細設計時のワイヤーフレーム、ER図、ワークフロー図の画像はdocsディレクトリに格納しています。（[こちらからアクセス](./docs)）

## 備考
[ESLintの実行結果_GitHub Actions](https://github.com/sophie0938/japanese-learning-app/actions/runs/29651529401/job/88098566384)

- 活用した生成AIとその用途
  - ChatGPT：要件定義、設計、各種リサーチ
  - v0：アプリのモック作成
  - GitHub Copilot Chat：ローカル環境でのコードの修正相談

