# Soldaten-Kalkulation

Dieser Artikel befasst sich mit den genauen offensiven und defensiven Daten aller Einheiten in Siedler 3, abhängig von ihrer Kampfkraft.

Das sind die grundlegenden Werte mit 100% Kampfkraft (kk). (Die Tabelle berücksichtigt nicht den Rüstungbonus der Speere. Ich erkläre dies nach der Tabelle)

| Einheit                   | Lebenspunkte | Schaden pro Schlag mit 100% kk. | Angriffe pro Sekunde | Schaden pro Sekunde | Reichweite | Geschwindigkeit |
| ------------------------- | ------------ | ------------------------------- | -------------------- | ------------------- | ---------- | --------------- |
| Lv.1 Schwert              | 101          | 10 (1 pro 10% kk)               | 1.3                  | 13.3                | 1          | 1               |
| Lv.1 Speer                | 101          | 4 (1 pro 25% kk)                | 1.3                  | 5.3                 | 2          | 0,9             |
| Lv.1 Bogen                | 101          | 5 (1 pro 20% kk)                | 0.6                  | 3.3                 | 15         | 0,8             |
| Lv.2 Schwer               | 121          | 14 (1 pro \~7.14% kk)           | 1.3                  | 18.6                | 1          | 1               |
| Lv.2 Speer                | 121          | 5 (1 pro 20% kk)                | 1.3                  | 6.6                 | 2          | 0.9             |
| Lv.2 Bogen                | 121          | 6 (1 pro 16.6% kk)              | 0.6                  | 4                   | 15         | 0.8             |
| Lv.3 Schwert              | 151          | 20 (1 pro 5% kk)                | 1.3                  | 26.6                | 1          | 1               |
| Lv.3 Speer                | 151          | 6 (1 pro 16.6% kk)              | 1.3                  | 8                   | 2          | 0.9             |
| Lv.3 Bögen                | 151          | 7 (1 pro \~14.29% kk)           | 0.6                  | 4.6                 | 15         | 0.8             |
| Priester                  | 81           |                                 |                      |                     |            | 0.6             |
| Pioniere, Geologen, Diebe | 21           |                                 |                      |                     |            | 0.8             |
| Kriegsmaschinen           | 501          |                                 |                      |                     |            | 0.6             |
| Esel                      |              |                                 |                      |                     |            | 0.8             |

Die aktuellen Lebenspunkte aller Einheiten kann nur eine natürliche Zahl sein.

Als erstes berechnet Siedler 3 den Schaden abhängig von der Kampfkraft. Falls die angegriffene Einheit ein Speerkämpfer ist, wird der Schaden halbiert und abgerundet. Beispiel: Ein Speerkämpfer bekommt 9 Schaden. Er erhält allerdings nur 4 Schaden anstatt 9 bzw. 4.5 Schaden. Als letztes werden Wunder von Priestern mit einberechnet und nochmal abgerundet. (mehr zu Wundern später)

Amazonen haben dieselben Werte, außer ihre Soldaten: Sie haben 20 Lebenspunkte weniger auf allen Leveln. (lv.1: 81/lv.2: 101/lv.3: 131)

### Schaden und Kampfkraft

Die folgende Tabelle repräsentiert die Kampfkraft und die Anzahl der „gedachten Goldbarren“ die man am Start bekommt, abhängig von der Anzahl der teilnehmenden Spieler.

| Anzahl der Spieler | Start kk. | Start Goldbarren |
| ------------------ | --------- | ---------------- |
| 1                  | 54%       | 60               |
| 2                  | 50%       | 48               |
| 3                  | 42%       | 38               |
| 4                  | 37%       | 32               |
| 5                  | 33%       | 26               |
| 6                  | 29%       | 22               |
| 7                  | 26%       | 18               |
| 8                  | 25%       | 16               |
| 9                  | 23%       | 13               |
| 10                 | 21%       | 11               |
| 11                 | 19%       | 9                |
| 12                 | 18%       | 8                |
| 13                 | 17%       | 6                |
| 14                 | 16%       | 5                |
| 15                 | 15%       | 4                |
| 16                 | 14%       | 3                |
| 17                 | 14%       | 2                |
| 18                 | 13%       | 1                |
| 19                 | 12%       | 0                |
| 20                 | 12%       | 0                |

