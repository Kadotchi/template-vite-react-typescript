# Vite + React + TypeScript + Prettier + ESLint + Tailwind CSS Template

このリポジトリは、Vite、React、TypeScript、Prettier、ESLint、Tailwind CSSを使用した最小設定のテンプレートプロジェクトです。迅速にフロントエンドプロジェクトを開始するためのベースとして使用できます。

## プロジェクトのセットアップ

### 必要要件

- Node.js (バージョン 20.12.2)
- npm

### インストール

1. リポジトリをクローンします。

```bash
git clone https://github.com/your-username/vite-react-ts-tailwind-template.git
cd vite-react-ts-tailwind-template
```

2. 依存関係をインストールします。

```bash
npm install
```

3. 開発サーバーの起動  
   開発サーバーを起動して、プロジェクトをローカルで実行します。

```bash
npm run dev
```

### ビルド

プロジェクトを本番環境向けにビルドします。

```bash
npm run build
```

### プロジェクトの構成

- src/: ソースコードディレクトリ
  - components/: Reactコンポーネント
  - styles/: Tailwind CSSを使用したスタイルシート
  - App.tsx: アプリケーションのエントリーポイント
- public/: 静的ファイル
- index.html: エントリーポイントのHTMLファイル

### プリティエとESLintの使用

コードをフォーマットするためにPrettier、コード品質をチェックするためにESLintを使用しています。

コードをフォーマットするには、以下のコマンドを実行します。

```bash
npm run format
```

ESLintでコードをチェックするには、以下のコマンドを実行します。

```bash
npm run lint
```

ESLintでコードの問題を自動修正するには、以下のコマンドを実行します。

```bash
npm run lint:fix
```

### Tailwind CSSの設定

Tailwind CSSの設定はtailwind.config.jsファイルで行います。必要に応じてカスタマイズしてください。

### 使用されている主要なパッケージのバージョン

- Node.js: 20.12.2
- React: ^18.2.0
- @eslint/js: ^9.2.0
- Prettier: ^3.2.5
- TypeScript: ^5.2.2
- vite-tsconfig-paths: ^4.3.2
