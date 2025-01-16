[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/dZO47OCI)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=11935589&assignment_repo_type=AssignmentRepo)
# Välkommen till HMTL Laboration 2

Projektet är ett **individuellt arbete**.

Objektivet i arbetet är att **bygga en webbplats åt en påhittad (eller riktig) organisation/kund**. Tanken är att ni kommer på er egen projektidé (och själva agerar kund), men här är tre exempel som kan användas för inspiration:

-   En webbplats åt en restaurang, ett café, eller liknande
-   En webbplats åt någon typ av evanemang, till exempel en musikfestival
-   En e-handelsbutik, som till exempel säljer kläder

Eftersom vi bara har gått igenom HTML och CSS, och inga andra språk förväntas användas i projektet, så **finns det inga krav kring programmering med JavaScript eller liknande**. Projektet behöver till exempel inte stödja inloggningar/konton, försäljning av produkter, och så vidare.

Webbplatsen **ska vara responsiv och fungera väl på alla bredder mellan `360px` (mobiler) och `980px` (desktop)**. Det kommer med största sannolikhet att vara betydligt effektivare att bygga sajten med “mobile-first”-process, istället för att börja med att bygga sajten för datorskärmar och sedan “skala ner” den till att fungera väl på mobiler men det är helt upp till er hur ni önskar utföra det och det finns inget rätt eller fel i hur man gör det men det ska kort och gott fungera på alla skärmar.

