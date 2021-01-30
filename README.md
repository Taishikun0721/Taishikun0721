

[![](https://raw.githubusercontent.com/Taishikun0721/Taishikun0721/master/profile-summary-card-output/vue/0-profile-details.svg)](https://github.com/vn7n24fzkq/github-profile-summary-cards)

[![](https://raw.githubusercontent.com/Taishikun0721/Taishikun0721/master/profile-summary-card-output/vue/1-repos-per-language.svg)](https://github.com/vn7n24fzkq/github-profile-summary-cards)[![](https://raw.githubusercontent.com/Taishikun0721/Taishikun0721/master/profile-summary-card-output/vue/2-most-commit-language.svg)](https://github.com/vn7n24fzkq/github-profile-summary-cards)


[![](https://raw.githubusercontent.com/Taishikun0721/Taishikun0721/master/profile-summary-card-output/vue/3-stats.svg)](https://github.com/vn7n24fzkq/github-profile-summary-cards)

# 紹介文
## アカウント
***
- [GitHub](https://github.com/Taishikun0721)
- [Gist](https://gist.github.com/Taishikun0721)
	- 短いプログラムを作成した時などはGistで管理しています。

## 使用したことのある技術
***
- OS: Mac
- 言語: Ruby / Javascript(ES5, ES6, jQuery) / HTML5 / CSS3(SCSS)
- フレームワーク: Ruby on Rails(5系、6系) / bootstrap4, bootstrap material design / Vue.js(勉強中)
- バージョン管理: Git, GitHub, GitHubCLI, 開発手法にはGit flowを採用

## Rails内で使用した経験があるgem
***
- bootstrap4、bootstrap-material-design(CSSフレームワーク)
- font-awesome-sass(アイコン)
- ply-byebug, binding_of_caller, better_errors(デバッグ)
- sorcery, jwt（ログイン機能・認証）
- CarrierWave, ActiveStorage, fog, aws-sdk-s3(画像投稿)
- rails-i18n(国際化対応)
- kaminari, pagy(ページネーション)
- ransack(検索機能)
- config(定数管理)
- dotenv-rails(環境変数管理)
- letter_opener, letter_opener_web(メールの開発環境確認)
- redis(セッション管理)
- line-bot-api(LINE Messaging API使用)
- faker(シードデータ)
- rubocop, rubocop-rails(リントチェック)
- factory_bot_rails(テストデータ作成)
- Rspec(テスト)

## 実装したことがある主な機能
***
- 基本的なCRUD機能
- フォームオブジェクトを使用した複数テーブルにまたがる検索機能
- ぐるなびAPIからデータを取得しLINEbotへの通知機能(APIロジック部分でサービスオブジェクト使用)
- ポリモーフィック関連を用いたフォロー機能
- CarrierWaveを用いた複数枚投稿機能
- Rspecでのテストコード
- 本番環境でのAWS S3の使用(carrierwave, activestorageの投稿画像永続化)
- Herokuへのデプロイ

## 現在の学習状況・アピールしたい事
***
平日は仕事終了後の3.4時間、休日は6時間ほど学習していました。
まとまった時間が取れない事も多かったので移動時間でテーブル設計を行ったり、デザインパターンをGistに書いたりして
とにかく小さい機能単位で学習する事を心がけました。

小さい機能をコツコツと勉強してその技術を結びつけるためにRailsなどのフレームワークを使うというイメージで学習を行ってきたので、プログラミング学習で一番大事な事は基礎にあると考えています。

また**MENTA**というメンター（教える人）とメンティー（教わる人）のマッチングサービスを利用してコミュニティ内でアウトプットを日常的に行ってきました。

コミュニティ内のslackでは個人で **times(分報チャンネル)** というチャンネルを持ってそれぞれが自由に進捗を呟く事で自然と様々なプログラミングの知識に触れることができて学習効率も上がり、モチベーション維持の助けにもなりました。

またわからない点を教え合う文化もできており、自分も`CarrierWave`という画像アップロード用gemの本番環境(heroku)でのデータ永続化方法について、zoomで解説をしたことがあります。

### ■CarrierWave説明用にまとめたメモ

[Heroku + CarrierWave + S3で画像投稿する方法](https://qiita.com/Taishikun0721/items/f8d18e03b65e4665ac6f)

無事エラーも解決できて、アップロードもできる様になって喜んで頂けましたし、人に教える事で自分の考えも整理されるのでとても良い勉強になるという事を学びました。


### ■作成した小さいプログラムの紹介

### 1. 動物園の餌やりのテーブル設計の練習
***
動物園の餌やりを実際に行う時に、どうすればうまく管理することができるのか飼育員になった気持ちで考えながら作成しました。
テーブル設計は実際にどんな業務を行うのか実務をわかっていないとできないので、実務を想像する力が養えるいい勉強になりました。

[動物園の餌やりのテーブル設計(GitHub)](https://gist.github.com/Taishikun0721/0c8f9f9a0c792e93d5111781351ba812)
***
### 2. 複数画像投稿処理のフォームオブジェクトをRubyで作成してみた
***
MVCに沿って自分でモデル、ビュー、コントローラーの責務を考えながら実装しました。
Railsを使用する上で保守性・可読性をどう高めるかを考える勉強になりました。

[MVCを意識して生RubyでRailsっぽく複数画像投稿処理を書いてみた(Gist)](https://gist.github.com/Taishikun0721/d73b10efcf0d131ed152e5d996709ef9)
***

### 3. Vueを使用したTodoアプリケーション
***
vue.jsを学習する際に基礎を学んだ後に、自分で考えたコードで作成しました。
最初は汚いコードでもリファクタリングで実力が上がるので、最初はスパゲッティコードでも書き上げる事を意識しています。

[![Image from Gyazo](https://i.gyazo.com/000fb2834c92a2cdaddf959b98f5218b.gif)](https://gyazo.com/000fb2834c92a2cdaddf959b98f5218b)

[Vueを使ったTodoアプリ(デプロイ済アプリ)](https://naughty-lamport-25a274.netlify.app/)

[GitHub](https://github.com/Taishikun0721/vue_todo_app)
***

## 個人開発で作成したアプリケーション
***
しっかりとしたポートフォリオを作成できていないのですがこれまで作成してきた物を紹介させて頂きます。

***
### 1. deliveryfood
テイクアウト可能な店を返してくれるLINE bot(2021年1月作成)
***
自分もそうなのですが、コロナ禍においてリスクを抱えながら出勤や外勤をしないといけない人は必ずいます。
その中で一番感染のリスクが高いとされている食事の場面で密になるのを避けるために、自分の現在地情報を送信すると半径500m以内のテイクアウトが可能な飲食店が表示されるLINE botを作成しました。(ぐるなびAPIで取得できる店舗に限る)

■QRコード

[![Image from Gyazo](https://i.gyazo.com/c12e1ecca0664fc4761ea89ea45e11a0.png)](https://gyazo.com/c12e1ecca0664fc4761ea89ea45e11a0)

***
### 2. foodapp
食べ物共有アプリ(2020年8月作成)
***

食べ物写真付きで投稿することができるアプリになります。
例:写真付きで食べ物を投稿→それについてコメントができる

■管理者アカウント

- email

	- admin@example.com

- パスワード
	- password

■一般アカウント

- email
	- test@example.com

- パスワード
	- password

[食べ物共有アプリ(デプロイ済みアプリ)](https://food-app-output.herokuapp.com/)
***

### 3. インスタグラムクローン
***
インスタグラムのクローンアプリです。
MENTAで契約しているメンターの方のオリジナル教材で実装したらPRをあげてレビューをして頂いて理解度を確認しながら進めています。

[インスタグラムクローン(GitHub)](https://github.com/Taishikun0721/iinsta_clone)

あくまで自分で実装をして、わからないところを質問するというスタイルなので、PRでレビューに対して質問したりする事でどんどん理解が深まっていくのでコードレビューの重要さが分かりました。


***

## 共同開発経験(2020年11月頃)
***
MENTAでお世話になっているメンターさんのプロジェクトで、メンティー同士の学習進捗を共有するwebサービスがありそのサービス開発に携わっています。

■実装した主な機能
- お題に対してのディスカッションで時系列順にディスカッションが並ばないバグを修正
- Web知識クイズの質問に対してコメント機能のCRUDをモーダルで行い、全て非同期処理で実装

***
## 企業案件(2020年12月下旬〜現在)
***
Railsを使用した企業と通訳者のマッチングサービス作成に参画して複数のissueに対してPRを作成してマージされました。

### ■アプリの概要
企業が立ち上げたプロジェクトの会議に対して、適切な通訳者をアサインさせるマッチングサービス

- 管理者ユーザー, 企業ユーザー, 通訳者の3つに権限が分かれている
1. まず管理者ユーザーが企業と企業ユーザーを登録する。
2. 企業ユーザーがプロジェクトを立ち上げ、プロジェクト事に会議を開催する
3. 会議を登録する際、同時に希望の通訳者の条件を設定する
4. 管理者側が条件に当てはまる通訳者にアサインの依頼をする
5. 承認されると会議開催

### ■実装した主な機能
- 企業プロジェクトのCRUD機能
- 一覧系画面全てへのページネーション実装
- 会議時間表記のフォーマットを必要条件に合わせて設定
- 全てRspecによるテスト(system spec)も作成。

## Webエンジニアになって挑戦したい事
***
Ruby On Railsを使用したバックエンドの開発に携わりたいと考えています。
またReact, Vueと言ったフロントエンドフレームーワーク。AWSやDockerなどインフラに関しても知識を深めて専門分野に縛られずに知識を深めていきたいと考えています。

技術を磨くのはエンジニアとしてもちろんですが、どうすればユーザーに良いサービスを届けられるかという根本の部分を考えて、開発ができるエンジニアになりたいと考えています。
また、技術を磨くことに固執せずに職場でいい人間関係を築いて、切磋琢磨しながら楽しく仕事をして組織に貢献したいです。
