
<p align="center">
  <a href="http://en.obins.net/obinslab-starter" target="blank"><img src="./obinslab.png" width="320" alt="Obinslab Logo" /></a>
</p>

# Obinslab Starter Translations

[English](./README.md) | [简体中文](./README-zh_CN.md) | [Español](./README-es.md) | [Deutsch](./README-de.md) | [Русский](./README-ru.md) | [Français](./README-fr.md) | ไทย

นี้คือโครงการแปลภาษาสำหรับ [Obinslab Starter](http://en.obins.net/obinslab-starter).

Obinslab Starter ให้คุณปรับแต่งรูปแบบแป้นพิมพ์เอฟเฟกต์แสงและมาโครสำหรับ ANNE PRO2 ของคุณ

ติดตาม <a href="https://twitter.com/obinslab" target="_blank"><img src="https://img.shields.io/twitter/follow/obinslab.svg?style=social&label=obinslab"></a> บน Twitter สำหรับการประกาศที่สำคัญ

## วิธีเริ่มการแปล
ตรวจสอบว่าไฟล์แปลสำหรับภาษาของคุณมีอยู่แล้วในโฟลเดอร์ `locales` หากมีอยู่แล้วเพียงแค่ปรับเปลี่ยน; ถ้าไม่ทำเช่นนั้นให้โคลน `en.yml` เป็น `language-code.yml`

ตัวอย่างเช่น: หากคุณต้องการสร้าง/อัปเดต ภาษา `Japanese` เพียงแค่แก้ไขชื่อไฟล์เป็น `ja.yml`.

Obinslab Starter ใช้ไลบรารี `l10n_util` ของ Chromium เพื่อดึงข้อมูลสถานที่ ที่เป็นไปได้

`language-code` มีระบุไว้ตามด้านล่างนี้:

| Language Code | Language Name |
|---------------|---------------|
| af | Afrikaans |
| am | Amharic |
| ar | Arabic |
| az | Azerbaijani |
| be | Belarusian |
| bg | Bulgarian |
| bh | Bihari |
| bn | Bengali |
| br | Breton |
| bs | Bosnian |
| ca | Catalan |
| co | Corsican |
| cs | Czech |
| cy | Welsh |
| da | Danish |
| de | German |
| de-AT | German (Austria) |
| de-CH | German (Switzerland) |
| de-DE | German (Germany) |
| el | Greek |
| en | English |
| en-AU | English (Australia) |
| en-CA | English (Canada) |
| en-GB | English (UK) |
| en-NZ | English (New Zealand) |
| en-US | English (US) |
| en-ZA | English (South Africa) |
| eo | Esperanto |
| es | Spanish |
| es-419 | Spanish (Latin America) |
| et | Estonian |
| eu | Basque |
| fa | Persian |
| fi | Finnish |
| fil | Filipino |
| fo | Faroese |
| fr | French |
| fr-CA | French (Canada) |
| fr-CH | French (Switzerland) |
| fr-FR | French (France) |
| fy | Frisian |
| ga | Irish |
| gd | Scots Gaelic |
| gl | Galician |
| gn | Guarani |
| gu | Gujarati |
| ha | Hausa |
| haw | Hawaiian |
| he | Hebrew |
| hi | Hindi |
| hr | Croatian |
| hu | Hungarian |
| hy | Armenian |
| ia | Interlingua |
| id | Indonesian |
| is | Icelandic |
| it | Italian |
| it-CH | Italian (Switzerland) |
| it-IT | Italian (Italy) |
| ja | Japanese |
| jw | Javanese |
| ka | Georgian |
| kk | Kazakh |
| km | Cambodian |
| kn | Kannada |
| ko | Korean |
| ku | Kurdish |
| ky | Kyrgyz |
| la | Latin |
| ln | Lingala |
| lo | Laothian |
| lt | Lithuanian |
| lv | Latvian |
| mk | Macedonian |
| ml | Malayalam |
| mn | Mongolian |
| mo | Moldavian |
| mr | Marathi |
| ms | Malay |
| mt | Maltese |
| nb | Norwegian (Bokmal) |
| ne | Nepali |
| nl | Dutch |
| nn | Norwegian (Nynorsk) |
| no | Norwegian |
| oc | Occitan |
| om | Oromo |
| or | Oriya |
| pa | Punjabi |
| pl | Polish |
| ps | Pashto |
| pt | Portuguese |
| pt-BR | Portuguese (Brazil) |
| pt-PT | Portuguese (Portugal) |
| qu | Quechua |
| rm | Romansh |
| ro | Romanian |
| ru | Russian |
| sd | Sindhi |
| sh | Serbo-Croatian |
| si | Sinhalese |
| sk | Slovak |
| sl | Slovenian |
| sn | Shona |
| so | Somali |
| sq | Albanian |
| sr | Serbian |
| st | Sesotho |
| su | Sundanese |
| sv | Swedish |
| sw | Swahili |
| ta | Tamil |
| te | Telugu |
| tg | Tajik |
| th | Thai |
| ti | Tigrinya |
| tk | Turkmen |
| to | Tonga |
| tr | Turkish |
| tt | Tatar |
| tw | Twi |
| ug | Uighur |
| uk | Ukrainian |
| ur | Urdu |
| uz | Uzbek |
| vi | Vietnamese |
| xh | Xhosa |
| yi | Yiddish |
| yo | Yoruba |
| zh | Chinese |
| zh-CN | Chinese (Simplified) |
| zh-TW | Chinese (Traditional) |
| zu | Zulu |

## วิธีดูตัวอย่างการแปลของคุณ

1. ใส่ไฟล์ `language-code.yml` ในโฟลเดอร์ `locales` ภายใต้ `Resources` แก้ไข `locales.json` และเพิ่มภาษาของคุณทั้ง `id` แล้วก็ `name`

    โฟลเดอร์ `locales` จะอยู่ที่:
    - Windows
    `C:\Program Files\Obinslab Starter\resources\locales`

    - Mac Osx
    `/Applications/Obinslab Starter.app/Contents/Resources/locales`


2. ปิด/เปิด Obinslab Starter, จากนั้นไปที่ `preferences`, เลือกภาษาใหม่

## คุณจะเข้าร่วมได้อย่างไร?

Fork -> Modify -> Pull request
