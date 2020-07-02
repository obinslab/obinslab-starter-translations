<p align="center">
  <a href="http://en.obins.net/obinskit" target="blank"><img src="./obinslab.png" width="320" alt="Obinslab Logo" /></a>
</p>

# ObinsKit Translations

[English](./README.md) | [简体中文](./README-zh_CN.md) | [Español](./README-es.md) | [Deutsch](./README-de.md) | [Русский](./README-ru.md) | [Français](./README-fr.md) | [ไทย](./README-th.md) | [Italiano](./README-it.md) | 日本語

[ObinsKit](http://en.obins.net/obinskit)の翻訳プロジェクトです。

ObinsKit では、ANNE PRO 2 のキーボードレイアウト、照明効果、マクロをカスタマイズできます。

重要なお知らせについては、 <a href="https://twitter.com/obinslab" target="_blank"><img src="https://img.shields.io/twitter/follow/obinslab.svg?style=social&label=obinslab"></a> をフォローしてください。

## 翻訳を始める方法

あなたの言語の翻訳ファイルがフォルダ `locales`に既に存在しているかどうかを確認してください。 存在する場合は、修正してください。 そうでない場合は、 `en.yml`を`language-code.yml`にクローンします。

例： `Japanese`言語を作成/更新したい場合、`ja.yml`という名前のファイルを編集するだけです。

ObinsKit は、Chromium の `l10n_util`ライブラリを使用してロケールを取得します。 対応している `language-code`は以下にリストされています：

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

## 翻訳をプレビューする方法

1.ファイル `language-code.yml`を`Resources`の下のフォルダー `locales`に置きます。 `locales.json`を編集して、言語の`id`と `name`を追加します。

フォルダー `locales`は通常次の場所にあります：

- Windows `C:\Program Files\ObinsKit\resources\locales`

- Mac Osx `/Applications/ObinsKit.app/Contents/Resources/locales`

2. ObinsKit を再起動し、`設定`(または`Preferences`) に移動して、新しい言語を選択します

## Contribution

Fork -> Modify -> Pull request
