![Banner](https://raw.githubusercontent.com/HPI-Hackathon/Info/master/Media/banner.jpg)

Ihr werdet 24h Zeit haben im Team eine eigene Idee mit der [eBay Kleinanzeigen](http://kleinanzeigen.ebay.de/anzeigen/) / [Mobile.de](http://www.mobile.de/) APIs umzusetzen. Dabei werden Studenten des HPI, sowie Experten von unseren Projektpartnern die Betreuung vor Ort übernehmen. Und natürlich wird es auch Preise zu gewinnen geben, darunter: 
- Xbox One
- iPad mini
- Moto 360
- Arduino Sets

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
