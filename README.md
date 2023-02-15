> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)


![eindresultaat](https://user-images.githubusercontent.com/112856021/219123786-8adf88f2-03bb-4073-b6eb-e1d3fb3b4fee.png)


# My tribe profile card

In deze opdracht was het de bedoeling om een eerder gemaakt visitekaartje uit week 1 opieuw te ontwerpen en bouwen. Ook heb ik voor het eerst met Node gewerkt in deze opdracht.

## Analyseren
In de analysefase kijk ik wat er moet gebeuren om een taak uit te voeren. Voordat ik met deze leertaak kan beginnen moet mijn ontwikkelomgeving ingericht worden door Node te installeren. Dit deed ik door de map aan te roepen in de terminal om vervolgens npm install erin te brengen. Hierdoor kan ik mijn website in de browser bekijken door naar mijn localhost te gaan.

## Ontwerpen
## Bouwen
Tijdens de bouw fase heb ik mijn bestanden van mijn vesitekaartje in sprint 1 moeten importeren. Mijn html heb ik naar de index.ejs overgeplaatst. De css en js heb ik in een apparte map gezet genaamd public. Ook maakte ik een media map in public om daar mijn foto's kwijt te maken.

Het verschil tussen dit project en het project in sprint 1 is dat ik dit keer mijn gegevens uit een datebase moet halen in https://whois.fdnd.nl/. Dit deed ik dus doormiddel van node.js. Node zorgde ervoor dat ik doormiddel van simpele code data kan laten zien uit de database. De namen van de visitekaarten haalde ik bijvoorbeeld uit de database doormiddel van de line <%= member.name %>. Super simpel en leuk om te zien!

## Intergreren 
Zodra ik klaar was met bouwen ging ik mijn website publiceren op het internet. Omdat we met Node werken is dit iets ingewikkelder dan voorheen, er moet namelijk een serveromgeving opgestart worden. Ik gebruikte hiervoor cyclic.sh als hostingpartij.

## Testen

