# Note  

## :octocat: コマンド一覧

`!来いよ`  
書き込んだテキストチャンネルの書き込みについて、自分が参加中のVCでbotが読み上げを開始します。

`!消えな`  
botをVCから退出させます。

`!声 XXXX`  
自分の声をXXXXに変更します。 [声帯リスト](#声帯リスト)

`!世界情勢`  
OldOnesの世界情勢

&nbsp;
## :wrench: メンテナンスについて

毎日AM6:00にbotは自動的に再起動します。お手数ですが、接続中の場合は一度botをVCから退出させ、再度入室させるようお願いします。:ant:

&nbsp;
## :date: 更新履歴

2021/03/07

- このREADME.mdに「お願い」の欄を追加。

2021/02/18

- テキストチャットを大きく占領するうるさい注意書きをページ化。

2021/02/17

- 「!消えな」コマンドでもbotが落ちてくれないバグ修正。
- 読み上げ対象のテキストチャンネルを明示。

2021/02/12

- VCに参加していないユーザーのテキストも読み上げるよう修正。

&nbsp;
### :memo: 補足
#### 声帯リスト

<details>
<summary>XXXXに該当する全声帯リストはこちら</summary>
<div>
Aditi | Amy | Astrid | Bianca | Brian | Camila | Carla | Carmen | Celine | Chantal | Conchita | Cristiano | Dora | Emma | Enrique | Ewa | Filiz | Geraint | Giorgio | Gwyneth | Hans | Ines | Ivy | Jacek | Jan | Joanna | Joey | Justin | Karl | Kendra | Kevin | Kimberly | Lea | Liv | Lotte | Lucia | Lupe | Mads | Maja | Marlene | Mathieu | Matthew | Maxim | Mia | Miguel | Mizuki | Naja | Nicole | Penelope | Raveena | Ricardo | Ruben | Russell | Salli | Seoyeon | Takumi | Tatyana | Vicki | Vitoria | Zeina | Zhiyu
</div>
</details>
  
&nbsp;  
## :bow: お願い
Github、AWS、Heroku、Node.js これらについてあたりがつく方がいたら、このbotの保守をお願いしたいと思っています(ついでにこのREADME代わりのGitHubpageも)。ボスケテまでお声がけください。その際に、手順はまとめて共有します。  
以下は少しでも興味を持っていただいた方への補足です。

- 保守といっても現在バグというバグは発生していませんし、このbotのコードはシングルサーバー(※Discordの意味でのサーバー)前提の作りになっています。つまりこのクラン内でのみの利用なので保守で神経を尖らせる必要はありません。
- AWS、Herokuも料金が発生する余地はありません(※厳密にはAWSで金額が発生する余地がありますが1年先に月額1円発生するかレベルです)。
- Herokuのクレカ登録が条件の無料枠を一つ占有する必要があります。
- なぜ保守をお願いしたいのかという点については、Herokuの利用枠をほかのことに使いたいからです。
