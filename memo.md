## ■ つぶやき:110225:110225
### DBの面倒について:111202:111202
やるって言ったのに全然出来てないじゃん。
監視しているインターフェースも間違ってるし。
安定しているって言ってたけどAWR取れてないし。
ぼろぼろだよ。DBの状態を見るだけで頭痛くなる。。

### サーバーのIPを変えるとき:110426:110426

IP変えたら ルーティングを確認するのはもちろんのこと
DNS、監視設定(ping？)、SNMP(アクセス制御、トラップ)等、
NTP、ホスト型FWルール、等々確認のこと。



### PoolPreparedStatement:110310:110310

Oracle側で SQL文のパースが結構はしっている。
Tomcat側で poolPreparedStatements を使ってもらうと幸せになれるらしい。

poolPreparedStatements="true"
maxOpenPreparedStatements="20"



### NetAPP と アイシロン:110307:110307

普通のNASアプライアナンスも、スケールアウトNASもどっちも好き。
知ってる製品の限りでは、ランダムアクセスに優れたものや
ランダムは遅いけど ストリーミングデータ等の大きなデータの
アクセスがすこぶる早いのがある。
違いをよく考えて採用しよう。



### Oracle の HAIP:110225:110307
Oracle の HAIP は、同じセグメントにしとくうまく動かない（動くときもあ
る？）


### DBへの データ移行の際の注意:110307:110307
には DBをArchiveモードのままでやるのか、ArchiveモードをOFFするのか
メリット・デモメリットを考えて計画しよう。
そして早めにArchiveモードに戻そう

### パワハラ

社長が部長に対してまた威嚇的に糾弾している。
その威嚇的な口調が部長に感染して、組織に反映されていく。
本当に社長であるべき人は人格者じゃないといけないと思う。

