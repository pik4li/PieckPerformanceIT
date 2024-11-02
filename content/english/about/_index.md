---
title: "Hey, ich bin Alex!"
meta_title: "Über mich"
description: "Damit sie mich ein wenig besser kennen lernen, bevor ich Sie kennen lerne :)"
image: "/images/avatar.png"
draft: false
---

Mein Name ist Alexander Pieck und ich beschäftige mich schon seit meiner Kindheit intensiv mit PCs. 2019 begann ich meine Ausbildung zum Fachinformatiker für Systemintegration und schloss diese 2022 erfolgreich ab. Während meiner Ausbildung in einem kleinen IT-Dienstleistungsunternehmen in Ulm konnte ich wertvolle Erfahrungen sammeln. Nach dem Abschluss wollte ich mich jedoch neuen Herausforderungen stellen und bin seitdem bei einem größerem lokalen Unternehmen angestellt, wo ich für die Administration von Windows-Servern und deren Anwendungen verantwortlich bin.

Da mir der direkte Kundenkontakt zu kleineren Unternehmen fehlt und ich ohnehin regelmäßig Freunden und Bekannten bei IT-Problemen helfe, habe ich mich entschieden, meine Dienste auch für weitere Kunden anzubieten. Als jemand, der aus einfachen Verhältnissen stammt, weiß ich, wie schwierig es sein kann, einen ehrlichen und bezahlbaren IT-Dienstleister zu finden.

Ich bin begeisterter Open-Source-Anhänger und empfehle daher gerne kostengünstige Alternativen zu kommerziellen Produkten. Natürlich habe ich auch umfassende Erfahrung mit Microsoft 365, VMware und anderen proprietären Lösungen, bevorzuge jedoch, wenn möglich, Open-Source-Alternativen zu integrieren, um langfristig Kosten zu senken und mehr Flexibilität zu bieten.

{{< accordion "Interessante Lösungen die ich selbst nutze" >}}

## Immich: Die private Lösung für Fotos und Videos

[Immich](https://immich.app) ist **die** Lösung für alle, die Google oder Apple nicht mit ihren Fotos und Videos vertrauen möchten. Datenschutz ist ein wertvolles Gut, denn große Cloud-Anbieter wie Google und Apple verdienen an Ihren Daten.

Ich nutze Immich seit über einem Jahr als meine zentrale Plattform für das Speichern und Verwalten all meiner Fotos und Videos. Die automatischen Backups von Google sind bei mir deaktiviert, und stattdessen sichert Immich alle Inhalte sicher auf meinem eigenen Server. Über die Immich-App und die dazugehörige Website kann ich meine Bilder und Videos jederzeit ansehen, sichern, herunterladen und bei Bedarf mit anderen Accounts auf meinem Server teilen. Durch die direkte Freigabe von Alben wird doppeltes Hochladen und die Entstehung von Duplikaten vermieden.

### Sicherheit und Kontrolle

Meine Immich-Installation läuft auf einem VPS (Virtueller Privater Server), den ich komplett selbst verwalte und der bei [Hetzner](https://www.hetzner.com) gehostet ist. Die Entscheidung für einen Cloudserver fiel bewusst, da mir die 1Gbit/s Bandbreite für schnelles Hochladen und komfortables Ansehen der Inhalte zur Verfügung steht. Der Zugriff auf meinen Immich-Server ist dabei ausschließlich über eine gesicherte VPN-Verbindung möglich, was maximale Sicherheit bietet.

Je nach den Anforderungen an Speicherkapazität und Performance variieren die monatlichen Serverkosten.

### Aktuelle Kostenübersicht

| Beschreibung                                                            | Preis             |
| ----------------------------------------------------------------------- | ----------------- |
| Hetzner CX32 Server (4 CPUs, 8GB RAM, 80GB Festplatte)                  | 6,30 €            |
| Zusätzliche 100GB virtuelle Festplatte (Speicher für Bilder und Videos) | 4,40 €            |
| Automatische Backups von Hetzner                                        | ca. 1,19 €        |
| **Gesamt**                                                              | **11,81 €/Monat** |

{{< /accordion >}}
