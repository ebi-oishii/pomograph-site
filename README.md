# Pomograph site

名刺道・national-team-siteと同じ、GitHub Pagesの標準Jekyll構成。
公開先：<https://ebi-oishii.github.io/pomograph-site/>

PagesのSourceは「Deploy from a branch」、main / root。追加依存・独自Actions・DNS設定なし。
公開リポジトリのGitHub Pages無料枠を使用する。公開URLはアプリ内のリンクにも含まれるため維持する。

## ストア登録URL

- プライバシー：<https://ebi-oishii.github.io/pomograph-site/privacy/>
- サポート：<https://ebi-oishii.github.io/pomograph-site/support/>
- マーケティング：<https://ebi-oishii.github.io/pomograph-site/>
- 利用規約：<https://ebi-oishii.github.io/pomograph-site/terms/>

app-ads.txtはこのプロジェクトのサブパスではなく、ホスト直下の
<https://ebi-oishii.github.io/app-ads.txt>をGoogleが参照する。既存ファイルに同じパブリッシャーIDがあることを確認済み。他アプリ・ホスト直下のリポジトリは変更していない。

## 更新

- データの取扱いが変わったときはprivacy.mdの実装との一致を確認し、日付を更新する。
- assets/licenses.txtはアプリ側のscripts/generate-licenses.mjsで生成したpublic/licenses.txtのコピー。依存更新時に再生成してコピーする。
- アプリのライセンス閲覧・法務リンクは別リポジトリの更新を含むため、サイト公開だけで配布済みアプリが更新されるわけではない。
- Androidは今回のライセンス収録・公開確認の対象外。Android公開前にネイティブ依存の表記を追加する。
