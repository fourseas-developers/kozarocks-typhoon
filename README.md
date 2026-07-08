# KOZAROCKS 2026 台風情報ページ

台風9号（2026年）接近に伴う KOZAROCKS 2026 向けの自動更新ページ。

- 公開URL: https://fourseas-developers.github.io/kozarocks-typhoon/
- 生成元: `claude_agent` リポジトリの `kozarocks/scripts/typhoon_fetch.py` / `typhoon_render.py`
- 更新: ローカルscheduled-task `kozarocks-typhoon-watch` が30分おき（6:00〜23:30 JST）に監視し、変化時にpush
- 設計書: claude_agent リポジトリ `docs/superpowers/specs/2026-07-08-typhoon-watch-design.md`
- データ出典: 気象庁 台風情報・気象警報等（bosai JSON API）

このリポジトリへの手動コミットは自動更新と競合するため避けてください。
