# stop-describing-ui

## コミットメッセージ

このリポジトリでは、github スキルの日本語の規約に代えて次の形式を使う。

- 形式は `type(scope): description`。モノレポではないが scope は常に付ける。
- description は英語で、端的に、すべて小文字で書く。動詞の原形から始める。
- scope は変更したトップレベルディレクトリ名。リポジトリ全体に関わる変更は `repo`。
- PR のタイトルも同じ形式にする。

```
OK: feat(src): add describe toggle
OK: chore(repo): add editorconfig
NG: feat: Describeトグルを追加
NG: Feat(src): Add describe toggle.
```

type や scope の選び方、その他の Git の運用は github スキルに従う。
