# Git研修
## 1. Discord記載の動画でハンズオン

## 2. Git&GitHubが正しく使えるかの確認
1. このレポジトリをクローンする. 
```bash
git clone https://github.com/vol4-Team22/git-training.git
```
2. 新しいブランチを作成します。ブランチ名は仮に `my-branch` とします（**適切な名前に変更してください**）。

3. `test/test.md`([こちら](./test/test.md))のファイルをVSCodeやその他IDEから編集する。
編集内容は以下の通りで、空いている箇所のうち一箇所に自分の名前を書く。
```markdown
### テスト確認
- 荻原
- (ここに自分の名前を書く)
- (ここに自分の名前を書く)
- (ここに自分の名前を書く)
- (ここに自分の名前を書く)
```

4. ステージング環境へあげる
```bash
git add ./test/test.md
```

5. コミット
```bash
git commit -m "コミットメッセージ(何を変更したか適宜考える)"
```
6. リモートへプッシュ
今回は2でブランチ名を`my-branch`としたのでこの部分は適宜変更すること
```bash
git push origin my-branch
```
7. Pull Requestを出す
**GitHub上で**レポジトリのページから`master`ブランチへPull Requestをだす。
8. 荻原をDiscordでメンション