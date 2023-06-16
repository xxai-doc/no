<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

# xxAI.art

En del av nettsidekoden er åpen kildekode, velkommen til å hjelpe med å optimalisere oversettelsen.

## front-end kode

* [front-end kode](https://github.com/xxai-art/web)
* [Språkpakker for nettstedet som helhet](https://github.com/xxai-art/web/tree/main/i18n)
* [Språkpakker for påloggingsmoduler](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [Nettstedets flerspråklige dokumentasjon](https://github.com/xxai-doc)

Front-end programmeringsspråket er [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) , som legger til noen funksjoner basert på coffeescript-syntaksen, se [./coffee_plus.md](./coffee_plus.md) .

## Internasjonalisering av nettsider og dokumenter

Bygg videre på følgende 3 prosjekter

* [@w5/mdt](https://www.npmjs.com/package/@w5/mdt)

  Suffikset er `.mdt` , du kan bruke syntaksen som ligner `<+ ./coffee_plus/import.js>` for å referere til eksterne filer, og generere markdown med suffikset `.md` .

* [@w5/trmd](https://www.npmjs.com/package/@w5/trmd)

  Markdown-oversettelse vil ikke oversette koder og lenker, og vil cache oversatte setninger. Hvis oversettelsen er endret, men originalteksten ikke er endret, vil ikke endringen av oversettelsen overskrives hvis du utfører den på nytt.

* [@w5/i18n](https://www.npmjs.com/package/@w5/i18n)

  Språkfiler for å oversette `yaml` genererte nettsteder.
