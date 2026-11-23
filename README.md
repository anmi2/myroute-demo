# マイルート 独立Webデモ

NextGuess本体、Laravel API、HEXデモに依存しない静的Webデモです。

## GitHub Pages

1. 新規公開リポジトリ `myroute-demo` のルートに `index.html` と `.nojekyll` を配置。
2. Settings → Pages → Build and deployment → Deploy from a branch → `main` / `/(root)` → Save。
3. `https://anmi2.github.io/myroute-demo/` にアクセス。

## データについて

仮イベントと勤務設定を使用します。登録データは閲覧中のブラウザのlocalStorageに保存され、他の端末や班長の端末とは共有されません。ブラウザのデータ削除で消える場合があります。個人情報・実際の営業記録は入力しないでください。

## バージョン

v0.2（基本設定で出庫・帰庫時刻を保持し、営業実績では営業時間を編集）
