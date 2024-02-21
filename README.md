# portfolio

■サービス概要
・どんなサービスなのかを３行で説明してください。

　婚活アプリ。実際に会った相手を評価できる機能を備えることで第三者がその対象相手の口コミ評価を見ることで適切な評価を下せる判断材料を得ることができます。

■ このサービスへの思い・作りたい理由
・このサービスの題材となるものに関してのエピソードがあれば詳しく教えてください。

　マッチングアプリで異性の出会いを求める場合にその対象相手が本当に誠意ある人物であるのか否かを判断する材料がない。そのマッチング対象相手と実際に会ったことのある人の評価があることで客観的にその対象相手の誠意等を評価することができると思いこのサービスを作ってみようと思いました。

・このサービスを思いつくにあたって元となる思いがあれば詳しく教えてください。

　食べログ等の口コミサイトをみて口コミ等の評価はそのお店を知らない人にとってそのお店を適正に判断する材料の一つになると思いました。そうであればマッチングアプリにも「実際にそのレストランで食事をとった上での評価」=「実際に対象相手に会った上での評価」を取り入れることでこれは一つの判断材料になり得ると思いました。


■ ユーザー層について
・決めたユーザー層についてどうしてその層を対象にしたのかそれぞれ理由を教えてください。

　マッチングアプリを利用してパートナーを探している方が対象になります。具体的にはユーザー層は出会いの機会に恵まれていないけれども将来のパートナーを探している方。いきなり結婚前提、結婚有りきではなく会って食事をしたりお喋りしたりとフィーリングが合うか否かを確認したい方が対象の層になります。
　今現在人々の結婚に対する価値観が多様化していて20代、30代の女性であっても結婚よりも仕事を優先したい方が増えており、結婚を急いでいない方が増えています。自分と価値観やフィーリングが合う異性を求めるニーズは常にありますが人によってはこのような出会いの機会がリモートワークの増加等で少なくなってきている中でマッチングの機会を増やすツールとして婚活アプリを始めとしたマッチングアプリのニーズは増加しています。
　けれどもマッチングアプリの問題点はマッチング対象相手の誠意を適切に評価する判断材料がないことです。この層が抱えるissueを解決するのが今回作るアプリの役目になります。


■サービスの利用イメージ
・ユーザーがこのサービスをどのように利用できて、それによってどんな価値を得られるかを簡単に説明してください。

　ユーザーはこのアプリを利用することでそのユーザーがマッチング対象相手に求める価値観とマッチしているのかをそのマッチング対象相手と実際に会ったことのある方々の評価を見ることで適切に判断するための判断材料を得ることができます。この適切な判断材料をもとにミスマッチのリスクを低減して貴重な時間と気力等の資源をこのユーザーはより自分と価値観がある別のマッチング対象相手に向けることができます。


■ ユーザーの獲得について
・想定したユーザー層に対してそれぞれどのようにサービスを届けるのか現状考えていることがあれば教えてください。

　マッチングアプリを利用する機会があり自分の価値観やフィーリングの会う異性との出会いを求めるユーザー層に対してマッチング対象相手となる異性の一覧リストとその異性と1対1の文字列での会話をする機能と会った後の相互評価する機能と、評価された結果を他のユーザーが確認して誠意があるか、自分との価値観が合うかを判断する指標を得た上でマッチング対象相手を評価することができるサービスを提供する予定です。


■ サービスの差別化ポイント・推しポイント
・似たようなサービスが存在する場合、そのサービスとの明確な差別化ポイントとその差別化ポイントのどこが優れているのか教えてください。
独自性の強いサービスの場合、このサービスの推しとなるポイントを教えてください。

　既存のマッチングアプリにはマッチング対象相手に関する誠意や価値観に関する情報を得ることが非常に困難であり今回作るマッチングアプリでは実際にあったことのある相手同士の相互の評価機能がありこの評価を他のユーザーが閲覧できるためマッチング対象相手の誠意や価値観に関する客観的な情報を獲得できこの判断材料を基にマッチング対象相手を適切に評価できるのでミスマッチの低減とマッチしない相手に会うために時間や労力を失わずに済みます。この点が既存のマッチングサービスにはない差別化ポイントになります。


■ 機能候補
・現状作ろうと思っている機能、案段階の機能をしっかりと固まっていなくても構わないのでMVPリリース時に作っていたいもの、本リリースまでに作っていたいものをそれぞれ分けて教えてください。

1. MVPリリース時に作っていたいものについて
- API作りきれないところはmockデータを用意
- 全画面共通
  - ヘッダー
  - 固定フッターバーとその中のボタン
  - レイアウト
  - 共通モーダル
- 会員登録画面
  - フォーム入力
  - バリデーション、既に登録済みのIDか否か等
  - PWの暗号化
  - APIとの疎通とDBへの保存、アクセストークン、SessionIDの発行
- ログイン機能
  - フォーム入力
  - バリデーション
  - APIとの疎通
- マッチング対象相手の一覧画面
  - APIから一覧情報取得、UIに反映
- 詳細画面
  - APIから対象の詳細情報を取得、UIに反映
  - いいねの状態管理
  - 実際にあったことのあるユーザーの評価結果
- 相手と1対1で文字列で会話できるチャット画面
  - チャット履歴の一覧表示
  - チャット投稿フォーム
  - APIとの疎通とDBへの保存

2. 本リリースまでに作っていたいものについて
- 全画面共通
  - CSRF対策、共通フォーム投稿にCSRFトークン付与
  - 全画面共通ログイン認証継続可否の判定機能
- 会員登録画面
  - auth0を使ったLineID等での登録
- ログイン機能
  - auth0を使ったLineID等でのログイン認証
  - APIとの疎通、DBからIDとPW一致するならアクセストークン、SessionIDの発行
- マッチング対象相手の一覧画面
  - 検索フォームと結果一覧
  - ページネーション
  - 一覧アイテム内のいいねの状態管理
- 自分にいいねしたユーザーの一覧画面
- ダイレクトメッセージ一覧画面
- 詳細画面
  - いいねの状態管理
  - 実際にあったことのあるユーザーの評価結果
- 相手と1対1で文字列で会話できるチャット画面
  - チャット投稿後のリアルタイム更新
- 会った相手に対する評価投稿画面
  - ボタン形式のアンケートフォーム


■ 機能の実装方針予定
・一般的なCRUD以外の実装予定の機能についてそれぞれどのようなイメージ(使用するAPIや)で実装する予定なのか現状考えているもので良いので教えて下さい。

　技術選定は以下をイメージしています。
　フロントエンドはTypeScriptで書いてフレームワークはNext.jsを使う方針です。
　UIコンポーネントのスタイルはStyled Componentsを使ってTSの中にスタイルを書く方針です。
　フォーム投稿についてはFormikかReact Hook Formのどちらかを使う予定です。
　ロジックの管理についてはコンポーネント間でバケツリレーするものについてはhooksのContextを使って管理しやすくする方針です。
　グローバルで管理する状態についてもReduxを使うことなくhooksのContextを使って管理する予定です。
　バックエンドはRuby on Railsを使いますがAPIサーバーとDBサーバーとしての役割に限定しWebサーバーの役割はNext.jsに持たせる方針です。
　DBはMySQLもしくはPostgreSQLを使う予定です。
　ORマッパーはActiveRecordを使い、テストはRSpecで書く方針です。
　インフラはAWSを使う方針です。
