# Projektdokumentation – M158 LB2 <br>WordPress-Migration

## Übersicht
# Projektdokumentation – Webserver-Projekt

Diese Dokumentation ist nach den Aufgaben (1–14) gegliedert. Jede Aufgabe ist in drei Phasen unterteilt. Bitte tragen Sie Ihre Ergebnisse jeweils unter den entsprechenden Abschnitten ein.

---

## Aufgabe 1 – Projektplan erstellen

### Zeitplan

```mermaid
gantt
    dateFormat  YYYY-MM-DD
    title WordPress-Web-App-Migration (15.05.2025 - 13.07.2025)
    section Planung
    Planung          : 2025-05-15, 2025-05-21
    section Vorbereitung
    Meilenstein-1      : 2025-05-22, 2025-05-31
    Vorbereitung     : 2025-05-22, 2025-05-31
    section Migration
    Meilenstein-2      : 2025-06-01, 2025-06-15
    Migration        : 2025-06-01, 2025-06-15
    section Testing
    Meilenstein-3      : 2025-06-16, 2025-06-30
    Testing          : 2025-06-16, 2025-06-30
    section Dokumentation
    Dokumentation    : 2025-07-01, 2025-07-13
```

---

## Aufgabe 2 – Architekturdiagramm erstellen

### Stufe 1 - 3

![image](/images/architekturdiagramm.png)

---

## Aufgabe 3 – AWS-Umgebung einrichten

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

DB_USERNAME: admin
DB_PASSWORD: Tony_onHisWAY218!
DB_URL: wp-database.c69qo3ofuvyq.us-east-1.rds.amazonaws.com
---

## Aufgabe 4 – DNS-Konfiguration

Ändern Sie die Stufe, für die Sie sich entschieden haben, selbst.

### Stufe ?

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 5 – Webserver konfigurieren

### Stufe 1

Wordpress User:

user: admin

ssh -i ~/.ssh/m158.pem -L 8888:localhost:80 ubuntu@<44.203.193.128> -N

Datenbank-User: wp_readwrite
Datenbank-Passwort: Tony_onHisWAY218!

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 3

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 6 – PHP einrichten

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 3

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 7 – MySQL/MariaDB aufsetzen

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 3

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 8 – Web-Datenbanktool (phpMyAdmin/Adminer)

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 3

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 9 – FTP-Zugang einrichten

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 10 – WordPress migrieren

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 3

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 11 – Backup-Konzept umsetzen

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 12 – Testing der Webapplikation

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 3

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 13 – Deployment automatisieren

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 3

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 14 – Docker verwenden

### Stufe 1 - 3

Fügen Sie hier Ihre Ergebnisse ein

---