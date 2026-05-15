---
tags: [kunde, netzwerk, telekom, angebot, analyse]
datum: 2026-05-15
status: analysed
kunde: unnamed
erstellt_von: Hermes (IOFDigital AI)
---

# Netz-Analyse: Telekom Company Tarife

**Dokument:** Gründer- und TechnologieCentrum, Gummersbach, 11.01.2024
**Quelle:** Angebot vom Kunden

---

## Tarifübersicht

| Tarif | Download | Upload | Preis | GTC-Mieter |
|---|---|---|---|---|
| **Company Start 500** | 500 Mbit/s | 100 Mbit/s | **69,95 €** | 62,95 € |
| **Company Pro 500** | 500 Mbit/s | 100 Mbit/s | **99,95 €** | 89,95 € |
| 500 mit fester IP | — | — | *Aufpreis* | — |
| **Company Start 1000** | 1.000 Mbit/s | 200 Mbit/s | **99,95 €** | — |
| **Company Pro 1000** | 1.000 Mbit/s | 200 Mbit/s | **129,95 €** | — |
| 1000 mit fester IP | — | — | *Aufpreis* | — |
| **Company Start 2000** | 2.000 Mbit/s | 1.000 Mbit/s | **149,95 €** | 134,95 € |
| **Company Pro 2000** | 2.000 Mbit/s | 1.000 Mbit/s | **179,95 €** | — |
| 2000 mit fester IP | — | — | *Aufpreis* | — |

### Download-Details

| Tarif | Download min | Download normal | Download max |
|---|---|---|---|
| 500er Serie | 200 Mbit/s | 500 Mbit/s | 500 Mbit/s |
| 1000er Serie | 700 Mbit/s | 850 Mbit/s | 1.000 Mbit/s |
| 2000er Serie | 1.400 Mbit/s | 1.700 Mbit/s | 2.000 Mbit/s |

### Upload-Details

| Tarif | Upload min | Upload normal | Upload max |
|---|---|---|---|
| Start 500 | — | 50 Mbit/s | 100 Mbit/s |
| Pro 500 | — | 80 Mbit/s | 100 Mbit/s |
| 1000er Serie | — | 200 Mbit/s | 200 Mbit/s |
| 2000er Serie | — | 1.000 Mbit/s | 1.000 Mbit/s |

---

## Technologie

- **Bis 500 Mbit/s:** VDSL-Technologie
- **Ab 1.000 Mbit/s:** Fiber-Technologie (Glasfaser)
- **Company Start 2000:** Fiber-Technologie

## Wichtige Hinweise

| Merkmal | Company Start | Company Pro |
|---|---|---|
| IP-Adresse | Dynamisch (IPv4 + IPv6) | Feste IP |
| Verfügbarkeit | 97,0 % im Jahresdurchschnitt | 97,0 % |
| Router | Nicht inklusive (ONT dabei) | Nicht inklusive |
| GTC-Mieter-Rabatt | Ja | Nein |

> **Router:** ONT (Glasfasermodem) ist im Preis enthalten. Der Router muss separat angeschafft werden bzw. vorhandener Router muss auf Kompatibilität geprüft werden.

---

## Anforderungsprofil Büro

### Eckdaten
- **8 Arbeitsplätze**
- **2 Geräte pro Arbeitsplatz** = 16 Endgeräte
- **Server** für Dateiablage, Backup, ggf. virtuelle Maschinen
- **Laptops via Dockingstation** (Kabelgebunden) — LAN bevorzugt
- **WiFi** als Ergänzung für Gäste/Mobilgeräte

### Bandbreitenbedarf Schätzung

| Nutzung | Pro Arbeitsplatz | Gesamt (16 Geräte) |
|---|---|---|
| Cloud / Teams / Zoom | 2-5 Mbit/s | ~30-50 Mbit/s |
| Datei-Server / NAS | 10-20 Mbit/s | ~50-80 Mbit/s |
| Updates / Sonstiges | — | ~20 Mbit/s |
| **Summe parallel** | | **~100-150 Mbit/s** |

