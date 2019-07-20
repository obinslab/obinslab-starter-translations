<p align="center">
  <a href="http://en.obins.net/obinslab-starter" target="blank"><img src="./obinslab.png" width="320" alt="Obinslab Logo" /></a>
</p>

# Obinslab Starter Translations

English | [简体中文](./README-zh_CN.md) | [Español](./README-es.md) | [Deutsch](./README-de.md) | [Русский](./README-ru.md) | [Français](./README-fr.md) | [ไทย](./README-th.md)

It's a translation project for [Obinslab Starter](http://en.obins.net/obinslab-starter).

Obinslab Starter let you customize keyboard layouts, light effects and macros for your ANNE PRO2.

Follow <a href="https://twitter.com/obinslab" target="_blank"><img src="https://img.shields.io/twitter/follow/obinslab.svg?style=social&label=obinslab"></a> on Twitter for important announcements.

## How to start a translation

Check if a translation file for your language is already exist in folder `locales`. If exist, then just modify on it; If not, clone `en.yml` to `language-code.yml`

For example: If you want create/update `Japanese` language, just edit a file named `ja.yml`.

Obinslab Starter uses Chromium's `l10n_util` library to fetch the locale. Possible `language-code` are listed below:

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

## How to preview your translation

1. Put file `language-code.yml` in folder `locales` under `Resources`. Edit `locales.json`, and add your language `id` and `name`.

   Folder `locales` is usually at:

   - Windows `C:\Program Files\Obinslab Starter\resources\locales`

   - Mac Osx `/Applications/Obinslab Starter.app/Contents/Resources/locales`

2) Start/Restart Obinslab Starter, go to `preferences`, select new language

## Contribution

Fork -> Modify -> Pull request
