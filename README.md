# Linka 360

Web komunitního projektu rodin kolem domácího vzdělávání na trase Sedlčany–Praha.

Linka 360 propojuje rodiny, které chtějí dětem dopřát učení skrze život, vztahy a reálný svět. Název odkazuje na autobusovou linku mezi Sedlčany a Prahou — a zároveň na cestu, která spojuje podobně naladěné rodiny.

Web: [linka360.cz](https://linka360.cz)

## Hlavní myšlenka

> Nasedáme na dětskou energii. Společnou cestou za objevováním a reálným životem.

Linka 360 není prezentovaná jako hotová škola, pevný vzdělávací systém ani univerzální návod. Je to vznikající komunita a živá cesta. Stojí na důvěře v dětskou zvídavost, učení prožitkem, respektu k individualitě a ochotě dětí i dospělých učit se společně.

Projekt nehledá „dokonalé rodiny“, ale lidi ochotné hledat cestu spolu.

## Kdo za projektem stojí

Za Linkou 360 stojí Karolína a Kamil, rodiče dvou malých dětí. Žijí v Kňovicích na trase autobusu 360, kde budují permakulturní zahradu Perma ráj.

Perma ráj je místem práce, odpočinku, setkávání, pozorování přírody a společného učení s dětmi. Z této zkušenosti vyrůstá i představa vzdělávání založeného na zahradě, výpravách, vztazích, společné práci, hře, chybách a zvědavosti.

Karolína a Kamil mají zkušenost s vedením malé páteční domškoly pro skupinu dětí. Linku 360 ale netvoří z pozice lidí, kteří mají všechny odpovědi. Jsou především rodiče hledající smysluplnou cestu pro vlastní rodinu a chtějí ji sdílet s dalšími.

## Principy Linky 360

- Opírat se o vnitřní motivaci dětí.
- Stavět na prožitku vlastní schopnosti místo na výkonu a neustálém hodnocení.
- Učit se reálným životem a v přirozených situacích.
- Brát chybu jako běžnou součást cesty.
- Respektovat individualitu a tempo každého dítěte.
- Učit se spolupracovat, domlouvat a procházet konflikty i frustrací.
- Nezapomínat na odpočinek a omezenou kapacitu dětí i dospělých.

## Hranice a svoboda

Důležitým tématem projektu je vědomé vymezování prostoru mezi dvěma krajnostmi:

- **Slepá poslušnost** — tlak, rigidní pravidla a potlačení hlasu dítěte; prostor, kde chybí svoboda.
- **Absolutní bezhranice** — chaos, nejistota a vyčerpání pro děti i dospělé; prostor, kde chybí bezpečí.

Linka 360 hledá bezpečné hranice, které chrání kapacitu dospělého a zároveň dávají dítěti svobodu růst.

## Tón komunikace

Texty mají působit lidsky, otevřeně a nehotově v dobrém slova smyslu. Projekt neslibuje dokonalé řešení a nevystupuje mentorsky. Přiznává otázky, pochybnosti, chyby i improvizaci.

Při psaní dalšího obsahu držíme zejména tyto zásady:

- mluvit z vlastní zkušenosti, ne z pozice autority nad ostatními;
- místo výkonu zdůrazňovat vztahy, prožitek a smysluplnost;
- děti neidealizovat ani nehodnotit nálepkami;
- nesklouzávat ani k rigidní výchově, ani k představě života bez hranic;
- používat konkrétní obrazy z reálného života;
- ponechávat prostor pro hledání, proměnu a nejistotu.

## Současná struktura webu

- **Úvod** — představení projektu, hlavní myšlenka, principy, příběh zakladatelů, hranice a výzva k zapojení.
- **360** — stránka věnovaná významu linky a cestě projektu.
- **Zastávky** — místa, aktivity a etapy společné cesty.
- **Kdo jsme** — podrobnější představení Karolíny, Kamila a vzniku projektu.
- **Akce** — samostatné stránky aktuálních kroužků, setkání a dalších aktivit.
- **Blog** — články a záznamy zkušeností.
- **Přidejte se** — kontakt a cesta pro rodiny, které se chtějí ozvat.
- **Ochrana osobních údajů** — informace o zpracování údajů zájemců a účastníků aktivit Linky 360.

### Zažij asijskou divočinu

První samostatnou akcí zveřejněnou na webu je podzimní venkovní kroužek **Zažij asijskou divočinu**.

Děti při něm prostřednictvím velké mapy, zahrady, příběhů, knih, realistických modelů zvířat, přírodních materiálů a skutečných nástrojů objevují různé oblasti a ekosystémy Asie. Program reaguje na počasí, proměnu ročního období i zájem konkrétní skupiny.

Stránka obsahuje podrobnosti o programu, přístupu k dětem, venkovním zázemí, vybavení, termínech, průvodcích a podmínkách účasti. Součástí je také krátký formulář pro projevení zájmu.

## Technické řešení

Web je jednoduchý statický projekt postavený v Eleventy a stylovaný pomocí SCSS.

### Hlavní soubory a složky

```text
web360/
├── _includes/          # šablony a partialy, včetně grafiky úvodní linky
├── _site/              # vygenerovaný web
├── css/                # zkompilované styly
├── img/
│   └── 360linka.svg
├── scss/
│   ├── _base.scss
│   ├── _boundaries.scss
│   ├── _footer.scss
│   ├── _hero.scss
│   ├── _homepage.scss
│   ├── _menu.scss
│   ├── _join.scss
│   ├── _variables.scss
│   └── style.scss
├── .eleventy.js
├── 360.html
├── blog.html
├── index.html
├── kdo_jsme.html
├── pridejte_se.html
├── zastavky.html
├── package.json
└── README.md
```

### Barevná paleta

| Proměnná | Hodnota | Použití |
| --- | --- | --- |
| `$color-linka-bg` | `#F4EFE6` | teplé světlé pozadí |
| `$color-linka-yellow` | `#E0B11F` | hlavní zlatá linka |
| `$color-linka-text` | `#22282B` | tmavý text |
| `$color-linka-brown` | `#4B3C29` | tmavě hnědé vybrané nadpisy |
| `$color-linka-green` | `#556B2F` | olivová navazující na zahradu |
| `$color-perma-clay` | `#B85C38` | terakotový doplňkový akcent |

### Typografie

- **Libre Baskerville** — patkové písmo pro výrazné nadpisy a vybrané akcenty.
- **Source Sans 3** — základní bezpatkové písmo pro běžný text a navigaci.

### Responzivní šířky

| Název | Hodnota |
| --- | --- |
| mobil | `576px` |
| tablet | `768px` |
| desktop | `1024px` |

## Vizuální identita



Základním motivem je žlutá linka a kruh připomínající trasu, pohyb a objevování. Vizuál má působit živě a organicky, ne technicky nebo školsky. Teplé pozadí, hnědá, olivová a terakota propojují web s přírodou a Perma rájem.

Rozvržení používá velkorysý prostor, výrazné patkové nadpisy a kratší textové bloky. Vizuální jazyk má podporovat dojem cesty a otevřeného procesu.

### Animovaná linka v záhlaví

Výrazným prvkem úvodní stránky je SVG grafika `img/360linka.svg`, vložená prostřednictvím partialu `partials/line-hero.njk`. Při načtení stránky se žlutá linka postupně vykresluje, obtáčí hlavní sdělení a vytváří nedokonalý kruh. Animace podporuje představu pohybu, cesty a postupného vznikání projektu. Kruh není dokonale geometrický ani uzavřený jedním přesným tahem — stejně jako Linka 360 zůstává živá, otevřená a proměnlivá.


## Stav projektu

Projekt i web jsou v rané fázi. Základní směr, hodnoty, vizuální identita a struktura už existují, konkrétní podoba komunity se ale bude dál vyvíjet podle zkušeností zapojených rodin.

> Linka 360 je cesta. Občas bloudíme. Občas improvizujeme. Ale dává nám smysl.

