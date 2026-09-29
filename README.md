# claude-skills

再利用する Claude Code のスキルを集めたリポジトリです。

## スキル

| スキル | 内容 |
|---|---|
| [ai-smell-japanese](./skills/ai-smell-japanese/SKILL.md) | AI くさい日本語（対比や否定から入る、抽象語や比喩で曖昧、対句で印象を作る）を検出して、具体的な文に直す |

## 使い方

個人用のスキルとして、使う場所に置く。

```bash
# 全プロジェクトで使う
ln -s "$(pwd)/skills/ai-smell-japanese" ~/.claude/skills/ai-smell-japanese

# 1 つのプロジェクトだけで使う
ln -s "$(pwd)/skills/ai-smell-japanese" <プロジェクト>/.claude/skills/ai-smell-japanese
```

置いたあと、Claude Code で `/ai-smell-japanese` と入力するか、日本語の文章の推敲を頼む。

## 出典とライセンス

`ai-smell-japanese` は、Kiminori Yokoi（@nasuvitz）氏のスライド「AI臭い文章とは何なのか」を、運用の形に整理したものです。スライドの作者は、教育用途での利用を案内しています。元の内容の権利は作者にあります。

- https://speakerdeck.com/nasuvitz/ai-kusai-bunshou-toha-nanina-no-ka

このリポジトリを公開する場合や、再配布する場合は、作者に確認してください。ライセンスは、確認が済むまで付けていません。
