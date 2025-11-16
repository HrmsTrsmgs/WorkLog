# Worklog

横断の作業記録・決定事項・Clockify公開CSVの保管庫。

- 週次: `/WORKLOG/`
- 決定: `/DECISIONS/`
- データ: `/docs/clockify/`（匿名化CSV）
- ライセンス:
  - `/LICENSE`（コード）= Apache-2.0
  - `/LICENSE-DOCS.md`（文書）= CC BY 4.0
  - `/LICENSE-DATA.md`（データ）= CC0 1.0
## ApplicationTemplate — テンプレ作成開始（2025-11-16）

- 初版設計メモを追加：`docs/solution-template-outline.md`
- 空ソリューション／プロジェクト雛形の生成スクリプトを追加：
  - PowerShell: `scripts/new-template.ps1`
  - Bash: `scripts/new-template.sh`
- 方針：骨格は人手で固定、AI は部品生成・修正のみ（自動全生成は行わない）