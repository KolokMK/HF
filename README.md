# Házi feladat

Ebbe a könyvtárba kerül az opcionális **házi feladat** megoldása. Továbbá ide kell majd a specifikációt is elkészíteni. 

## Beadás és értékelés
> [!IMPORTANT]
> A specifikációt és a házi feladatot a laborokhoz hasonlóan pull request formájában kell beadni a határidő előtt a Moodle alatt található **Git tudnivalók** leírásban található utasítások alapján.
> - Hozz létre egy **új branchet** `megoldas` néven, és ezen dolgozz.
> - Töltsd ki a `neptun.txt` fájlt a saját Neptun kódoddal.
> - Minden egyes részegység után kommitolj, és használj értelmes kommit üzeneteket.
> - A feladat végeztével **pushold** a megoldásodat és hozz létre egy **pull requestet**.
> - Ellenőrizd a pull request tartalmát és rendeld hozzá a laborvezetődet **reviewernek**.

> [!CAUTION]
> A nem ilyen formában megadott megoldások nem lesznek értékelve!

# Specifikáció
## Feladat Informális leírása
  A feladat célja egy táborhelyeket nyílvántartó adatbázis létrehozása és karbantartása. Az adatbázisban tárolni szeretnénk Magyarország táborhelyeit ahol tudunk táborozni, illetve a táborozó csapatokat. Cél, hogy lehessen foglalni és nyílvántartsuk ezeket és, hogy tájékozódni tudjunk, hogy hová tudunk menni táborozni továbbá értékelni tudjuk a táborhelyeket.

## Elérhető funkciók
Az alkalmazás a következő funkciókat biztosítja:
* Táborhelyek:
  * Új táborhely létrehozása
  * Meglévő táborhelyek adatainak módosítása
  * Táborhely törlése
  * Táborhelyek listázása, keresés tájegység, név, és fajta alapján
  * Táborhelyek megjelenítése a térképen
  * Táborhely értékelése 0-5 skálán és rövid szöveggel
* Csapatok:
  * Új csapat létrehozása
  * Csapatadatok módosítása
  * Csapatok törlése
* Táborozás:
  * Táborhely foglalása
  * Foglalás törlése
  * Adott táborhely táborozási előzményének listázása
  
## Adatbázis séma
Az adatbáziban a következő entitásokat és attribútumokat tároljuk:
* Táborhely: név, tályegység, koordináták, fentartó, elérhetőség, rövid leírás, képek
* Csapat: név, közösség (például cserkészet, egyházközség), vezető neve, vezető telefonszáma
* Táborozás: Csapat, táborhely, táborozás kezdete, táborozás vége, létszám

![](schema.png)


## Elkészült házi feladat

A házi feladat működését bemutató videó (max. 5 perc) linkje: [Videó](https://...) 
