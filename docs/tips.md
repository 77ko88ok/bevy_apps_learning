# tips 

### 可変クエリ
Query<&mut >


### .chane()
2つのシステムで.chain()を使用していることに注意してください。これは、コードにリストされている順序（update_peopleがgreet_peopleの前に発生する）で正確に両方を実行する必要があるためです。そうでない場合、人々に挨拶した後で名前が変更される可能性があります。


### ドキュメントの読み方
[Timer](https://docs.rs/bevy/latest/bevy/time/struct.Timer.html)の場合
implementations欄のパブリックのメソッドを呼び出す
例えば、[Timer.from_seconds](https://docs.rs/bevy/latest/bevy/time/struct.Timer.html#method.from_seconds)


## todo
- Query内のwithの挙動
- #[derive()]はstructごとに必要？
- timerなどのリソースの