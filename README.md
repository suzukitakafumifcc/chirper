# Chirper

[Laravel Bootcamp](https://bootcamp.laravel.com/)を実践します。

リポジトリの内容はチュートリアルで作成するマイクロブログ、Chirperです。

フロントエンドは、動的な[Livewire](https://livewire.laravel.com/)や
[Vue](https://vuejs.org/)・[React](https://react.dev/)の知識が必要な
[Inertia](https://inertiajs.com/)ではなく、
シンプルな[Blade](https://laravel.com/docs/11.x/blade)を選択します。

## 前提条件

- PHP >= 8.2
- Composer
- Node.js >= 16

データベースはデフォルトではSQLiteです。
MySQLやPostgreSQLに設定することも可能です。

## インストール

### 環境変数の設定

```bash
cp .env.example .env
```

### Composerパッケージのインストール

```bash
composer install
```

### Nodeパッケージのインストール

```bash
npm install
```

### アプリケーションキーの生成

```bash
php artisan key:generate
```

### データベースのマイグレーション

```bash
php artisan migrate
```

## 使い方

### 開発サーバーの起動

```bash
composer run dev
```

### テストの実行

```bash
php artisan test
```

## Contributing

プルリクエストは歓迎します。大きな変更については、まずIssueを開いて変更したい内容について話し合ってください。

必要に応じてテストを更新してください。

## License

[MIT](https://choosealicense.com/licenses/mit/)
