# issue-practice-sandbox

プラグイン issue-practice (https://github.com/akm/claude-plugins/tree/main/issue-practice) のスキルの手順を、本物の GitHub で確認するためのリポジトリ。

## 確認の手順

スキルの手順は、次の順に確認する。

1. 確認したい単位ごとに、管理 Issue を 1 つ作る。管理 Issue には、この README に節を足すなどの小さな要望と、作業 Issue を 2 つ程度置く。
2. 管理セッションがスキル issue-practice:managing-issue-plan で計画案を作り、利用者の承認を得てから作業 Issue を作る。続けてスキル issue-practice:managing-issue-run で作業セッションを起動する。
3. 作業セッションがスキル issue-practice:working-issue で作業 Issue を受け持ち、ブランチを作って README.md だけを変え、PR を作る。
4. 作業セッションは、クローズ条件の項目ごとに根拠のコメントを作業 Issue に書いてからチェックを入れ、管理セッションに報告する。
5. 管理セッションが PR をマージし、スキル issue-practice:managing-issue-close で作業 Issue と管理 Issue を閉じる。

手順書と実際の振る舞いが合わないところを見つけたら、作業 Issue にはコメントを書かず、確認を進めているセッションに知らせる。

## 確認の記録

確認の結果は、このリポジトリの作業 Issue のコメントに記録する。

- クローズ条件の項目ごとの確認の結果は、その作業 Issue のコメントに書く。チェックを入れるときは、そのコメントの URL を根拠のリンクにする。
- 作業セッションから管理セッションへの報告 (PR を作った・チェックを入れたなど) は、作業 Issue の記録のコメント (1 行目が `issue-practice:` で始まるコメント) に書く。

手順書と実際の振る舞いが合わないところは、このリポジトリには記録しない (節「確認の手順」の最後の段落を参照)。
