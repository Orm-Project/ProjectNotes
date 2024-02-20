# ORM Project Code-First and Database-First


## Team Members

* Simon
* PandaOnCaffeine (Tue)
* Quan (Andreas)


# The project plan:

## Research

### Hvad er ORM?

* ORM, som står for "Object-Relational Mapping", er en programmeringsteknik der bruges til at konvertere data mellem systemer, der normalt ikke arbejder direkte sammen, ved hjælp af objektorienterede programmeringssprog. ORM gør det muligt for udviklere at arbejde med databaser ved hjælp af de avancerede og brugervenlige kodestrukturer de er vant til, i stedet for at skrive kompleks SQL-kode. Ved at mape database tabeller til programmeringssprogets klasser, kan udviklere manipulere data i databasen gennem objektinstanser, hvilket gør kode mere intuitiv og lettere at vedligeholde.


### Hvad er de vigtigeste funktioner i dette ORM-framework?

* **Data Mapping:** Automatisk mapping af objekter i programmeringssproget til databasetabeller og omvendt hvilket gør det nemmere at arbejde med data.

* **CRUD-operations:** Forenklet udførelse af Create, Read, Update og Delete operations på databasen gennem objektmetoder uden direkte SQL.

* **Transaktionshåndtering:** Automatisering og forenkling af databasetransaktioner, hvilket sikrer dataintegritet og konsistens.

* **Forespørgselsbygning:** Letbyggede forespørgsler ved hjælp af objektmetoder i stedet for kompleks SQL-kode, hvilket forbedrer læsbarheden og vedligeholdelsen af kode.

* **Caching:** Forbedring af applikationens ydeevne ved at cache ofte brugte data, så databasen ikke overbelastes med gentagne forespørgsler.


### Hvordan håndterer dette ORM-framework relationer mellem forskellige tabeller (one-to-one, one-to-many, og many-to-many)?

* **One-to-One:** Et element i en tabel er direkte knyttet til et element fra en anden tabel, dette tillader objekter at referere til hinanden som om de var en del af samme enhed

* **One-to-Many:** Et element i en tabel kan have forbindelse til flere elementer i en anden tabel. ORM muliggør at et objekt kan indeholde en liste over disse relationer hvilket afspejler situationer fra den virkelige verden, som f.eks. en kunde med flere bestillinger

* **many-to-Many:** Flere elementer i en tabel kan have relationer til flere elementer i en anden tabel. ORM håndterer dette gennem en mellemstående tabel, der registrerer alle de krydsende forbindelser, typisk for relationer som studerende og kurser, hvor mange studerende kan tilmelde sig mange kurser.


### Hvordan bruger dette ORM-framework migrations til at styre ændringer i databasens skema?

* ORM bruger migrations til at styre og anvende ændringer i databasens skema på en kontrolleret og versioneret måde. Migrations er scripts eller filer, der definerer, hvordan databasens skema skal ændres, f.eks. ved at tilføje, ændre eller fjerne tabeller og kolonner. Når en udvikler foretager ændringer i applikationens datamodel, genererer ORM-frameworket en migration, der afspejler disse ændringer. Dette giver mulighed for at opdatere databasen til den nyeste skema-version uden at miste data. Migrations sikrer konsistens og sporbarhed af skemaændringer over tid, hvilket gør det lettere at udrulle og tilbagerulle ændringer i både udviklings- og produktionsmiljøer.


### Hvordan kan man optimere ydeevnen med dette ORM-framework?

* **Effektiv Forespørgselsbygning:** Skriv effektive forespørgsler ved kun at hente de data, der er nødvendige. Undgå at hente hele objekter, når du kun har brug for enkelte felter fra dem.

* **Lazy Loading:** Anvend lazy loading til at forsinke indlæsningen af relaterede data, indtil det er nødvendigt. Dette kan reducere den indledende belastning ved at hente data.

* **Caching:** Benyt caching til at gemme ofte anvendte data i hukommelsen, så databasen ikke behøver at blive forespurgt hver gang dataene er nødvendige.

* **Indeks:** Sørg for, at databasetabeller er korrekt indekseret baseret på dine forespørgselsmønstre for at fremskynde dataopslag.


### Hvordan håndterer dette ORM-framework arv i både Code-First og Database-First tilgange?


## Code-First

### Step 1
...
### Step 2
...

## Database-First

### Step 1
...
### Step 2
...
