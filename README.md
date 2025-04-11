# lab-6
# Gegevens transformeren met Spark in Azure Synapse Analytics

## Overzicht
Dit project demonstreert hoe Spark-notebooks in **Azure Synapse Analytics** gebruikt kunnen worden om gegevens te transformeren. Het project richt zich op het transformeren van verkoopgegevens uit CSV-bestanden die zijn opgeslagen in een Azure Data Lake Storage Gen2-account. Deze transformaties maken deel uit van typische **ETL (Extract, Transform, Load)** workflows die data engineers gebruiken.

## Uitgevoerde Stappen
1. **Resources Proviseren**:
   - Een Azure Synapse-werkruimte gemaakt met gekoppelde opslag en een Apache Spark-pool.

2. **Gegevens Verkennen**:
   - De aanwezigheid van verkoopgegevensbestanden (.csv) in de map *data* van de opslag gecontroleerd.

3. **Gebruik van Spark Notebooks**:
   - Het `Spark Transform.ipynb`-notebook geïmporteerd en geconfigureerd.
   - De krachtige gegevensverwerkingsmogelijkheden van Spark gebruikt om gegevens te reinigen, te transformeren en te analyseren.

4. **Uitvoering**:
   - Het notebook met succes uitgevoerd, waardoor ruwe verkoopgegevens werden omgezet in een gestructureerd formaat dat klaar is voor analyse.

## Tools en Technologieën
- Azure Synapse Analytics
- Apache Spark
- Azure Data Lake Storage Gen2
- Spark Notebooks

## Resultaten
- Geleerd om Spark-notebooks in Azure Synapse Analytics op te zetten en te gebruiken.
- Ruwe verkoopgegevens getransformeerd en georganiseerd voor verdere analytische taken.

## Hoe te Reproduceren
1. Resources in Azure Portal provisioneren.
2. Upload uw CSV-bestanden naar de map `data` in de opslagaccount.
3. Importeer het `Spark Transform.ipynb`-notebook in Synapse Studio.
4. Voer het notebook uit door het aan de Spark-pool te koppelen.

## Conclusie
Dit project toont aan hoe data engineers Spark-notebooks in Azure Synapse Analytics kunnen gebruiken voor efficiënte gegevensverwerkingstaken. Het is een essentiële stap in het bouwen van robuuste ETL-pijplijnen.