Diese Tabelle beschreibt, wie viel/viele Kampfkraft/Goldbarren man braucht, um einen bestimmten Schadenswert zu erreichen. (_Beispiel: Ein **Lv. 1 Schwertkämpfer** mit **35%** Kampfkraft bzw. **29 Goldbarren** richtet 4 Schaden pro Schlag an. Auf einer 4 gegen 4 Karte werden 29-16, also **13** Goldbarren benötigt_)

| Schaden | Lv. 1 Schwert | Lv. 1 Speer   | Lv. 1 Bogen |
| ------- | ------------- | ------------- | ----------- |
| 1       | 12% / 0       | 12% / 0       | 12% / 0     |
| 2       | 15% / 4       | 37,5% / 32    | 30% / 23    |
| 3       | 25% / 16      | 62,5% / 80    | 50% / 48    |
| 4       | 35% / 29      | 87,5% / 272   | 70% / 120   |
| 5       | 45% / 42      | 112,5% / 784  | 90% / 328   |
| 6       | 55% / 61      | 137,5% / 1296 | 110% / 736  |
| 7       | 65% / 94      | 130% / 1144   |             |
| 8       | 75% / 144     |               |             |
| 9       | 85% / 248     |               |             |
| 10      | 95% / 432     |               |             |
| 11      | 105% / 632    |               |             |
| 12      | 115% / 840    |               |             |

| Schaden | Lv. 2 Schwert | Lv. 2 Speer   | Lv. 2 Bogen     |
| ------- | ------------- | ------------- | --------------- |
| 1       | -             | 12% / 0       | 12% / 0         |
| 2       | 12% / 0       | 30% / 23      | 25% / 16        |
| 3       | 17,9% / 7     | 50% / 48      | 41.6% / 38      |
| 4       | 25% / 16      | 70% / 120     | 58.3% / 70      |
| 5       | 32,1% / 21    | **90%** / 328 | 75% / 144       |
| 6       | 39,3% / 35    | 110% / 736    | **91.6%** / 360 |
| 7       | 46,4% / 44    | 130% / 1144   | 108.3% / 704    |
| 8       | 53,6% / 58    |               | 125% / 1040     |
| 9       | 60,7% / 76    |               |                 |
| 10      | 67,9% / 108   |               |                 |
| 11      | 75% / 144     |               |                 |
| 12      | 82,1% / 220   |               |                 |
| 13      | 89,3% / 312   |               |                 |
| 14      | 96,4% / 456   |               |                 |
| 15      | 103,6% / 608  |               |                 |
| 16      | 117,9% / 896  |               |                 |
| 17      | 125% / 1040   |               |                 |

| Schaden | Lv. 3 Schwert | Lv. 3 Speer  | Lv. 3 Bogen   |
| ------- | ------------- | ------------ | ------------- |
| 1       | -             | 12% / 0      | 12% / 0       |
| 2       | 12% / 0       | 25% / 16     | 21.4% / 12    |
| 3       | 12.5% / 1     | 41.6% / 38   | 35.7% / 30    |
| 4       | 17.5% / 7     | 58.3% / 70   | 50% / 48      |
| 5       | 22.5% / 14    | 75% / 144    | 64.3% / 90    |
| 6       | 27.5% / 20    | 91.6% / 360  | 78.6% / 184   |
| 7       | 32.5% / 26    | 108.3% / 704 | 92.9% / 384   |
| 8       | 37.5% / 33    | 125% / 1040  | 107.1% / 680  |
| 9       | 42.5% / 39    |              | 121.4% / 968  |
| 10      | 47.5% / 46    |              | 135.7% / 1264 |
| 11      | 52.5% / 55    |              |               |
| 12      | 57.5% / 67    |              |               |
| 13      | 62.5% / 80    |              |               |
| 14      | 67.5% / 106   |              |               |
| 15      | 72.5% / 132   |              |               |
| 16      | 77.5% / 172   |              |               |
| 17      | 82.5% / 220   |              |               |
| 18      | 87.5% / 372   |              |               |
| 19      | 92.5% /376    |              |               |
| 20      | 97.5% / 480   |              |               |

