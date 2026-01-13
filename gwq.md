## worktree作成
|コマンド|操作|
|---|---|
| gwq add \<branch\>  | 既存ブランチからworktree作成 |
| gwq add -b \<branch\> | 新規ブランチを作成してworktree作成 |
| gwq add -i | インタラクティブに選択 |

## worktree一覧
|コマンド|操作|
|---|---|
| gwq list   | 一覧表示 |
| gwq status [--csv] | ステータス付きで一覧表示 |

## worktree削除
|コマンド|操作|
|---|---|
| gwq remove   | インタラクティブに削除 |
| gwq remove \<branch\> | 指定ブランチのworktree削除 |

## worktreeでコマンド実行
|コマンド|操作|
|---|---|
| gwq exec \<branch\> -- \<command\>  | 指定worktreeでコマンド実行 |
