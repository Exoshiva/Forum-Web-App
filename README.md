# Tekknoforum.space // Visual Architecture & MVP Status

Dieses Dokument dient als **visueller Konzeptnachweis** (Proof of Concept) für die Tekknoforum-Plattform.
Es dokumentiert den aktuellen Entwicklungsstand (v1.0 MVP) und die implementierte Design-Sprache "Cyber-Industrial".

---

## 1. Core Identity & Landing
**Status:** Implemented
Das Frontend nutzt ein dunkles, immersives Design mit Hexagon-Strukturen und Cyan-Akzenten (#06b6d4), um die Zielgruppe (Techno/Modular-Szene) direkt anzusprechen.
- **Hero Section:** Klare Typografie ("TEKKNOFORUM") mit direktem Einstieg ins Archiv.


<img src="img/landing_hero.png" width="800" alt="Landing Page">

---

## 2. The Hive Mind (Community Module)
**Status:** Functional
Ein Echtzeit-Kommunikationshub, der klassische Foren-Strukturen mit modernem Chat-Design verbindet.
- **UI:** Dunkle "Card"-Optik für Threads.
- **UX:** Markdown-Support für Beiträge und klare Status-Indikatoren ("Secure Connection").

<img src="img/forum_hive_mind.png" width="800" alt="Hive Mind Interface">

---

## 3. Black Market (E-Commerce)
**Status:** MVP Ready
Ein spezialisierter Marktplatz für Hardware (Synthesizer, Eurorack).
- **Architecture:** Datenbank-gestützte Produktverwaltung (SQLite/SQLAlchemy).
- **Filter Logic:** Kategorisierung nach Gear-Typen (Synth, Eurorack, DJ).

<img src="img/black_market.png" width="800" alt="Black Market UI">

---

## 4. Artist Node & Dashboard
**Status:** Beta
Ein Dashboard für Künstler zur Verwaltung ihrer Statistiken und Tracks.
- **Data Viz:** Visualisierung von Streams und Revenue (Mockup-Daten im MVP).
- **Booking:** Integriertes Anfragen-Formular für Promoter.

### Artist Dashboard external - empty
<img src="img/artist_dashboard_external_empty.png" width="800" alt="Artist Dashboard">

### Artist Dashboard external - filled
<img src="img/artist_dashboard_external.png" width="800" alt="Artist Dashboard">

### Artist Dashboard internal
<img src="img/artist_dashboard_internal.png" width="800" alt="Artist Dashboard">

### Upload Dashboard
<img src="img/upload_artist_dashboard.png" width="800" alt="Upload Artist Dashboard">

### Booking Dashboard
<img src="img/booking_artist_dashboard.png" width="800" alt="Booking Artist Dashboard">



## 5. User Node & Dashboard
**Status:** Beta
Ein Dashboard für User zur Verwaltung ihrer Kontakte, Follows und gefolgten Playlists.

### User Dashboard external
<img src="img/user_dashboard_external.png" width="800" alt="Artist Dashboard">

### User Dashboard internal
<img src="img/user_dashboard_internal.png" width="800" alt="Artist Dashboard">

---


### 6. Event Dashboard
<img src="img/events_dashboard.png" width="800" alt="Events Dashboard">

---

## 7. System Access & Security
**Status:** Implemented
Das Login-System ("System Access") führt die Cyberpunk-Lore fort.
- **Auth:** Flask-Login basierte Authentifizierung.
- **Design:** Terminal-inspirierte Eingabefelder.

<p align="center">
  <img src="img/auth_system.png" width="44%" alt="Auth System">
  &nbsp; &nbsp;
  <img src="img/register_system.png" width="45%" alt="Register System">
</p>


---

## 8. Error Handling & Lore
**Status:** Polished
Selbst Fehlerseiten sind Teil der User Experience.
- **404 Page:** "Lost Signal" Design statt Standard-Browser-Fehler.

<img src="img/error_404_lore.png" width="800" alt="404 Error">
