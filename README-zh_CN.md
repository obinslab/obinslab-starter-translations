<p align="center">
  <a href="http://www.obins.net/obinslab-starter" target="blank"><img src="./obinslab.png" width="320" alt="Obinslab Logo" /></a>
</p>

# Obinslab Starter Translations

[English](./README.md) | 简体中文 | [Español](./README-es.md) | [Deutsch](./README-de.md) | [Русский](./README-ru.md) | [Français](./README-fr.md) | [ไทย](./README-th.md) | [Italiano](./README-it.md)

这里是 [Obinslab Starter](http://www.obins.net/obinslab-starter)的软件界面翻译项目

Obinslab Starter 是用于自定义 ANNE PRO 键盘配列、灯效、宏的桌面软件

关注我们的 Twitter<a href="https://twitter.com/obinslab" target="_blank"><img src="https://img.shields.io/twitter/follow/obinslab.svg?style=social&label=obinslab"></a> 获取最新公告。

## 如何开始翻译

检查本项目`locales`文件夹下是否已经存在翻译文件。如果文件存在，则可直接更新这个文件；如果文件不存在，则可将拷贝`en.yml`为`language-code.yml`

举例来说：我们想翻译`Japanese`，我们需要编辑名为`ja.yml`的文件

Obinslab Starter 使用 Chromium 的 `l10n_util` 库来获取语言环境。 `language-code`可能的值如下:

| Language Code | Language Name           |
| ------------- | ----------------------- |
| af            | Afrikaans               |
| am            | Amharic                 |
| ar            | Arabic                  |
| az            | Azerbaijani             |
| be            | Belarusian              |
| bg            | Bulgarian               |
| bh            | Bihari                  |
| bn            | Bengali                 |
| br            | Breton                  |
| bs            | Bosnian                 |
| ca            | Catalan                 |
| co            | Corsican                |
| cs            | Czech                   |
| cy            | Welsh                   |
| da            | Danish                  |
| de            | German                  |
| de-AT         | German (Austria)        |
| de-CH         | German (Switzerland)    |
| de-DE         | German (Germany)        |
| el            | Greek                   |
| en            | English                 |
| en-AU         | English (Australia)     |
| en-CA         | English (Canada)        |
| en-GB         | English (UK)            |
| en-NZ         | English (New Zealand)   |
| en-US         | English (US)            |
| en-ZA         | English (South Africa)  |
| eo            | Esperanto               |
| es            | Spanish                 |
| es-419        | Spanish (Latin America) |
| et            | Estonian                |
| eu            | Basque                  |
| fa            | Persian                 |
| fi            | Finnish                 |
| fil           | Filipino                |
| fo            | Faroese                 |
| fr            | French                  |
| fr-CA         | French (Canada)         |
| fr-CH         | French (Switzerland)    |
| fr-FR         | French (France)         |
| fy            | Frisian                 |
| ga            | Irish                   |
| gd            | Scots Gaelic            |
| gl            | Galician                |
| gn            | Guarani                 |
| gu            | Gujarati                |
| ha            | Hausa                   |
| haw           | Hawaiian                |
| he            | Hebrew                  |
| hi            | Hindi                   |
| hr            | Croatian                |
| hu            | Hungarian               |
| hy            | Armenian                |
| ia            | Interlingua             |
| id            | Indonesian              |
| is            | Icelandic               |
| it            | Italian                 |
| it-CH         | Italian (Switzerland)   |
| it-IT         | Italian (Italy)         |
| ja            | Japanese                |
| jw            | Javanese                |
| ka            | Georgian                |
| kk            | Kazakh                  |
| km            | Cambodian               |
| kn            | Kannada                 |
| ko            | Korean                  |
| ku            | Kurdish                 |
| ky            | Kyrgyz                  |
| la            | Latin                   |
| ln            | Lingala                 |
| lo            | Laothian                |
| lt            | Lithuanian              |
| lv            | Latvian                 |
| mk            | Macedonian              |
| ml            | Malayalam               |
| mn            | Mongolian               |
| mo            | Moldavian               |
| mr            | Marathi                 |
| ms            | Malay                   |
| mt            | Maltese                 |
| nb            | Norwegian (Bokmal)      |
| ne            | Nepali                  |
| nl            | Dutch                   |
| nn            | Norwegian (Nynorsk)     |
| no            | Norwegian               |
| oc            | Occitan                 |
| om            | Oromo                   |
| or            | Oriya                   |
| pa            | Punjabi                 |
| pl            | Polish                  |
| ps            | Pashto                  |
| pt            | Portuguese              |
| pt-BR         | Portuguese (Brazil)     |
| pt-PT         | Portuguese (Portugal)   |
| qu            | Quechua                 |
| rm            | Romansh                 |
| ro            | Romanian                |
| ru            | Russian                 |
| sd            | Sindhi                  |
| sh            | Serbo-Croatian          |
| si            | Sinhalese               |
| sk            | Slovak                  |
| sl            | Slovenian               |
| sn            | Shona                   |
| so            | Somali                  |
| sq            | Albanian                |
| sr            | Serbian                 |
| st            | Sesotho                 |
| su            | Sundanese               |
| sv            | Swedish                 |
| sw            | Swahili                 |
| ta            | Tamil                   |
| te            | Telugu                  |
| tg            | Tajik                   |
| th            | Thai                    |
| ti            | Tigrinya                |
| tk            | Turkmen                 |
| to            | Tonga                   |
| tr            | Turkish                 |
| tt            | Tatar                   |
| tw            | Twi                     |
| ug            | Uighur                  |
| uk            | Ukrainian               |
| ur            | Urdu                    |
| uz            | Uzbek                   |
| vi            | Vietnamese              |
| xh            | Xhosa                   |
| yi            | Yiddish                 |
| yo            | Yoruba                  |
| zh            | Chinese                 |
| zh-CN         | Chinese (Simplified)    |
| zh-TW         | Chinese (Traditional)   |
| zu            | Zulu                    |

## 如何语言修改过的语言包

1. 将文件`language-code.yml`放在`Resources`下的`locales`文件夹中。编辑`locales.json`，添加语言对应的`id`和`name`。

   文件夹`locales`通常在如下位置:

   - Windows `C:\Program Files\Obinslab Starter\resources\locales`

   - Mac Osx `/Applications/Obinslab Starter.app/Contents/Resources/locales`

2. 打开或重启 Obinslab Starter, 打开 `首选项`, 选择新语言

## 贡献语言包

Fork -> Modify -> Pull request
