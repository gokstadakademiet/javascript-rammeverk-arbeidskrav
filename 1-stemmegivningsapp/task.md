# Oppgave: Lag en Enkel Stemmegivningsapp

## Mål:
Lag en React-applikasjon som lar brukere stemme på sine favorittkandidater. Hver kandidat skal ha sin egen stemmeteller, og brukere skal kunne øke eller redusere stemmetallet for hver kandidat. Målet er å øve på å bruke `useState` for å håndtere tilstanden i React-komponenter.

## Krav:
1. **Flere Kandidater:** Appen skal vise en liste med kandidater. Hver kandidat skal ha sin egen stemmeteller.
2. **Øke/Redusere Knapper:** Hver kandidat skal ha to knapper: en for å øke stemmetallet med 1 og en for å redusere med 1.
3. **Legg til/Fjern Kandidater:** Appen skal ha knapper; én for å legge til ny kandidat og én for å fjerne kandidater.
4. **Vis Totale Stemmer:** Appen skal vise det totale antallet stemmer på tvers av alle kandidater.
5. **Søkefelt:** Legg til et søkefelt for å filtrere kandidater etter navn.
6. **Rediger Kandidatnavn:** Gjør det mulig å redigere navnet på hver kandidat.
7. **Stemmegivningshistorikk:** Hold en historikk over avgitte stemmer og vis den. Hvis en kandidat er blitt fjernet etter de ble stemt på, skal stemmene denne kandidaten har mottatt også fjernes fra stemmegivningshistorikken.

## Instruksjoner:
1. **Oppsett:** Lag en ny React-applikasjon ved å bruke `Vite`.
2. **Komponentstruktur:**
    * **App-komponent:** Hovedkomponenten som holder tilstanden for alle kandidatene.
    * **Option-komponent:** En barnekomponent som representerer en enkelt kandidat med sine øke- og redusereknapper.
    * Eventuelle andre komponenter dere ser er hensiktsmessig for å oppnå god struktur
3. **Tilstandshåndtering:**
    * Bruk `useState` for å håndtere tilstanden til kandidatene i `App`-komponenten.
    * Tilstanden skal være en array av kandidatobjekter, hver med en `name` og `votes`-egenskap.
4. **Funksjonalitet:**
    * Implementer logikken for å legge til en ny kandidat med en initial stemmetall på 0.
    * Implementer logikken for å fjerne en kandidat.
    * Implementer logikken for å øke og redusere stemmetallet for hver kandidat.
    * Beregn og vis det totale antallet stemmer på tvers av alle kandidater.
    * Implementer et søkefelt for å filtrere kandidater etter navn.
    * Implementer muligheten til å redigere navnene på hver kandidat.
    * Implementer logikken for å holde en stemmegivningshistorikk og vis den. Fjern stemmene fra historikken hvis en kandidat blir fjernet.

## Generelt:
1. **Sett opp et nytt React-prosjekt med Vite.**
2. **Implementer i henhold til krav gitt over**
3. **Test Appen Din:** Sørg for at alle funksjonaliteter fungerer som forventet.

Denne oppgaven vil hjelpe studenter med å øve på å bruke `useState` for å håndtere tilstand i en React-komponent og forstå hvordan man sender tilstand og funksjoner som props til barnekomponenter.

