# Extra Oefeningen: Lussen (Loops)

## Niveau 1: Basis en Algoritmes

### Oefening 1: Veelvouden van 5 filteren

Schrijf een lus die alle veelvouden van 5 tussen 5 en 100 afdrukt in de console.

### Oefening 2: De machtsverheffing van 2

Schrijf een programma dat de eerste 10 machten van 2 afdrukt (van `2^1 = 2` tot `2^10 = 1024`).

### Oefening 3: Product van een reeks (Faculteit)

Bereken met een lus het product van alle getallen van 1 tot en met 8 (`1 * 2 * 3 * ... * 8`) en toon het eindresultaat.

### Oefening 4: Pincode controle (Validation loop)

Simuleer een pinautomaat met een `while`-lus. Loop door een array met ingevoerde pincodes `["1234", "0000", "9876", "4512", "1111"]`. Stop zodra de juiste pincode `"4512"` is gevonden en toon `"Pincode correct! Geld wordt voorbereid."`.

---

## Niveau 2: Array- en Dataverwerking

### Oefening 5: Kleinste getal bepalen [length]

Gegeven een array met dagtemperaturen: `[14, 9, 21, 6, 18, 11]`. Zoek met een lus de laagste temperatuur op zonder gebruik te maken van ingebouwde sorteer- of `Math.min()` functies.

### Oefening 6: Korting toepassen op producten [push]

Gegeven een array met originele prijzen: `[50, 120, 35, 80, 15]`. Maak een nieuwe array waarin elk bedrag boven de €40 een korting van 15% krijgt. Bedragen van €40 of lager blijven ongewijzigd.

### Oefening 7: Klinkers tellen in een tekst [includes]

Schrijf een lus die een string (bijvoorbeeld `"Informatica"`) teken per teken doorloopt en telt hoeveel klinkers (`a, e, i, o, u`) erin voorkomen (hoofdletterongevoelig).

### Oefening 8: URL's controleren op veiligheid [startsWith]

Gegeven een lijst met webadressen: `["https://school.be", "http://onveilig.com", "https://portaal.be", "ftp://server.local"]`. Lus door de lijst en druk enkel de veilige links af die beginnen met `"https://"`.

---

## Niveau 3: Geavanceerde toepassingen en Nested Loops

### Oefening 9: Server- en poortcombinaties genereren

Gegeven een lijst met servers:

```javascript
const servers = ["Web", "Mail", "Database"];
```

Gebruik een nested loop om voor elke server poort `80` en poort `443` te koppelen en af te drukken in het formaat `"Web:80"`, `"Web:443"`, enz.

### Oefening 10: Dataverbruik met datalimiet (Stop-conditie)

Gegeven een array met dagelijks dataverbruik in MB: `[450, 1200, 800, 2100, 600, 950]`. Je databundel heeft een limiet van `4000` MB. Tel met een lus het verbruik op per dag. Zodra de limiet van `4000` MB overschreden zou worden, breek je de lus af met `break` en druk je af op welke dag (index) de limiet bereikt werd.
