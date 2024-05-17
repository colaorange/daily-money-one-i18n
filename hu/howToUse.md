
[`View introduction video on YouTube`](https://youtu.be/uN3GkA_Afuw)

## Fogalmak

A Daily Money fő fogalmai nagyon egyszerűek, mindössze három van:

> 1. Egy vagy több `Számlakönyv`
> 2. Különböző `Számlák` a Számlakönyvekben
> 3. Összegek áthelyezése különböző számlák között és ezeknek a `Tranzakcióknak` a rögzítése

## ![Számlakönyvek](icon:///notebook-multiple) Számlakönyvek

Legalább egy Számlakönyvre van szükség, ahol a számlák ugyanabban a pénznemegységben vannak. Igény szerint több Számlakönyvet is létrehozhat ugyanabban a pénznemegységben.

## ![Számlák](icon:///bookmark-multiple) Számlák

Öt különböző típusú számla létezik, amelyeket hozzáadhat, szerkeszthet vagy törölhet a számlakezelő képernyőn.

> - `Bevétel`: Fizetés, stb.
> - `Kiadás`: Étel, szórakozás, stb.
> - `Eszközök`: Készpénz, bank, stb.
> - `Kötelezettségek`: Hitelkártyák, kölcsönök, stb.
> - `Egyéb`: ...

* A számlanevekben használhat pontokat (.) a különválasztásra (pl. Étkezés.Vacsora, Étkezés.Barátokkal), így jobb hierarchikus megjelenítést biztosít a számlák kiválasztásakor vagy mérleglapok megtekintésekor.
* Rendezheti a számlákat, hogy előtérbe helyezze a gyakrabban használt számlákat.

## ![Tranzakciók](icon:///receipt) Tranzakciók

Amikor tranzakció történik a számlák között, például költés, pénzfelvétel, befizetés vagy hitelkártyás vásárlás (pl. 320 yuan-t költött egy étkezésre), használja az `Új Tranzakció` lehetőséget egy új tranzakció létrehozásához.
> - Válassza ki a `Dátumot és Időpontot`: A tranzakció dátuma és időpontja.
> - Válassza ki az `Átvezetés Számlát`: Készpénz
> - Válassza ki a `Cél Számlát`: Vacsora
> - Írja be az `Összeget`: 320
> - Írja be a `Megjegyzést`: Barátokkal találkozás
> - Kattintson a `Létrehozás` gombra

## Példák

### Fizetés átutalása a bankba

> Átvezetés `Bevétel` Számla: Fizetés
> Cél `Eszközök` Számla: Bank

### Készpénz felvétele a bankból

> Átvezetés `Eszközök` Számla: Bank
> Cél `Eszközök` Számla: Készpénz

### Telefonvásárlás hitelkártyával

> Átvezetés `Kötelezettségek` Számla: Hitelkártya
> Cél `Kiadás` Számla: Elektronika

### Hitelkártya számla kifizetése bankkal

> Átvezetés `Eszközök` Számla: Bank 
> Cél `Kötelezettségek` Számla: Hitelkártya

## ![Mérleg](icon:///scale-balance)![Mérleg diagram](icon:///chart-pie) Mérleg és diagram

A szorgalmas könyvelés révén az alkalmazás segít rögzíteni minden tranzakció részletét és lekérdezési feltételek szerint mérleget készíteni. Ez a mérleg világosan bemutatja az eszközök és kötelezettségek egyenlegét különböző időszakokban, lehetővé téve, hogy jobban megértse pénzügyi helyzetét. Ezenkívül az alkalmazás különféle diagramokat készíthet, hogy vizuálisan ábrázolja a bevételeit és kiadásait, megkönnyítve a pénzügyi áramlás megértését.

## Számlák kezdeti értékei

Amikor először használja az alkalmazást, előfordulhat, hogy már vannak aktuális számlái tényleges értékekkel, például bankbetétek, készpénz vagy hitelkártya-adósságok. A mérleg pontosabb számítási eredményeinek biztosítása érdekében használhatja a számlák inicializálásának funkcióját, hogy megállapítsa ezeknek a számláknak a helyes kezdeti értékeit. Ily módon a mérleg valódi pénzügyi helyzetet tükrözhet.

## Egy-az-egyben bontás

Néha egyetlen kiadás több kiadási kategóriát is magában foglalhat. Például, ha bevásárol a szupermarketben, egyszerre vásárolhat élelmiszert, napi szükségleteket és elektronikai termékeket. Az ilyen helyzet kezelésére az alkalmazás fejlett tranzakciószerkesztést biztosít, amely lehetővé teszi egyetlen kiadás több különböző kiadási kategóriára történő felosztását. Más szóval, egyetlen hitelkártya-kiadás összegét feloszthatja több kategóriára, például élelmiszer, napi szükségletek és elektronikai termékek. Kérjük, vegye figyelembe: Az azonos számlakönyvön belüli tranzakcióknál, mivel a pénznemek azonosak, az összes átvezetett összegnek meg kell egyeznie az összes bevezetett összeggel, különben a program elutasítja a tranzakció létrehozását.

## Átvezetés számlakönyvek között

A program lehetővé teszi a számlakönyvek közötti átvezetést. Akár az alap-, akár a fejlett tranzakciószerkesztési vagy létrehozási képernyőn, kiválaszthat számlákat más számlakönyvekből, amikor számlákat választ. Mivel a különböző számlakönyvek közötti pénzértékek különbözhetnek, és az árfolyam jelenleg nem rögzített, például az új tajvani dollárok átváltása amerikai dollárokra, a program nem korlátozza, hogy létrehozzon egy tranzakciót, ahol az összes átvezetett összegnek meg kell egyeznie az összes bevezetett összeggel. Kérjük, a tranzakciók létrehozásakor a valós összegek alapján járjon el és legyen óvatos.

## Gyors nézet a mérlegről és diagramokról

A mérleg vagy diagramok böngészésekor a konkrét számlatételeket hozzáadhatja a gyors nézethez a kezdőképernyőn [*1]. Egyszerűen húzza jobbra az elemet a mérlegben és kattintson az `Hozzáadás a gyors nézethez`, vagy kattintson a "Hozzáadás a gyors nézet ikonhoz" a mérleg diagramkártya jobb felső sarkában. Ezután a kezdőképernyőn látni fogja az adott tétel eszköz- és kötelezettség-egyenlegét, vagy megtekintheti a kezdőképernyő diagram oldalán. Ezenkívül rendezheti vagy eltávolíthatja ezeket a tételeket a `Beállítások > Kezdőképernyő beállításai` menüpontban.

[*1] A túl sok gyors nézet a kezdőképernyőn befolyásolhatja a kezdőképernyő betöltési idejét.
