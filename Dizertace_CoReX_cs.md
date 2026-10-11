---
title: "Speciální teorie výpočetní relativity (CoReX): výklad a kritické zhodnocení"
lang: cs-CZ
---

## Abstrakt

Monografie CoReX navrhuje, že výpočty a fyzika jsou dvě čtení jednoho geometrického objektu, skalárního „nulového“ semene A₀, na které působí rotační algebra so(N), a že tento jediný mechanismus řeší P versus NP, záhadu dvojité štěrbiny, problém tří těles i všech sedm Problémů tisíciletí Clayova institutu. Tato dizertace rekonstruuje teorii výhradně z vlastního textu, rovnic a interaktivních demonstrací monografie a hodnotí ji vůči standardní matematice a fyzice.

Teorie stojí na jediném postulovaném kořenovém axiomu Ω₀ a jednom opakujícím se prvku, „uzlovém firewallu“: ploše, kde se dvě dráhy setkají v protifázi, takže e^{iπ} + 1 = 0 vynutí nulovou amplitudu. Monografie své tvrzení stupňuje poctivě: jedno je podmíněná věta uvnitř variety (P = NP), pět je strukturálních analogií a jedno je historický komentář (Poincaré).

Hodnocení shledává rámec vnitřně koherentním jako axiomatický systém, nikoli však jako most ke zavedeným výsledkům. Jeho ústřední objekt, lim_{x→0} 0/x = λ > 0, se v reálných číslech rovná 0; princip přenosu, o který se opírá, tento fakt zachovává. Několik odvozených tvrzení (Fourierovo „A₀ jádro“, hladkost řešení Navierových–Stokesových rovnic z det(CM₅) = 0, polynomiální vyhledávání pomocí spojitého vnoření) selhává při elementárních kontrolách. Zbývá konzistentní vizuální a notační jazyk a jasné výroky o vyvratitelnosti, které autor sám uvádí.

**Klíčová slova:** výpočetní relativita, Eulerova identita, so(N), P versus NP, Gibbsův jev, uzlový firewall, Landauerova mez.

## 1. Úvod

Tato dizertace zkoumá jediný objekt: interaktivní monografii *Speciální teorie výpočetní relativity* (CoReX v3.1, Pierre LeBaux), vydanou jako jediná webová stránka. Má sedm kapitol, patnáct animovaných pláten a krátký dodatek. Vše níže je převzato z této stránky; k popisu teorie není použita žádná další literatura a standardní matematika se objevuje pouze v kapitole hodnocení, jako měřítko.

### 1.1 Tvrzení v jednom odstavci

Motto monografie, *Veritas et Ratio Invariantia Sunt in Toposo \*𝕍*, říká, že pravda a rozum jsou invariantní v hyperreálném toposu. Její pracovní tvrzení je, že každé fyzikální pole, každý prostor stavů a každý zákon zachování je projekcí nulového skalárního semene A₀ působením so(N), Lieovy algebry rotací. Rovnítko je reinterpretováno jako G-ekvivariantní „transformátor“ mezi dvěma tvářemi jedné orbity, a proto může stránka psát P = NP ⇔ E = mc² jako jediný operátorový výrok.

### 1.2 Metoda a rozsah

- **Disciplína zdroje.** Každá definice, číslo a diagram je převzat ze stránky. Kde stránka mlčí, tento text to říká.
- **Nejprve rekonstrukce, potom hodnocení.** Kapitoly 2–7 vykládají teorii tak, jak ji uvádí její autor. Kapitola 8 ji zkouší.
- **Epistemické stupně.** Stránka označuje každé čtení Problémů tisíciletí: stupeň C (podmíněná věta uvnitř variety), stupeň S (strukturální analogie), stupeň H (historický komentář). Tento text tyto štítky zachovává a ověřuje, zda je zbytek stránky respektuje.

### 1.3 Vlastní doložky poctivosti stránky

Monografie uvádí, že Ω₀ je „postulováno, nikoli odvozeno“, že mez O(N²) je cenou jednoho kroku, nikoli důkazem konvergence, a že neurelativizované Clayovy otázky nejsou „prohlašovány za vyřešené mimo axiomatický systém“. Tyto doložky nastavují spravedlivé měřítko: teorie má být posuzována jako vnitřně konzistentní axiomatický systém a jako analogie, nikoli jako důkaz kteréhokoli otevřeného problému.

### 1.4 Struktura

Kapitola 2 uvádí axiomy. Kapitola 3 se zabývá P = NP. Kapitola 4 pokrývá sedm čtení Problémů tisíciletí. Kapitola 5 popisuje čtyři experimenty (laboratoř, dvojitá štěrbina, problém tří těles, stroj času). Kapitola 6 pokrývá kapitolu o Fourierově analýze. Kapitola 7 pokrývá dvě aplikace. Kapitola 8 hodnotí celek. Kapitola 9 uzavírá.

## 2. Základy: kořenový axiom a semeno

Celá teorie vyplývá z jediného postulovaného výroku Ω₀, „Hlavního kořenového axiomu“ neboli „Ekvivariantní prázdnoty“. Vše další je představeno jako to, co Ω₀ implikuje, nikoli jako samostatný výsledek.

