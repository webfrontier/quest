# 🏰 Git/GitHub冒険者ギルド

GitとGitHubの知識を深め、バージョン管理の達人を目指そう！

本ガイドでは、あなたのスキルレベルに応じたペルソナを設定し、それぞれの冒険を支援する。

## 🌟 冒険者ランク一覧

| 🏅 ランク | 🛡️ 新米コード守護者 | ⚔️ 戦術的コード指揮官 | 🔮 伝説のリポジトリ管理者 |
|------|--------------|---------------|--------------|
| 📅 冒険歴 | 0-1年程度 | 1-3年程度 | 3年以上 |
| ⌨️ Git/GitHub経験 | 数ヶ月未満 | 6ヶ月〜2年程度 | 2年以上 |
| 🗺️ 探索範囲 | 個人プロジェクト中心 | チーム開発の実践 | 大規模開発とワークフロー設計 |
| 📜 バージョン管理スキル | コミット＆プッシュで精一杯 | ブランチ戦略を活用 | CI/CDや自動化でワークフロー最適化 |
| 🔍 扱えるリポジトリの規模 | 小規模プロジェクト | チームコラボ型リポジトリ | 組織規模のリポジトリ管理 |

## 🛡️ 新米コード守護者のプロフィール

| 項目 | 詳細 |
|------|------|
| **📋 所属ギルド** | 🧑‍💼 GitとGitHubを学び始めた初心者 |
| **🧙‍♂️ 習得したスキル** | ✅ `git init`, `git clone`, `git add`, `git commit` などの基本コマンド<br>✅ リモートリポジトリの作成と管理<br>✅ GitHubのWeb UIでの操作 |
| **😅 よくある失敗談** | ❌ `git status` を見ずにコミットしてしまう<br>❌ `git push` した後に間違いに気づく<br>❌ リモートリポジトリの設定ミス |
| **💪 特殊能力** | 🌱 新しい技術への柔軟な適応力<br>📚 Gitの基本ワークフローを学ぶ意欲 |
| **🛠️ 装備品** | 🖥️ VSCode / Git Bash / Terminal<br>📦 GitHubの基本操作 |
| **🏆 達成クエスト例** | 📝 個人プロジェクトのバージョン管理<br>📂 リポジトリの作成と初期設定 |
| **🌠 冒険者の野望** | 🏁 チーム開発に参加するための基礎を固める |

## ⚔️ 戦術的コード指揮官のプロフィール

| 項目 | 詳細 |
|------|------|
| **📋 所属ギルド** | 👨‍💻 チーム開発の実践経験を持つ中級者 |
| **🧙‍♂️ 習得したスキル** | ✅ `git branch`, `git merge`, `git rebase` を活用したブランチ管理<br>✅ `git stash`, `git reset`, `git revert` での変更管理<br>✅ GitHubのプルリクエストとコードレビュー |
| **😅 よくある失敗談** | ❌ `git merge` のコンフリクトでパニックになる<br>❌ `git rebase` で履歴を壊す<br>❌ `git pull --rebase` の挙動を理解せずに実行 |
| **💪 特殊能力** | 🔄 コードの変更履歴を正しく管理するスキル |
| **🛠️ 装備品** | 🛠️ GitHubのIssueやProjects機能 |
| **🏆 達成クエスト例** | 📊 PRベースの開発フローに参加し、レビューを行う |
| **🌠 冒険者の野望** | 🔥 より高度なGitの活用（Cherry-pickやSubmodule管理） |

## 🔮 伝説のリポジトリ管理者のプロフィール

