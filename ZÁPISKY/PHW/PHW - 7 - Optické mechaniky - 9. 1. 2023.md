---
parent: PocitacovyHardware
nav_order: 7
---
# PHW - 7 - Optické mechaniky - 9. 1. 2023
**CD:**
- Jedná se o optické úložné médium s kapacitou 650-700MB.
- Data se ukládají do stopy ve tvaru spirály, která se vine od středu disku.
- Ta je také rozdělena na sektory.
- Stoupání spirály je 1,6um, šířka 0,6um a nalezneme na ní tzv. pity (prohlubně) a landy (hladké plochy).
- Snímání dat je prováděno pomocí laseru a optických prvků v mechanice.
- Disk obsahuje reflexní vrstvu, na kterou když přes soustavu čoček laser dopadne, dojde k odrazu do příslušného čtecího zařízení (fotocitlivý prvek), který jej dále převádí naelektrický signál (0,1).
- To se stane ovšem v případě, pokud narazí na land.
- V opačném případě, tedy pokud dopadne na pit, dojde k jeho rozptýlení a čtecí zařízení nezachytí nic.
- CD mechaniky mohou být s rozhraním ATA nebo SATA, přístupová doba se pohybuje okolo 100ms.
- Přenosová rychlost se odvíjí od typu, např. 1x 150kB/s, 2x 300kB/s, 24x 3600kB/s.
- V mechanice jsou čtyři servomechanismy pro otáčení, zaostřování, vyhledávání stopy a sledování stopy.

**Příklad:**
*Výpočet kapacity hudebního CD:*
- 44 100 x 2 x 2 x 74 x 60 = 783 216 000 B
- 44 100 -počet vzorků za sekundu na jeden kanál
- 2 -rozlišení 16 bitů na vzorek, tj.2 bajty2 -2 kanály (stereo)
- 74 -max. 74 minut hudby
- 60 -převod minut na sekundy

![[36optical.gif]]

![[1200px-Disk-structure2.svg.png]]
![[se-2018-00340w_0002.webp]]


 - CD-ROM (Compact Disc -Read Only Memory)-Vyrábí se lisováním, je určeno pouze ke čtení.
 - CD-RW (Compact Disc –Rewritable)-Lze zapisovat data opakovaně (data se dají vymazat a nahrát nová). Spolehlivost a životnost je o něco nižší než u lisovaných CD-ROM.

**DVD:**
- Technologie je obdobná jako u CD.
- Rozdíl je v hustějším záznamu dat.
- Dalším rozdílem je možnost ukládat data na obou stranách disku, ale také ve dvou vrstvách.
- Čtení je pak prováděno přeostřením laseru na jednu nebo druhou vrstvu. Horní vrstva je polopropustná.
	- DVD-ROM
	- DVD-R
	- DVD-RW

![[Track-pitches-comparison-of-CD-R-Double-Density-CD-R-and-DVD-3.png]]

![[Comparison_CD_DVD_HDDVD_BD.svg.png]]

**Blu-Ray:**
- Jedná se o vysokokapacitní médium, určené především pro uložení videa ve vysokém rozlišení.
- Název je odvozený podle barvy laseru, který má vlnovou délku 405nm.
- Díky tomu je možné uložit na běžný disk o průměru 12 cm mnohem více dat oproti DVD.
- Tam se používá laser červený o vlnové délce 650nm.