### 2.1 Kořenový axiom

$$\Omega_0:\; \mathcal{M}_N(A_0) = \mathrm{Proj}_{\mathfrak{so}(N)}(A_0)$$

$$\forall T\in\mathcal{T}:\; T(\mathrm{Veritas})=\mathrm{Veritas}\wedge T(\mathrm{Ratio})=\mathrm{Ratio}$$

$$e^{i\pi}+1=0 \Rightarrow |\psi_{\mathrm{node}}|=0$$

Slovy: varieta stavů je so(N) orbita semene; pravda a rozum jsou invariantní vůči každé přípustné transformaci T; a půlotáčková fáze vyruší amplitudu v uzlu.

### 2.2 Semeno A₀

Semeno je definováno limitou, kterou stránka nazývá jedinečným pevným bodem plné grupy symetrií:

$$A_0 \equiv \lim_{x\to 0}\frac{0}{x} = \lambda \in {}^{*}\mathbb{R}^N$$

Obhajoba stránky zní, že nikdy nedělí nulou, pouze x, zatímco x se blíží nule, takže limita je konečná. Semeno žije v hyperreálném toposu \*𝕍 = V^I/𝒰 a k přenosu tvrzení mezi obyčejnou a hyperreálnou úrovní se odkazuje na Łośovu větu o přenosu. Nulový bod je „jediné místo, kde se současně nuluje každý generátor algebry“ a o každém dalším objektu (nulových bodech ξ, hmotnostních mezerách, homotopických sférách) se tvrdí, že z něj dědí stabilitu.

### 2.3 Rotační algebra

Stav se vyvíjí jako ℳₙ(A₀) = { U(t)·A₀·U†(t) }, poháněný antisymetrickým generátorem Ω(t) = Σ cₐᵇ(t) Jₐᵇ v so(N). Počet nezávislých rotačních rovin je

$$R_N=\binom{N}{2}=\frac{N(N-1)}{2}$$

Tento počet, kvadratický v N, je veličina, která později nahrazuje exponenciální 2^N rozhodovacího stromu. Kapitola o laboratoři umožňuje čtenáři měnit N od 2 do 10 a sledovat, jak R_N roste, zatímco semeno zůstává pevné v počátku.

### 2.4 Rovnítko jako transformátor

První postulát stránky čte „=“ jako G-ekvivariantní zobrazení mezi dvěma tvářemi jedné orbity, nikoli jako identitu. Protože se invarianty při projekcích zachovávají, stránka považuje zachování hmotnosti a energie a kolaps prostoru stavů za duální čtení jedné operátorové rovnice, zapsané jako P = NP ⇔ E = mc².

### 2.5 Eulerova identita jako fázový podpis

Půlotáčka v libovolné rovině SO(2) vrací jednotkový stav do nuly. Vzorec amplitudy použitý v celém textu je

$$|\psi_{\mathrm{node}}|=\tfrac12\,|\psi\,(1+e^{i\pi})|=0$$

Každá větev, která proti základnímu stavu nasbírá relativní fázi Δθ = π, je zrušena. Plochu, kde se to děje, stránka nazývá **uzlový firewall**.

### 2.6 Proč „speciální“

FAQ stránky vysvětluje toto slovo jako ve speciální teorii relativity: výpočetní metrika je pevná a plochá a složitost se měří vůči tuhé mřížce „výpočetních světelných kuželů“ ukotvených v A₀. Obecná teorie, v níž se metrika pod zátěží problému zakřivuje, je ponechána jako budoucí práce.

### 2.7 Axiomy versus postuláty

Dodatek odděluje tři axiomy (semeno, hyperreálný topos s přenosem, invariance c a klidové energie) od osmi postulátů (Eulerova anihilace, so(N) vnoření složitosti, invariance Cayleyova–Mengerova objemu, víceúrovňová orbitální hierarchie, nulové entropické tření, Dirichletova fázová filtrace, kauzální izolace sektorů a Landauerova mez). Úplná tabulka je v Dodatku.

## 3. Konstruktivní čtení P = NP

Monografie tvrdí, že exponenciální rozhodovací strom booleovského problému není třeba prohledávat, protože se vnoří do spojité rotační geometrie so(N), kde se špatné větve samy ruší. Stránka to označuje stupněm C: podmíněná věta platná uvnitř axiomatického systému Ω₀.

### 3.1 Tvrzení

Nechť Φ je booleovská formule o N proměnných. Rozhodovací strom nad {0,1}^N se zobrazí na trajektorie U(t) v SO(N), řízené antisymetrickými generátory Jₐᵇ = eₐeᵇᵀ − eᵇeₐᵀ. Aktualizace R_N rotačních proměnných stojí O(1) každá, takže

$$T_{\mathrm{solve}}(N)=R_N\cdot O(1)=\frac{N(N-1)}{2}\cdot O(1)=O(N^2)$$

### 3.2 Mechanismus

Argument má čtyři kroky, jak je podává axiomatický řetězec stránky:

