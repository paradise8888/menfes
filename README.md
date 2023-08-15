
![MenfessTelegramBot](https://telegra.ph/file/c793578cfabf67d292dd0.png)
# Menfess Telegram Bot
Simple Script Menfess Telegram Bot




edit file .env terlebih dahulu
```shell
nano .env
```
letakkan semua itu di file .env

```env
BOT_TOKEN = "54321:abcde" // token bot
CHANNEL = "-6969" // id channel bukan username
LINK = "t.me/garzmenfess" // link channel publik
ADMIN = [12344, 1111] // id admin untuk broadcast
DELAY = 60 // jarak waktu pengguna memposting
TAG = ["#spill", "#random", "#curhat", "#ask", "#jokes"] // tag untuk menfess


```



### Runing in Termux or Localhost

```shell
apt -y update && apt -y upgrade
apt -y install python python-pip
pip install pytelegrambotapi
pip install python-dotenv
git clone https://github.com/GarzProject/MenfessTelegramBot
cd MenfessTelegramBot
nano .env
python menfess.py
```
Jangan Lupa Jadikan Bot Sebagai Admin Di Channelmu!!
command /broadcast untuk pesan broadcast ke seluruh pengguna bot



Demo : [@GarzMenfessBot](https://t.me/GarzMenfessBot)
## Bingung??

* Jika masih bingung silahkan tanyakan kepada saya di [TELEGRAM](https://t.me/tegarprayuda)
* Menemukan error? silahkan tarik permintaan, atau bisa beritahu saya di [TELEGRAM](https://t.me/tegarprayuda)
* Ingin Bot Menfess Full Fitur? Bisa Order atau Hubungi [TELEGRAM](https://t.me/tegarprayuda)
* [garz api](https://garz.my.id/)
