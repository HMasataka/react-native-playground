# React Native Playground

React Native (Expo) + NativeWindを使ったプロジェクト

## プロジェクト作成手順

このプロジェクトを新規作成する場合のコマンド：

```bash
# Expoプロジェクトの作成
npx rn-new@latest react-native-playground --nativewind

# NativeWindのインストール
npm install nativewind react-native-reanimated@~3.17.4 react-native-safe-area-context@5.4.0
npm install --dev tailwindcss@^3.4.17 prettier-plugin-tailwindcss@^0.5.11
```

## 環境構築

### セットアップコマンド

```bash
# 依存関係のインストール
npm install

# または
npm ci

# 開発サーバーの起動
npm start

# プラットフォーム別の起動
npm run ios      # iOSシミュレーター
npm run android  # Androidエミュレーター
npm run web      # Webブラウザー

# コード品質チェック
npm run lint     # ESLintとPrettierのチェック
npm run format   # コードの自動フォーマット

# プリビルド（必要に応じて）
npm run prebuild
```