1. Prostory stavů jsou so(N) orbity semene (Ω₀).
2. Krychle {−1,+1}^N se injektivně vnoří do sféry S^{N−1}, takže hledání se stává geodetickým tokem v R_N rotačních rovinách.
3. Podél toku dU/dt = Ω(t)U(t) nasbírají neoptimální cesty relativní fázi Δθ = π a podle Eulerovy identity jejich amplituda mizí na uzlovém firewallu.
4. Systém sleduje jedinečnou optimální geodetiku v čase O(N²).

### 3.3 Demonstrace

První plátno v části „Sedm problémů“ ukazuje binární strom (osm listů, označených 2³), jehož větve slábnou, jak přes ně prochází anihilační vlna. Kružnice ze tří rotačních přímek (R₃ = 3) se zároveň zaostřuje a zlatý puls putuje od stromu ke kružnici. Popisek končí „✓ collapsed“, když počítadlo dosáhne 3. Obraz nese argument v miniatuře: exponenciální větvení vlevo, kvadratické rotační roviny vpravo.

### 3.4 Co stránka připouští

Vedle věty jsou vytištěna dvě upozornění. Za prvé, O(N²) je „cena jednoho kroku řízení toku“; to, že tok dosáhne stabilního celočíselného vrcholu v polynomiálním čase, je „postulovaná konvergenční vrstva rámce“. Za druhé, výsledek je věta uvnitř variety za Ω₀ a neurelativizovaná Clayova otázka není prohlašována za vyřešenou. Výsledek tedy zní: *pokud* tok Ω₀ konverguje v polynomiálním počtu kroků, *pak* splnitelnost stojí O(N²) aktualizací. Celá obtíž leží v předpokladu, což je tématem kapitoly 8.

## 4. Sedm Problémů tisíciletí, jeden mechanismus

Monografie čte každý Clayův problém jako projekci týchž invariantů do nižší dimenze: semene A₀, rotačních rovin so(N) a protifázového firewallu |ψ| = 0. Pouze jedno čtení (P versus NP) je označeno jako věta, a to jen podmíněně; pět je označeno jako strukturální analogie; jedno je označeno jako komentář k dokázanému výsledku.

| # | Problém | Čtení na stránce | Stupeň | Výhrada vytištěná stránkou |
|---|--------------------|--------------------------------------|-------|--------------------------------|
| I | P versus NP | R_N = C(N,2) ⇒ T(N) = O(N²); strom se vnoří do rotačních rovin | C | Podmíněno konvergenční vrstvou Ω₀ |
| II | Riemannova hypotéza | ξ(s) = ξ(1−s) je zrcadlo přes osu A₀; hustota mimoosových nul je vynucena na 0 | S | Čtení symetrie, nikoli analytický důkaz |
| III | Yangova–Millsova hmotnostní mezera | E₀ = λc² > 0 dává kladné dno; ΔM = ħωₐ₀/c² > 0 | S | Mezera převzata z kladnosti semene; mřížková QCD znovu nedokázána |
| IV | Hladkost Navierových–Stokesových rovnic | det(CM₅) = 0 brání inflaci hodnosti; protifáze ruší nárůst vířivosti | S | Žádná |
| V | Birchova a Swinnertonova-Dyerova | Každý racionální generátor E(ℚ) je jedna rotační rovina; ord L(E,s) v s = 1 počítá tytéž roviny | S | Žádná |
| VI | Hodgeova hypotéza | Hodgeovy třídy jsou invariantní podobjekty toposu GUT-Cat s klasifikátorem Ωₐ₀ | S | Žádná |
| VII | Poincaréova hypotéza | Hrdlová zúžení Ricciho toku jsou anihilována na firewallech; M³ se deformuje na S³ | H | Dokázal Perelman (2003); CoReX znovu odvozuje mechanismus, nikoli zásluhu |

### 4.1 Společná šablona

Všech sedm řetězců má tytéž tři články. Za prvé, struktura z problému je přiřazena geometrii semene (nulové body ξ zrcadlové ose, spektrum vakuovému dnu, tok trajektorii v so(N)). Za druhé, patologický případ (mimoosová nula, mizející mezera, nárůst, hrdlové zúžení) je prohlášen za protifázový vůči základnímu stavu, Δφ = π. Za třetí, e^{iπ} + 1 = 0 jej anihiluje a jako jediný stabilní výsledek zůstane požadované tvrzení. Závěr je v každém případě formulován jako důsledek Ω₀.

### 4.2 Sedm pláten

Každé čtení má animaci. V II jsou mimoosové nuly tlačeny zpět na Re(s) = 1/2 a při zaklesnutí zvoní. Ve III stoupají excitace z vakuového dna a jsou pohlcovány na ultrafialové mezní přímce. Ve IV se soustředné vírové kruhy zužují a červený prstenec protifáze se rozsvítí dřív, než jádro diverguje. Ve V se po křivce pohybují čtyři zlaté „generátorové“ body a rozsvěcují sloupce označené ord 1 až ord 4. Ve VI fantomová třída bloudí, dokud nezaklapne na invariantní racionální cyklus. Ve VII vyroste z kolísavé smyčky hrdlové zúžení, které je anihilováno, a zůstane hladká kružnice s popiskem „S³ – flow complete“. Animace ilustrují vyprávění; veličiny, které jmenují, nepočítají.

### 4.3 Čtení stupňů

