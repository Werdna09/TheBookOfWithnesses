# The Book of Witnesses

**Příběhový repozitář** pro temnou izometrickou pixel-artovou hru. Zatím **neobsahuje herní kód ani definitivní game design**. Nejdřív vzniká příběh, teprve z něj budou vycházet mechaniky, prostředí a nepřátelé.

> „To, že se dvě výpovědi shodují, ještě neznamená, že vznikly nezávisle.“

## O čem příběh je

Hráč je mladý putovní **Svědek**: vyšetřovatel sporných náboženských událostí. V prostředí mnoha odlišných kultů zprvu věří vlastnímu řádu a jeho důkazním postupům. První případ ve Vřesově jej přivede k mylnému závěru, protože svědectví a důkazy byly připraveny před jeho příjezdem. Teprve **neohlášený návrat** odhalí, co se stalo vyhnancům v mokřinách.

V dalších krajích hráč odhaluje, že zneužití víry není jen lokální problém. V pozadí stojí **Kapitula**, hospodářská a institucionální síť využívající různá náboženství. Také řád Svědků je do systému zapleten. Hlavní postava svět nespasí; přesto může konkrétním lidem pomáhat.

## Kde co najít

```text
docs/
  00_VIZE_A_KANON.md         Základní pravdy příběhu a autorské hranice
  01_POSTAVY_A_INSTITUCE.md  Hlavní postavy, klášter, řád, Kapitula
  02_PLAN_KAMPANE.md        Rámcová cesta po krajích (zatím návrh)
  03_OTEVRENE_OTAZKY.md     Co zatím vědomě není rozhodnuto
pribeh/
  README.md                 Konvence případů a kapitol
  pripady/
    01_Propitia_Vresov/
      PREHLED.md             Celá první kauza a její dramatická logika
      DUKAZY.md              Fakt × domněnka × inscenace
      POSTAVY.md             Vztahy, motivace, znalosti
      CASOVA_OSA.md          Kdo co ví a kdy
      LOKACE_A_ATMOSFERA.md  Mapa prostoru, vibe, opakované návštěvy
      VEDLEJSI_PRIBEHY.md    Dobrovolné lidské příběhy
      UKAZKY_DIALOGU.md      Autorské ukázky tónu dialogů
      kapitoly/
        00_Klaster_Vyslani/
        01_Vresov_Ohlasena_Navsteva/
        02_Klaster_Pochybnost/
        03_Vresov_Neohlaseny_Navrat/
        04_Klaster_Uzavreni/
```

Každá kapitola obsahuje `PRIBEH.md` (dramatická osnova a scény), `ATMOSFERA.md` (výtvarné a zvukové ladění) a `META.yaml` (strojově čitelná metadata pro pozdější tooling). V prologu je navíc `UKAZKA_SCENY.md` jako krátká ukázka prózy.

## Jak s materiály pracovat

1. Novou dějovou myšlenku nejdříve zapiš jako návrh do `docs/03_OTEVRENE_OTAZKY.md`.
2. Schválené změny promítni do `docs/00_VIZE_A_KANON.md` a konkrétního případu.
3. Pokud upravíš stopu, aktualizuj zároveň `DUKAZY.md`, `CASOVA_OSA.md` a dotčené kapitoly.
4. Nedoplňuj herní systémy ani technické zadání pro Codex dřív, než budou příběhově zdůvodněné.
5. Každou ucelenou změnu ulož do samostatného git commitu.

## První milník

Dokončit příběh **Propitia / Vřesov** jako pět kapitol a ověřit, že první mylné vyšetřování je spravedlivě vystavěné, druhý návrat má silný důvod a závěrečné uzavření nezradí pozdější odhalení Kapituly.