_Generell gilt: Mit 12% kk bekommt man durchschnittlich 0.8% pro Goldbarren. Mit 51% kk bekommt man durchschnittlich 0.4% pro Goldbarren. Mit 63% kk bekommt man durchschnittlich 0.2% pro Goldbarren. Mit 76% kk bekommt man durchschnittlich 0.1% pro Goldbarren. Mit 88% kk bekommt man durchschnittlich 0.05% pro Goldbarren. Ab jetzt bleibt es bei 0.05% bis ins Unendliche. Ägypter bekommen halb so viel kk pro Goldbarren aber doppelt so viel für Edelsteine_

Da die Schadenswerte relativ niedrig sind und nicht mit ungeraden Zahlen gerechnet wird, sind ein paar recht unerwartete Ergebnisse hervorgekommen. Hier sind ein paar Beispiele:

\* Ein lv. 1 Speer mit 12% Kampfkraft richtet denselben Schaden gegen andere Speerkämpfer wie ein lv. 1 Speer mit bis zu 87,4% an. Ab 85,5% richtet der lv. 1 Speer doppelt Schaden an. \* Wenn 70% überschritten werden, sind die lv. 2 Speere genau so stark wie gegnerische lv. 2 Speere mit 100%. (Solange Speer gegen Speer gekämpft wird) \* Wenn 92,9% überschritten werden, sind die lv. 3 Bögen und Speere genauso stark wie mit 100%. \* Wenn 108,3% überschritten werden, haben die lv. 3 Bögen und Speere einen erheblichen Vorteil gegenüber den heimischen Einheiten. \* Auf einer 1 gegen 1 Karte mit 50% Kampfkraft, sind anfangs lv. 2 Speere stärker als Schwerter. \* Lv. 2 Bögen haben den gleichen Schaden wie lv. 3 Bögen gegen Speere im eigenen Land.

### Soldaten und Wunder

Schadensveränderungen durch Wunder werden nach der Kampfkraft und Rüstungsberechnung berechnet. Ungerade zahlen werden wieder abgerundet. _(Beispiel: Ein lv. 1 Schwertkämpfer mit 65% Kampfkraft bzw. 7 Schaden wird mit dem Wunder Angreifer ängstigen verzaubert. Jetzt richtet er nur noch 1 Schaden gegen Speerkämpfer an. Die 7 Schaden werden zuerst durch den Rüstungsbonus auf 3 verringert. Danach wird durch das Wunder der Angriff nochmals halbiert und auf 1 abgerundet.)_

#### Römer

Angreifer ängstigen: Halbiert den Schaden gegnerischer Soldaten die im eigenen oder verbündeten Land kämpfen.

#### Ägypter

Soldaten stärken: Verdoppelt den Schaden von eigenen oder verbündeten Soldaten im neutralen oder gegnerischen Land.

#### Asiaten

Samuraischwert: Verdoppelt die Angriffsgeschwindigkeit und erhöht den Schaden pro Schlag um 33%.

Göttlicher Schuild: Verringert den erhaltenen Schaden von eigenen oder verbündeten Einheiten um 33%.

#### Amazonen

Pfeile verfluchen: Macht eigene oder verbündete Einheiten immun gegen Pfeile.
