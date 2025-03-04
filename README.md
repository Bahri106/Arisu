
<p align="center">
	<img src="https://telegra.ph/file/ceac8c133c2363d799f02.jpg" width="35%" style="margin-left: auto;margin-right: auto;display: block;">
</p>
<h1 align="center">Arisu Sakayanagi</h1>

This is Script of WhatsApp multi device, working with [`@adiwajshing/baileys`](https://github.com/adiwajshing/baileys)

## HEROKU BUILDPACK
```bash
heroku/nodejs
heroku/python
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest
https://github.com/clhuang/heroku-buildpack-webp-binaries.git
```

## UNTUK PENGGUNA WINDOWS/RDP

* Unduh & Instal Git [`Klik Disini`](https://git-scm.com/downloads)
* Unduh & Instal NodeJS [`Klik Disini`](https://nodejs.org/en/download)
* Unduh & Instal FFmpeg [`Klik Disini`](https://ffmpeg.org/download.html) (**Jangan Lupa Tambahkan FFmpeg ke variabel lingkungan PATH**)


```bash
git clone https://github.com/alvino-prog/Arisu
cd Arisu
npm install
```

## HOW TO CONNECT TO MONGODB WHEN RUN IN HEROKU

* Create account and database in mongodb atlas [`watch here`](https://youtu.be/rPqRyYJmx2g)
* when you already have a database, you just need to take mongourl
* Put mongourl in Procfile `worker: node . --db 'mongourl'`
* Example `worker: node . -- db 'Your Mongo URI'`
* Example `worker: node . -- db 'mongodb+srv://hisoka:arisu@arisus.axmu8.mongodb.net/?retryWrites=true&w=majority'`



## FOR TERMUX/UBUNTU/SSH USER

```bash
apt update && apt upgrade
apt install git -y
apt install nodejs -y
apt install ffmpeg -y
git clone https://github.com/alvino-prog/Arisu
cd Arisu
npm install
```

## RECOMMENDED INSTALL ON TERMUX

```bash
pkg install yarn
yarn
```

## INSTALLING
```bash
$ node .
```

## ❗ WARNING
WhatsApp bot is still in the development stage, so there are a few bugs
WhatsApp Connection (BETA, not working perfectly)

Editing Number Owner & session name in [`config.js`](https://github.com/alvino-prog/Arisu/blob/master/config.js)
Get Apikey zenz on [`zenz`](https://zenzapis.xyz/)


## THANKS TO
* [`@adiwajshing/baileys`](https://github.com/adiwajshing/baileys)
* [`Nurutomo`](https://github.com/Nurutomo)
* [`Mhankbarbar`](https://github.com/MhankBarBar)
* [`Faiz`](https://github.com/FaizBastomi)
* [`Gimenz`](https://github.com/Gimenz)
* [`rayy`](https://github.com/rayyreall)
* [`FatihArridho`](https://github.com/FatihArridho)
* [`Pa7rick`](https://github.com/pa7rickr)
* [`RidhoUhuy`](https://github.com/Atak676) 
* [`zhwzein`](https://github.com/zhwzein)
* [`CAF-ID`](https://github.com/CAF-ID)
* [`bintang`](https://github.com/Bintangp02)

```Thanks to all who have participated in the development of this script```


License: [MIT](https://en.wikipedia.org/wiki/MIT_License)

