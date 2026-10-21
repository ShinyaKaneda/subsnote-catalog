# subsnote-catalog
サブスク手帳（SubsNote）のカタログ配信用。`catalog.json` と `icons/` を GitHub Pages で配信します。
アプリは起動時（6 時間に 1 回）と設定の「今すぐ更新を確認」で `catalog.json` の `version` を比較し、大きければ取り込みます。
