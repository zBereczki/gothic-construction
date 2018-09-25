---
title: From parchment to 3D to HTML&#58; the use of the 3D and the Web in architectural history research (a case study)
author: Dr. Bereczki Zoltán
bibliography: /Users/zbereczki/Dropbox/Bibdesk-library/Library.bib
csl: /Users/zbereczki/Documents/tudomany/csl/ieee.csl
---

**Index Terms:** építészettörténet, középkor, gótika, kivitelezés, Bécs, GitHub, Jekyll, WebGL, Rhinoceros 3D

# Abstract

The construction of Gothic church towers with carved stone spires and often with significant height required the most advanced technology and financial support of their age, and the application of advanced machines was also inevitable for it. In the second part of my PhD thesis defended in 2017 I attempted to reconstruct the process of a 15th-century tower construction, including the main auxiliary structures: scaffoldings and machinery, on the example of the unrealised north tower of the St. Stephen’s church, with the use of mostly contemporary sources. [@bereczki_2017_gotikus] While creating the images for the final version of the thesis I faced the problem that the paper as a medium is only able to communicate fragments of the information contained by the 3D model. This project is the result of this realisation, so it serves as an extension of the printed thesis: I created an online visualisation of the model with animations, embedded models, and links to the most important and online available drawn sources.

# Introduction

One of the main questions of the research of the mediæval technical drawings is whether they served as a modern blueprint or not; so was their main purpose to make possible the realisation of a structure (machine, building), or something else (education, representation, etc). [@bucher_design_1968] [@lefevre_picturing_2004] [@bereczki_machine_2015] The most reassuring way to answer this question would be conducting a lifesize experiment: to construct the structures relying only on the drawings representing them. Since there is hardly an opportunity to achieve this, 3D-modelling emerges as a solution.

It is important to emphasise – as it is discussed in several papers written by Norbert Nußbaum of the University of Cologne –, that the Gothic construction praxis cannot be generalised. While the forms could spread on paper or parchment, the technical details, solutions could not. [@nusbaum_form_2010] [@nussbaum_planning_2011] [@nussbaum_planen_2012] So not only I do not state that a particular tower was constructed this way, but I also do not state that Gothic towers were generally constructed this way: my 3D model and the resulting drawing series illustrates a possible solution, based almost exclusively on contemporary sources. As far as I know a similar series of drawings about a Gothic tower’s construction – illustrating not only the tower, but also the auxiliary structures, based on historic sources – wasn’t published in the literature yet.

# The 3D reconstruction