| 項目 | 詳細 |
|------|------|
| **📋 所属ギルド** | 🧙‍♂️ 大規模リポジトリ管理のエキスパート |
| **🧙‍♂️ 習得したスキル** | ✅ `git bisect` でバグの特定<br>✅ GitHub Actionsを活用したCI/CD構築<br>✅ `git submodule`, `git worktree` の活用 |
| **😅 よくある失敗談** | ❌ `git reset --hard` で大事な変更を失う<br>❌ CI/CDの設定ミスでデプロイが失敗 |
| **💪 特殊能力** | 🧠 Git/GitHubのワークフロー最適化 |
| **🛠️ 装備品** | 📂 モノレポ管理の知識 |
| **🏆 達成クエスト例** | 🏢 CI/CDパイプラインを導入し開発を効率化 |
| **🌠 冒険者の野望** | 🌍 Git/GitHubの戦略設計を行い、開発文化を変革 |

## 🔥 各レベルの冒険者が書く魔法の違い

### 🛡️ 新米コード守護者の魔法書
```bash
# 基本的な呪文
git init                       # 新しい魔法の書を作成
git clone <URL>                # 遠くの魔法書を複製
git add .                      # 全ての変更を魔法陣に配置
git commit -m "魔法の記録"      # 変更を魔法の書に記録
git push origin main          # 魔法の書を本部に送信
git pull origin main          # 本部から最新の魔法を取得
```

### ⚔️ 戦術的コード指揮官の魔法書
```bash
# 戦術的な呪文
git branch feature/新機能       # 新しい魔法の分岐を作成
git checkout -b bugfix/修正    # 修正用の分岐を作成して移動
git merge feature/新機能        # 魔法の分岐を統合
git rebase main               # 魔法の歴史を整理
git stash                     # 作業中の魔法を一時保管
git stash pop                 # 保管した魔法を取り出す
git reset --soft HEAD~1       # 直前の魔法を解除（変更は保持）
git revert HEAD               # 魔法を打ち消す新たな魔法を作成
```

### 🔮 伝説のリポジトリ管理者の魔法書
```bash
# 高度な呪文
git bisect start              # バグ探しの二分探索を開始
git bisect good <commit>      # この魔法は正常と記録
git bisect bad <commit>       # この魔法に問題ありと記録
git cherry-pick <commit>      # 特定の魔法だけを取り込む
git submodule add <URL>       # 従属魔法書を追加
git filter-branch            # 魔法の歴史を書き換える強力な呪文
git reflog                   # 失われた魔法の履歴を参照
git worktree add <path>      # 並行作業のための魔法の分身を作成
```

## 🚀 冒険者のレベルアップ攻略法

### 🛡️ 新米コード守護者 → ⚔️ 戦術的コード指揮官へ
1. **ブランチ戦略の習得**：feature、bugfix、releaseなど目的別のブランチを使い分ける
2. **コンフリクト解決の練習**：意図的に同じファイルを編集し、マージ時のコンフリクト解決を繰り返す
3. **GitHubフロー体験**：個人プロジェクトでもPRを作成し、セルフレビューする習慣をつける
4. **チーム開発への参加**：オープンソースプロジェクトにコントリビュートし、実践的な経験を積む
5. **Git履歴の整理**：rebaseやsquashを用いて、履歴を美しく保つ技術を身につける

### ⚔️ 戦術的コード指揮官 → 🔮 伝説のリポジトリ管理者へ
1. **CI/CDの導入**：GitHub Actionsを使って自動テスト・デプロイ環境を構築する
2. **バージョン戦略の確立**：セマンティックバージョニングやGitFlowなどの戦略を実装する
3. **コードレビュー文化の醸成**：PRテンプレートやレビューガイドラインを整備する
4. **モノレポ管理の習得**：複数プロジェクトを効率的に管理する技術を身につける
5. **Git操作の自動化**：エイリアスやGitHook、カスタムスクリプトで効率化を図る

## 🏛️ 冒険者訓練所からの秘伝

### 🛡️ 新米コード守護者への秘伝
- **小さくコミットする習慣**：一度に大きな変更をするのではなく、小さな機能や修正ごとにコミットしよう
- **コミットメッセージの型**：「動詞(変更・削除など) + 何を(対象) + なぜ(理由や意図)」の形式で書くと、履歴が読みやすくなる
- **git statusの習慣化**：コミット前には必ずgit statusで変更内容を確認しよう
- **エイリアスの活用**：頻繁に使うコマンドには短いエイリアスを設定して効率化しよう
- **GitHubの練習場**：初心者向けの「Hello World」リポジトリを作成し、安全に実験できる環境を用意しよう