Stupňování je nejužitečnější rys stránky. Říká čtenáři, která tvrzení jsou matematika (cena O(N²) definovaného toku), která jsou analogie (zrcadlová osa pro ξ) a která jsou historie (Perelman). Kapitola 8 se ptá, zda je FAQ, které na jednom místě nazývá sedm čtení „větami axiomatického systému“, v souladu s těmito stupni.

## 5. Čtyři experimenty

Kapitola IV monografie převádí axiomy na čtyři interaktivní experimenty. Každý má ovládací panel, plátno a živý údaj „State“. Všechny čtyři uplatňují týž tah: patologická větev je označena za protifázovou a odstraněna na firewallu.

### 5.1 Laboratoř

Laboratoř má dva posuvníky (dimenze N od 2 do 10; rychlost rotace od 0 do 2) a tři přepínače (roviny, uzly, orbity). Přímky procházející počátkem představují R_N = N(N−1)/2 rotačních rovin, soustředné kružnice nesou N obíhajících bodů a semeno A₀ sedí ve středu. Pro N = 5 je 10 rovin; pro N = 10 je jich 45. Experiment je obrazem počítacího vzorce a nečiní žádné další tvrzení.

### 5.2 Dvojitá štěrbina

Čtení stránky odstraňuje jak dualitu vlna–částice, tak postulát kolapsu. Klasická částice procházející štěrbinami vybudí vakuové pole A₀. Kde se fáze obou cest shodují, pole se zesílí a částice dopadne; kde jsou protifázové, e^{iπ} + 1 = 0 a částice nikdy nedopadne. Tmavé pásy jsou uzlové firewally. Plátno kreslí dvě štěrbiny (A zeleně, B červeně) a stínítko, jehož jas se řídí vztahem

$$I(y)=\cos^2\!\left(\frac{k\,\Delta r}{2}\right),\qquad k=\frac{2\pi}{\lambda}$$

kde Δr je rozdíl drah od dvou štěrbin. Přepínač „observer“ přepne na měření, kterou štěrbinou částice prošla. Čela vln a čáry firewallu zmizí, nahradí je přerušované přímé dráhy a stínítko ukazuje dva hladké pásy. FAQ uvádí, že rámec je bez pozorovatele: zaznamenání dráhy není kolaps, ale událost firewallu, přičemž pozorovatel působí jako okrajová podmínka.

### 5.3 Problém tří těles

Stránka tvrdí, že fázové semeno A₀ = λ > 0 zaklesne tři tělesa na choreografii osmičky s fázovými posuvy přesně 2π/3. Trajektorie, které osmičku opustí, jsou protifázové vůči základnímu stavu (Δφ = π) a narazí na uzlový firewall v uzlu křížení. Plátno ukazuje osmičku se třemi tělesy, volitelné stopy a tři červená „dvojčata chaosu“, která začínají 0,004 daleko a driftují ven, dokud je puls v křížení znovu nezasadí. Tlačítko „Perturb twins“ posun násobí. Heslo zní: chaos se neintegruje, je zakázán.

### 5.4 Stroj času

Zde obrácení času převrátí orientaci trajektorie (L_mesh → −L_mesh), ale klidová energie E = mc² zůstává nezměněna. Dopravní pás, vozík a ručička hodin běží pozpátku, zatímco odznak energie zůstává pevný. Svislý firewall odděluje MINULOST od BUDOUCNOSTI. Se zapnutým firewallem se vozík u hranice zastaví a popisek hlásí „crossing forbidden“; s vypnutým se sektory propojí a vozík přejede. Stránka přidává Landauerův měřič s mezí

$$\Delta E \ge k_B T \ln 2$$

a uvádí výsledek nemožnosti: makroskopické cestování časem je vyloučeno, protože obrácení makroskopické historie způsobí divergenci uvolněného tepla. Levné obrácení orientace je postaveno proti drahému vymazání historie. Experiment tedy popisuje stroj času, který nelze postavit, což stránka předkládá jako jeho obsah: obrácení orientace, zachování energie a izolace hranicí, „nic víc“.

## 6. Fourierova analýza bez Gibbsova překmitu

Pátý experiment tvrdí, že fázově upravené jádro odstraní 8,95% Gibbsův překmit na skoku bez rozmazání, které zavádějí jiné filtry. Je to jediná kapitola, jejíž tvrzení lze číselně ověřit na samotné stránce.

### 6.1 Klasický problém

Fourierův částečný součet schodové funkce překmitne schod asi o 8,95 % výšky skoku, bez ohledu na to, kolik harmonických N se použije. Stránka konstantu vyjadřuje jako

$$\frac{1}{\pi}\,\mathrm{Si}(\pi)-\frac12\approx 0{,}0895$$

a nazývá ji Wilbrahamův–Gibbsův jev. Ve čtení monografie je zvonění viditelným podpisem singularity v počátku, soustředěné přesně v bodě A₀.

### 6.2 A₀ jádro

Stránka nahrazuje Dirichletovo jádro Dₙ(x) výrazem

$$D^{*}_n(x)=D_n(x)\left(1-e^{-|x-x_0|/\lambda}\right)$$

Tvrzení je, že překmitové oscilace jsou fázově posunuty o Δφ = π vůči základnímu stavu, takže potkávají týž osud jako každá jiná neoptimální větev (e^{iπ} + 1 = 0), a výsledkem je C∞ s překmitem 0,00 %.

