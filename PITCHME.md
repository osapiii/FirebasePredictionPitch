---?image=assets/cover.png

## Firebase Predictionsで始める
## 1歩先を読むグロース戦略
<br>
@koyamauchi
<br>
<br>
2019.03.28
<br>
Firebase Meetup #12 Growth Day

---?image=assets/cover.png
#### 本日のお題目

1. @color[black](Voicyの紹介)
2. アプリグロースハックをシンプルに考える
3. FirebasePredictionってどんなサービス?
4. FPを使い始める準備をしよう！
5. バンバン活用しようぜ！
6. まとめ

+++?image=assets/introduce_fin.png
+++?image=assets/introduce_2.png
---
### Voicyの紹介
(1/6)

+++?image=assets/voicy_introduction_2.png
+++?image=assets/introduction.png
@snap[north-west]
+++
@snap[north-west]
#### Voicyのデータ環境
@size[0.6em](toCアプリのログは、サーバーログとFirebaseAnalyticsを併用して使用)
<br>
@size[0.6em](音声聴取ログとアプリ内でのアクションログの2つをまとめてBigQueryに投入)
<br>
![](assets/data_architecture.png)
@snapend

+++
#### Voicy と Firebase
@size[0.6em](必要に応じて、いくつかのサービスを使用しています)
![](assets/voicy_introduction_3.png)
---?image=assets/cover.png

### アプリのグロースについて考えてみる
(2/6)

+++
#### @size[0.8em](継続率が何よりも重要だというのはよくある話...)
![](assets/aarrr.png) 
<br>
@size[0.5em](まずはサービスを使い続けてくれる土台作りがダイジ)
+++
#### @size[0.8em](加えて、1度離脱したユーザーはもう戻ってこない現実...)
![](assets/sample.png) 
<br>
@size[0.5em](分析->ソリューション実行の段階で既にユーザーいなくなってる問題)
+++
#### @size[0.8em](行動予測をビジネスに取り込んでいる企業は結構ある)
![](assets/sample.png) 
<br>
@size[0.5em](Amptitude/Leanplume...etc Prediction)
+++
#### 予測での体験向上を手軽にアプリに取り入れるなら、Firebase Predictionsがオススメ💡
---?image=assets/cover.png
### Predictionsって何?
(3/6)
+++
##### @size[0.7em](まずは公式の紹介動画が分かりやすいので見てみましょう！)
![Video](https://www.youtube.com/embed/ORrvrVEHJz4)

+++
@snap[midpoint span-100]
#### ざっくり言うと、、 
@size[0.7em](アプリ利用者の翌7日間における、特定イベントの発生予測を行うモデルで学習を行い、各Firebaseプロダクトで利用可能なセグメントを生成)
@snapend

+++?image=assets/voicy_case.png
+++?image=assets/ec_app.png
+++?image=assets/game_app.png
+++?image=assets/architecture_1.png
@snap[north-west]
#### @size[0.8em](Predictionsの位置付け)
@snapend
+++
#### いよいよ準備完了！
---?image=assets/cover.png
### Predictionsを使い始めるまでの準備
(4/6)
+++?image=assets/architecture_2.png
+++
#### ①何はともあれアクティベート!
@size[0.6em](MAU5,000以上 かつ Firebase Analyticsで計測中! 無償!)
![](assets/activate.png) 
+++
#### ②仕組みを理解する
@size[0.6em](ブラックボックスを排除して、正しく用法と用量を守る)
![](assets/understand.png) 
+++
@snap[north-west]
#### 大事なポイント1: 
@size[0.7em](Predictionsは、翌7日間のイベント発生確率を予測する)
@snapend
<br>
<br>
![](assets/Remote_Config_3.png) 
+++
@snap[north-west]
#### 大事なポイント2: 
@size[0.7em](施策に応じて、最適なリスク許容度を選択することができる)
@snapend
<br>
<br>
![](assets/risk_low.png) 
+++
@snap[north-west]
#### 大事なポイント3: 
@size[0.7em](予測精度が低い時は、自動でオーディエンス解除される)
@snapend
<br>
<br>
![](assets/Remote_Config.png)
+++
@snap[north span-100]
#### ③その他済ましておきたい下準備いくつか
![](assets/prepare.png)
+++?image=assets/pre_download.png
+++
#### 準備完了!
---?image=assets/cover.png
### いざアクション！🔥
(5/6)
+++?image=assets/architecture_4.png
+++?image=assets/cloud_ab.png
+++?image=assets/in_app_messaging.png
+++?image=assets/cloud_messaging_2.png
+++?image=assets/architecture_3.png
+++?image=assets/database.png
@snap[north span-100]
##### @size[0.8em]("ログ"x"予測"の掛け合わせで、踏み込んだ分析が可能！)
@snapend
---?image=assets/cover.png
### 最後にまとめ
(6/6)

+++
@snap[midpoint span-100]
@ol
- @size[1.1em](準備が大変だけど、色々と応用先)
<br>
- @size[1.1em](準備が大変だけど、色々と応用先)
<br>
- @size[1.1em](準備が大変だけど、色々と応用先)
@olend
@snapend
---
##### @size[0.8em](Voicyでは、共に音声の未来を作る仲間を募集しています！)
![](assets/sample.png) 