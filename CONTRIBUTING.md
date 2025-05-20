# Contributing to Koke Design / 貢献ガイド

*Thank you for considering a contribution!*  
*貢献をご検討くださりありがとうございます！*

---

## Table of Contents / 目次
1. [Ways to Contribute / 貢献方法](#ways-to-contribute--貢献方法)  
2. [Ground Rules / 基本ルール](#ground-rules--基本ルール)  
3. [Development Setup / 開発環境の準備](#development-setup--開発環境の準備)  
4. [Branch & Commit Conventions / ブランチとコミット規約](#branch--commit-conventions--ブランチとコミット規約)  
5. [Pull-Request Checklist / PR チェックリスト](#pull-request-checklist--pr-チェックリスト)  
6. [Reporting Security Issues / セキュリティ報告](#reporting-security-issues--セキュリティ報告)  
7. [License / ライセンス](#license--ライセンス)

---

## Ways to Contribute / 貢献方法

| Type / 種類                        | How / 方法                                      | Effort / 目安 |
|------------------------------------|------------------------------------------------|---------------|
| **Bug Report / バグ報告**          | Open an Issue                                  | ★☆☆           |
| **Feature Idea / 機能提案**        | Discuss in an Issue first                      | ★★☆           |
| **Pull Request / プルリク**        | Fork → Branch → Code → PR                    | ★★★           |
| **Design Example / デザイン例追加**| Add templates under `examples/`                | ★★☆           |
| **Docs / ドキュメント改善**        | Update `.md` files or translations             | ★☆☆           |

---

## Ground Rules / 基本ルール

- Be respectful and inclusive — see **[Code of Conduct](CODE_OF_CONDUCT.md)**.  
  *敬意と包摂性を忘れずに — 行動規範を参照してください。*

- Before coding, open an Issue to agree on the approach.  
  *実装前に Issue で方向性を共有してください。*

---

## Development Setup / 開発環境の準備

```bash
# prerequisites / 事前条件
node --version   # ≥ 20.x
npm  --version   # ≥ 10.x

# clone & install / クローンして依存関係を取得
git clone https://github.com/koke-design/koke-design.git
cd koke-design
npm install
```

Run linters & tests before committing  
コミット前にリンターとテストを実行してください

```bash
npm run lint
npm test
```

---

## Branch & Commit Conventions / ブランチとコミット規約

- **Branch names / ブランチ名**  
  `feature/short-title`, `fix/bug-description`, `docs/update-readme`, …

- **Commit style / コミットスタイル** — follow [Conventional Commits](https://www.conventionalcommits.org/)  
  - `feat: add new color palette`  
  - `fix: correct typo in guidelines`

---

## Pull-Request Checklist / PR チェックリスト

- [ ] Linked to an Issue (e.g., `Closes #123`). / 対応 Issue をリンクしましたか？  
- [ ] Lint passes. / Lint が通っていますか？  
- [ ] Tests pass. / テストに失敗していませんか？  
- [ ] Description explains **why** & **what**. / 変更理由と内容を説明しましたか？  
- [ ] No unresolved TODOs. / TODO が残っていませんか？  

---

## Reporting Security Issues / セキュリティ報告

Please **open a new Issue with the `security` label** and **do not include exploit details in the description**.  
脆弱性を報告する際は、**`security` ラベルを付けた新規 Issue** を作成し、具体的な再現手順やコードは記載しないでください。  
A maintainer will contact you privately within **72 hours** to coordinate a fix.  
メンテナが **72 時間以内** に個別連絡し、修正を進めます。

---

## License / ライセンス

By contributing you agree your work will be released under the project’s **MIT License**.  
貢献内容はプロジェクトの **MIT ライセンス** で公開されることに同意したものとみなされます。
