# Datenschutzerklärung für Oratrek
**Stand: 29. September 2026**

---

## 1. Verantwortlicher
**Lars Hebing**
Kardenstr. 102
45768 Marl, Deutschland
E-Mail: [oratrek@gmail.com](mailto:oratrek@gmail.com)

---

## 2. Übersicht der Datenverarbeitung
Die App ist **offline-zentriert**. Online-Verbindungen werden nur für notwendige Funktionen genutzt (z. B. Karten-Downloads, Generierung von Abbiegehinweisen) oder nach Ihrer Zustimmung (z. B. Analysedaten, Upload zu Intervals.icu).

### 2.1 Verarbeitete Datenkategorien
- **Lokale Aktivitätsdaten**: GPS-Positionen, Zeitstempel, Distanz, Geschwindigkeit, Höhenmeter, Sensorwerte (nur lokal als `.fit`-Dateien gespeichert).
- **Technische Metadaten**: IP-Adresse, Geräteinformationen, App-Version, Zeitstempel (bei Karten-Downloads, GPX-Import, Crashlytics/Analytics).
- **Optionale Daten**: Aktivitätsdaten (`.fit`-Datei mit GPS-Track, Zeitstempeln und Sensorwerten sowie der Aktivitätsname) für Intervals.icu, nur nach manueller Verknüpfung mit Ihrem persönlichen API-Key. Der API-Key wird verschlüsselt auf dem Gerät gespeichert.

### 2.2 Zwecke der Verarbeitung
- Bereitstellung der Kernfunktionen (Aktivitätsaufzeichnung, Offline-Navigation, Kartenverwaltung).
- Stabilität und Fehlerbehebung (Crashlytics/Analytics, nur nach Opt-In).
- Optionale Datenübermittlung an Intervals.icu (nur nach aktiver Verknüpfung).
- Netz- und Infrastrukturabrufe (Karten-Downloads, GPX-Routing).

---

## 3. Rechtsgrundlagen
- **Vertragserfüllung** (Art. 6 Abs. 1 lit. b DSGVO): Kernfunktionen der App.
- **Einwilligung** (Art. 6 Abs. 1 lit. a DSGVO): Upload zu Intervals.icu, Crashlytics/Analytics (jederzeit widerrufbar).
- **Berechtigte Interessen** (Art. 6 Abs. 1 lit. f DSGVO): Betrieb der IT-Infrastruktur, Sicherheit.

---

## 4. Datenübermittlung und Empfänger

| Empfänger          | Zweck                          | Rechtsgrundlage                     | Drittlandtransfer |
|--------------------|--------------------------------|-------------------------------------|-------------------|
| Hetzner (Deutschland) | Hosting GraphHopper (GPX-Routing) | Berechtigte Interessen (Art. 6 Abs. 1 f) | Nein (EU)         |
| Cloudflare (USA/EU-Edge) | CDN für Kartendateien          | Berechtigte Interessen (Art. 6 Abs. 1 f) | Ja (DPF/Standardvertragsklauseln) |
| Google (Firebase)  | Crashlytics/Analytics (Opt-In) | Einwilligung (Art. 6 Abs. 1 a)      | Ja (DPF/Standardvertragsklauseln) |
| intervals.icu Ltd. (Vereinigtes Königreich) | Upload von Aktivitäten | Einwilligung (Art. 6 Abs. 1 a) | Ja (nur nach Nutzerzustimmung, siehe Abschnitt 5) |

- **Auftragsverarbeitung**: Mit allen Auftragsverarbeitern bestehen Vertragsverarbeitungsverträge (Art. 28 DSGVO).
- **Intervals.icu**: Agiert als eigenständiger Verantwortlicher (intervals.icu Ltd., 71-75 Shelton Street, Covent Garden, London WC2H 9JQ, Vereinigtes Königreich). Es gilt zusätzlich die Datenschutzerklärung von Intervals.icu.

---

## 5. Internationale Datentransfers
- **USA**: Cloudflare und Firebase können Daten in die USA übermitteln. Grundlage sind das **EU-US Data Privacy Framework (DPF)** und Standardvertragsklauseln.
- **Vereinigtes Königreich**: Intervals.icu hat seinen Sitz im Vereinigten Königreich, für das ein Angemessenheitsbeschluss der EU-Kommission besteht. Laut Intervals.icu werden die Daten unter anderem in Deutschland und Finnland verarbeitet und bei Cloud-Anbietern (Google, Backblaze, Wasabi) gespeichert.
- **EU**: Hetzner verarbeitet Daten ausschließlich in der EU.

---

## 6. Speicherdauer
- **Lokale Daten** (`.fit`-Dateien): Bis zur Löschung durch den Nutzer.
- **Intervals.icu**: Gemäß der Datenschutzerklärung von Intervals.icu. Hochgeladene Aktivitäten können Sie in Ihrem Intervals.icu-Konto löschen. Das Trennen der Verbindung in der App löscht nur den gespeicherten API-Key.
- **Server-Logs** (Hetzner/Cloudflare): 14 Tage.
- **Crashlytics/Analytics**: 14 Monate.

---

## 7. App-Berechtigungen
 | Berechtigung       | Zweck                          | Rechtsgrundlage                     |
 |--------------------|--------------------------------|-------------------------------------|
 | Standort           | Aktivitätsaufzeichnung, Navigation | Vertragserfüllung (Art. 6 Abs. 1 b) |
 | Dateispeicher      | Speicherung/Verwaltung von `.fit`-Dateien | Vertragserfüllung (Art. 6 Abs. 1 b) |
 | Netzwerkzugriff    | Karten-Downloads, GPX-Routing, Intervals.icu-Upload | Berechtigte Interessen (Art. 6 Abs. 1 f) |

---

## 8. Nutzerrechte
- **Auskunft, Berichtigung, Löschung, Einschränkung, Datenübertragbarkeit** (Art. 15–20 DSGVO).
- **Widerruf von Einwilligungen** (z. B. Intervals.icu, Analytics) jederzeit in der App (Profil → Verbindungen bzw. Datenschutz-Einstellungen).
- **Widerspruchsrecht** gegen Verarbeitungen nach Art. 6 Abs. 1 lit. f DSGVO.
- **Beschwerderecht** bei einer Aufsichtsbehörde.

---

## 9. Sicherheit
- **Technische Maßnahmen**: TLS/SSL-Verschlüsselung, Zugriffskontrollen, Datensparsamkeit.
- **Organisatorische Maßnahmen**: Regelmäßige Überprüfung der Sicherheitsstandards.

---

## 10. Änderungen dieser Datenschutzerklärung
- Aktualisierungen werden in der App veröffentlicht.
- Bei **wesentlichen Änderungen** (z. B. neue Datenverarbeitungen) informieren wir Sie gesondert.

---

## 11. Kontakt und Aufsichtsbehörde
- **Fragen/Kontakt**: [oratrek@gmail.com](mailto:oratrek@gmail.com)
- **Aufsichtsbehörde**: Landesbeauftragte für Datenschutz und Informationsfreiheit Nordrhein-Westfalen.

---

### Hinweis für Nutzer
- **Keine automatisierte Entscheidungsfindung/Profiling** (Art. 22 DSGVO).
- **Keine Pflicht zur Bereitstellung**: Ohne Standortfreigabe sind Kernfunktionen nicht nutzbar.
