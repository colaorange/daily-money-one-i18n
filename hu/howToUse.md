[`Bevezető video megtekintese YouTube-on`](https://youtu.be/uN3GkA_Afuw)
[`Online dokumentacio`](https://colaorange.gitbook.io/daily-money-one-doc/eng)

## Fogalmak

A Daily Money fő fogalmai nagyon egyszerűek, mindossze harom van belőluk:

> 1. Egy vagy több `Könyv`
> 2. A konyvekben talalhato kulonfele `Számlak`
> 3. Összegek athelyezese különböző számlák kozott, es ezeknek a `Tranzakcióknak` a rogzitese

## ![Könyvek](icon:///notebook-multiple) Könyvek

Legalabb egy Könyvre szukseg van, amelyben a számlák azonos pénznemet hasznalnak. Igeny szerint több, azonos pénznem? Könyvet is letrehozhatsz.

## ![Számlak](icon:///bookmark-multiple) Számlak

Ot különböző számlatipus letezik, amelyeket a számlákezelő képernyőn adhatsz hozza, szerkeszthetsz vagy torolhetsz.

> - `Bevétel`: fizetes stb.
> - `Kiadás`: etel, szorakozas stb.
> - `Eszköz`: keszpenz, bank stb.
> - `Kötelezettség`: hitelkartyak, hitelek stb.
> - `Egyéb`: ...

* A számlanevekben ponttal (.) lehet elvalasztani az alszinteket (pl. Etel.Etterem, Etel.Osszejovetel), igy számlavalasztaskor es egyenlegkimutatásnal áttekinthetőbb hierarchia jelenik meg.
* A számlák sorrendezhetők, hogy a gyakrabban hasznalt számlák előrebb keruljenek.

## ![Tranzakciók](icon:///receipt) Tranzakciók

Amikor számlák kozott tranzakció tortenik, peldaul koltes, penz athelyezese vagy hitelkartyas fizetes (peldaul 320 forintot koltottel etkezesre), az `Új tranzakció` funkcioval hozz letre új tranzakciót.
> - Valaszd ki a `Datum es idő` erteket: a tranzakció datuma es ideje.
> - Valaszd ki a `Forrás` erteket: Keszpenz
> - Valaszd ki a `Cél` erteket: Etterem
> - Add meg az `Összeg` erteket: 320
> - Add meg a `Jegyzet` erteket: Bárati osszejovetel
> - Kattints a `Letrehozas` gombra

## Peldak

### Fizetes atvezetese bankba

> `Bevétel` tipusu Forrásszámla: Fizetes
> `Eszköz` tipusu Célszámla: Bank

### Keszpenzfelvetel bankbol

> `Eszköz` tipusu Forrásszámla: Bank
> `Eszköz` tipusu Célszámla: Keszpenz

### Telefon vasarlasa hitelkartyaval

> `Kötelezettség` tipusu Forrásszámla: Hitelkartya
> `Kiadás` tipusu Célszámla: Elektronika

### Hitelkartya-számla fizetese bankbol

> `Eszköz` tipusu Forrásszámla: Bank
> `Kötelezettség` tipusu Célszámla: Hitelkartya

## ![Egyenlegkimutatás](icon:///scale-balance)![Egyenlegdiagram](icon:///chart-pie) Egyenlegkimutatás es diagram

A rendszeres könyveléssel az alkalmazas segit minden tranzakció reszletet rogziteni, majd a lekerdezesi feltetelek alapjan egyenlegkimutatást keszit. Ez a kimutatas vilagosan megjeleniti az eszközok es kötelezettségek egyenleget különböző időszakokban, igy jobban átláthatod pénzügyi helyzetedet. Emellett az alkalmazas kulonfele diagramokat is keszithet a bevételek es kiadások vizualis megjelenitesehez, hogy konnyebben megertsd penzaramlasodat.

## Számlak kezdő egyenlegei

Az első hasznalatkor mar lehetnek meglévő számlaid valos ertekekkel, peldaul bankszámla-egyenleg, keszpenz vagy hitelkartya-tartozas. Ahhoz, hogy az egyenlegkimutatás pontosabb szamitasokat adjon, a számlák inicializalasaval beallithatod ezek helyes kezdő egyenleget. Igy az egyenlegkimutatás a valos pénzügyi helyzetedet tukrozheti.

## Egy-a-többhoz felosztas (halado)

Előfordulhat, hogy egyetlen kiadás több kategoriat erint. Peldaul egy szupermarketben egyszerre vasarolhatsz elelmiszert, haztartasi cikkeket es elektronikai termekeket. Erre az alkalmazas halado tranzakció-letrehozasi es szerkesztesi lehetőseget ad, amellyel egyetlen kiadást több különböző kiadási kategoriara oszthatsz. Mas szoval egy hitelkartyas vasarlas összeget több kategoria, peldaul elelmiszer, haztartasi cikk es elektronika kozott oszthatod fel. Megjegyzes: azonos konyvon beluli tranzakcióknal, mivel a pénznem azonos, a kimenő összeg teljes ertekenek meg kell egyeznie a bejövő összeg teljes ertekevel, kulonben a program elutasitja a tranzakció letrehozasat.

## Atvezetes konyvek kozott

A program lehetőve teszi az atvezetest különböző konyvek számlai kozott. Akar alap, akar halado tranzakciószerkesztő vagy -letrehozo képernyőn vagy, számlavalasztaskor mas konyvek számlait is kivalaszthatod. Mivel a különböző konyvek pénznemertekei elterhetnek, es az arfolyam nem rogzitett, peldaul új tajvani dollarrol amerikai dollarra történő atvezetesnel a program nem korlatozza, hogy a kimenő es bejövő összegek teljes erteke egyezzen. A tranzakciókat a tenyleges összegek alapjan, körültekintően hozd letre.

## Egyenlegkimutatás es diagramok gyorsnezete

Egyenlegkimutatás vagy diagramok bongeszesekor konkret számlaelemeket adhatsz hozza a Kezdőképernyő gyorsnezetehez [*1]. Egyszerően huzd jobbra az elemet az egyenlegkimutatásban, es koppints a `Hozzaadas a gyorsnezethez` gombra, vagy koppints a diagramkartya jobb felső sarkaban lévő "Hozzaadas a gyorsnezethez" ikonra. Ezutan a Kezdőképernyőn latni fogod az adott elem eszköz- es kötelezettségegyenleget, illetve a Kezdőképernyő diagramoldalan is megtekintheted. Ezeket az elemeket a `Beallitasok > Kezdőképernyő` alatt rendezheted vagy eltavolithatod.

[*1] A tul sok gyorsnezeti elem novelheti a Kezdőképernyő betoltesi idejet.

## Sablonok es ismétlődő ütemezés

Gyakori könyvelési műveletekhez tranzakciósablonokat állíthatsz be, igy gyorsabban adhatsz hozza tranzakciókat. Rendszeresen ismétlődő könyvelési műveletekhez ismétlődő ütemezés? sablonokat is letrehozhatsz. A program esedekessegkor ertesit, igy gyorsan hozzaadhatod a tranzakciót, es automatikusan beutemezi a következő esedekesseget. Ehhez huzd balra az elemet a tranzakciólistaban, koppints az `Új sablon` elemre, add meg az ütemezési időt, majd hozd letre. Ezeket az elemeket a `Sablonok` oldalon rendezheted, szerkesztheted vagy eltavolithatod.

## Költségkeret-beallitasok

Az egyenlegkimutatás bongeszese kozben huzd jobbra a számlaelemet, majd koppints a `Költségkeret letrehozasa` gombra, es válaszd ki a modot. Letrehozas utan a költségkeret előrehaladasat az egyenlegkimutatásban vagy a Kezdőképernyő gyorsnezeteben láthatód. Ezeket az elemeket a `Költségkeretek` oldalon rendezheted, szerkesztheted vagy eltavolithatod.
