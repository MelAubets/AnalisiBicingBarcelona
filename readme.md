# Anàlisi de dades del Bicing Barcelona
## Projecte Final Introducció al Big data
### Mel Aubets

En aquest projecte s’analitzen dades del Bicing de l’ajuntament de Barcelona per extreure’n informació rellevant sobre el seu ús. També s’utilitzen les dades de població per districte postal per analitzar la rendibilitat per zones.

#### Es realitzen les següents consultes:
- Considerant rendibles aquelles estacions en les que hi ha més d’un 50% de bicicletes usades de mitjana, quantes estacions rendibles hi ha? Quantes no ho son?
- Quins són els districtes postals amb més i menys rendibilitat?
- Quins són els districtes postals amb més i menys estacions per població?
- A quins districtes postals s’haurien d’afegir estacions? quins en sobren?

Aquestes consultes s'han realitzat amb diferents configuracions de PySpark, també s'ha comparat l’us del mòdul de pyspark, SQLcontext, obsolet, en front del mòdul de pyspark.sql SparkSession.
Finalment, s'han realitzat les consultes mitjançant pandas i s'han comparat els temps d’execució.

Per realitzar les consultes s'han utilitzat les bases de dades dels següents enllaços, és necessari descarregarles per executar el notebook.

- [Estat estacions bicing](https://opendata-ajuntament.barcelona.cat/data/es/dataset/estat-estacions-bicing)
- [Informació estacions bicing](https://opendata-ajuntament.barcelona.cat/data/es/dataset/informacio-estacions-bicing)