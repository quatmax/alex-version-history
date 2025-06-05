---
title: ALEX Release Notes
layout: home
nav_order: 0
---

Neue Alex-Versionen erscheinen im Monatszyklus. Folgendes gilt:

* Development-Version: Entwicklungsversion, wird am Monatserstem zu Stabilize 
* Stabilize-Version: nur Showstopper, wird am Monatsersten zu Release 
* Release-Version: nur mehr Hotfixes 

Das Schema der Versionsnummer ist wie folgt, wobei:
```
YYYY = Jahr vierstellig
M = Monatsnummer
N = fortlaufende Nummer
```
|**Version**| **Major** |**Minormajor**|**Minorminor**|**Bugfix**|
|:----------|:----------|:-------------|:-------------|:---------|
|development|`YYYY`     |`(M * 2) - 1` |`90`          |`N`       |
|stabilize  |`YYYY`     |`(M * 2) - 1` |`99`          |`N`       |
|master     |`YYYY`     |`(M * 2)`     |`0`           |`N`       |


|**Zeitpunkt**|**Jänner Version**|**Februar Version**|**März Version**|**April Version**|
|:------------|:-----------------|:------------------|:---------------|:----------------|
|im Januar    |`YYYY.02.00`      |`YYYY.03.99`       |`YYYY.05.90`    |                 |
|im Februar   |                  |`YYYY.04.00`       |`YYYY.05.99`    |`YYYY.07.90`     |
|im März      |                  |                   |`YYYY.06.00`    |`YYYY.07.99`     |
|im April     |                  |                   |                |`YYYY.08.00`     |

----