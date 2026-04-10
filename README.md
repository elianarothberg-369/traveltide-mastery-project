# TravelTide Customer Segmentation Project

## Projektübersicht
In diesem Projekt habe ich das Nutzerverhalten auf der TravelTide-Plattform analysiert, um datenbasierte Kundensegmente zu identifizieren und daraus konkrete Handlungsempfehlungen abzuleiten.

Ziel war es, eine fundierte Grundlage für ein personalisiertes Belohnungsprogramm zu schaffen, das auf realem Nutzerverhalten basiert und geschäftlich sinnvoll eingesetzt werden kann.

## Business-Ziel
Das Projekt verfolgt das Ziel, TravelTide dabei zu unterstützen, Kunden besser zu verstehen und datenbasierte Entscheidungen zu treffen, insbesondere im Hinblick auf:

•⁠  ⁠Steigerung der Conversion Rate
•⁠  ⁠Verbesserung der Kundenbindung
•⁠  ⁠Optimierung von Rabattstrategien
•⁠  ⁠Reduktion von Stornierungen
•⁠  ⁠Identifikation wertvoller Kundensegmente

## Zentrale Business-Frage
Welche Kundengruppen lassen sich auf Basis ihres Verhaltens identifizieren und wie können diese gezielt zur Optimierung von Marketing-, Loyalty- und Umsatzstrategien genutzt werden?

## Datengrundlage
Die Analyse basiert auf mehreren relationalen Tabellen:

•⁠  ⁠users
•⁠  ⁠sessions
•⁠  ⁠flights
•⁠  ⁠hotels

Die sessions-Tabelle bildet dabei die zentrale Grundlage, da sie das tatsächliche Nutzerverhalten (Klicks, Buchungen und Stornierungen) abbildet.

## Methodik

### SQL – Feature Engineering
Im ersten Schritt habe ich eine User-Level Feature Table erstellt, in der pro Nutzer die wichtigsten Verhaltenskennzahlen aggregiert wurden.

Dazu gehören unter anderem:

•⁠  ⁠total_sessions
•⁠  ⁠total_clicks
•⁠  ⁠avg_clicks_per_session
•⁠  ⁠flights_booked
•⁠  ⁠hotels_booked
•⁠  ⁠cancellations
•⁠  ⁠avg_discount_total
•⁠  ⁠conversion_rate
•⁠  ⁠cancellation_rate
•⁠  ⁠booking_type
•⁠  ⁠customer_value

Diese Tabelle bildet die Grundlage für alle weiteren Analysen.

### Explorative Datenanalyse (EDA)
Im Rahmen der explorativen Analyse habe ich zentrale Muster im Nutzerverhalten untersucht, insbesondere:

•⁠  ⁠die Verteilung des Kundenwerts
•⁠  ⁠den Zusammenhang zwischen Buchungstyp und Umsatz
•⁠  ⁠den Einfluss von Rabatten auf das Verhalten
•⁠  ⁠Unterschiede in Conversion und Stornierungsraten

### Datenaufbereitung und Clustering (Python)
Auf Basis der vorbereiteten Daten habe ich eine Segmentierung durchgeführt:

•⁠  ⁠Bereinigung und Prüfung der Daten
•⁠  ⁠Auswahl relevanter Features
•⁠  ⁠Skalierung der Variablen
•⁠  ⁠Durchführung eines Clustering-Ansatzes
•⁠  ⁠Interpretation der resultierenden Segmente im Business-Kontext

## Zentrale Erkenntnisse

Die Analyse hat gezeigt, dass sich deutliche Unterschiede im Nutzerverhalten erkennen lassen:

•⁠  ⁠High-Value-Kunden buchen überwiegend kombinierte Leistungen (Flug und Hotel) und weisen die höchste Conversion auf
•⁠  ⁠Hohe Rabatte stehen in einem negativen Zusammenhang mit der Profitabilität
•⁠  ⁠Low-Value-Nutzer zeigen geringes Engagement und niedrige Conversion Rates
•⁠  ⁠Ein Teil der Nutzer weist erhöhte Stornierungsraten auf
•⁠  ⁠Medium-Value-Kunden stellen ein wichtiges Wachstumspotenzial dar

## Business-Empfehlungen

Auf Basis dieser Erkenntnisse lassen sich folgende Maßnahmen ableiten:

•⁠  ⁠Ausbau von Cross-Selling-Angeboten für High-Value-Kunden
•⁠  ⁠Optimierung der Rabattstrategie durch gezielte und moderate Preisnachlässe
•⁠  ⁠Weiterentwicklung von Medium-Value-Kunden durch personalisierte Angebote
•⁠  ⁠Aktivierung von Low-Value-Nutzern durch gezielte Maßnahmen im Funnel
•⁠  ⁠Reduktion von Stornierungen durch Optimierung des Buchungsprozesses

## Business Impact

Die Ergebnisse ermöglichen es, Kundenverhalten nicht nur zu beschreiben, sondern gezielt für geschäftliche Entscheidungen zu nutzen.

Insbesondere ergeben sich Vorteile in den Bereichen:

•⁠  ⁠Kundensegmentierung
•⁠  ⁠personalisierte Ansprache
•⁠  ⁠effizientere Marketingstrategien
•⁠  ⁠Steigerung von Conversion und Umsatz
•⁠  ⁠nachhaltige Verbesserung der Kundenbindung

## Projektstruktur

Das Repository enthält:

•⁠  ⁠Python Notebook (EDA und Segmentierung)
•⁠  ⁠SQL-Logik zur Erstellung der Feature Table
•⁠  ⁠Datenbasis (User-Level Tabelle)
•⁠  ⁠Visualisierungen
•⁠  ⁠Präsentation und Summary

## Fazit

Das Projekt zeigt, wie durch strukturierte Datenanalyse und eine klare Interpretation im Business-Kontext konkrete Mehrwerte geschaffen werden können.

Die Kombination aus SQL, explorativer Analyse und Clustering bildet eine belastbare Grundlage für datengetriebene Entscheidungen im Bereich Kundenbindung und Personalisierung.

Vielen Dank für Ihr Interesse

Elen Mrgic
