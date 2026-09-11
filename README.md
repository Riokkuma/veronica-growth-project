# Veronica 美容アカウント 成長＆運用体制構築プロジェクト

美容情報発信アカウント（[@Veronica_kuma](https://x.com/Veronica_kuma)）の継続可能な運用体制を構築し、半年間でフォロワー1,000人を目指すプロジェクトです。

---

## 1. プロジェクトの目的と概要
- **対象アカウント**: Veronica ヴェロニカ（[@Veronica_kuma](https://x.com/Veronica_kuma)）
- **ゴール**: 半年間でフォロワー1,000人達成 ＆ 学業と両立できる自走型運用体制の確立
- **現状ベースライン**: フォロワー515人 / フォロー1,132人（2026年9月時点）
- **プロジェクトオーナー**: リオックマ（Veronica）

---

## 2. ディレクトリ構成と各ファイルの役割

```text
veronica-growth-project/
├── README.md                     # 本ファイル（プロジェクト全体の総合案内）
├── CLAUDE.md                     # Claude Codeが守るべき行動規範・作業ルール
├── PROJECT_CHARTER.md            # プロジェクト憲章（目的、ゴール、スコープ、体制）
├── CURRENT_ANALYSIS_REQUEST.md   # 現状分析の依頼指示書（Claude Codeへのタスク定義）
├── CURRENT_ANALYSIS.md           # [今後出力] 現状分析レポート
├── REQUIREMENTS.md               # [今後作成] 運用支援ツールの要件定義
├── WBS.md                        # [今後作成] 作業計画・スケジュール
├── CONTENT_PLAN.md               # [今後作成] コンテンツ運用設計・投稿テンプレート
├── KPI_TRACKING.md               # [今後作成] 指標計測・進捗管理シート
├── RISKS.md                      # [今後作成] リスク管理表
├── DECISIONS.md                  # [今後作成] PM意思決定ログ
└── data/
    └── x_metrics.csv             # 過去の投稿実績データ（23件）
```

---

## 3. 現在地と今後のロードマップ

現在、**フェーズ1（現状分析フェーズ）**の準備が整った段階です。

| フェーズ | 内容 | 状態 | 主な成果物 |
| :--- | :--- | :--- | :--- |
| **Phase 1** | **前提整理と現状分析** | **進行中（依頼準備完了）** | `CLAUDE.md`, `PROJECT_CHARTER.md`, `x_metrics.csv`, `CURRENT_ANALYSIS_REQUEST.md` |
| **Phase 2** | **分析結果の確認と施策立案** | 未着手 | `CURRENT_ANALYSIS.md` の確認、成長仮説の採択 |
| **Phase 3** | **要件定義と計画策定** | 未着手 | `REQUIREMENTS.md`, `WBS.md`, `CONTENT_PLAN.md` |
| **Phase 4** | **運用支援ツールの実装・運用開始** | 未着手 | 下書き支援・KPI管理ツールの開発、週2回投稿運用 |

---

## 4. 指導教員・Claude Codeへの依頼手順

先生にプロジェクトフォルダを共有し、Claude Codeへ以下のように依頼していただくことを想定しています。

### 依頼コマンド例（Claude Code向け）
```bash
# プロジェクトフォルダを開いた状態で
claude "CURRENT_ANALYSIS_REQUEST.md の指示に従って、data/x_metrics.csv などのデータを詳細に分析し、結果を CURRENT_ANALYSIS.md に出力してください。"
```

### 先生への伝達メッセージ例
> 美容アカウントの半年間の運用改善プロジェクトを進めています。
> いきなり制作やツール開発に入るのではなく、PMとしてまずは実績データの現状分析から行いたいと考えています。
> プロジェクトの目的やルール（CLAUDE.md、PROJECT_CHARTER.md）と、過去の投稿実績（data/x_metrics.csv）をまとめました。
> お手すきの際にClaude Codeで CURRENT_ANALYSIS_REQUEST.md を実行していただき、分析レポート（CURRENT_ANALYSIS.md）を出力していただけますと幸いです！
