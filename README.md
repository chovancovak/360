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

## Současná struktura webu

Samostatné stránky konkrétních kroužků a akcí jsou přístupné ze stránky **Co se děje**. Nemusejí mít vlastní položku v hlavní navigaci.
- **Úvod** — představení projektu, hlavní myšlenka, principy a výzva k zapojení.
- **360** — stránka věnovaná významu linky a cestě projektu.
- **Zastávky** — místa na trase Linky 360 a jejich význam pro projekt.
- **O nás** — představení současné komunity, Karolíny, Kamila a přístupu k soukromí ostatních rodin a dětí.
- **Co se děje** — pravidelná setkávání rodin, aktuální aktivity a prostor pro další společné výpravy a události.
- **Blog** — články a záznamy zkušeností.
- **Přidejte se** — kontakt a cesta pro rodiny, které se chtějí ozvat.
- **Ochrana osobních údajů** — informace o zpracování údajů zájemců a účastníků aktivit Linky 360.


### Zažij asijskou divočinu

První samostatnou akcí zveřejněnou na webu je podzimní venkovní kroužek **Zažij asijskou divočinu**.

Děti při něm prostřednictvím velké mapy, zahrady, příběhů, knih, realistických modelů zvířat, přírodních materiálů a skutečných nástrojů objevují různé oblasti a ekosystémy Asie. Program reaguje na počasí, proměnu ročního období i zájem konkrétní skupiny.

Stránka obsahuje podrobnosti o programu, přístupu k dětem, venkovním zázemí, vybavení, termínech, průvodcích a podmínkách účasti. Součástí je také krátký formulář pro projevení zájmu.

## Technické řešení

Web je jednoduchý statický projekt postavený v Eleventy a stylovaný pomocí SCSS.

### Metadata, sdílení a vyhledávače

Společná metadata webu jsou uložena v souboru `_data/site.json`. Obsahuje název a adresu webu, výchozí titulek, popis, Open Graph obrázek a případný ověřovací kód pro Google Search Console.

Společná část `<head>` dynamicky pracuje s údaji jednotlivých stránek. Podporuje zejména:

* jazyk stránky pomocí `lang`;
* vlastní titulek a SEO titulek;
* popis stránky;
* kanonickou adresu;
* pravidla indexace;
* Open Graph metadata pro sdílení;
* Twitter/X Card;
* vlastní OG obrázek stránky;
* favicony a Apple Touch Icon;
* budoucí propojení jazykových variant pomocí `hreflang`.

Jednotlivé stránky mohou ve front matteru používat například:

---
title: Zažij asijskou divočinu
description: Podzimní venkovní kroužek v Kňovicích, při kterém děti objevují zvířata, krajinu a ekosystémy Asie.
ogImage: /img/asie/og-asijska-divocina.jpg
ogImageAlt: Panda před velkou mapou Asie – Zažij asijskou divočinu.
lang: cs
navKey: co-se-deje
---


Pokud stránka nemá vlastní `ogImage`, použije se společný obrázek:

/img/og-linka-360.jpg

Oba OG obrázky mají rozměr 1200 × 630 px a barevný profil sRGB.

Web používá tyto ikony:

/img/favicon-32.png
/img/favicon-512.png
/img/apple-touch-icon.png


SVG favicon se v současné verzi nepoužívá.

Stránky, které nemají být součástí výsledků vyhledávání, například děkovací stránka po odeslání formuláře, používají:


---
noindex: true
---

Šablony `sitemap.njk` a `robots.njk` při sestavení webu automaticky vytvářejí veřejné soubory:

/sitemap.xml
/robots.txt

### Plánovaná anglická verze

Do budoucna se počítá s anglickou verzí webu. České stránky zůstanou na současných adresách a anglické stránky budou umístěny pod `/en/`.

Předpokládaná struktura:

/o-nas/       česká verze
/en/about/    anglická verze


Layout už podporuje dynamický jazyk dokumentu a Open Graph locale. Výchozím jazykem je čeština:

<html lang="{{ lang or 'cs' }}">

Anglické stránky budou ve front matteru používat:

---
lang: en
---

Vzájemně přeložené stránky bude možné propojit pomocí:

translations:
  cs: /o-nas/
  en: /en/about/


Z těchto údajů se v `<head>` automaticky vytvoří odkazy `hreflang`. Každá jazyková stránka musí mít vlastní kanonickou adresu. Návštěvníci nebudou automaticky přesměrováváni podle jazyka prohlížeče; jazyk si budou moci zvolit pomocí odkazu na webu.

Samotný anglický obsah, překlad navigace a přepínač jazyků zatím nejsou vytvořené.


### Formuláře

Krátký formulář na stránce Asijské divočiny využívá **Netlify Forms**. Formulář je součástí statického HTML a Netlify jej rozpozná při sestavení a nasazení webu.

Formulář obsahuje:

- jméno a věk dítěte;
- jméno zákonného zástupce;
- e-mail a telefon;
- prostor pro dotaz nebo důležitou poznámku;
- odkaz na informace o zpracování osobních údajů;
- skryté honeypot pole pro základní ochranu proti spamu.

Po odeslání je uživatel přesměrován na stránku `/dekujeme/`.

