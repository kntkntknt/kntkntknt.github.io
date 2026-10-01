# tag.newdrop.com

iOSアプリ「ストック」のUniversal Link用の設定ファイルだけを置く場所。人が見るページは無い。

- `.well-known/apple-app-site-association` タグのURL `https://tag.newdrop.com/t/<ID>` をアプリに結びつける
- `.nojekyll` これが無いとGitHub Pagesが `.well-known` を公開しない
- `CNAME` 独自ドメインの指定

消すと、新しくアプリを入れたiPhoneでタグが反応しなくなる。
