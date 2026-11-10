# カットシート・スタジオ

動画からカットシートを作るWebアプリです。動画を読み込むとカットとディゾルブの終了位置を検出します。タイトルや音声メモを入力し、A4縦のPDFを保存できます。動画と入力内容はブラウザ内で処理します。

## 使い方

ブラウザで `index.html` を開き、動画を読み込んでください。カットの境目は再生位置から追加・削除できます。

## GitHub Pagesで公開

1. GitHubで配布用のリポジトリを作り、このフォルダのファイルを `main` ブランチの直下に置きます。`.nojekyll` も含めます。
2. リポジトリの **Settings → Pages** を開きます。
3. **Source** に **Deploy from a branch**、ブランチに **main**、フォルダに **/(root)** を選び、**Save** を押します。
4. 公開が完了すると、Pages設定に **Visit site** が表示されます。そのURLを共有できます。

以後は `main` の `index.html` を更新すると、GitHub Pagesが新しい版を公開します。

[GitHub Pagesの公開元を設定する公式手順](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
