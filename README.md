# Auto_FitBit
流羽がおねんねする→fitbit睡眠を感知→サーバに「流羽が寝たよ」と知らせる→サーバがnatureRemoに電気消してと命令する→電気が消える

1. サーバーからfitbitAPIに5分に1回リクエストを送る
2. fitbitAPIが睡眠を感知したタイミングでサーバにリクエストを送信
4. サーバからnatureRemoにリクエストを送る
5. natureRemoが電気を消す
