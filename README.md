# nanami-threads-images

七海（@nanami_all_ai / @nanami_ALL_AI）のThreads/X投稿用画像アセット置き場。

`threads-poster`（自動投稿パイプライン、private repo）の各投稿から、この公開リポジトリの `posts/<日付>_<slug>.png` を
raw.githubusercontent.com 経由で参照する（Threads/X APIが画像URLとして直接fetchできる公開先が必要なため）。

生成は `afi` リポジトリの `tools/post-image/`（HTML→PNG）を使用。数値は実測値と同期する（brand-safety-check対象）。