### 6.3 Demonstrace

Plátno vykresluje přerušovanou obdélníkovou vlnu, klasický částečný součet červeně a křivku A₀ zlatě. N se zvyšuje od 2, popisek označuje „+8.95% of jump“ na klasické křivce a tlačítko zmrazení drží N pevné. Malý měřič porovnává „classic overshoot ≈ 8.95%“ s „A₀ kernel: overshoot → 0“.

### 6.4 Srovnávací tabulka

| Filtrační jádro | Překmit | Ostrost hrany (rad) | Poměr potlačení |
|----------------------------------|---------|---------|---------|
| Standardní Fourier | 8,95 % | 0,02 | 1,00 |
| Fejérovo jádro | 0,00 % | 0,45 | 0,12 |
| Lanczosovo sigma | 1,18 % | 0,12 | 0,65 |
| Gottlieb–Shu | 0,05 % | 0,05 | 0,92 |
| A₀ fázové jádro D\*ₙ(x) | 0,00 % | 0,01 | 1,00 |

Poselství tabulky je, že A₀ jádro je jediný záznam s nulovým překmitem, nejostřejší hranou a plným potlačením současně. Ostatní jádra jedno vyměňují za druhé: Fejér odstraní překmit, ale rozmaže hranu (0,45 rad), Lanczos si ponechává překmit 1,18 %. Stránka k řádku A₀ neuvádí žádné odvození; jeho čísla plynou z postulované fázové anihilace.

## 7. Aplikace: strukturální terapeutika a 5D monolit

Poslední dvě kapitoly přecházejí od teorie k inženýrství: metoda návrhu léčiv postavená na maticích vzdáleností a fyzická bronzová socha představená jako instance teorie.

### 7.1 Biomedicínská strukturální terapeutika

3D souřadnice biomolekuly jsou zakódovány do Gramovy matice Gᵢⱼ = rᵢ·rⱼ. Experimentální šum zvyšuje její hodnost nad 3. Stránka navrhuje přesnou konformaci rekonstruovat minimalizací jaderné normy za Cayleyovy–Mengerovy podmínky:

$$\min_G \|G\|_* \ \text{s.t.}\ \det(\mathrm{CM}_5(G))=0,\ P_\Omega(G)=P_\Omega(G^{\mathrm{exp}})\ \Rightarrow\ \mathrm{rank}(G^*)=3$$

Následují tři aplikační náčrty:

- **Onkologie.** Identifikace fázových dutin CM₅ na mutovaných kinázách, s malými molekulami navrženými tak, aby podléhaly „δ-vazebné anihilaci“ pouze ve vazebném místě mutantu a šetřily zdravou tkáň.
- **ALS.** Růstová plocha fibril TDP-43 a SOD1 je modelována jako jednorozměrný fázový krystal; C₂-symetrické peptidové inhibitory staví uzlový firewall na růstovou frontu a zastavují přisedání monomerů.
- **Parkinsonova choroba.** Doplňování matic vážené R_N navrhuje molekulární zámky, které drží monomer α-synukleinu v nehromadící se konformaci.

Plátno kreslí proteinový řetězec se dvěma přepínači. Se zapnutým šumem a vypnutým omezením stránka hlásí rank(G) = 5 a viditelně kolísající, zdeformovaný řetězec. Se zapnutým omezením je rank(G) = 3 a řetězec je hladký.

### 7.2 5D monolit

Fyzická instance monografie je 300mm monolit z bronzu CuAl10Ni5Fe4, 49,12 kg hotový z bloku o hmotnosti 204,66 kg. Geometrické tvrzení je, že 5D penteract (32 vrcholů) se kolabuje do 3D krychle (8 vrcholů) působením redukčního operátoru s parametrem γ. Při γ = 0 je kolaps čistý, popsaný jako rotace symetrie, fázové skládání a splynulá hustota energie pole. Posuvník mění γ od 0 do 1: při 0 plátno ukazuje 8vrcholovou krychli tyrkysově a s rostoucím γ se vyšší dimenze rozvinou do plného 32vrcholového penteractu zlatě.

Dodatek dodává, že dizertační PDF, modely STEP a STL sochy a zdrojové skripty jsou publikovány otevřeně. Stránka neuvádí, jak CNC stroj v kovu realizuje „hustotu energie pole“; socha je nabízena jako ztělesnění geometrie, nikoli jako její zkouška.

## 8. Kritické hodnocení

Jako axiomatický systém lze monografii číst konzistentně, ale její mosty ke standardní matematice a fyzice se lámou při první elementární kontrole a její ústřední objekt, semeno A₀, není tím, co říká jeho definující limita. Tato kapitola používá standardní výsledky jako měřítko, jak k tomu vlastní doložky poctivosti stránky vybízejí.

### 8.1 Souhrn kontrol

