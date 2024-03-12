# App name
ー トレーニングシェアアプリ ー
  
🏋️ご自身のトレーニングメニューに他の人にもシェアしよう💪

私自身、トレーニングを行なっている際に日々のトレーニングメニューを”メモ帳”で書き込んで記録していました。しかし、メモ帳を忘れたり紛失した場合などは、メニューを別のもので記録しており煩わしいと思っていました。

そこでアプリ内で一括して記録を残せる、またトレーニングメニューを他のトレーニングしており方々にシェアしたり、知見を得れるアプリがあると非常に役に立つと考え作成しました。

また、簡易的なカロリー計算もアプリ内で一括管理できたら効率的だと思い実装しました。

## 今後実装していきたいこと
・より幅広いカロリー計算が行えるようにAPIを叩ける機能を実装したい。

（現時点では、限りあるメニューしかないため実用性としては非常に低いと感じております。そのため、あすけん様などカロリー計算サイトからAPIを叩けることで一つのサイトでトレーニングユーザーを囲めると考えているからです。）

# Webアプリケーション

【ユーザーが日々のトレーニングの記録などを登録し、ユーザー同士でその投稿を共有するアプリ】

ホームページは、HTMLとCSSで作成し、ページ内で「投稿」に遷移するための導線、簡易的なカロリー計算、参考動画、お問い合わせがあります。

日々のトレーニングの記録などを投稿するページは、Rubyを利用しています。
本ページではユーザーログイン機能など実装し、投稿ユーザー以外のユーザーは投稿の閲覧のみという機能制限を設け、また投稿記事を検索できるように検索機能を実装しました。
それに加えて、記録投稿ページにてユーザーが投稿した記事に対して、他のユーザーがいいね！をできる機能を実装しました。（いいね数が多くなることで、自身の投稿が他のユーザーに役に立っていると嬉しくなるからです。）

簡易的にカロリー計算については、Javascriptを利用しています。
計算ボタンを押下するとカロリー計算が実行できるなど必要に応じてカロリーを取得することができます。

## サインアップを行う。（ユーザー登録）

https://github.com/YUJI1027/portplio1/assets/145771966/52b35a19-9e36-4128-b009-e29f5fddfd9b

## サインインを行う。（ログイン）

https://github.com/YUJI1027/portplio1/assets/145771966/e7da3c00-f1a7-4d33-bcee-fdf89e7c331f

## トレーニングメニューを投稿を行う。（新規で投稿を行う）

https://github.com/YUJI1027/portplio1/assets/145771966/2bd28145-0347-4846-966d-326dd0ec8218

## 投稿した内容を編集する。

https://github.com/YUJI1027/portplio1/assets/145771966/d34de793-f0eb-42d5-bcbe-42ee342c5f4d

## 投稿した内容を削除する。

https://github.com/YUJI1027/portplio1/assets/145771966/a59c8a3c-54e3-4dad-8a48-c15b1ad40fe4

## ログアウトを行う。

https://github.com/YUJI1027/portplio1/assets/145771966/bc227407-095d-45c9-b675-44635d4c8b51

## 投稿の検索を行う。

https://github.com/YUJI1027/portplio1/assets/145771966/41ddf8b8-5f1b-4c30-8701-826652d19bb1

## ご自身のアカウント以外での編集・削除は不可（閲覧といいね！のみ可能）

https://github.com/YUJI1027/portplio1/assets/145771966/6005a2d1-d8a3-4613-a6a2-e88892b1a44b

# 使用技術

<img width="314" alt="スクリーンショット 2024-03-12 16 40 20" src="https://github.com/YUJI1027/portplio1/assets/145771966/4fb78796-058b-4e7f-a72b-0e94cb954a92">


# ER図

<img width="690" alt="スクリーンショット 2024-03-12 16 17 48" src="https://github.com/YUJI1027/portplio1/assets/145771966/115cf986-46d0-41d3-9f29-e65107d6530d">

## 画面遷移図

<img width="784" alt="スクリーンショット 2024-03-12 18 20 29" src="https://github.com/YUJI1027/portplio1/assets/145771966/54a93442-8bbc-4c52-891b-70f13e709287">
