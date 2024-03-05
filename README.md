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



### 画面遷移図
Figma:https://www.figma.com/file/KaMUVCFuZzqoMz4pWNu6hq/%E7%84%A1%E9%A1%8C?type=design&mode=design&t=YGou8J31GHqzC76Z-0

- [ ] API作りきれないところはmockデータを用意
- [ ] 全画面共通
  - [ ] ヘッダー
  - [ ] 固定フッターバーとその中のボタン
  - [ ] レイアウト
  - [ ] 共通モーダル
  - [ ] CSRF対策、共通フォーム投稿にCSRFトークン付与
  - [ ] 全画面共通ログイン認証継続可否の判定機能
- [ ] 会員登録画面
  - [ ] フォーム入力
  - [ ] バリデーション、既に登録済みのIDか否か等
  - [ ] PWの暗号化
  - [ ] APIとの疎通とDBへの保存、アクセストークン、SessionIDの発行
  - [ ] auth0を使ったLineID等での登録
- [ ] ログイン機能
  - [ ] フォーム入力
  - [ ] バリデーション
  - [ ] APIとの疎通
  - [ ] auth0を使ったLineID等でのログイン認証
  - [ ] APIとの疎通、DBからIDとPW一致するならアクセストークン、SessionIDの発行
- [ ] マッチング対象相手の一覧画面
  - [ ] APIから一覧情報取得、UIに反映
  - [ ] 検索フォームと結果一覧
  - [ ] ページネーション
  - [ ] 一覧アイテム内のいいねの状態管理
- [ ] 自分にいいねしたユーザーの一覧画面
- [ ] ダイレクトメッセージ一覧画面
- [ ] 詳細画面
  - [ ] APIから対象の詳細情報を取得、UIに反映
  - [ ] いいねの状態管理
  - [ ] 実際にあったことのあるユーザーの評価結果
  - [ ] いいねの状態管理
  - [ ] 実際にあったことのあるユーザーの評価結果
- [ ] 相手と1対1で文字列で会話できるチャット画面
  - [ ] チャット履歴の一覧表示
  - [ ] チャット投稿フォーム
  - [ ] APIとの疎通とDBへの保存
  - [ ] チャット投稿後のリアルタイム更新
- [ ] 会った相手に対する評価投稿画面
  - [ ] ボタン形式のアンケートフォーム



