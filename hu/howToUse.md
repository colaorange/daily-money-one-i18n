
[`Nézd meg az előzetes videót a YouTube-on`](https://youtu.be/uN3GkA_Afuw)

## Fogalmak

A Daily Money fő fogalmai nagyon egyszerűek, mindössze három van:

> 1. Egy vagy több `Számlakönyv`
> 2. Különböző `Számlák` a Számlakönyvekben
> 3. Összegek átutalása különböző számlák között, és ezeknek a `Tranzakcióknak` rögzítése

## ![Számlakönyvek](icon:///notebook-multiple) Számlakönyvek

Legalább egy Számlakönyv szükséges, ahol a számlák azonos valutában vannak. Igény szerint létrehozhatsz több Számlakönyvet ugyanabban a valutában.

## ![Számlák](icon:///bookmark-multiple) Számlák

Öt különböző típusú számla létezik, amelyeket hozzáadhatsz, szerkeszthetsz vagy törölhetsz a számlakezelő képernyőn.

> - `Bevétel`: Fizetés, stb.
> - `Kiadás`: Élelmiszer, szórakozás, stb.
> - `Eszközök`: Készpénz, bank, stb.
> - `Kötelezettségek`: Hitelkártyák, kölcsönök, stb.
> - `Egyéb`: ...

* A számlanevek pontokkal (.) választhatók el (pl. Élelmiszer.Ebéd, Élelmiszer.Találkozó), így jobb hierarchikus megjelenítést biztosítva a számlák kiválasztásakor vagy az egyenlegjegyzékek megtekintésekor.
* A számlákat rendezheted annak érdekében, hogy a gyakrabban használt számlák előrébb kerüljenek.

## ![Tranzakciók](icon:///receipt) Tranzakciók

Ha tranzakció van számlák között, például költségek, készpénzfelvétel, betételés vagy hitelkártyás fizetés (pl. 320 jüan egy étkezésre költöttél), használd az `Új Tranzakció` funkciót az új tranzakció létrehozásához.
> - Válaszd ki a `Dátumot és Időt`: A tranzakció dátuma és ideje.
> - Válaszd ki a `Kifizető Számlát`: Készpénz
> - Válaszd ki a `Befizetett Számlát`: Ebéd
> - Add meg az `Összeget`: 320
> - Add meg a `Megjegyzést`: Barátokkal való találkozás
> - Kattints a `Létrehozás` gombra

## Példák

### Fizetés Bankra Történő Utalása

> Kifizető `Bevétel` Számla: Fizetés
> Befizetett `Eszközök` Számla: Bank

### Készpénz Felvétele a Bankból

> Kifizető `Eszközök` Számla: Bank
> Befizetett `Eszközök` Számla: Készpénz

### Telefon Vásárlása Hitelkártyával

> Kifizető `Kötelezettségek` Számla: Hitelkártya
> Befizetett `Kiadás` Számla: Elektronika

### Hitelkártya Számla Fizetése Bankból

> Kifizető `Eszközök` Számla: Bank
> Befizetett `Kötelezettségek` Számla: Hitelkártya

## ![Egyenlegjegyzék](icon:///scale-balance)![Egyenleg Diagram](icon:///chart-pie) Egyenlegjegyzék és Diagram

Szorgalmas könyvelés révén az alkalmazás segít rögzíteni az összes tranzakció részleteit, és egy egyenlegjegyzéket generál lekérdezési feltételek alapján. Ez a jegyzék világosan bemutatja az eszközök és kötelezettségek egyenlegét különböző időszakokban, lehetővé téve, hogy jobban megértsd a pénzügyi helyzetedet. Emellett az alkalmazás különféle diagramokat generál a bevételek és kiadások vizuális reprezentálásához, megkönnyítve a pénzügyi áramlás megértését.

## Számlák Kezdeti Értékei

Amikor először használod az alkalmazást, lehet, hogy már rendelkezel néhány jelenlegi számlával valós értékekkel, például banki betétekkel, kézpénzzel vagy hitelkártya adósságokkal. Annak érdekében, hogy az egyenlegjegyzék pontosabb számítási eredményeket adjon, használhatod a számlák inicializálásának funkcióját, hogy meghatározd ezeknek a számláknak a helyes kezdeti értékeit. Így az egyenlegjegyzék tükrözi a valós pénzügyi helyzetet.

## Egy-az-Több Felosztás

Néha egyetlen kiadás több kiadási kategóriát is magában foglalhat. Például, amikor bevásárolsz egy szupermarketben, egyszerre vehetsz élelmiszert, napi szükségleteket és elektronikai term

ékeket. Ennek a helyzetnek a kezelésére az alkalmazás lehetővé teszi az összetett tranzakció létrehozásának szerkesztését, lehetővé téve egyetlen kiadás több különböző kiadási kategóriára történő elosztását. Más szóval, egyetlen hitelkártyás kiadás összegét több kategóriára, például élelmiszerre, napi szükségletekre és elektronikai termékekre oszthatod fel. Kérlek, vegye figyelembe: Az azonos számlakönyvben lévő tranzakciók esetén, mivel a valuták azonosak, a kifizetett összegnek egyenlőnek kell lennie a befizetett összeggel, különben a program elutasítja a tranzakció létrehozását.

## Átutalás Számlakönyvek Között

A program lehetővé teszi az átutalást különböző számlakönyvek között. Legyen szó alap vagy összetett tranzakció szerkesztéséről vagy létrehozásáról, más számlakönyvekből is választhatsz számlákat a számlák kiválasztásakor. Mivel a különböző számlakönyvek közötti valuták értéke eltérhet, és az árfolyam pillanatnyilag nem fix, például ha történik egy átutalás Új Tajvani Dollárról Amerikai Dollárra, a program nem korlátoz téged abban, hogy olyan tranzakciót hozz létre, ahol a kifizetett összegnek egyenlőnek kell lennie a befizetett összeggel. Kérlek, hozz létre tranzakciókat a tényleges összegek alapján, és légy óvatos.

## Gyors Egyenlegjegyzék és Diagramok Megtekintése

Amikor böngészed az egyenlegjegyzéket vagy a diagramokat, hozzáadhatsz specifikus számlatételeket a gyors nézethez a kezdőképernyőn [*1]. Egyszerűen húzd jobbra az elemet az egyenlegjegyzéken, és kattints a `Hozzáadás a Gyors Nézethez` gombra, vagy kattints a kezdőképernyő bal felső sarkában található "Hozzáadás a Gyors Nézethez" ikonra a egyenleg diagram kártyán. Ezután a kezdőképernyőn láthatod az eszközök és kötelezettségek egyenlegét az adott tételnél, vagy megtekintheted a diagram oldalon a kezdőképernyőn. Emellett rendezheted vagy eltávolíthatod ezeket az elemeket a `Preferenciák > Kezdőképernyő Beállítások` menüpontban.

[*1] A túlzott gyors nézetek a kezdőképernyő betöltési idejét befolyásolhatják.