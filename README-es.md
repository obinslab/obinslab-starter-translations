<p align="center">
  <a href="http://en.obins.net/obinslab-starter" target="blank"><img src="./obinslab.png" width="320" alt="Obinslab Logo" /></a>
</p>

#  Traducciones Obinslab Starter 

English | [简体中文](./README-zh_CN.md) | [Español](./README-es.md)

Es un proyecto de traducción para [Obinslab Starter](http://en.obins.net/obinslab-starter).

Obinslab Starter te permite personalizar distribuciones de teclado, efectos de ilumninacion y macros en tu ANNE PRO2.

Siguenos <a href="https://twitter.com/obinslab" target="_blank"><img src="https://img.shields.io/twitter/follow/obinslab.svg?style=social&label=obinslab"></a> en Twitter para avisos importantes.

## Como comenzar una traducción
Comprueba si existe ya un archivo de traducción para tu idioma en el directorio `locales`. Si existe , realiza la modificación sobre este; Si no, clona `en.yml` a `codigo-idioma.yml`

Por ejemplo: Si quieres crear/actualizar el idioma `Japones`, simplemente edita el archivo `ja.yml`.

Obinslab Starter usa la libreria `l10n_util` de Chromium para extraer el lugar.Los posibles
`language-code` son los siguientes:

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

## Como previsualizar tu traducción

1. Coloca el archivo `language-code.yml` en el directorio `locales` dentro de `Resources`. Edita `locales.json`, y añada el `id` y `name`.

    El directorio `locales` normalmente se encuentra en:
    - Windows
    `C:\Program Files\Obinslab Starter\resources\locales`

    - Mac Osx
    `/Applications/Obinslab Starter.app/Contents/Resources/locales`


2. Inicie/Reinicie Obinslab Starter, vaya a `preferences`, selecione el nuevo idioma

## Contribuciones

Fork -> Modify -> Pull request