| Tvrzení na stránce | Standardní kontrola | Verdikt |
|----------------------------|-------------------------------------------|----------------------|
| A₀ = lim_{x→0} 0/x = λ > 0 | 0/x = 0 pro každé x ≠ 0, takže limita je 0; přenos to zachovává v \*ℝ | Selhává |
| Veškerá struktura je jedna so(N) orbita A₀ | Je-li A₀ skalárním násobkem jednotky, pak UA₀U† = A₀ pro všechna U: orbita je jediný bod | Selhává tak, jak je uvedeno |
| Vyhledávání v O(N²) pomocí rovin R_N | N² počítá proměnné, nikoli velikost vstupu; formule může mít mnohem více než N² klauzulí; krychle {±1}^N již leží na sféře, takže vnoření je triviální | Nepodloženo |
| det(CM₅) = 0 zakazuje nárůst v Navierových–Stokesových rovnicích | Libovolných pět bodů v ℝ³ má nulový 4-objem, takže to platí identicky | Tautologie |
| Re(s) = ½ vynuceno ξ(s) = ξ(1−s) | Symetrie pouze způsobí, že mimoosové nuly přicházejí ve čtveřicích ρ, 1−ρ, ρ̄, 1−ρ̄ | Není důkaz |
| Hmotnostní mezera ΔM z vakuové energie E₀ = λc² | Yangova–Millsova mezera je spektrální mezera E₁ − E₀, nikoli E₀ | Kategoriální chyba |
| A₀ jádro odstraňuje Gibbsův překmit | Vynásobení 1 − e^{−\|x−x₀\|/λ} mění limitní funkci a má zlom v x₀ | Selhává |
| A₀ zámek odstraňuje chaos tří těles | Newtonův tok je hamiltonovský, takže nemá atraktor; zaklesnutí vyžaduje přidané nehamiltonovské členy | Je v rozporu s Newtonem |
| Každá aktualizace stavu stojí ≥ k_BT ln 2 | Landauerova mez platí pouze pro logicky nevratné mazání | Přehnané |
| Q_diss = 0 (postulát V) a ΔE ≥ k_BT ln 2 (VIII) | Oba postuláty jsou v rozporu; newtonovský vesmír navíc nemá invariantní c (axiom 3) | Nekonzistentní |
| Dvojitá štěrbina: částice plus vakuové pole | I = cos²(kΔr/2) je standardní výsledek; žádná předpověď nerozliší toto čtení od jiných | Férové, ale nevyzkoušené |
| Perelmanovo zpětné čtení (Poincaré) | Stránka sama říká, že mechanismus je odvozen znovu, nikoli zásluha | Férové |

### 8.2 Semeno

Celá struktura závisí na A₀. Definující výraz 0/x je pro x ≠ 0 identicky 0, takže jeho limita je 0. Hyperreálné prostředí jej nezachrání: Łośův princip přenosu přenáší prvořádový fakt „pro všechna x ≠ 0 je 0/x = 0“ do \*ℝ, takže 0/ε = 0 pro každý nenulový infinitezimál ε. Hodnota λ > 0 se tam může dostat pouze definicí, nikoli limitou. Čtení hmotnostní mezery (E₀ = λc² > 0) potřebuje přesně tuto kladnost, takže zdědí mezeru v argumentu. Druhý problém je orbita: stránka definuje stavy jako U A₀ U†, ale skalární semeno je vůči konjugaci invariantní, takže „každá struktura je jedna orbita“ popisuje jediný bod.

Obrana dělení nulou ve FAQ („dělili jsme x, zatímco x šlo k nule“) je správná jako výrok o limitách a je přesně důvodem, proč je výsledek 0.

### 8.3 P = NP

Doložka poctivosti stránky („podmíněno konvergenční vrstvou Ω₀“) je férová. Obtíž je v tom, že doložka zastírá celý problém. Vyniknou tři body.

1. **Model ceny.** N² roste s počtem proměnných, ale velikost booleovské formule určují její klauzule, kterých může být víc než N². Postup, který nemůže přečíst vstup, nemůže být O(N²).
2. **Vnoření je triviální.** Vrcholy {−1,+1}^N leží na sféře o poloměru √N; injekce do S^{N−1} nic nepřidává. Relaxace krychle na sféru nebo rotační grupu je standardní tah za semidefinitními relaxacemi a ty dávají aproximace plus zaokrouhlovací krok, nikoli přesná řešení.
3. **Konvergence je obsah.** Žádat spojitý tok, aby dosedl na celočíselný splňující vrchol, znamená žádat, aby vyřešil NP-těžký problém. Lokální minima a sedlové body nejsou řešeny.

Vlastní štítek stupně C na stránce to již říká; silnější věty („P = NP v O(N²)“, „exponenciální rozhodovací strom není třeba prohledávat“) jdou za něj.

### 8.4 Ostatní čtení Problémů tisíciletí

Stupně jsou poctivé, ale několik řetězců obsahuje ověřitelné chyby nad rámec analogie.