During my research I modelled the partially realised north tower of the Stephanskirche (St. Stephan's church) in Vienna using exclusively its contemporary (15th-century) plans. I choose wittingly an unrealised tower, as I wanted to avoid any possible misunderstanding. I do not want to introduce how a particular tower was built (this would be impossible), but how a tower could have been constructed using the instruments in the discussed sources. 

During the construction of a tower the scaffolding and machinery are the most important auxiliary structures. Ennek megfelelően az építést bemutató modellem három fő részből áll: magából a toronyból, az állványokból, és a gépekből. A felhasznált non-written források részletes bemutatása túlmutat jelen írás keretein, így itt csak a legfontosabbak felsorolására szorítkozom.

A bécsi északi torony legteljesebb alaprajza a Wien Museum Karlsplatz gyűjteményében lévő 105.064-es jelű rajz, legteljesebb homlokzata pedig a 105.067-es, szintén a Wien Museum Kalrsplatz gyűjteményében lévő rajz; így a modellemhez ezeket használtam.[@kronberger_dombau_2011] Ahol a kettő eltér, ott az alaprajzot tekintettem mérvadónak. Mivel a célom az volt, hogy kizárólag eredeti tervek alapján rekonstruáljak egy struktúrát, a modellhez kizárólag a rajzokat használtam fel, a torony megvalósult részeiről készült fotókat legfeljebb a rajzok értelmezéséhez. Így azok a részek, amik nem szerepelnek a rajzokon és következtetni sem lehet rájuk (ez leginkább a földszint keleti és nyugati homlokzata), csak sematikusan szerepelnek.

Discussing the machines, the mediaeval machine drawings survived almost only in warfare-themed manuscripts. Notable exception is the portfolio of the Strasbourg master Hans Hammer, where many machine drawings can be found, likely in connection with the tower plans of the master. [@fuchs_introduction_1992] I used mainly this manuscript for the reconstruction of the machines.

The survived contemporary drawings about scaffoldings are almost exclusively book illuminations and paintings, these were my main sources for the modelling of the scaffolding. [@binding_mittelalterliche_2001] An additional source available from the Modern Age, but before the age of industrialisation is the detailed drawing and description of the scaffolding used during the early 19th-century reconstruction of the top of the south spire at the St. Stephen’s church. [@trost_umbau_1843] Further important sources of information were the surviving or reconstructable scaffoldings inside of Gothic towers and the related literature. [@tatton-brown_building_1997] [@jones_salisbury_2005] [@jones_ironwork_2005] [@caston_spatmittelalterliche_1997]

A modellezéshez a Rhinoceros 3D-t használtam. A torony modellezése úgy zajlott, hogy az alaprajzon kívülről indulva átrajzoltam az egy szinten lévő alaprajzi kontúrokat. Ehhez tudni kell azt, hogy a gótikus alaprajzok egy lapon ábrázolják a struktúra összes (különböző magasságokban lévő) alaprajzát. Amikor egy szint kontúrjával megvoltam, a homlokzati rajzon meghatároztam, hogy az adott kontúr milyen magasságban van; majd a megfelelő magasságba emelt kontúrok közötti teret (szintén a homlokzati rajz alapján) kitöltöttem a 3D-s struktúrával.

A torony modellezésénél természetesen egyszerűsítéseket alkalmaztam: a díszítéseknek (keresztrózsáknak, kúszóleveleknek) csak a geometriai befoglalóformáját modelleztem meg, hasonlóan ahhoz, ahogy Matthäus Roriczer korabeli, egy fiatorony szerkesztéséről szóló könyvében látható [@roriczer_buchlein_1999]; mérműveket pedig sehol sem ábrázoltam.

Az építést öt fő szakaszban modelleztem meg. Az első szakaszban a torony alsó, négyzetes szintjei vannak készen, a második szakaszban a harangház épül, a harmadik szakasz az oktogon építését mutatja, a negyedik a sisakét, végül az utolsó a keresztrózsa elhelyezését.

For each phase, at first I modelled the tower to the desired height, using the mediaeval drawings (floor plan, elevation); then I designed a possible solution for the scaffolding, based on the discussed sources; finally I put Hans Hammer’s machines to the appropriate places.

![The five main phases](arnyekolt_egyben.jpg)

# The online representation

In my thesis I illustrate the construction with five phases. Consequently, the on-line presentation consists of five subpages. 

Az oldalak struktúrája a következő:

- egy rövid animáció az adott építési szakaszról
- beágyazott modellek
    - a teljes modell
    - a felhasznált gépek, külön-külön ablakban
- a felhasznált archív rajzok, tervek forrásai (ha online elérhető az adott rajz, akkor linkkel)
- references

The main content of each site is the embedded WebGL-window with the model of that phase.

A technikai megvalósítás során fontos szempont volt a pluginek nélküli működés; az egyszerű, offline szerkesztés lehetősége; és a verziókövetés. Ennek megfelelően a beágyazott modellek WebGL-t használnak, az oldal pedig Markdownban készült és a GitHub Pagesen hosztolódik.

A WebGL-t a Khronos Group fejleszti, a hivatalos meghatározás szerint „WebGL is a cross-platform, royalty-free web standard for a low-level 3D graphics API based on OpenGL ES, exposed to ECMAScript via the HTML5 Canvas element.” [@Khronos_2018_webgl] According to the Wikipedia, "WebGL evolved out of the Canvas 3D experiments started by Vladimir Vukićević at Mozilla. Vukićević first demonstrated a Canvas 3D prototype in 2006. […]
In early 2009, the non-profit technology consortium Khronos Group started the WebGL Working Group, with initial participation from Apple, Google, Mozilla, Opera, and others. Version 1.0 of the WebGL specification was released March 2011." [@wikipedia-WebGL] A modern desktop böngészők (pl. Apple Safari, Google Chrome, Mozilla Firefox, Opera) pluginek telepítése nélkül támogatják, ahogy a legelterjedtebb mobil böngészők is (Safari, Chrome, Firefox). A Khronos Group egy egyszerű tesztoldalt is üzemeltet, ahol könnyű leellenőrizni, hogy az általunk használt böngésző WebGL-kompatibilis-e: https://get.webgl.org. Ha igen, egy forgó kockát kell látnunk.

A Rhino-modell exportálásához a Luis E. Fraguada által fejlesztett, Iris nevű plugint használtam. The plugin generates JSON data from a Rhino model that is parseable and viewable through WebGL in a modern web browser. [@iris-web] A JSON egy, a JavaScriptből kifejlesztett nyílt forrású formátum. [@json-web] Iris depends on the following libraries:

- Three.js
- Bootstrap
- Tween.js
- jQuery
- JSON.net

Az Iris képes a modellünkből egy úgynevezett Web Archive-ot exportálni, ami egy mappa a gépünkön a következő tartalommal:

- Archive (Named during export)
    - index.html (the html page for the Iris Scene)
    - app
        - iris.min.js (the Iris WebApp Javascript Code)
    - data
        - data.json (the exported model in Three.js json format)
    - ui (this is the default UI template that ships with Iris)
        - css
            - styles.min.css (the css required by the ui)
    - js
        - ui.min.js (the javascript required for the ui)

Ha az index.html-t iframe-mel beágyazzuk egy weboldalba, akkor egy 3D-s ablakot kapunk, a sarkában egy számos gombból álló User Interface-szel (UI). A modell a data mappából töltődik be, az UI pedig az ui és a js mappákból.

A plugin verziószáma jelenleg 0.6.0.2, ennek megfelelően a működése nem tökéletes. Az UI nem szerkeszthető, így számos (számomra) felesleges elem van benne (ilyen például a Planes, a Materials, vagy a Positions). Ezért, hogy az oldal felhasználója ne vesszen el a lehetőségek között, az oldalon szerepeltetek egy kis manualt is a legfontosabb UI-elemekkel. Ezek nálam a következők:

- Zoom Extents
- Views, ezen belül az általam fontosnak tartott, előre elmentett nézetek

A navigáláshoz szükséges legfontosabb shortcutokat szintén szerepeltetem:

- Left mouse button: pan around the scene
- Right mouse button: orbits the scene camera
- Middle mouse wheel: zooms
- Zooming extents - ‘z’
- Zooming selected - ‘s’

A Views menüben megjelenő nézeteket magában a Rhinocherosban lehet definiálni, a NamedView parancs segítségével. Mindegyik beágyazott modellem esetében definiáltam olyan nézeteket, amik valamilyen fontos részletre hívják fel a figyelmet. Az Iris UI-ja ezenkívül a sztenderd nézeteket is megjeleníti.

A honlap létrehozására a Jekyllt és a Github Pagest használtam. A technika lényege, hogy a teljes oldalt a saját gépemen hozom létre egy egyszerű text editor segítségével, Markdownban. A hivatalos weboldalt idézve "Markdown is a text-to-HTML conversion tool for web writers. Markdown allows you to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML)." [@markdown-web] A Markdown azonban mára sokkal több ennél: de-facto standarddé vált, és a nyílt forrású Pandoc segítségével a Markdownban írt dokumentumokat szinte bármilyen szövegformátumba exportálhatjuk. [@pandoc-web] A Pandoc fejlesztője John MacFarlane, Professor of Philosophy, University of California, Berkeley.

A Markdownban létrehozott oldalstruktúrát egy nyílt forrású szerveroldali alkalmazás, a Jekyll fordítja át html-be. [@jekyll-web] Az eredmény így egy adatbázist nem igénylő, lightweight statikus website lesz. Hogy a Jekyll el tudja végezni a dolgát, természetesen az oldalstruktúrát és magukat az md-fájlokat a Jekyll konvenciói szerint kellett létrehozni (ez tulajdonképpen a megfelelő mapparendszert, a megfelelő fájlneveket és a megfelelő YAML-headerek létrehozását jelenti).

A Jekyll az egyszerű, local szerkeszthetőség és a statikus oldalak létrehozása mellett azzal az előnnyel is rendelkezik, hogy a GitHub webhosztingszolgáltatása, a GitHub Pages is ezt használja. A publikálás úgy történik, hogy a gépünkön létrehozott, a honlap  fájljait használó Git repositoryt a GitHubra szinkronizálunk. A GitHub online felületén a repository beállításai között a megfelelő kapcsoló bekapcsolása után az oldalt legenerálja a GitHub szerverén futó Jekyll. Az oldal szerkesztése, frissítése továbbra is localban történik: a gépünkön szerkeszthetjük a Markdown-fájlokat és a mapparendszert, és ha készen vagyunk a szerkesztéssel, a repositoryt szinkronizáljuk a GitHubra, ahol a Jekyll figyeli a változásokat és legenerálja a frissített statikus website-ot. Ezzel szinte észrevétlenül a verziókövetés is megtörténik, mivel a GitHub alapvetően egy verziókövető rendszer: minden szinkronizálás gyakorlatilag egy Commit a fő (online) repositoryba.

The result is the detailed online interpretation of the model, where the intricate spatial structure can be observed interactively, in detail.

# Conclusions

A korabeli forrásokat felhasználó modellezés megmutatta, hogy with the exceptions of some contradictions and hidden parts, the contemporary plans of the north tower in Vienna carried enough information to build up the structure in 3D. Around and inside the 3D-model, based on historic representations and survived structures I could construct a scaffolding the way it would be constructible using technology available in the Middle Ages. With this scaffolding the construction of the tower would be possible. By placing Hans Hammer’s machines, as well as the clever ladders of the portfolio on the model I was able to clarify their possible application modes.

The mediæval drawings used for the project are definitely workshop drawings, „blueprints”: relying on them and only them it was possible to build up in 3D both the complex building, both the elaborate machines. For the presentation the Web as a medium was much more appropriate than printing. A nyomtatott disszertációban eleve csak korlátozott számban és méretben tudtam képeket elhelyezni, ezek ráadásul (nyilván) egy bizonyos szögből, egy bizonyos méretben ábrázolják a modellt. A webes reprezentáció ezzel szemben tetszőlegesen forgatható, nagyítható; és a fontos nézeteket az Iris UI-ja segítségével előre definiálhattam.

A teljes képhez ugyanakkor hozzátartozik, hogy a technológia még nem működik zökkenőmentesen. Egyrészt az Iris működésében is vannak hibák, a legnagyobb talán az, hogy nem mindig az előre definiált nézetet tölti be, és vagy üres ablak jelenik meg, vagy a modellnek csak egy része látszik. Ezért minden oldalra ki kellett írnom, hogy "if the models are not visible or not centered, press *Z*". Ezenkívül a teljes, igen komplex modell megjelenítése meglehetősen nagy hardverigényű. A pontos hardverigényekről nem tudok beszámolni, csak arról, hogy hogy jelenik meg a beágyazott toronymodell az általam tesztelésre használt gépeken. Egy 2017-es MacBook Pro (Intel Iris Plus Graphics 640 1536 MB) gond nélkül megbirkózik vele, és egy jóval régebbi és gyengébb, 2013-as Macbook Airen (Intel HD Graphics 5000 1536 MB) is megjelenik. Az általam tesztelésre elérhető legerősebb telefon, egy iPhone SE azonban csak a gépek modelljeit volt képes megjeleníteni, a toronymodellt nem.

# References
