# Moje jazdy

Slovenská aplikácia pre Android na meranie rýchlosti, zaznamenávanie trás a plánovanie ďalších jázd. Funguje na telefónoch s Androidom 15 a novším.

## Čo aplikácia ponúka

- **Tachometer.** Po povolení presnej polohy vidíš rýchlosť, nadmorskú výšku a stav GPS aj pred spustením záznamu. V Nastaveniach si vyber medzi analógovou stupnicou a digitálnym zobrazením s väčšími číslicami. Otvorený tachometer drží displej zapnutý aj pred spustením záznamu.
- **Záznam jazdy.** Spustíš ho tlačidlom alebo automaticky pri prekročení nastavenej rýchlosti. Počas jazdy vidíš čas, vzdialenosť a priemernú aj maximálnu rýchlosť. Rozbehnutý záznam pokračuje pri zamknutom displeji. Záznam môžeš pozastaviť a znovu spustiť na tachometri alebo v oznámení. Ručná pauza zastaví aj čas jazdy. Pri bežnom státí s aktívnym záznamom čas beží ďalej.
- **Mini tachometer.** Po odchode na plochu počas záznamu vidíš v plávajúcom okne rýchlosť a čas jazdy. V Nastaveniach si môžeš pod rýchlosťou zvoliť nadmorskú výšku, vzdialenosť, priemer alebo maximum.
- **Oznámenie o jazde.** Po povolení oznámení vidíš v systémovej lište aktuálnu rýchlosť, prejdenú vzdialenosť a čas jazdy. Jazdu môžeš ukončiť priamo z oznámenia.
- **História a prehrávanie.** Jazdy si pozrieš na 2D mape alebo v 3D teréne s vlajočkou a označenými zastávkami. Pri časovej osi si vyber rýchlosť od 0,5× do 4×. Rýchlosť môžeš meniť aj počas prehrávania a na celej obrazovke. Aplikácia si ju pamätá. Pri dlhšom spomalení vykresľovania automaticky zníži rozlíšenie 3D mapy. Zaznamenaná zastávka sa pri prehrávaní zobrazí aspoň na dve sekundy aj pri rýchlosti 4×. Na vyskúšanie je v histórii ukážková jazda cez Donovaly.
- **Mazanie jázd.** V Histórii podrž položku a vyber zmazanie alebo označenie viacerých jázd. Jednu jazdu môžeš zmazať aj z detailu. Zmazanie sa synchronizuje na zariadenia s rovnakým účtom a aktuálnou verziou aplikácie.
- **Plánovač.** Štart, cieľ a zastávky vyberieš z návrhov pri písaní, priamo na mape alebo zadaním súradníc. Zapni možnosť **Vyhnúť sa diaľniciam** alebo nastav maximálnu rýchlosť vozidla v **Nastaveniach → Plánovanie trás**. Aplikácia vypočíta vzdialenosť, čas jazdy a príchod vrátane zastávok. Maximálna rýchlosť sa použije pri odhade času po vypočítanej trase. Uložené plány môžeš zmazať po jednom aj hromadne.
- **Jazda podľa plánu.** V detaile uloženého plánu stlač **Jazdiť podľa plánu**. Spustíš záznam alebo pripojíš plán k prebiehajúcej jazde. Pri tachometri uvidíš ďalší bod, zostávajúcu vzdialenosť a odhad príchodu podľa aktuálnej polohy a času. Ťuknutím na panel vyberieš ďalší bod alebo plán odpojíš. Pôvodný harmonogram uloženého plánu zostáva zachovaný.
- **Synchronizácia cez Google Drive.** Po pripojení rovnakého Google účtu môžeš obnoviť uložené jazdy na ďalšom zariadení. Zálohy sú v skrytom priestore aplikácie `appDataFolder`.

## Inštalácia

Stiahni si súbor `Moje-jazdy-*.apk` z najnovšieho vydania, otvor ho v Androide a potvrď inštaláciu. Presnú polohu povoľ pri prvom spustení, aby mohla aplikácia zobrazovať živé údaje a zaznamenávať trasu. [Najnovšie vydanie](https://github.com/PieterAnt/moje-jazdy-releases/releases/latest)

## Aktualizácie

GitHub je predvolený zdroj aktualizácií. V **Nastaveniach → Aktualizácie → Zdroj aktualizácií** môžeš použiť vlastný odkaz alebo tlačidlo **Použiť GitHub**. Verziu a poznámky k vydaniam nájdeš v sekcii **O aplikácii**.

```text
https://github.com/PieterAnt/moje-jazdy-releases/releases/latest/download/release.json
```

Novú verziu vyhľadáš tlačidlom **Skontrolovať aktualizácie**. Aplikácia overí stiahnuté APK a odovzdá ho Androidu na potvrdenie inštalácie.

Čísla verzií majú tvar `major.minor.release`. Prehľad zmien pri každej novej verzii nájdeš po slovensky v sekcii Releases. [Všetky vydania](https://github.com/PieterAnt/moje-jazdy-releases/releases)
