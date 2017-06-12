**Dračí doupě<sup>®</sup> , DrD<sup>TM</sup> a ALTAR<sup>®</sup> jsou zapsané ochranné známky nakladatelství [ALTAR](http://altar.cz/).**

*Pokud hledáš prostě jen nejnovější verzi Dračího doupětě, zkus [DrD 2](http://www.drd2.cz/)*

*Pokud jsi techničtější, nevadí ti hodně pravidel a chceš dotek reality, zkus [DrD+](http://www.altar.cz/drdplus/).*

*Hledáš-li živou komunitu kolem RPG, mrkni na [rpgforum.cz](http://rpgforum.cz/forum/viewforum.php?f=238), nebo rovnou na [sekci pro DrD+](rpgforum.cz).*

**Tady najdeš pouze studii *Jak zjednodušit DrD+ a zachovat jeho silné, dospělé stránky.* Kompletní pravidla tu nehledej.**

### Pokud nevlastníš pravidla DrD, prosím, kup si je - podpoříš autory a budoucnost DrD
 - [obchod.altar.cz](http://obchod.altar.cz/)
 
---

#### Z lásky k ošklivému káčátku

Pravidla DrD+ byla spásou a ránou pod pás zároveň. Jejich vydání mě zastihlo, po letech osobního dospívání, dychtivého něčeho dospělejšího a propracovanějšího než pravidla [původní, prvotní](http://www.altar.cz/drd/).

 - jsou drsná:
    - velký vliv únavy
    - smrtící těžká zranění
    - dlohodbá postižení těla i duše
    - obtížná léčba
    - náročné ovládnutí zbraně
    - důležité kvalitní osvětlení
    - ...
 - jsou postavena na přírodních zákonech, respektive na logaritmu (bonus z všemocné Tabulky zranění a únavy = 20xlog(hodnota)-10)

A jak už to bývá, když se příliš dlouho vyvíjí bez [řádného testování na lidech](http://soch.cz/blog/management/lean/lean-metody-ve-vyvoji-softwaru/), a ještě k tomu "matfizáky" (odkaz na článek s historií DrD+ hledám...), výsledek je dokonalý. A složitý. Složitě dokonalý. Dokonale složitý.

 - a proto neměla úspěch:
    - přepočet bonusů na hodnoty podle matematické funkce, respektive obrovské převodní tabulky
    - několik vzájemně se ovlivňujících pravidel pro boj, takže když v zápalu boje popadnu klacek, dalších deset minut počítám nové parametry

Přesto podle nich doteď hrajeme a nechceme jinak.

Vlastně chceme.

### Chce to revizi

- mnoha lety hraní podle prvnotních DrD jsme objevili krásu jednoduchosti
- během stejně dlouhého hraní podle DrD+ jsme se našli v drsném životě únavy a letitých zranění
- a při [přenášení pravidel do programu](https://packagist.org/search/?q=drd) jsem zjistil, jak nekonzistentní a poslepovaná pravidla DrD+ vlastně jsou

*Mají výborný základ, dobré nápady, ale jsou autem na vodík co se rozjíždí šlapáním a brzdí padákem.*

> Dobré pravidlo směr ukazuje, špatné zakazuje.

## Navrhované změny

### Opravy

- [chybí zmínka o atletice u pohybové rychlosti](./opravy/chybí_zmínka_o_atletice_u_pohybové_rychlosti_a_délky_skoku.md)
- [matoucí popis rozdílu osvětlení způsobující oslnění](./opravy/matoucí_popis_rozdílu_osvětlení_způsobující_oslnění.md)
- [ujasnit neprůhlednost a opravit příklad s ní](./opravy/příklad_s_neprůhledností_má_chybu.md)
- [opravit příklad s postihy za prudkého světla](./opravy/příklad_s_prudkým_světlem_podle_rozšiřujících_pravidel_má_chybu.md)
- [boj se dvěma zbraněmi má neúplné popisy na více místech](./opravy/boj_se_dvěma_zbraněmi_by_mel_mít_popis_na_jednom_místě.md)
- [zmínka o zlepšeném smyslu při důkladném hledání není ve vzorečku](./opravy/zmínka_o_zlepšeném_smyslu_při_důkladném_hledání_není_ve_vzorečku.md)
- [u smyslů chybí zmínka že význačný smysl nelze použít při zběžném hledání](./opravy/zopakovat_že_význačný_smysl_nelze_použít_při_zběžném_hledání.md)

### Úpravy

- [zjednodušit získání bonusu za výšku (má vliv na Rychlost a Boj)](úpravy/velikost_vs_výška.md)
- [ujasnit rozdíl mezi bonusy k Boji na blízko a na dálku](úpravy/číslo_boj_při_boji_na_blízko_a_na_dálku.md)
- [štít považovat za pouhou překážku pokud není přímo použit k obraně](úpravy/příliš_mocné_pasivní_krytí_štítem.md)
- [přípravu na oslepení ujasnit pro ostré světlo a náhlou tmu](úpravy/popis_přípravy_na_oslepení_vyvolává_otázky.md)
- [ujasnit a upřesnit skřetí citlivost na světlo](úpravy/skřetí_citlivost_na_světlo_je_matoucí.md)
- [snížit laťku obtížnosti pro nedostatečné osvětlení](úpravy/příliš_počítání_pro_světlo_a_tmu.md)
- [odstranit pravidlo povolující jediný bod únavy](úpravy/nulová_mřížka_únavy_by_měla_znamenat_smrt.md)
- [ke zranění při pádu či skoku může dojít i ze stoje](./úpravy/zranění_při_pádu_či_skoku_může_být_i_ze_stoje.md)
- [ujasnit utlumení pádu zbrojí](./úpravy/snížení_zranění_z_pádu_zbrojí_by_mělo_být_pevněji_dané.md)
- [význačný smysl by měl být použitelný i při automatickém a zběžném hledání](./úpravy/význačný_smysl_použitelný_i_při_automatickém_a_zběžném_hledání.md)
- [zoologie by měla dávat bonus k obraně, nikoli pouze ke krytu](./úpravy/zoologie_by_měla_dávat_bonus_k_obraně_namísto_pouhého_krytu.md)

... to be continued (12. 6. 2017)