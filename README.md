# Rust & Claude3

RustでClaude3のAPIをコールするためのサンプルコードです。

[Zenn:Rustの勉強ついでにClaude3のAPIを呼び出してみた](https://zenn.dev/ttks/articles/6e6f35a8def9a6)の記事で解説しています。

## 使い方

### 1. クローン

```bash
git clone <this repository>
```

### 2. 環境変数の設定

`.env.sample`をコピーして`.env`を作成し、Claude3のAPIキーを設定してください。

※詳細はZennの記事を参照してください。

```bash
cp .env.sample .env
```

### 3. 実行

```bash
cargo run
```