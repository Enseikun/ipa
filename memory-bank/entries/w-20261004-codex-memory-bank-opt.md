# Codex向けMemory Bank運用の最適化
- id: w-20261004-codex-memory-bank-opt
- tags: memory-bank,codex,setup
- updated: 2026/10/04 20:08

## 要点
`AGENTS.md` は毎回必要な読み取りルーティングと基本規則に絞った。
詳細な更新書式、行数制限、監査手順は `memory-bank/OPERATIONS.md` に分離し、
Memory Bankの更新・監査時だけ読む方式へ変更した。
同一セッションでは未変更の既読ファイルを再読しない規則も追加した。

## 根拠
常時注入される指示と毎タスクの再読量を減らしつつ、従来のインデックス方式と
更新規約を維持するため。関連ファイルは `AGENTS.md` と `memory-bank/OPERATIONS.md`。
