# kntkntknt.github.io

iOSアプリ「ストック」のUniversal Link用の設定ファイルを置く場所。人が見るページは無い。

- `.well-known/apple-app-site-association` タグのURL `https://kntkntknt.github.io/t/<ID>` をアプリに結びつける
- `.nojekyll` これが無いとGitHub Pagesが `.well-known` を公開しない

消すと、新しくアプリを入れたiPhoneでタグが反応しなくなる。
このリポジトリ名を変えると、書き込み済みのタグが全部使えなくなる。