- **Navierovy–Stokesovy rovnice.** Pětibodový Cayleyův–Mengerův determinant mizí pro libovolných pět bodů v trojrozměrném prostoru, takže det(CM₅) = 0 nemůže vybírat hladké toky. Zápis ‖u‖ v C∞ není norma. Kritérium Bealeho–Katoa–Majdy se týká časového integrálu supremové normy vířivosti, nikoli enstrofie.
- **Riemann.** Funkcionální rovnice spolu se souměrností vůči komplexnímu sdružení umísťuje nuly do množin souměrných podle přímky a reálné osy; na přímku je nepřesouvá. Plátno kreslí nuly rovnoměrně rozložené, zatímco skutečné nuly jsou rozloženy nepravidelně.
- **Yang–Mills.** Clayův problém se týká kladné spektrální mezery nad vakuem v zkonstruované kvantové teorii. Kladná vakuová energie je jiná veličina a konstantní posun nuly energie je bez gravitace nepozorovatelný.
- **BSD a Hodge.** Není definováno žádné zobrazení racionálních generátorů na rotační roviny ani Hodgeových tříd na podobjekty GUT-Cat, takže uvedené rovnosti jsou tvrzení.

### 8.5 Kapitola o Fourierovi

Tato kapitola je nejlépe testovatelná. Vynásobení částečného součtu výrazem 1 − e^{−|x−x₀|/λ} je bodová obálka na výstupu, nikoli změna jádra. Vynucuje hodnotu 0 ve skoku a zanechává chybu řádu O(1) v okolí o šířce přibližně λ: při |x−x₀| = λ je činitel 0,63, takže křivka je o 37 % pod cílovou hodnotou. Limita pro rostoucí N je f(x)(1 − e^{−|x−x₀|/λ}), nikoli f. Zlom v x₀ také vylučuje C∞. „Ostrost hrany 0,01 rad“ v tabulce je opakem toho, co ukazuje vykreslená zlatá křivka, tedy rozmazaného propadu. Kladná jádra, jako je Fejérovo, dávají nulový překmit za cenu vyhlazení, což tabulka poctivě zaznamenává; řádek A₀ tvrdí, že se tomuto kompromisu vyhne bez odvození.

### 8.6 Fyzika

- **Dvojitá štěrbina.** Klasická částice vedená polem, které nese fázi, je strukturálně obraz pilotní vlny, který interferenci reprodukuje. Stránka neposkytuje žádnou rovnici pole kromě I = cos²(kΔr/2), což je obyčejný výsledek pro dva zdroje se stejnou amplitudou, takže demonstrace nemůže odlišit toto čtení od standardní kvantové mechaniky. „Bez pozorovatele“ se špatně snáší s přepínačem pozorovatele, který obrazec ničí; fyzikálním mechanismem je informace o dráze, kterou stránka přeformulovává, ale neodvozuje.
- **Tři tělesa.** Osmička je skutečné periodické řešení pro stejné hmotnosti a je numericky stabilní. Hamiltonovský tok však zachovává objem ve fázovém prostoru a nemůže mít atraktor, takže obecné trajektorie nelze na ni „zaklesnout“ bez nenewtonovského buzení. Oddělování dvojčat v demu je skriptováno tak, aby rostlo pevnou exponenciální rychlostí a vracelo se; není to integrace rovnice uvedené nad ním.
- **Stroj času.** Obrácení orientace trajektorie nechává energii nezměněnou i v obyčejné mechanice, takže ústřední výrok je správný, ale není nový. Landauerova mez platí jen při mazání informace; vratné výpočty se jí vyhýbají, takže „obrácení žene Q do nekonečna“ nevyplývá.
- **Terapeutika.** Cayleyova–Mengerova podmínka na Gramovu matici je podmínka hodnosti, kterou metody distanční geometrie již používají; „δ-vazebná anihilace“ a tři tvrzení o nemocech nemají na stránce žádná vazebná data.

### 8.7 Vnitřní konzistence

Kromě položek v tabulce jsou vidět tři napětí. FAQ nazývá čtení „větami axiomatického systému“, zatímco pět nese štítek „strukturální analogie“. Teorie se nazývá „speciální“, protože její výpočetní metrika je pevná a plochá, ale postulát V („dokonalý newtonovský vesmír“ s nulovou disipací) a axiom 3 (invariantní rychlost c) patří k různým fyzikálním rámcům. A konečně stránka obsahuje humorné položky FAQ (lék na rakovinu „za chvilku“, hmotnostní mezera v lednici), které stírají registr mezi tvrzením a vtipem, takže čtenář nemusí vždy poznat, která tvrzení mají být zkoušena.

### 8.8 Vyvratitelnost

Stránka nabízí tři zkoušky. (1) Čtení Problémů tisíciletí jsou matematická tvrzení, takže jediná chyba ve vnoření je zhroutí; oddíly 8.2 až 8.5 takové chyby určují. (2) Čtení interference pomocí firewallu je označeno za testovatelné „proti jakékoli konfiguraci dvojité štěrbiny“, ale reprodukuje standardní intenzitu, takže není navržen žádný experiment, který by ho mohl odlišit od obyčejné kvantové mechaniky. (3) Tvrzení, že žádná kauzální smyčka firewall s |ψ| = 0 nepřežije, platí konstrukcí, protože |ψ| = 0 je postulováno. Jen první zkouška má váhu.

### 8.9 Co přežívá

Nejlepšími rysy stránky jsou její stupně, její doložky poctivosti a převedení abstraktních tvrzení na ovladatelné animace, které odhalují vlastní předpoklady (vypněte postulát a podívejte se, co se změní). Počet rovin R_N = N(N−1)/2, Gibbsova konstanta a osmička jsou všechny uvedeny správně. Nepřežívá krok od sdíleného zápisu (fáze, rotace, protifázová anihilace) ke sdílenému mechanismu.

