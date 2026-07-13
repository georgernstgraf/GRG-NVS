# GRG-NVS – Netzwerk- & Verteiltes Systeme

Unterlagen, Übungen und Projekte für das Fach **Netzwerk- & Verteiltes Systeme (NVS)** an der **HTL Spengergasse**, Abteilung Informatik.

**Klasse:** 2DAIF (Schuljahr 2024/25)  
**Lehrperson:** Georg Graf

---

## Beurteilung

Die Note setzt sich aus drei gleich gewerteten Bereichen zusammen:

| Bereich | Gewicht |
|---|---|
| PLF (Praxis-Leistungs-Feststellung) | 1/3 |
| Hausübungen | 1/3 |
| Mitarbeit | 1/3 |

Mitarbeit umfasst auch Schulübungen und Stundenwiederholungen; deren Qualität und
Intensität werden von der Lehrperson beurteilt.

## Hausübungen

- **Abgabe:** spätestens am nächsten Unterrichtstag **00:00 Uhr** (in der Regel eine Woche später).
- **Nachreichung:** jederzeit möglich – die erreichte Punktezahl zählt **75 %**.
- **Cutoff:** Genau **eine Woche vor dem Notenschluss, 00:00 Uhr**, ist Endtermin.
  Danach werden die Repos automatisiert ausgewertet.

---

## Themenübersicht

### Netzwerktechnik
- **Subnetting** – Aufteilung von IPv4-Netzen, VLSM, Subnetzmasken, Netz- und Hostanteil
- **DNS** – Namensauflösung, dig, recursive vs. autoritative Nameserver
- **NAT** – Network Address Translation
- **DHCP, NTP, WHOIS** – Grundlegende Netzwerkdienste
- **Firewall** – Absicherung und Härtung von Systemen
- **HTTP-Protokoll** – Cookies, Sessions

### Webentwicklung (JavaScript / Node.js)
- **JavaScript-Grundlagen** – Algorithmik (Two Sum), erste Schritte
- **Quiz-App** – Browserbasierte Quiz-Anwendung mit Bootstrap
- **Express.js** – Einführung in serverseitige Webentwicklung:
  - Routen und Middleware
  - Statische Dateien ausliefern
  - HTMX-Integration

### Tools & Arbeitsumgebung
- **Filius** – Netzwerksimulation (Übungsaufgaben)
- **WSL** – Windows Subsystem for Linux
- **Git / VS Code** – Versionsverwaltung und Entwicklungsumgebung

---

## Repository-Struktur

```
Unterlagen_und_Folien/          # PDF-Folien und Übungsblätter
  ├── Dienste_dhcp_dns_ntp_whois.pdf
  ├── Filius_Uebungsaufgaben.pdf
  ├── subnetting_exercises.pdf
  └── Student-Repos.md          # Übersicht der Schüler-Repositories

2024-04-30__js_begin_twosums/   # JS-Einstieg: Two-Sum-Algorithmus
2024-05-28__projekt_quiz/       # Quiz-Projekt (JS/HTML)
2024-06-04__AufgabeQuiz/        # Quiz-App mit Bootstrap
2024-06-11__express_app/        # Erste Express.js-App
2024-06-25__express/            # Express.js mit Static-Files und HTMX
2025-03-13_subnetting/          # Subnetting-Übung (Aufgabenblatt)

Netze_Schueler.md               # IP-Adresszuweisung pro Schüler/in
```

Die Datumspräfixe der Ordner entsprechen den Unterrichtseinheiten.

---

## Schüler-Repositories

Eine Liste aller individuellen Schüler-Repositories mit NVS-Übungen findet sich in [`Unterlagen_und_Folien/Student-Repos.md`](Unterlagen_und_Folien/Student-Repos.md).

---

## Lizenz

Sofern nicht anders angegeben: unterrichtsinterne Materialien der HTL Spengergasse.
