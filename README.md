# LibraryM295

Spring Boot Backend-Applikation zur Verwaltung von Büchern. Die Anwendung stellt eine REST API bereit, über die Bücher mit Titel und Autor erstellt, abgerufen, aktualisiert und gelöscht werden können (CRUD). Als Datenbank wird H2 (In-Memory) verwendet.

## Voraussetzungen

- Java 17+
- Maven 3.6+
- IntelliJ IDEA (empfohlen)

## Starten

Projekt in IntelliJ IDEA öffnen, dann die Datei starten:

```
src/main/java/ch/library/LibraryApplication.java
```

Das Backend läuft auf **http://localhost:8080**.

## API-Endpunkte

| Methode | Endpunkt | Beschreibung |
|---|---|---|
| GET | /books | Alle Bücher abrufen |
| POST | /books | Neues Buch erstellen |
| PUT | /books | Buch aktualisieren |
| DELETE | /books/{id} | Buch löschen |

## H2-Datenbank-Konsole

Erreichbar unter: http://localhost:8080/h2-console

- **JDBC URL:** `jdbc:h2:mem:library`
- **Benutzername:** `sa`
- **Passwort:** *(leer lassen)*