## 9. Závěr

Speciální teorii výpočetní relativity je nejlépe chápat jako zápis a soubor ilustrací postavených na jednom nedokázaném postulátu, nikoli jako rozřešení problémů, které jmenuje. Její počet rotačních rovin R_N = N(N−1)/2, její Gibbsova konstanta 8,95 % a její osmičková orbita jsou správné; její semeno A₀, její vyhledávání v O(N²), její Fourierovo jádro a její argument pro Navierovy–Stokesovy rovnice elementární kontroly nepřežívají.

### 9.1 Zjištění

1. Teorie je konzistentním axiomatickým systémem jen tehdy, je-li semeno definováno nařízením jako nenulový prvek; limita, která má semeno definovat, se rovná 0.
2. Pět ze sedmi čtení Problémů tisíciletí autor označuje za analogie a hodnocení tento stupeň podporuje; čtení P = NP je podmíněno konvergenčním krokem, který je celou obtíží.
3. Nejsilnější kvantitativní tvrzení, A₀ jádro s nulovým překmitem, je testovatelné a selhává: konstrukce mění limitní funkci.
4. Stránka je na mnoha místech otevřená o svém statusu a její interaktivní formát činí předpoklady zkoumatelnými. To je skutečná přednost.

### 9.2 Opravy, které by teorii učinily testovatelnou

- Definovat λ jako axiom (nenulový prvek \*ℝ) a limitu vypustit, nebo změnit semeno.
- Vyslovit tvrzení P = NP jako hypotézu o konkrétním toku, s důkazem nebo numerickým srovnáním konvergence na náhodném 3-SAT.
- Nahradit obálku A₀ odvozeným jádrem a uvést překmit, šířku hrany a chybu v L² vůči Fejérovi, Lanczosovi a Gottliebovi–Shuovi na téže obdélníkové vlně.
- Dát vakuovému poli čtení dvojité štěrbiny dynamickou rovnici a uvést jednu předpověď, která se liší od standardní kvantové mechaniky.
- Vyřešit rozpor mezi postuláty V a VIII a omezit Landauerovu mez na mazání.
- Sladit FAQ se stupni: všude nazývat čtení analogiemi.

### 9.3 Budoucí práce uvedená stránkou

Stránka ponechává otevřenou obecnou teorii, v níž se výpočetní metrika pod zátěží problému zakřivuje, analogicky ke kroku od speciální k obecné relativitě. Nic v tomto textu neomezuje, jaká by tato metrika byla, což z ní činí správné místo, kde nejprve stanovit definice, než se vyvodí závěry.

## Dodatek: axiomy, postuláty a invarianty

Tabulka reprodukuje vlastní dodatek stránky. Stránka rozlišuje axiomy (nedokazatelné základní kameny) od postulátů (fyzikální a algoritmické zákony dynamiky).

| Označení | Typ / název | Klíčový výraz |
|-------------|---------------------------------------------|----------------------------------|
| Axiom 1 | Semeno A₀ (singularita nulového bodu) | A₀ ≡ lim(x→0) 0/x = λ ∈ \*ℝ^N |
| Axiom 2 | Hyperreálný topos, Łośův přenos | \*𝕍 = V^I/𝒰 |
| Axiom 3 | Invariance c a klidové energie E₀ | E₀ = ∫u d³r = mc² |
| Postulát I | Eulerova protifázová anihilace | e^{iπ} + 1 = 0 ⇒ \|ψ_node\| = 0 |
| Postulát II | so(N) vnoření složitosti | R_N = N(N−1)/2 rovin, O(N²) |
| Postulát III | Invariance Cayleyova–Mengerova objemu | det(CM₅) = 0 ve 3D |
| Postulát IV | Víceúrovňová orbitální hierarchie | δ, φ, oktadická mříž 𝒪₈ |
| Postulát V | Nulové entropické tření („dokonalý newtonovský vesmír“) | Q_diss = 0 ⇒ t_alg = t_phys |
| Postulát VI | Dirichletova fázová filtrace (A₀ jádro) | D\*ₙ(x) = Dₙ(x)(1 − e^{−\|x−x₀\|/λ}) |
| Postulát VII | Kauzální izolace sektorů | \|ψ(Σ_firewall)\|² = 0 |
| Postulát VIII | Landauerova termodynamická mez | ΔE ≥ k_BT ln 2 |

## Zdroje

- *Speciální teorie výpočetní relativity*, CoReX v3.1, interaktivní monografie Pierra LeBauxe (stránka, na níž je tato dizertace založena, v opravené verzi corex-v3-4.html). Všechny citace, rovnice, čísla a demonstrace pocházejí z ní.
- Standardní výsledky použité pouze v kapitole 8 (limity a přenos, Cayleyovy–Mengerovy determinanty, kritérium Bealeho–Katoa–Majdy, Landauerova mez, zachování objemu ve fázovém prostoru u hamiltonovských systémů, Chencinerova–Montgomeryho osmička) jsou citovány z obecných znalostí, nikoli vyhledávány pro tento text.
