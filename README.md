# kntkntknt.github.io

iOSアプリ「ストック」のUniversal Link用の設定ファイルと、人が見るページ2つを置く場所。

- `privacy/` プライバシーポリシー(App Store の提出に必須。アプリの「家族」の画面からも開く)
- `404.html` シールのURL(`/t/<ID>`)でアプリが開かなかったときの逃げ道。アプリで開くボタンを出す

- `.well-known/apple-app-site-association` タグのURL `https://kntkntknt.github.io/t/<ID>` をアプリに結びつける
- `.nojekyll` これが無いとGitHub Pagesが `.well-known` を公開しない

消すと、新しくアプリを入れたiPhoneでタグが反応しなくなる。
このリポジトリ名を変えると、書き込み済みのタグが全部使えなくなる。
