# egov.zilina.sk

![Žilina](https://upload.wikimedia.org/wikipedia/commons/thumb/2/29/%C5%BDilina_-_N%C3%A1mestie_A._Hlinku.jpg/1200px-%C5%BDilina_-_N%C3%A1mestie_A._Hlinku.jpg)
(image by Marcin Szala, [source](https://en.wikipedia.org/wiki/%C5%BDilina#/media/File:%C5%BDilina_-_N%C3%A1mestie_A._Hlinku.jpg))

"[Git scraped](https://simonwillison.net/2020/Oct/9/git-scraping/)" open data from [egov.zilina.sk](https://egov.zilina.sk/Default.aspx?NavigationState=1100:0:) - open eGovernment data of [Žilina, Slovakia](https://en.wikipedia.org/wiki/%C5%BDilina).

This gives us not just snapshot of the current version of the files, but also regurally updated information about their changes. This can be browsed using git(hub) and built upon later.

Example [changes](https://github.com/daddy32/egov.zilina.sk/commit/b69f3116fa0e687a0c6d90c179464a077d1f6cfc) detected in "contracts" dataset:

```diff

    "Druh": "hrobového miesta",
    "Zmluvné_strany": "Ing. Hubert Čapčík",
    "Poznámky_k_zmluve": "",
-   "Cena_celkom": "   6,64",
+   "Cena_celkom": "   6,60",
    "Mena": "EUR",
    "Dátum_podpisu": "20.11.2012",
    "Dátum_zverejnenia": "27.11.2012"
    "Druh": "hrobového miesta",
    "Zmluvné_strany": "Anna Gabajová",
    "Poznámky_k_zmluve": "",
-   "Cena_celkom": "   6,64",
+   "Cena_celkom": "   6,60",
    "Mena": "EUR",
    "Dátum_podpisu": "12.11.2012",
    "Dátum_zverejnenia": "26.11.2012"
```

## Licence

**Data**: [![License: CC BY 4.0](https://licensebuttons.net/l/by/4.0/80x15.png)](https://creativecommons.org/licenses/by/4.0/) - Creative Commons Attribution. Atribution of original data: egov.zilina.sk.
**Software**: [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0). Based on scripts by [simonw](https://github.com/simonw).