Projektet  **måste**  vara tillgängligt i det avseende att det alltid är **[en tillräckligt hög kontrast mellan text och bakgrund](https://webbriktlinjer.se/riktlinjer/126-tillrackliga-kontraster/)**. [https://color.review/](https://color.review/) kan vara behjälpligt kring att identifiera lämpliga färger att använda. Det räcker att uppfylla kraven för AA.

Det finns inga krav på att ni måste göra ett antal sidor, det är valfritt men glöm ej att sidan måste ha:  
- Navbar  
- Innehåll  
- Footer


### Krav för G

- Ni ha **minst en media query** som bidrar till att webbplatsen nyttjar det extra utrymme som finns tillgängligt på bredare skärmar. Detta skulle till exempel kunna innebära att visst innehåll som tidigare visats vertikalt på smalare skärmar (såsom mobiler), börjar visas horisontellt på bredare skärmar (såsom desktops). **Hela webbplatsen måste vara responsiv.** Det vill säga, inget innehåll ska “hamna utanför” webbläsaren.

- Ni **måste använda både class selector- och ID selector-väljarna**, på ett meningsfullt sätt samt logiska namn på dessa.

- Man ska ha **Flexbox eller Grid Layout** för att lösa minst ett lämpligt layoutproblem. Det anses till exempel **inte** vara lämpligt att använda Flexbox för att skapa två “vanliga” och simpla vertikala element (eftersom blockelement redan beter sig så), eller att använda Flexbox för att centrera text i ett blockelement (eftersom att detta enkelt kan göras med `text-align`-egenskapen). Två exempel på lämpliga layoutproblem för Flexbox är att skapa kolumner eller utföra vertikal centrering i ett element med en okänd höjd.

- Man ska även bidra till sajtens tillgänglighet genom att använda **minst ett HTML5-strukturelement** för att [hjälpa användare med skärmläsare att bläddra mellan sidans delar](https://webbriktlinjer.se/riktlinjer/75-gruppera-och-skapa-mojlighet-att-hoppa-forbi-delar-pa-sidorna/). (ARIA behöver inte användas.)

- Man ska använda **[`title`](https://developers.google.com/search/docs/beginner/seo-starter-guide?hl=sv&visit_id=637667214098085977-1872329024&rd=1#uniquepagetitles) och [`description`](https://developers.google.com/search/docs/beginner/seo-starter-guide?hl=sv&visit_id=637667214098085977-1872329024&rd=1#descriptionmeta)**, samt **rubrikelement** (alltså `h1`-`h6`), på ett lämpligt sätt, enligt [Google:s SEO-rekommendationer kring att hjälpa Google och användare att förstå innehållet](https://support.google.com/webmasters/answer/7451184?hl=sv&ref_topic=9460495#understand_your_content) och tillgänglighetsrekommendationerna [Skriv beskrivande sidtitlar](https://webbriktlinjer.se/riktlinjer/135-skriv-beskrivande-sidtitlar/) och [Skapa rubriker med h-element](https://webbriktlinjer.se/riktlinjer/105-skapa-rubriker-med-h-element/).

- All kod ska vara **fri från fel i W3C:s valideringstjänster för HTML och CSS (det räcker att hela görs på HTML och CSS även om ni såg vid live kodningen att det kan vara hjälpligt att göra efter varje ny "section" eller "avsnitt" och man måste ange och bekräfta med en kommentar att både HTML och CSS är validerat innan inlämning.**

**Exempel i CSS: /*All kod validerad*/ längst ned på sidan**

Varje person i ska redovisa sin insats i projektet i en **presentation som ni sedan presenterar**, samt lämna in sitt arbete.  

### Ytterligare krav för VG

- Man ska skriva **semantisk HTML-kod**, det vill säga använda det mest passade HTML-elementet för allt innehåll. Det är till exempel inte acceptabelt att använda ett `div`-element för att kapsla in ett textstycke, eller att använda `h4` för att representera en huvudrubrik. Vidare ska `br`-element generellt sett inte användas för att skapa avstånd (det är väldigt ovanligt att `br` är rätt element att använda för detta; använd som utgångspunkt `margin`- eller `padding`-egenskaperna istället). Semantisk kod bidrar till sökmotoroptimering, tillgänglighet, samt kod som är enklare att underhålla och vidareutveckla.

- Man ska skriva **enhetligt formaterad kod**. Indenteringen ska vara konsekvent. Det ska till exempel inte vara två mellanslags indentering i ett CSS-block, och fyra i ett annat. Detta gäller för både HTML och CSS. Se modulen “Några kodkonventioner” för ett exempel kring hur automatisk kodformatering kan konfigureras. Enhetlig formatering bidrar till kod som är enklare att underhålla och vidareutveckla.

- Man ska använda åtminstone **en väljare utöver type selector, class selector och ID selector**, för att lösa ett problem där väljaren i fråga är lämplig.

- Man ska **namnge klasser, ID-värden och filer på ett beskrivande sätt**. Det är till exempel inte acceptabelt att skapa en klass som heter “my-class”, eller en bild till “my-image”, eftersom detta namn inte kommunicerar tillräckligt mycket om vad objektet i fråga representerar. Beskrivande namn bidrar till kod som är enklare att underhålla och vidareutveckla.

-Ni ska ha lagt in **minst en [responsiv bild](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images) dvs får plats på den befintliga ytan.**

Minst två bildvarianter ska anges för bilden i fråga. Bildfilerna **ska se likadana ut**, förutom att de ska **skilja sig i upplösning** (hur många bildpunkter bilderna består av). Optimerade bilder bidrar till sökmotoroptimering. [The GIMP](https://www.gimp.org/) kan användas för att skapa olika storleksvarianter av en bild. Vidare måste `img`-elementet som utgångspunkt ha ett beskrivande `alt`-attribut, som en del i tillgänglighetskravet kring att [beskriva med text allt innehåll som inte är text](https://webbriktlinjer.se/riktlinjer/115-textalternativ/) och [Google:s SEO-rekommendationer kring optimering av bilder](https://support.google.com/webmasters/answer/7451184?hl=sv&ref_topic=9460495#images).

Gör gärna, om tid finns, ytterligare tillgänglighets- och sökmotorsoptimeringsförbättringar utöver kraven som nämns ovan.


- 


