# Taskzen

## サービス概要
達成した目標に集中できない人々を支援するために、
自分にとって今最も重要なことだけを管理するToDoアプリです。
このアプリは、自分にとって最も重要なことだけを効果的に管理し、目標に向けて集中力を高める手助けをします。

### サービスURL: https://taskzen-front.vercel.app/
### 紹介記事:
### Githubリポジトリ
- フロントエンド https://github.com/mikurikuri1919/taskzen_front
- バックエンド https://github.com/mikurikuri1919/taskzen_backend

## 想定されるユーザー層
日々の忙しさの中で、本当にやりたいことをできていない人

## サービスコンセプト
私は社会人2年目でSler業界で働いています。まだ2年目とはいえ、業務は基本的に忙しいです。そんな中で、自分のやりたいこととのギャップを感じ、転職を考えています。そのため、RUNTEQというプログラミングスクールに通い、Web系企業への転職を目指し、仕事の合間を縫って学習しています。しかし、仕事をしながらの学習は中々ハードで、時には疲れ果てて、Youtubeやテレビを見たりなど、ダラダラしてしまうことがあります。もちろん、本当に疲れたときは心身を休めることも大切だと思います。しかし、そればかりでは自分の目標から遠ざかるだけです。自分にとって今最も重要なことに時間を充てることが、目標達成への近道だと感じています。今の私にとって、それはWeb系企業へ転職するための学習です。現代のような様々な誘惑が身近にある中で意思の力だけで、それをしっかりと認識し、注力し続けるのは困難だと思います。そのため、自分にとって今最も重要なことが何かを認識し、それに集中できるアプリを作りたいと思いました。
<br>
<br>
※この考え方は、スティーブン・R・コヴィーの「7つの習慣」の第3の習慣、「最優先事項を優先する」にインスパイアされています。

## 実装を予定している機能
### MVP
* トップページ
* Googleログイン
* LINEログイン（本番環境でうまく動作していない）
* ToDo一覧
* ToDo投稿
* ToDo詳細
* ToDo達成率の算出機能
* 利用規約
* プライバシーポリシー

### その後の機能
* 管理者ページ
* LINE通知機能
* レコメンド機能
* ドキュメントページ
* ToDo達成率のグラフ、レポート化
* ToDo達成後のボーナス機能
* 共有機能（OGP）
* Rspecテスト

## 主な使用技術
### フロントエンド
* Next.js 13.5.4
* React 18.2.0
* TypeScript 5.2.2
* TailwindCSS 3.3.3

### バックエンド
* Rails（APIモード） 7.0.8
* ruby 3.1.4
* PostgreSQL

### 環境構築
* Docker
* dokcer-compose

### インフラ
* Vercel
* Heroku

### 主要ライブラリ
## Next.js
* Auth.js
* recoil
* react-hook-form
* react-icons

## Rails
* bcrypt
* rubocop
* rubocop-performance
* rubocop-rails

### 画面遷移図
Figma：https://www.figma.com/file/YapIXTHD4FXu8UDSSShg2Z/Todo-For-7Habits?type=design&node-id=0%3A1&mode=design&t=9wl7gwmpInpzcaOp-1