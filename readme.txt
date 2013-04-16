audioタグがhtmlでサポートされていない場合に、flashを利用して再生できるようにする動作

名称:
audioPlayer

作成経緯：
youtubeの音楽を再生できるwebアプリをつくって、html5のaudioタグで再生しているわけだが
PCでも再生できるようにしたい・・・
でも、mp4はhtml5のaudioタグでは再生できないことが結構あるので、flashでそのあたり吸収させておきたい。
できたら、audioタグを利用する、無理ならaudioPlayerを使うみたいな動作がいいな・・・

作者情報：
taktod
poepoemix@hotmail.com
http://twitter.com/taktod
http://poepoemix.blogspot.jp/

ライセンス：
MITライセンスとします。

特徴：
mp4の再生はchromeとかsafariなら実行できるみたいですが、firefoxとかではうまく動作しないみたいです。
flashがたまたまmp4の再生可能になっているので、audioタグで再生できない場合、このプレーヤーに動作させてお茶を濁します。

対応javascript命令：
イベント
　loaddeddata
　play
　pause
　timeupdate
　ended
　ready

メソッド
　doPause()
　doPlay()
　doStop()
　setSource(url:String)
　setCurrentTime(time:Number)
プロパティー
　src
　loaded
　paused
　currentTime (シークは読み込み完了データのみに対して有効)
　duration
　totalSize

属性
　loop