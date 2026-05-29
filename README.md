📕 Java CRM ポートフォリオ README（Spring Boot + React 日本語）

概要

Spring Boot をバックエンド、React（SPA）をフロントエンドとしたフルスタック CRM デモプロジェクトです。職務経歴書の補足資料として活用できます。

🚀 主な機能

🛡️ Spring Security による JWT 認証

📇 顧客管理用の REST API

⚛️ React 18 + Vite による SPA 構成

🐳 Docker によるフルスタック開発環境

🗂️ Maven（または Gradle）対応

🛠️ 技術スタック

層

技術構成

バックエンド

Java 17, Spring Boot, Spring Sec

フロントエンド

React 18, Vite, Axios

データベース

PostgreSQL

コンテナ

Docker, Docker Compose

認証

JWT

📂 ディレクトリ構成（概要）

portfolio-java-crm/
├── backend/
│   └── src/main/java/com/example/crm/
│       ├── controller/
│       ├── service/
│       ├── model/
│       └── security/
│   └── pom.xml
├── frontend/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── App.tsx
│       └── main.tsx
├── docker-compose.yml
└── README.md

⚙️ 起動方法

git clone https://github.com/techpage383/portfolio-java-crm
cd portfolio-java-crm
docker-compose up --build

フロントエンド: http://localhost:3000

バックエンド: http://localhost:8080

API ドキュメント: http://localhost:8080/swagger-ui/index.html

📃 ライセンス

MIT License

🙋 作者

GitHub: tnohara48
