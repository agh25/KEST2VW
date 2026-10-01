# KEST2VW Lokaverkefni haust 2026 (20%)

Verkefnið er einstaklingsverkefni. Verkefnið skal halda utan um í lokaðri geymslu á [GitHub](https://github.com). Skilið hlekknum á geymsluna í skilahólfið á Innu. Sendið mér boð um að tengjast geymslunni.

Þið þurfið að halda dagbók á github um hvað þið gerið og hvenær (10%).

## Verkefnið
Þið eigið að setja upp eina tölvu sem frumgerð fyrir ungt hugbúnaðarfyrirtæki þar sem starfa 9 starfsmenn. 

### 1. Uppsetning á Windows og grunn stillingar (10%)
- Setjið upp nýja Windows 10 uppsetningu á tölvuna.
- Passið að velja **Setup for organization** og **Domain join instead** þegar það er í boði [sjá mynd](../Myndir/MicrosoftSignIn.png).
- Búið ykkur til sem notanda í uppsetningarferlinu.
- Breytið nafninu (e. computer name) á tölvunni í KEST2VW-[nöfnin ykkar] (án íslenskra stafa og bila (e. space)).
- Setjið upp Python3 (64 bita) og VS Code (með Python stuðningi).
- Setjið upp Git á tölvuna.
- Setjið upp annan hugbúnað eftir þörfum.

### 2. Notendur (20%)

Búið til notendahópana (e. user group) Innkaup, Sala, Yfirstjórn og Allir. Allir starfsmenn eiga að vera í einum deildarhóp og síðan í Allir hópnum.

Skrifið svo skriftu í PowerShell sem býr til notendurna í þessari [skrá](https://raw.githubusercontent.com/gestskoli/KEST2VW/master/Annad/notendur.csv). Skriftan á að búa til notendurna út frá þeim upplýsingum sem eru í skránni ásamt því að setja lykilorð á þá og setja þá í hópana sem þið gerðuð hér fyrir ofan. Athugið að líklega þarf líka að setja þá í aðra hópa, t.d. Allir hópinn.

Gott er að skoða [`Import-Csv`](https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.utility/import-csv?view=powershell-7) skipunina í PowerShell fyrir lausnina á þessum lið. Sjá dæmi um notkun [hér](https://github.com/gestskoli/KEST2VW/blob/master/PowerShell/UmPowerShell.md#lesa-úr-csv-skrá).

**Tryggið að allir notendurnir geti skráð sig inn.**

### 3. Skrár, möppur og réttindi (20%)
Hver hópur þarf að eiga sér sína eigin möppu sem eingöngu þeir sem eru í þeim hóp hafa aðgang að. Síðan þarf að vera til mappan Sameign sem allir notendurnir hafa aðgang að. Búðu til möppuna *Gögn* á rót C drifsins. Búið svo möppurnar fyrir hópana til í möppunni Gögn og stillið svo réttindin á möppunum. Búið til textaskrá í hverri möppu sem heitir eftir nafninu á möppunni.

### 4. Öryggismál (10%)
  - Breyttu lykilorðareglunni þannnig að:
    - Lágmarkslengd lykilorða verður 8 stafir.
    - Einföld lykilorð eru ekki heimil.
  - Eldveggur: 
    - Lokað fyrir alla innkomandi netumferð nema ping.

### 5. Netkerfi (30%)

Leysið [þetta](https://github.com/gestskoli/KEST2VW/raw/master/Annad/Lokaverkefni_V20.pka) PacketTracer verkefni. Áður en þið byrjið á því gæti verið gott að skoða [þetta](https://github.com/gestskoli/KEST2VW/raw/master/Annad/10.2.1.7%20Packet%20Tracer%20-%20Web%20and%20Email.pka) æfingaverkefni. 

## Skil á verkefninu

Liði 1 til og með 4 sýnið þið kennaranum ykkar.

Lið 5 á að skila á Innu.
