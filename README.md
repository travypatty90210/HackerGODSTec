# HackerGODSTec
## KBC Kompas

Een interactieve visie op persoonlijker digitaal bankieren: een helder dagelijks overzicht dat zich aanpast aan wat de klant zelf nodig heeft, zonder de controle over geldzaken of persoonsgegevens uit handen te nemen.

Open `index.html` in een browser om de conceptdemo te proberen. De profielkeuzes simuleren levensfase, uitgavenpatroon, gezin, beleggen en app-frictie. De gegevens zijn fictief; overschrijvingen worden niet uitgevoerd.

### Productvisie

Kompas maakt bankieren begrijpelijker en relevanter door op het juiste moment het juiste overzicht, hulpmiddel of menselijke contactpunt te tonen. Personalisatie moet klanten helpen, nooit sturen of toegang tot essentiële bankfuncties beperken.

- Geef klanten inzicht in inkomsten, uitgaven, categorieën en trends, afgestemd op hun gekozen doelen.
- Maak veelgebruikte acties direct bereikbaar; bied bij herhaalde of lange sessies duidelijke hulp en een eenvoudige route naar een medewerker.
- Bied opt-in gezinsoverzichten met afzonderlijke toestemmingen en rechten voor elke rekeninghouder.
- Geef beleggers een aparte informatie-ervaring; scheid feitelijke informatie van advies en commerciële aanbevelingen.
- Laat klanten hun startscherm, signalen, meldingen en personalisatie bekijken, aanpassen, pauzeren of wissen.
- Gebruik leeftijd niet als proxy voor vaardigheid of behoefte. Test toegankelijkheid met klanten van verschillende leeftijden en bied een instelbare eenvoudige weergave.

### Veiligheid en vertrouwen

De demo draait volledig in de browser en gebruikt geen echte klantdata, backend, analytics of betalingsverkeer. Dit is een UX-prototype, geen productieklare bankapp en geen bewijs van beveiliging.

“400 rondes pentesten” is geen toetsbare veiligheidsnorm en kan niet als garantie worden beloofd. Spreek een concreet assuranceplan af met scope, dreigingsmodel, onafhankelijke testers, bevindingsernst en hertestcriteria. Voor productie zijn onder meer nodig:

- Dataminimalisatie en expliciete, herroepbare toestemming; geen ruwe transactie- of sessiedata voor onnodige profilering.
- Sterke klantauthenticatie, sessiebeveiliging, server-side autorisatie en controle van begunstigde en bedrag voor iedere betaling.
- Versleuteling tijdens transport en opslag, sleutelbeheer, fraudedetectie, auditlogging zonder gevoelige gegevens en incidentrespons.
- Threat modeling, secure code review, SAST/DAST, dependency- en secretscans, API- en autorisatietests, onafhankelijke penetratietests en aantoonbare hertests.
- Privacy-, toegankelijkheids- en fairnessbeoordeling, inclusief bescherming tegen schadelijke of discriminerende afleidingen uit leeftijd, gezinssituatie of bestedingen.

### Wat te valideren

Meet taakvoltooiing, tijd tot de juiste actie, begrip van uitgaveninzichten, hulpverzoeken, opt-in/opt-out en vertrouwen. Vergelijk met de huidige ervaring en laat klanten bepalen of de aanpassing nuttig voelt. Stel vooraf doelen en guardrails vast; optimaliseer niet op app-tijd of transactiewaarde.