Podrobná závazná přihláška bude rodičům odeslána až po potvrzení volného místa. Bude vytvořena samostatně prostřednictvím Google Forms a nebude veřejnou součástí webu.

### Hlavní soubory a složky

web360/
├── _includes/
│   ├── layouts/
│       └── home.njk
│   └── partials/
│       ├── footer.njk
│       ├── head.njk
│       ├── line-hero.njk
│       └── menu.njk
├── _site/
├── akce/
│   ├── dekujeme.html
│   └── asie.html
├── css/
├── img/
│   ├── 360linka.svg
│   ├── og-linka-360.jpg
│   ├── favicon-32.png
│   ├── favicon-512.png
│   ├── apple-touch-icon.png
│   ├── karolina-linka-360.jpg
│   ├── kamil-linka-360.jpg
│   ├── principy/
│   └── asie/
│       └── og-asijska-divocina.jpg
├── scss/
│   ├── _asie.scss
│   ├── _base.scss
│   ├── _boundaries.scss
│   ├── _co-se-deje.scss
│   ├── _dekujeme.scss
│   ├── _footer.scss
│   ├── _hero.scss
│   ├── _homepage.scss
│   ├── _join.scss
│   ├── _menu.scss
│   ├── _o-nas.scss
│   ├── _ochrana-osobnich-udaju.scss
│   ├── _page-360.scss
│   ├── _stops.scss
│   ├── _variables.scss
│   └── style.scss
├── .eleventy.js
├── 360.html
├── blog.html
├── co-se-deje.html
├── index.html
├── o-nas.html
├── ochrana-osobnich-udaju.html
├── pridejte-se.html
├── zastavky.html
├── package.json
├── package-lock.json
├── robots.njk
├── sitemap.njk
└── README.md

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


### Hlavní navigace

Hlavní navigace rozlišuje mezi právě otevřenou stránkou a výzvou k zapojení.

Aktivní stránka je označena malou žlutou tečkou připomínající zastávku na trase. Odkaz **Přidejte se** má podobu žlutého zaobleného tlačítka. Je tak zvýrazněný jako výzva k akci, aniž by působil jako stále aktivní položka menu. Na samotné stránce Přidejte se se jeho barevnost obrátí.

Aktivní položka se nastavuje v úvodních údajích jednotlivých stránek pomocí proměnné `navKey`:


---
navKey: o-nas
---

### Animovaná linka v záhlaví

Výrazným prvkem úvodní stránky je SVG grafika `img/360linka.svg`, vložená prostřednictvím partialu `partials/line-hero.njk`. Při načtení stránky se žlutá linka postupně vykresluje, obtáčí hlavní sdělení a vytváří nedokonalý kruh. Animace podporuje představu pohybu, cesty a postupného vznikání projektu. Kruh není dokonale geometrický ani uzavřený jedním přesným tahem — stejně jako Linka 360 zůstává živá, otevřená a proměnlivá.


## Stav projektu

Projekt i web jsou v rané fázi. Základní směr, hodnoty, vizuální identita a struktura už existují, konkrétní podoba komunity se ale bude dál vyvíjet podle zkušeností zapojených rodin.

> Linka 360 je cesta. Občas bloudíme. Občas improvizujeme. Ale dává nám smysl.


### Ochrana osobních údajů

Stránka `/ochrana-osobnich-udaju/` popisuje zpracování údajů zájemců a přihlášených účastníků aktivit Linky 360.

První veřejný formulář sbírá pouze údaje potřebné pro vyřízení zájmu a navazující komunikaci. Podrobnější údaje, včetně fakturačních a zdravotních informací, se zjišťují až po přijetí dítěte.

Souhlas se zpracováním zdravotních údajů a případný souhlas s fotografováním musí být vedeny samostatně. Souhlas s fotografováním není podmínkou účasti dítěte.

Odpovědi z formulářů se nemají uchovávat déle, než je nutné pro uvedený účel.


### Organizace SCSS

Styly jsou rozdělené podle společných částí webu a jednotlivých stránek. Každý modul se připojuje v souboru `style.scss` pomocí `@use`.

Příklady:

scss
@use "variables";
@use "base";
@use "menu";
@use "hero";
@use "homepage";
@use "asie";
@use "ochrana-osobnich-udaju";
@use "dekujeme";
@use "footer";


### Plánované technické úpravy

- Vytvořit společný modul `_buttons.scss` pro opakovaně používané třídy `.button` a `.button--primary`.
- Přesunout do společných modulů také opakované styly kontejnerů, pokud se budou objevovat na dalších stránkách.
- Odstranit následně duplicitní definice tlačítek z `_asie.scss` a `_dekujeme.scss`.
- Otestovat Netlify Forms na veřejně nasazeném webu a nastavit e-mailové upozornění.
- Po potvrzení podoby kroužku doplnit medailonek Kamila a referenci rodiče.

* Připojit doménu `linka360.cz` ke Google Search Console pomocí DNS ověření.

* Po ověření webu odeslat sitemapu do Google Search Console a zkontrolovat indexaci hlavních stránek.

* Vytvořit anglickou verzi webu pod `/en/`.

* Doplnit přepínač mezi českou a anglickou verzí stránky.

* Přeložit navigaci a společné části layoutu.
