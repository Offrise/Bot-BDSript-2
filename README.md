# BDSript 2
Official Wiki [Bot Desgainer For Discord](https://nilpointer-software.github.io/bdfd-wiki/foreword.html#foreword)
## Language Indonesia
BDScript adalah sebuah bahasa coding tetapi khusus untuk Bot Desgainer For Discord(BDFD) dan Memakai Bahasa coding BDScript lebih mudah ketimbang memakai Python, JavaScript(Node.js),DLL
Tetapi kalau ada yang mudah pasti ada bayaran nya contoh command seperti [$alwaysReplay](https://nilpointer-software.github.io/bdfd-wiki/premium/alwaysReply.html?highlight=Alwa#alwaysreply) yang mana berguna untuk membuat bot bertema Leveling(economy), Bot moderator, Bot tracker(mungkin bisa, karena aku tidak membeli permium tetapi aku langsung tau kalau kegunaan command ini lebih banyak dan membuat ku ingin membeli premium)

## Contoh:
command trigger: $alwaysReply
```BDScript
$nomention
$if[$checkContains[$message;cooking;etc]==true]
 $deletecommand
 $title[Message Containings Bad Words]
  $description[Your message Containings Bad word so i deleted your message and timeout you during `5 minute`]
 $timeout[5m;$authorID]
$endif
```
Tetapi sudah ada sih command yang berurusan dengan kata-kata buruk yaitu $checkContains, yak yang ada di contoh :), ok coba yang lain.
```BDScript
$nomention
$if[$toLowercase[$message]==$toLowercase[$getServerVar[prefix]]ping]
 $channelSendMessage[$channelID;Pong! `$ping`]
$elseif[$toLowercase[$message]==$toLowercase[$getServerVar[prefix]]time]
 $time[America/New_York]
 New York : $hour:$minute:$second
$endif
```
Sama sih seperti buat command pada umum nya, tetapi kalau ada yang sulit kenapa pilih yang mudah.
## Language English
I can't speak English but only a little, so I need the help of someone who can speak English.
This message use Google translate If there is a mistake, I'm sorry :)