### ⚔️ 戦術的コード指揮官への秘伝
- **インタラクティブリベース**：`git rebase -i HEAD~3`で直近3つのコミットを整理できる
- **部分的なステージング**：`git add -p`で変更を部分的にステージングし、関連する変更だけをコミットできる
- **ブランチ命名規則**：`feature/`, `bugfix/`, `hotfix/`など、目的に応じた接頭辞をつけると管理しやすい
- **PRサイズの最適化**：レビューしやすいよう、PRは300行以内に収めることを意識しよう
- **Git Hookの活用**：コミット前のリントチェックなど、品質管理を自動化しよう

### 🔮 伝説のリポジトリ管理者への秘伝
- **リポジトリ考古学**：`git blame`と`git log -p`を組み合わせて、コードの歴史と意図を掘り下げよう
- **高度なログ検索**：`git log --grep="キーワード" --author="名前"`などで特定の変更を素早く見つけよう
- **パッチ管理**：`git format-patch`と`git am`を使ってメールベースのワークフローも扱えるようになろう
- **リポジトリ最適化**：定期的に`git gc`や`git prune`を実行し、リポジトリのパフォーマンスを維持しよう
- **カスタムマージ戦略**：複雑なマージシナリオに対応するため、カスタムマージドライバーを設定しよう

## 📜 冒険者の図書館

### 🛡️ 新米コード守護者の本棚
- [Git公式ドキュメント](https://git-scm.com/doc)：基本コマンドと概念を学ぶ最も信頼できる資料
- [GitHub Skills](https://skills.github.com/)：ハンズオン形式でGitHubの使い方を学べる
- [Learn Git Branching](https://learngitbranching.js.org/)：視覚的にGitのブランチ操作を学べるインタラクティブツール
- [Atlassian Git チュートリアル](https://www.atlassian.com/git/tutorials)：わかりやすい解説と図解でGitの基本を学べる
- [Oh My Git!](https://ohmygit.org/)：ゲーム形式でGitを学べる楽しいツール

### ⚔️ 戦術的コード指揮官の本棚
- [Pro Git](https://git-scm.com/book/ja/v2)：Gitの内部構造まで深く理解できる無料の電子書籍
- [GitHub Flow](https://guides.github.com/introduction/flow/)：GitHub推奨の開発フローを学ぶ
- [Git Flow](https://nvie.com/posts/a-successful-git-branching-model/)：複雑なプロジェクト向けのブランチ戦略
- [GitHub Actions ドキュメント](https://docs.github.com/ja/actions)：CI/CDの自動化を学ぶ
- [Conventional Commits](https://www.conventionalcommits.org/ja/)：構造化されたコミットメッセージの書き方

### 🔮 伝説のリポジトリ管理者の本棚
- [Git Internals](https://git-scm.com/book/en/v2/Git-Internals-Plumbing-and-Porcelain)：Gitの内部構造を理解する
- [GitHub REST API](https://docs.github.com/ja/rest)：GitHubをプログラムから操作する方法
- [Trunk Based Development](https://trunkbaseddevelopment.com/)：トランクベース開発の戦略
- [Git Secret](https://git-secret.io/)：Gitでの安全な秘密情報管理
- [Git Large File Storage](https://git-lfs.github.com/)：大容量ファイルを効率的に管理する方法

## 📖 まとめ

- **新米コード守護者** → 基本を学び、Gitの基礎を固める
- **戦術的コード指揮官** → チームでの開発戦略を駆使し、ブランチ管理をマスター
- **伝説のリポジトリ管理者** → CI/CDと自動化を極め、組織の開発フローを最適化

🎉 **さあ、あなたもGit/GitHubの冒険へ旅立とう！** 🚀