---

## Empfehlung: **Company Start 1000 + feste IP**

### Begründung

| Kriterium | Bewertung |
|---|---|
| **Bandbreite ausreichend** | ✅ 1.000 Mbit/s Down — alle 16 Geräte gleichzeitig |
| **Upload für Server** | ✅ 200 Mbit/s Up — ausreichend für Backup, VPN, Cloud-Sync |
| **Feste IP für Server** | ✅ Notwendig für Remote-Zugriff (VPN, RDP, etc.) |
| **Preis/Leistung** | ✅ 99,95 € + feste IP (~5-10 €) ≈ **110 €/Monat** |
| **Fiber (Glasfaser)** | ✅ Zukunftssicher, symmetrischere Leitung |

### Vergleich mit Alternativen

| Tarif | Vorteil | Nachteil |
|---|---|---|
| Start 500 (69,95 €) | Günstig | Upload zu gering (50-100 Mbit/s) |
| **Start 1000 (99,95 €)** ✅ | **Bester Kompromiss** | Feste IP optional |
| Start 2000 (149,95 €) | Sehr hohe Bandbreite | Deutlich teurer, für 8 Plätze Overkill |
| Pro 1000 (129,95 €) | Feste IP inklusive | 30 € teurer als Start + IP |
| Pro 2000 (179,95 €) | Maximalausbau | Viel zu teuer für die Anforderungen |

---

## Server & Netzwerk-Infrastruktur

### Komponenten

| Komponente | Empfehlung | Geschätzte Kosten |
|---|---|---|
| **Router** | FritzBox 5590 (Fiber, Business) | ~250-300 € |
| **Switch** | 24-Port Gigabit Managed Switch (z. B. TP-Link TL-SG1024DE, Ubiquiti USW-24) | ~100-150 € |
| **Access Point** | Ubiquiti U6+ oder Fritz!Repeater | ~80-120 € |
| **Patchpanel + Dosen** | 8x LAN-Dose verkabelt zu Patchpanel | ~200-300 € |
| **Server / NAS** | Synology DS224+ (2 Bay) oder DS923+ (4 Bay) | ~300-700 € |
| **Verkabelung** | CAT6/CAT7 Kabel, Verlegearbeit | ~200-500 € |
| **≈ Gesamt einmalig** | | **~1.200-2.000 €** |

### Netzwerk-Topologie

```
Internet (Fiber)
    ↓
ONT (vom Provider, inklusive)
    ↓
FritzBox 5590 (Router + Firewall + DHCP)
    ↓
Managed Switch (24-Port Gigabit)
    ↓
├── 8x LAN-Dosen → Dockingstations → Laptops
├── Server / NAS (kabelgebunden)
├── Access Point (WLAN für Gäste/Mobil)
└── Reserve-Ports
```

> **Wichtig:** Jeder Arbeitsplatz bekommt eine **LAN-Dose** → Dockingstation → Laptop.  
> WLAN nur als Ergänzung für Gäste, Handys und Besprechungsräume.

---

## Nächste Schritte

1. [ ] Kunde über Empfehlung informieren
2. [ ] Festen IP-Adresse bei Telekom beauftragen
3. [ ] Router beschaffen (FritzBox 5590 oder gleichwertig)
4. [ ] LAN-Verkabelung planen und durchführen
5. [ ] Switch, AP und Server beschaffen
6. [ ] Netzwerk einrichten und testen

---

## Verknüpfte Notizen

- [[Server-Planung Büro]]
- [[Netzwerk-Infrastruktur IOFDigital]]
- [[Vorlage Angebotsanalyse]]

---

*Erstellt von Hermes (IOFDigital AI Operations) am 15.05.2026*
*Im Auftrag von Imran Moujtahid, IOFDigital*
