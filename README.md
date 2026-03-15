# Datenschutzerklärung für Oratrek
**Stand: 15. März 2026**

---

## 1. Verantwortlicher
**Lars Hebing**
Kardenstr. 102
45768 Marl, Deutschland
E-Mail: [veloq.tracker@gmail.com](mailto:veloq.tracker@gmail.com)

---

## 2. Übersicht der Datenverarbeitung
Die App ist **offline-zentriert**. Online-Verbindungen werden nur für notwendige Funktionen genutzt (z. B. Karten-Downloads, Generierung von Abbiegehinweisen) oder nach Ihrer Zustimmung (z. B. Analysedaten, Strava-Upload).

### 2.1 Verarbeitete Datenkategorien
- **Lokale Aktivitätsdaten**: GPS-Positionen, Zeitstempel, Distanz, Geschwindigkeit, Höhenmeter, Sensorwerte (nur lokal als `.fit`-Dateien gespeichert).
- **Technische Metadaten**: IP-Adresse, Geräteinformationen, App-Version, Zeitstempel (bei Karten-Downloads, GPX-Import, Crashlytics/Analytics).
- **Optionale Daten**: Aktivitätsdaten für Strava (nur nach manueller Verknüpfung).

### 2.2 Zwecke der Verarbeitung
- Bereitstellung der Kernfunktionen (Aktivitätsaufzeichnung, Offline-Navigation, Kartenverwaltung).
- Stabilität und Fehlerbehebung (Crashlytics/Analytics, nur nach Opt-In).
- Optionale Datenübermittlung an Strava (nur nach aktiver Verknüpfung).
- Netz- und Infrastrukturabrufe (Karten-Downloads, GPX-Routing).

---

## 3. Rechtsgrundlagen
- **Vertragserfüllung** (Art. 6 Abs. 1 lit. b DSGVO): Kernfunktionen der App.
- **Einwilligung** (Art. 6 Abs. 1 lit. a DSGVO): Strava-Upload, Crashlytics/Analytics (jederzeit widerrufbar).
- **Berechtigte Interessen** (Art. 6 Abs. 1 lit. f DSGVO): Betrieb der IT-Infrastruktur, Sicherheit.

---

## 4. Datenübermittlung und Empfänger

| Empfänger          | Zweck                          | Rechtsgrundlage                     | Drittlandtransfer |
|--------------------|--------------------------------|-------------------------------------|-------------------|
| Hetzner (Deutschland) | Hosting GraphHopper (GPX-Routing) | Berechtigte Interessen (Art. 6 Abs. 1 f) | Nein (EU)         |
| Cloudflare (USA/EU-Edge) | CDN für Kartendateien          | Berechtigte Interessen (Art. 6 Abs. 1 f) | Ja (DPF/Standardvertragsklauseln) |
| Google (Firebase)  | Crashlytics/Analytics (Opt-In) | Einwilligung (Art. 6 Abs. 1 a)      | Ja (DPF/Standardvertragsklauseln) |
| Strava (USA)       | Upload von Aktivitäten         | Einwilligung (Art. 6 Abs. 1 a)      | Ja (nur nach Nutzerzustimmung) |

- **Auftragsverarbeitung**: Mit allen Anbietern bestehen Vertragsverarbeitungsverträge (Art. 28 DSGVO).
- **Strava**: Agiert als eigenständiger Verantwortlicher.

---

## 5. Internationale Datentransfers
- **USA**: Cloudflare, Firebase und Strava können Daten in die USA übermitteln. Grundlage sind das **EU-US Data Privacy Framework (DPF)** und Standardvertragsklauseln.
- **EU**: Hetzner verarbeitet Daten ausschließlich in der EU.

---

## 6. Speicherdauer
- **Lokale Daten** (`.fit`-Dateien): Bis zur Löschung durch den Nutzer.
- **Strava**: Gemäß Strava-Richtlinien.
- **Server-Logs** (Hetzner/Cloudflare): 14 Tage.
- **Crashlytics/Analytics**: 14 Monate.

---

## 7. App-Berechtigungen

| Berechtigung       | Zweck                          | Rechtsgrundlage                     |
|--------------------|--------------------------------|-------------------------------------|
| Standort           | Aktivitätsaufzeichnung, Navigation | Vertragserfüllung (Art. 6 Abs. 1 b) |
| Dateispeicher      | Speicherung/Verwaltung von `.fit`-Dateien | Vertragserfüllung (Art. 6 Abs. 1 b) |
| Netzwerkzugriff    | Karten-Downloads, GPX-Routing
