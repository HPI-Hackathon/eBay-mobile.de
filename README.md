![Banner](https://raw.githubusercontent.com/HPI-Hackathon/Info/master/Media/banner.jpg)

Ihr werdet 24h Zeit haben im Team eine eigene Idee mit der [eBay Kleinanzeigen](http://kleinanzeigen.ebay.de/anzeigen/) / [Mobile.de](http://www.mobile.de/) APIs umzusetzen. Dabei werden Studenten des HPI, sowie Experten von unseren Projektpartnern die Betreuung vor Ort übernehmen. Und natürlich wird es auch Preise zu gewinnen geben, darunter: 
- Xbox One
- iPad mini
- Moto 360
- Arduino Sets

## Fotos
Eindrücke vom Event sind im [Google+ Album](https://plus.google.com/photos/100169449129032220413/albums/6134982738880644641?authkey=CKHeqd3or43H6AE) zu finden.

## APIs
[Mobile.de Docs](http://m.mobile.de/svc/api.html) und 
[eBay Kleinanzeigen Docs](http://api.ebay-kleinanzeigen.de/docs/pages/home)
```
Suche nach Marken bei mobile.de (JSON):
$ curl 'http://m.mobile.de/svc/r/makes/Car'

Suche nach BMW Autos bei mobile.de (JSON):
$ curl 'http://m.mobile.de/svc/s/?mk=3500'

Lade eine Anzeige von eBay Kleinanzeigen (XML):
$ curl --user USERNAME:PASSWORD 'https://api.ebay-kleinanzeigen.de/api/ads.json'
```

## Bilder URLs in den APIs

Beim Anfragen der Bilder URLs kann mit einem Präfix bestehend aus ID + '_' eine bestimmte Größe requestet werden:

| Id	| Width	 | Height |
|----|--------|--------| 
|0 |	96	 |96 |
| 1 |	400 |	400 |
| 2 |	200 |	200 |
| 3 |	800 |	800 |
| 6 |	70	 |70 |
| 7 |	150 |	150 |
| 8 |	400 |	300 |
| 12 |	500 |	500 |
| 14 |	64	 |64 |
| 20 |	800 |	600 |
| 22 |	60	 |60 |
| 23 |	80	 |80 |
| 26 |	140 |	140 |
| 27 |	640 |	480 |
| 34 |	50	 |50 |
| 35 |	300 |	300 |
| 37 |	175 |	175 |
| 39 |	32	 |32 |
| 45 |	1200 |	1200 |
| 56 |	100 |	100 |
| 57 |	1600 |	1600 |
| 58 |	640 |	640 |
| 59 |	960 |	960 |
| 62 |	225 |	225 |
| 85 |	726 |	726 |
| 86 |	1024 |	1024 |
| 90 |	220 |	220 |
| 97 |	90	 |90 |
| 103|	180	 |180 |
| 107|	1000 |	1000 |
| 116|	250	 |250 |
| 118|	275	 |275 |
| 119|	110	 |110 |

## Projekte
Reicht eure Hacks bitte bis zur Deadline bei unserem [Event auf Hacker League](https://www.hackerleague.org/hackathons/hpi-hackathon-mit-ebay-and-mobile-dot-de) ein. Alle eingereichten Projekte müssen mit einer open-source Lizenz auf GitHub gehostet sein. Wir haben dazu eine [HPI Hackathon Organisation](https://github.com/HPI-Hackathon) eingerichtet.

## Themen
Orientieren solltet Ihr euch an einem der folgenden Themen:

**Wearables**
Wie nutze ich mobile.de oder eBay Kleinanzeigen mit Wearables?

**Inspire**
Wie finde ich das beste Produkt oder Auto für mich?

**Gamification**
Wie kann ich spieltypische Elemente in einer App basierend auf den Daten von eBay Kleinanzeigen oder mobile.de nutzen

**Location Based Services**
Wie helfen mir Location Based Services oder Geofencing, wenn ich eBay Kleinanzeigen oder mobile.de nutze?
