
[`Bemutató videó megtekintése a YouTube-on`](https://youtu.be/uN3GkA_Afuw)
[`Online dokumentáció`](https://colaorange.gitbook.io/daily-money-one-doc/eng)

## Alapelvek

A Daily Money fő alapelvei rendkívül egyszerűek, mindössze három van belőlük:

> 1. Egy vagy több `Könyv`
> 2. Különböző `Számlák` a könyveken belül
> 3. Összegek átvitele a különböző számlák között, és ezen `Tranzakciók` rögzítése

## ![Könyvek](icon:///notebook-multiple) Könyvek

Legalább egy Könyv szükséges, amelyben a számlák azonos pénznemmel rendelkeznek. Igényeid szerint több, azonos pénznemű Könyvet is létrehozhatsz.

## ![Számlák](icon:///bookmark-multiple) Számlák

Öt különböző típusú számla létezik, amelyeket a számlakezelő képernyőn adhatsz hozzá, szerkeszthetsz vagy törölhetsz.

> - `Bevétel`: Fizetés stb.
> - `Kiadás`: Étel, szórakozás stb.
> - `Eszköz`: Készpénz, bank stb.
> - `Kötelezettség`: Hitelkártyák, hitelek stb.
> - `Egyéb`: ...

* A számlanevekben használhatsz pontot (.) az elválasztáshoz (pl. Étel.Étterem, Étel.Összejövetel), ami szebb hierarchikus megjelenítést biztosít a számlák kiválasztásakor vagy az egyenlegkimutatások megtekintésekor.
* Rendezheted a számlákat, hogy a gyakrabban használtak kerüljenek előtérbe.

## ![Tranzakciók](icon:///receipt) Tranzakciók

Ha tranzakció történik a számlák között – például költés, pénzmozgatás a számlák között, vagy hitelkártyás fizetés (pl. elköltöttél 320 forintot egy étkezésre) –, használd az `Új tranzakció` lehetőséget egy új tranzakció létrehozásához.
> - Válaszd ki a `Dátum és idő` mezőt: a tranzakció dátuma és ideje.
> - Válaszd ki a `Forrás` mezőt: Készpénz
> - Válaszd ki a `Cél` mezőt: Étkezés
> - Add meg az `Összeg` mezőt: 320
> - Add meg a `Jegyzet` mezőt: Összejövetel a barátokkal
> - Kattints a `Létrehozás` gombra.

## Példák

### Fizetés átutalása a bankba

> Forrás `Bevétel` számla: Fizetés
> Cél `Eszköz` számla: Bank

### Készpénz felvétele bankból

> Forrás `Eszköz` számla: Bank
> Cél `Eszköz` számla: Készpénz

### Telefon vásárlása hitelkártyával

> Forrás `Kötelezettség` számla: Hitelkártya
> Cél `Kiadás` számla: Elektronika

### Hitelkártya-számla kiegyenlítése bankból

> Forrás `Eszköz` számla: Bank 
> Cél `Kötelezettség` számla: Hitelkártya

## ![Egyenlegkimutatás](icon:///scale-balance)![Egyenlegdiagram](icon:///chart-pie) Egyenlegkimutatás és diagram

A szorgalmas könyvelés révén az alkalmazás segít rögzíteni az összes tranzakció részleteit, és a keresési feltételek alapján egyenlegkimutatást készít. Ez a kimutatás egyértelműen mutatja az eszközök és kötelezettségek egyenlegét a különböző időszakokban, így jobban átláthatod a pénzügyi helyzetedet. Ezenkívül az alkalmazás különféle diagramokat is tud készíteni, amelyek vizuálisan ábrázolják a bevételeidet és kiadásaidat, megkönnyítve a pénzmozgások megértését.

## Számlák kezdő egyenlege

Amikor először használod az alkalmazást, előfordulhat, hogy már rendelkezel néhány valós egyenleggel rendelkező számlával, mint például banki betétek, készpénz vagy hitelkártya-tartozások. Annak érdekében, hogy az egyenlegkimutatás pontosabb számítási eredményeket mutasson, használhatod a számlák inicializálása funkciót, amellyel beállíthatod ezen számlák helyes kezdő egyenlegét. Így elérheted, hogy az egyenlegkimutatás a valós pénzügyi helyzetet tükrözze.

## Egy-a-többhöz megosztás (Haladó)

Esetenként egyetlen kiadás több különböző kiadási kategóriát is érinthet. Például egy szupermarketben történő vásárlás során egyszerre vehetsz élelmiszert, napi szükségleti cikkeket és elektronikai termékeket is. Ennek kezelésére az alkalmazás haladó tranzakciószerkesztést biztosít, amellyel egyetlen kiadást több különböző kiadási kategóriához rendelhetsz. Más szóval, egyetlen hitelkártyás vásárlás összegét feloszthatod például élelmiszerre, napi szükségletekre és elektronikai cikkekre. Kérjük, vedd figyelembe: Az ugyanazon a könyvön belüli tranzakcióknál – mivel a pénznemek megegyeznek – a kimenő (forrás) összegek összegének meg kell egyeznie a bejövő (cél) összegek összegével, különben a program elutasítja a tranzakció létrehozását.

## Átvitel könyvek között

A program lehetővé teszi a különböző könyvekben lévő számlák közötti átvitelt is. Akár az alap, akár a haladó tranzakciószerkesztő vagy -létrehozó képernyőn vagy, a számlák kiválasztásakor választhatsz számlákat más könyvekből is. Mivel a különböző könyvek pénznemei eltérhetnek, és az átváltási árfolyam nem rögzített (például ha forintról euróra utalsz), a program nem korlátozza a tranzakció létrehozását az alapján, hogy a kimenő és bejövő összegeknek meg kell egyezniük. Kérjük, a tranzakciók létrehozásakor a tényleges összegek alapján járj el, és légy körültekintő.

## Egyenlegkimutatások és diagramok gyorsnézete

Az egyenlegkimutatás vagy a diagramok böngészése közben bizonyos számlaelemeket hozzáadhatsz a Kezdőlap Gyorsnézetéhez [*1]. Egyszerűen húzd jobbra az elemet az egyenlegkimutatásban, és kattints a `Hozzáadás a gyorsnézethez` gombra, vagy kattints a diagram kártya jobb felső sarkában található „Hozzáadás a gyorsnézethez” ikonra. Ezután a Kezdőlapon láthatod majd az adott elem eszközeinek és kötelezettségeinek egyenlegét, illetve a Kezdőlap diagram oldalán is megtekintheted azt. Ezenkívül rendezheted vagy eltávolíthatod ezeket az elemeket a `Beállítások > Kezdőképernyő` menüpontban.

[*1] Túl sok Gyorsnézet elem a Kezdőlapon növelheti a Kezdőlap betöltési idejét.

## Sablonok és ismétlődő ütemezések

A gyakori könyvelési műveletekhez tranzakciósablonokat állíthatsz be, így gyorsan hozzáadhatsz tranzakciókat. Rendszeresen ismétlődő könyvelési tételekhez is beállíthatsz ismétlődő ütemezési sablonokat. A program értesítést küld az esedékességkor, lehetővé téve a tranzakció gyors hozzáadását, és automatikusan ütemezi a következő esedékességet. Egyszerűen húzd balra az elemet a tranzakciólistában, koppints az `Új sablon` lehetőségre, add meg az ütemezési időt, majd hozd létre. Ezenkívül rendezheted, szerkesztheted vagy eltávolíthatod ezeket az elemeket a `Sablonok` oldalon.

## Költségkeret-beállítások

Az egyenlegkimutatás böngészése közben egyszerűen húzz jobbra egy számlát, kattints a `Költségkeret létrehozása` gombra, és válaszd ki a módot. A létrehozás után a költségkeret állását az egyenlegkimutatásban vagy a Kezdőlap Gyorsnézetében követheted nyomon. Ezenkívül rendezheted, szerkesztheted vagy eltávolíthatod ezeket a tételeket a `Költségkeretek` oldalon.
