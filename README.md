# Královský klenot – mockupapp k videohře

**Author:** Tomáš Machálka
<br>**Postavy nahráli:** Tomáš Machálka a Helena Lánská
<br>Grafika byla částečně generována pomocí nástroje Leonardo AI.
<br>
<br>Gameplay je nastíněn v souboru "ukázka", ve kterém je vše rozpohybováno pomocí Powerpointu.
![asdasd](

## Děj hry
Hra vychází ze stejnojmenné povídky Tomáše Machálky, který je zároveň autorem designu.
<br>Jedná se o 2D skákací hru, která je rozčleněná na 3 levely – město, palác a sklepení
<br>Hráč hraje za postavu zloděje Kiliana Golda, jehož cílem je ukrást korunovační klenoty francouzského krále Ludvíka XV.

## Gameplay
Hráč hraje za 2D postavičku a šipkami či WASD se pohybuje po mapě. Možné je běhat do stran a skákat. Pro skok se použije frame 7 z running_cycle.
Během hraní se postava musí vyhýbat strážným + může sbírat bonusové zlaťáky. Kamera se pohybuje společně s postavou (záleží vždy, jestli postava postupuje po X-ové či Y-ové ose.

## Rozdělení hry
<ul>
    <li>Menu</li>
    <li>Level 1 – město</li>
    <li>Level 2 – palác</li>
    <li>Level 3 – sklepení</li>
</ul>
Mezi levelem 2 a 3 se nachází cutscene_1 a na konci cutscene_2.
<br>Počet stráží se s každým levelem stupňuje, v druhém a třetím levelu se mohou stráže pohybovat (nemají samostatnou animaci)
