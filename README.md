# Spanish Verbs GitHub Pages Tables

Grupo Moreral『6つのモードでつかむスペイン語の動詞』の授業プリント用Web資料です。

## 構成

- `index.html`：資料入口ページ
- `tables/index.html`：基本動詞の活用表
- `assets/style.css`：表示・印刷用CSS

## GitHub Pagesで公開する手順

1. GitHubで新しいリポジトリを作る。例：`spanish-verbs`
2. このフォルダ内のファイルをリポジトリ直下にアップロードする。
3. GitHubの `Settings` → `Pages` を開く。
4. `Build and deployment` で `Deploy from a branch` を選ぶ。
5. `Branch` は `main`、フォルダは `/root` を選ぶ。
6. 数分後に公開URLが表示される。

想定URLは次の形です。

- 入口：`https://<GitHubユーザー名>.github.io/spanish-verbs/`
- 活用表：`https://<GitHubユーザー名>.github.io/spanish-verbs/tables/`

プリントに入れるQRコードは、原則として入口URLに対して作成するのが安全です。活用表だけを直接見せたい場合は、`/tables/` のURLを使います。
