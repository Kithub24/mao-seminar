# dev/mao-seminar — 真央ゼミ Webサイト

真央ゼミの静的Webサイト。GitHub Pagesで公開されている。「わかばちゃんと学ぶGit使い方入門」の練習用リポジトリとして作成。

## 技術スタック
- HTML / CSS（静的サイト）
- GitHub Pages（公開）

## セットアップと実行方法
- ローカルで確認: ブラウザで `index.html` を直接開く
- 公開URL: `https://elmas3.github.io/mao-seminar/`

## フォルダ構成
```
index.html    … トップページ
member.html   … メンバー紹介ページ
works.html    … ゼミ活動紹介ページ
css/
  common.css  … 共通スタイル
images/       … 画像素材（.jpg, .psd）
README.md
```

## 注意事項
- 静的サイトのため秘密情報は含まないが、コミット前に画像に個人情報が含まれていないか確認する
- `.psd` ファイル（Photoshopデータ）は重いためコミット対象か要確認

## git状態
- `.git`: あり
- `.gitignore`: あり
- リモート(origin): `https://github.com/Kithub24/mao-seminar.git`
- ブランチ: `master`

## ブランチ運用
- ブランチ命名: ルートAGENTS.md「dev/ のブランチ運用」参照
- GitHub Pagesの公開は `master` ブランチから行われている