### 画面遷移図
drow.io:https://viewer.diagrams.net/index.html?border=0&tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=ER%E5%9B%B3.drawio#R7V3bcuO4Ef0aP3pL4EWXR0szm6TiSSb2bm32yQWbsMQKRWpIeGTt1we8QBc2KZG2BFBsVLlmSAgCKfQBDnAaaNzYs%2BX732K6WnyLPBbcWAPv%2Fcb%2BcmNZ1mA0Fv%2BlKZsixR0O8pR57Ht5GtklPPp%2FsSJRZnvzPZYcZORRFHB%2FdZj4EoUhe%2BEHaTSOo%2FVhttcoOHzqis4ZSHh8oQFM%2FcP3%2BCJPHVujXfrfmT9fyCeT4ST%2FZEll5uKXJAvqReu9JPvrjT2Lo4jnV8v3GQvS2pP1kn%2Fv15pPty8Ws5A3%2BcLk7uXPH%2BTHxvvX85f3sfcP6%2FvSviVOXsxPGrwVv%2Fj3hMVJ8cp8I%2BtBvP0qveT0OU2aJpzGvDCXPRAJwgCc%2BiGLRQLJ7oOArhI%2Fy56nLPzAu6eb6I3LguTd9NV%2FZ95Dbq00rzDcvSgsvU0LfxWFPxYvk35MA38eiusX8dvTJ05jloh3uacJL3Is%2BDIoLotfyGLO3mvrjmwtIrDMoiXj8UZkKb7g2oURCxiTcXG%2F3mFiC9nFHh7sQZFICxzOt2XvTCUuCmu1sZwLLHfcaA8p%2BKaLKPb%2FSk0VFFW7b8jsfu0vAxoKVFOvlDSNsmacGcQPglkURKm1wyhkwOBpJi%2BOVr%2FReM54kbCK%2FJBnFeFOxZ%2BomtngF%2FfGFe86E%2Fdkdy%2F%2B0uwxn0VhwmMBrLQMJuy7ZqmNpzxaFYUG7FWWHxcVn14%2FR5xHyzYQONJAIDA20r5NcXApGAwBDL7%2FsxYI4udynwYPoqek4TzIzZZ1nHRntgrbVtb2tobLVV9urZGo%2BNcg6%2FsWvucx0XKn64XP2eOKvqSZ1oI8PtBmj7QLaLA9C9ktDVQUtqu11qXRQHRTIeWiCb2FXgKsvn3PTwBhBICQ5r8TLYfNRR%2BpFxKyw87zThNheD%2Bc3%2BffHJYw43YFM%2B%2B1jXxLAOfBUKPiVIBobEilEakMLkkqQ%2B2kMmkOAzX9B%2FN8WZ56RhnjZBQ5cdlDQUiX4upONB7Re3edUjoBEnQUImvMUIhOCpnophBpdUMhu0aBkEJsgIJnP%2BYLj4pS7zzxbEMiDWCCj0SgLGlIRDmJEEs7i7QQORGwSI25es8iUONcxexVvPNbzK5H4uoEVvBRCdRFZwvKjYer5OGSfX3R99%2B6Y6cZRIh7sd7fqJEqXFx5C2nj4mrdVXwOBlCNxO3ispAKkvKRxsV1PswcGQ%2B45x0PNClOBYiMPqlianmCVCpcXGpJxTb6JGgUCBkF6pOi7rhxcbUBCT4KMepkByikwsWlmEKMOAkaBUIKgeKkYY0GuMDHGlCINKyhnDWqfFqKaaOFqomANmrM1Xva6NwSy47RRg0u0NGGA0XPB%2FbTZ2vjwTqEBBnIGYF0YTkQJFZVV29dbJOWY8RGFR4sZ1CNjCObtJRSvgPFxl9Re7AcpHqjA%2FXGOOvMWfz0loh%2FjD%2FrkwiqHx9Y5x0fNCpOBaSMGKliWnmCYqq2bKmlGCNGgkaBkF%2BgGFnwC7s%2BfvkAYg4HNWeHDz5yMZplB8ilajOXWnIxkiVoFAjJpUqyHAZpQ3kWF%2FP04sebaDl%2BFJaIJs8lnrrN2EPyOT%2Bi0PGNfA3DNzr5pnLfl1LCcVvopv0nHLfGXH0nHBfKpllj6%2FUU5vwwwcciUGV9ZEkihiXGZ3aICUf26kXPP2q6OuJym75co2eqcJnlbaSNy0ztKhkX6pm4N325SCVNF0qa1yRianWS1WEG3SIa1%2BiYKuaVJ0hF%2B6Yv1%2BiYoFEgZBSoYxrf2KdRg45TZG9mOEUnp2jfBTY0UiVoFPg4ZQilyiSXnHJaMduJG0MFH5FAudIQiXIi0b8xbNhC%2BUTAJDXm6j2TdG4hZ8doowYX%2BGgDalpJWpk9nsI2Qs2JOIdy2iYdHYgAA9UvtqR%2BgH542hIxVTJmPxFDBg12KTNvzqSuJKrU55sHFtB0EeDX3Se5%2BpSPTYl1aCMWenfpSY3i9uuDAM5v0TcablJwpD%2BMybFr%2FuD0accNKV4ueotf2LHfVYy0uBzS1mY8OQYhgwpTbRPjrCZ%2BHr7xETx8z5a3bKE3KrnnyaSEgfyXFt%2Fa2R8UNClh2HFKBeU1AQo6G5Bk1PCeAWlkXQeQxiX7u2X7NwUSsd0SkuR49QSShGHoZi9bMYGsfWNijw4fNCz6v9o3c%2BzSF8jBF8RF%2Fg5nBnYD%2Be8Kgd24h8xbgEZkn6uLBOED3HJUgIv3kVBDBFCaC4uvbuoGNYeDspvt0cNtgiiU6tNuKrBfbkUYbGH3%2Fv8YvqV8x1BzvAEqDtt%2BGsZGzvy84avN3pX1e1DTxh3x4nQr7aWaCSXtq1tqoTds%2B1G2xqNdmcPuVbjIjnOK9uV7nYu0qnX1Hk5CgU6PVRwJQ7Kr4hSNy%2FcMoWT1YI6W0k8o2tfudS4Gq05CQXqoVBPPxPWzx9lhgY4wmgj9hjEuzBj6F%2Bk1EenxcAZBGseVtFiyi5E06nCBjzUGRghv6LCqV5n62YWQBprmpd29k3L8D7cpv5JLEaxcUrMf%2BCFXeI4Pt27QOHxPK3%2BqTWY2sKjw%2BNYttemKy3cEnX24Q7aMkG5hGUFmuyZxXqvDtw4z6EbOoxbePtSk8jm95QSpaPf5jlpE7um%2F3pI3CoSMAt11V7eOSJ%2FPtw41%2BDilhcPPcMqlOEW721c%2BzHDKrlHg45QxdOhxn6c2QL4dthVK0HHIGOqThkOUc4h%2BR%2FC4cy5ArYuHaszVexKBmqfHuAmq0BIm6FiEEAgc7H7hGr8WNr9wxRmO%2FpLO2RMxfUor4JQ6FTlyGOPpZCrO7cuhZBsonQFKloMISlCHz6FkGSidA0oED5QIJDg0Q59T0TdKMUgqZrn9HPRYUIz7T3GUKL5AHy1BcutWdR6KY7RI9cPIYpeN%2BlEHjq4sAiMW1MVwrwIrmgY%2BbYxYUOM4cNhfy8BR64KwWvjg08wsEwVEhevlFMdoXxNGLBMJBLYLjAQDRYkfxazhasilG1BBSCYmAkgXyET7YjBimSggsF0gJBP5zO7goGvcYUKBSKiYWCBd4A79i8CI3UL2REAeNtp4IJ1bDdgx8qhDBkLyaHDM3zWeGCFznjwyIl81cbSTuOiREWISXHKgkfJRDx8%2BDuXWUn1qhA1FUeNNL%2FACTvQAnUxP2aiBPnqNXUzTQ2l09zAT6xB4pBx6pfmhNOWSVPcuFfGWaZKso9h78vx5Nh9ALrS2PD2wSvDq60gHKmuGmrJPnXLcrYpFyf2kJgdKJysW%2B1G6LsATjza9SGUvQg7xMsa08riBxHLewcySht6%2FM%2FBkAl3VBxcb49SdUq9q6DIsHbs4Kpu86dDFLa1wVn7kqGOi0p1ZpG0XS3IyqOij1KqzTgOpBZE66yCNR0ccqJEIsz1lG1jQz1%2FaYQWfXuvAWczvCYtnC8rN1oTjw9TbKslN9c4EWbIZB1x2Z4JTEyGmMzsTXDj1RCNHHGsaCAcELpxT5vOaJxlWsOODAb1bEupwg29w4JpJppKVQCfIRf%2BWBNdMNWG7wMgscKrppTsSwkyNvBZ60RerthY5CLnFREDvArfo36HgmhjosF1g5Ba4ZellQbnhk4%2BgBSGfmOjnXeCTDuxakNMlQyh7DQMhoQxb7GO6Xia5ADLwkccQKqZoxPOWTi9SMWPoaf%2BB%2BHDbtqBAE7942KH9TaLsePPf7XfEzZ%2FpJ7%2B48vbL%2B37OL3Kwmr%2FwWRb0yRglJzctNPHGXXTp33ZR6dZ7%2F9G1f%2BVFhLt1AKoW%2Fw0bhIrq8w6Y2kmIKjC5AALnwhIpl%2FRhLInbOIr4fnbBBYtvkcfSHP8H#%7B%22pageId%22%3A%22sNS6qJ4tYWTP2NnqHWyx%22%7D
