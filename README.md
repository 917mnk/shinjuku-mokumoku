# What's Shinjuku Mokumoku Programming?

![](/assets/images/shinjuku-mokumoku-banner-960x180.png)

１人だと勉強をサボりそうなオーガナイザーが **~~強制的に~~ ストイックにプログラミングする** ための時間を作ることを目的に毎週開催されているもくもく会です。

そのため、新宿プログラミングもくもく会では参加しているプログラマー各位が相談したりしながら、以下のようなテーマにそれぞれ取り組みます。

- 新しい言語・フレームワークを触りこむ
- 今後使うかもしれないミドルウェアの特性を掴む
- 分散データストアをとりあえず触って肌感覚を掴む
- 機械学習についてまとまって時間作って学習する
- 数学や統計を学び直す、論文を読む
- OSS活動やプライベートプロダクトを集中して進めたい

また、自身にプレッシャーを与えるためにもcheck-inにてやることを宣言し、check-outにて成果を発表します！

過去の雰囲気 : [shinjuku-mokumoku](https://github.com/shinjuku-mokumoku/shinjuku-mokumoku/meetups)

質問などありましたら、slackの [shinjuku-mokumoku](https://shinjuku-mokumoku.slack.com/) もしくは、twitter [#shinjukumokumoku](https://twitter.com/hashtag/shinjukumokumoku) にてご連絡ください。
slack 未登録の方は方は https://shinjuku-mokumoku.herokuapp.com よりぜひ登録ください。

# check-in & out

差し込み業務を回避するには強い意志！ということで、check-inにてやることを宣言し、check-outにて成果を発表します 💪

以下を参考に、自己紹介とやることの宣言を行うPull Requestを [shinjuku-mokumoku](https://github.com/shinjuku-mokumoku/shinjuku-mokumoku) の `meetups/<開催回数>/<あなたのお名前>.md` ([template](https://raw.githubusercontent.com/shinjuku-mokumoku/shinjuku-mokumoku/master/meetups/template.md)) へお出しください。

参考: https://github.com/shinjuku-mokumoku/shinjuku-mokumoku/pull/137

> 💡 Pull Requestとは？その出し方は？
>
> - [Github help - About pull requests](https://help.github.com/articles/about-pull-requests/)
> - [Github help - Creating a pull request](https://help.github.com/articles/creating-a-pull-request/)

gitやpull requestに不安な点がありましたら[shinjuku-mokumoku slack](https://shinjuku-mokumoku.slack.com/general)までご質問ください。

## ToC

- Pitch
  - [Introduction, Closing](https://gitpitch.com/shinjuku-mokumoku/shinjuku-mokumoku)
  - [Boardgame](https://gitpitch.com/shinjuku-mokumoku/shinjuku-mokumoku/master?p=boardgame)
- Community
  - [slack](https://shinjuku-mokumoku.slack.com/) (regstration is [here](https://shinjuku-mokumoku.herokuapp.com))
  - [connpass group](https://shinjuku-moku.connpass.com/)
- Organize
  - [connpass event descritpion](connpass.md)
  - [Organizer works](ORGANIZE.md)

## Other Usage

提出された自己紹介markdownから発表順を決定する

```sh
node scripts/presenter.js <num>

OR

MEETUP=<num> docker-compose run presenter
```

次回eventのtemplateを作る

```sh
node scripts/generate-next-event.js

OR

docker-compose run node node ./scripts/generate-next-event.js
```
