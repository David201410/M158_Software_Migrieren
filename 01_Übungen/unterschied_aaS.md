# Iaas Paas Saas On-Site/On-Premises

## Aufgabenstellung
Unser Auftrag war es zwei verschiedene Diagramme zu vergleichen. Beide Diagramme stellen dar, wie die Verantwortung bei as a Service Modellen aufgeteilt ist. 

![bild-1](/images/iaas-paas-saas-diagram.png)


![bild-2](/images/shared-responsibility.svg)

**Fragestellung**
- Welche Gemeinsamkeiten und Unterschiede lassen sich erkennen?
- Welche unterschiedlichen Schwerpunkte setzen die Diagramme?
- Wie lassen sich die Inhalte beider Grafiken sinnvoll miteinander in Verbindung bringen?


## Unterschiede in der Darstellung
| Merkmal                       | Erste Grafik (PNG) – Verantwortungsebenen  | Zweite Grafik (SVG) – Shared Responsibility      |
| ----------------------------- | ------------------------------------------ | ------------------------------------------------ |
| **Darstellungsform**          | Matrixstruktur mit farblichem Vergleich    | Pyramiden-/Balken-Diagramm mit Layern            |
| **Fokus**                     | Klare Trennung: Wer verwaltet was          | Verantwortungsteilung mit Fokus auf Sicherheit   |
| **Detaillierungsgrad**        | Detailliert bis zur Netzwerk- und OS-Ebene | Fokus auf Sicherheit, Compliance, Konfiguration  |
| **Technische Ebene**          | Technische Komponenten                     | Operative und sicherheitsrelevante Verantwortung |
| **Visualisierung der Rollen** | Farbe zeigt Verantwortung (blau/rot)       | Layer-Ansicht mit erklärenden Texten             |

**Was mir sonst noch aufgefallen ist:**
- Bei jedem Modell, bis auf On-Prem, liegt die Verantwortung für die Infrastruktur (Hardware) beim Cloud Provider.
- Platform und Software as a Service kann man nicht immer eindeutig abtrennen. Was jedoch immer vom Manager (ich) aus kommen muss, sind die entsprechenden Accounts, Geräte und Daten.
