# japan-nomad-tax-db
日本デジタルノマドビザ対応・多国籍税制DB + AI収入判定エンジン（2026年5月版）

# 日本デジタルノマドビザ 税制DBモジュール

多国籍収入明細をAIで瞬時判定 → 税後年収1,000万円以上を自動チェック

## ✨ 機能
- 49カ国税制DB（月次自動更新）
- OpenAI Vision + Claude対応収入明細解析
- AWS ECS Fargate 本番デプロイ済み
- Audit Log（入管提出用ハッシュ署名）

## 🚀 クイックスタート
```bash
docker-compose up -d --build
# → http://localhost:8000/docs
