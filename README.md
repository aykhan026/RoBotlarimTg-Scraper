<p align="center">
  <img src="https://telegra.ph/file/d827dfc6b2da61667a5d4.jpg" width="300" height="300">
</p>

<p align="center"><img src="https://img.shields.io/badge/Version-3.1-brightgreen"></p>
<p align="center">
  <a href="https://github.com/aykhan026">
    <img src="https://img.shields.io/github/followers/aykhan026?label=Follow&style=social">
  </a>
  <a href="https://github.com/aykhan026/RoBotlarimTg-Scraper">
    
  </a>

<div align="center">
  <h1>RoBotlarım 👨🏻‍💻</h1>
  <h1>Scraper</h1>
</div>

---
## Qeyd 
Telegraph programının işləməməsi nəticəsində artıq 
Telegramda user daşımaq minimum səviyyədədir və ancaq Azərbaycan nömrələriylə mümkündür
Bu script vaistəsiyıə +1 (fake) nömrələr vaistəsiylədə user daşıya biıəcəksiniz.
Tam Azərbaycan Dilindədir 🇦🇿


## • APİ almaq
* Brauzerlə http://my.telegram.org adresinə daxil olun
* Qeydiyyatdan keçin
* APİ id və APİ Hash kopyalayıb bir yerə qeyd edin

## • Quraşdırmaq
* Termuxu açın və kodları növbəylə yazın

`$ apt update`

`$ pkg install python git`

* "Y" yazaraq təsdiqləyin

`$ git clone https://github.com/aykhan026/RoBotlarimTg-Scraper.git`

`$ cd RoBotlarimTg-Scraper`

* Install requierments

`$ python3 setup.py -i`

* setup configration file ( apiID, apiHASH )

`$ python3 setup.py -c`

* To Genrate User Data

`$ python3 scraper.py`

* ( members.csv is default if you changed name use it )
* Send Bulk sms To Collected Data 

`$ python3 smsbot.py members.csv`

* Update Tool

`$ python3 setup.py -u`

---

