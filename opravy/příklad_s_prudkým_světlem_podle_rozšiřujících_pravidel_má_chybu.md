### Chyby v příkladu u Rozšiřujících pravidel pro vidění

#### PPH verze 1.0, edice B

Na stránce 130 vpravo je
[výčet ras a jejich postihů při ostrém světle s kontrastem 80](https://pph.drdplus.jaroslavtyc.com/#postih_za_uplnou_tmu).

> Naopak při extrémně ostrém magickém světle s Kvalitou 80 budou mít lidé a hobiti postih −2, elfové a krollové −3,
trpaslíci −4 a skřeti −5.

V samotné kapitole [*Rozšiřující pravidla pro vidění*](https://pph.drdplus.jaroslavtyc.com/#rozsirujici_pravidla_pro_videni)
není zmínka o zaokrouhlování pro výsledný kontrast, respektive postih, takže zkusíme reverzní inženýrství podle příkladů.

Při [běžném zaokrouhlování](https://pph.drdplus.jaroslavtyc.com/#zaokrouhlovani) ale pro lidi a hobity vychází postih
vyšší a to -3 a pro změnu při [zaokrouhlování dolů](https://pph.drdplus.jaroslavtyc.com/#zaokrouhlovani_dolu_a_nahoru)
vychází pro trpaslíky postih nižší a to -3.

Pokud vyzkoušíme obě pravidla na příklad s absolutní tmou, kdy by měla **každá** rasa mít nejvyšší možný postih -20
(když pomineme vliv infravidění), tak jediné možné zaukrouhlování
je [běžné]((https://pph.drdplus.jaroslavtyc.com/#zaokrouhlovani)), tedy od poloviny nahoru.

###### Řešení
Aby příklad vycházel správně s uvedenými postihy, stačí změnit kvalitu extrémně ostrého magického světla z 80 na 79:

> Naopak při extrémně ostrém magickém světle s Kvalitou **79** budou mít lidé a hobiti postih −2, elfové a krollové −3,
trpaslíci −4 a skřeti −5.

#### Odlišnosti mezi zjednodušenými a rozšiřujícími pravidly pro vidění

Ovšem ve zjednodušených pravidlech kapitole [Oslnění](https://pph.drdplus.jaroslavtyc.com/#oslneni) na straně 128 vpravo
se u [výpočtu kontrastu](https://pph.drdplus.jaroslavtyc.com/#zaokrouhleni_kontrastu_pro_oslneni)
výslovně uvádí zaokrouhlování dolů, konkrétně při výpočtu kontrastu a tím i postihu:

> Dělení deseti se jednoduše udělá tak, že se vynechá poslední číslice. V minulém příkladu se tak z hodnoty
80 stalo 8.

Výsledné postihy se pak liší o jedničku oproti těm
z [*Rozšiřujících pravidel pro vidění*](https://pph.drdplus.jaroslavtyc.com/#rozsirujici_pravidla_pro_videni) a přitom zbytečně.
Není valný důvod zaokrouhlovat dolů, snad jen kvůli mírňouličkému zjednodušení výpočtu.

###### Řešení
Navrhujeme proto toto speciální zaokrouhlování úplně vypustit, aby byly výsledky napříč zjednodušenými a rozšířenými
pravidly sjednoceny.

Tím se mírně upraví některé popisy a příklady:

V kapitole [Oslnění](https://pph.drdplus.jaroslavtyc.com/#oslneni) namísto
>Dělení deseti se jednoduše udělá tak, že se vynechá poslední číslice. V minulém příkladu se tak z hodnoty 80 stalo 8.

použít
> Při dělení deseti zaokrouhluj běžným způsobem, od poloviny nahoru. Kdybvy v minulém příkladu byl rozdíl kvalit
světla 85, byl by kontrast už 9.

V kapitole [Postihy za nedostatečné světlo](https://pph.drdplus.jaroslavtyc.com/#postihy_za_nedostatecne_svetlo)
 v příkladu namísto
> Rozdíl je 0 − (−28) = 28, bez poslední číslice 2. Kontrast je 2 a zloděj si tedy bude započítávat postih −2.

použít
> Rozdíl je 0 − (−28) = 28, po zaokrouhlení 3. Kontrast je 3 a zloděj si tedy bude započítávat postih −3.

### Nedostatečný příklad v Rozšiřujících pravidlech s úplnou tmou
> *Opakování je matkou moudrosti*

Navíc v příkladu s úplnou tmou chybí zopakování, že postih -20 je sice číselně správně, ale trpaslíci a skřeti budou
nejspíše moci používat svoji infravizi. Navrhujeme proto za větu
> Vidíme tedy, že po přizpůsobení na okolní podmínky budou mít v úplné tmě (Kvalita osvětlení −200) všechny rasy postih −20.

přidat 

> Připomínáme, že pro trpaslíky a skřety bude postih nejspíš "pouze" -17, pokud budou moci použít své
[infravidění](https://pph.drdplus.jaroslavtyc.com/#infravideni).

(5. 1. 2016)