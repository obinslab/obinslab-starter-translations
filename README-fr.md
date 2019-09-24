<p align="center">
  <a href="http://en.obins.net/obinslab-starter" target="blank"><img src="./obinslab.png" width="320" alt="Obinslab Logo" /></a>
</p>

# Traduction d'Obinslab Starter

[English](./README.md) | [简体中文](./README-zh_CN.md) | [Español](./README-es.md) | [Deutsch](./README-de.md) | [Русский](./README-ru.md) | [Finnish](./README-fi.md) | Français | [ไทย](./README-th.md) | [Italiano](./README-it.md)

Projet de traduction pour [Obinslab Starter](http://en.obins.net/obinslab-starter).

Obinslab Starter permet de personnaliser les différents layouts du clavier, les effets de rétroéclairage ainsi que les macros pour l'ANNE PRO2.

Suivez <a href="https://twitter.com/obinslab" target="_blank"><img src="https://img.shields.io/twitter/follow/obinslab.svg?style=social&label=obinslab"></a> sur Twitter pour vous tenir au courant des annonces importantes.

## Comment débuter la traduction
Vérifier si une traduction n'existe pas déjà dans votre langue dans le dossier 'locales'. Si la traduction existe déjà vous n'avez qu'a la modifier directement; Si non, dupliquer `en.yml` en `language-code.yml`

Par exemple: Si vous voulez mettre à jour la traduction française, vous n'avez qu'a éditer le fichier nommé 'fr.yml'.

Obinslab Starter utilise la librairie `l10n_util` de Chromium pour récupérer les locales.

Les variables possibles sont listées ci dessous:

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

## Comment prévisualiser votre traduction

1. Mettre le fichier `language-code.yml` dans le dossier `locales` sous `resources`. Éditer le fichier `locales.json`, et ajouter votre langue `id` et `name`.

    Le dossier `locales` est habituellement situé dans:
    - Windows
    `C:\Program Files\Obinslab Starter\resources\locales`

    - Mac Osx
    `/Applications/Obinslab Starter.app/Contents/Resources/locales`


2. Redémarrer Obinslab Starter, aller dans `preferences`, et sélectionner votre langue.

## Contribution

Fork -> Modify -> Pull request
