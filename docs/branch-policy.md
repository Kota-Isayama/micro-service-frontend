# branch policy
このプロジェクトでは，"GitHub Flow"を採用する．GitHub Flowの詳細については[この記事](https://qiita.com/onishi_820/items/d98c61e0faa67f417829)を参照されたい．

## mainブランチへのコミット方法
本プロジェクトでは，mainブランチへのフォースプッシュを行うことをGitHubの`branch protection`機能を用いて禁止している．新機能開発等を行ったブランチの変更をmainブランチへ反映させたい場合は，GitHubのGUI上からmainブランチへのPull Requestを発行し，そのマージをもってmainブランチへコミットする．ただし，マージにあたっては，全メンバー（今は2人なのでお互い）からのコードレビューおよび承認を必要とする．

## branch　命名規則
GitHub Flowに従い，作業用ブランチを適宜mainブランチから切って開発を行う．この作業用ブランチ名は以下のパターンに従って命名することとする．
```
feature/<feature-name>
```
上記の`<feature-name>`に，開発する機能名（や作業を表す言葉）が入る．
