Onderzoek naar microservices

## INTRODUCTIE

Voordat ik begon aan semester 3 heb ik een aantal dingen gehoord over microservices. Het was nu alleen nog maar de vraag of ik dat zou gebruiken voor het maken van mijn projecten. Met het groepsproject hadden we al snel besloten dit wel te doen. Maar nu moet ik weten of ik microservices ook voor mijn individuele project moet gebruiken. Ik ga dus onderzoeken of het het waard is om microservices te gebruiken.
Eerst ga ik onderzoeken wat microservices zijn, wat de voor- en nadelen zijn en daaruit ga ik een conclusie trekken.

Om te onderzoeken wat de voor- en nadelen zijn ga ik mijn eigen ervaringen tijdens het groepsproject in gedachte nemen (Lab Research). Ook zal ik iemand uit mijn klas die microservices voor zijn individuele project heeft gebruikt interviewen over zijn ervaringen (Field Research). Daarnaast zal ik dingen op het internet moeten opzoeken (Library Research).

Moet ik microservices gebruiken voor mijn project?

## DEELVRAGEN

### Wat is zijn microservices?
Microservices zijn kleine applicaties die onafhankelijk van elkaar worden ingezet. Ze kunnen ook onafhankelijk van elkaar ontwikkeld en getest worden. Iedere microservice heeft zijn eigen verantwoordelijkheid. Single Responsible is een belangrijke term bij het ontwikkelen van microservices. Dit betekend dat het slechts één ding doet en makkelijk is om te begrijpen.

Hieronder staat een architectuur diagram van hoe een applicatie die microservices gebruikt eruit kan zien:
![architectuur](https://docs.microsoft.com/nl-NL/azure/architecture/includes/images/microservices-logical.png)
Je ziet dat er meerdere services zijn en een API gateway die de gebruiker naar de goede service stuurt.

### Waarom zijn microservices zo populair geworden?
Wanneer een bedrijf een grote applicatie heeft gemaakt die jaren lang alleen maar groter is geworden word het na een tijdje moeilijk of onmogelijk om deze nog te kunnen onderhouden. Ook word het moeilijk om functionele toevoegingen te maken aan deze app.
Veel grote bedrijven liepen tegen deze problemen aan. Veel van die bedrijven hadden dus een veel technische problemen opgebouwd door de jaren heen. Om die problemen op te lossen en in de toekomst te voorkomen zijn er veel die zijn geswitched naar een applicatie bestaande uit microservices.

### Wat zijn de voordelen van microservices?
Een microservice-architectuur heeft veel voordelen tijdens het ontwikkelen van een applicatie. Het team krijgt daarmee de mogelijkheid om onafhankelijk van elkaar te ontwikkelen en te testen. Ook word het makkelijker om problemen op te zoeken. Al dit leidt tot snellere implementatie en probleemoplossing.
Uit mijn persoonlijke ervaring met het gebruik van microservices heb ik geconstateerd dat het handig was om met het hele groepje tegelijk bezig te zijn aan verschillende projecten. Zo konden we het werk makkelijk opsplitsen en waren we niet afhankelijk van elkaar tijdens het ontwikkelen. Ook hadden we aan het begin vaak problemen met een van de microservices, die crashte dan. Wanneer dat gebeurde waren de andere microservices nog wel live. Hierdoor werkte een deel van de applicatie altijd.

### Wat zijn de nadelen van microservices?
Microservices hebben ook een aantal nadelen. Een daarvan is dat het lastig is om een grote hoeveelheid services te managen. Ook is het werken met microservices in het algemeen gewoon complexer. Daarnaast heb ik ook gemerkt tijdens het werken aan het groepsproject dat de communicatie tussen de verschillende services een lastig puntje is. Er is een grotere kans op errors tijdens die communicatie. Ook is het moeilijker om algemene testen uit te voeren over het gesplitste systeem.

### Wat is mijn project?

## CONCLUSIE

We hebben dus bevonden dat het maken van een microservice systeem veel werk is maar het in een groep developers wel veel voordelen heeft.

Is het het waard om microservices te gebruiken?
Het antwoord is geen simpele ja of nee. Het ligt namenlijk erg aan de situatie. Het heeft een groter voordeel wanneer het gebruikt word door een groep developers. Dan kun je namelijk gebruik maken van het feit dat de services zijn opgesplit en daardoor minder merge problemen gaat krijgen als iedereen zich focust op een specifieke service. Maar als je in je eentje werkt. Lijkt het me niet altijd nodig, op dat moment is de tijd die je moet nemen voor het opzetten van het systeem het gewoon niet waard.
