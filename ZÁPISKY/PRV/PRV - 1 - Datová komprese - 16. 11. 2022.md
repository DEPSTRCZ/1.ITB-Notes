---
parent: ProgramoveVybaveni
nav_order: 1
---
# PRV - 1 - Datová komprese - 16. 11. 
- Způsob ukládání dat s cílem zmenšit velikost souborů
- Data se kůdují pomocí kompresního algorythmu
- Pro  kompresi slouží encoder a k dekompresi slouží decoder
- Kompresi dělíme na ztrátovou a bezztrátovou


**Ztrátová Komprese:**
- Některé informace jsou nenávratně ztraceny
- Používáme, když je možni tolerovat ztrátu dat
- Využíváme převším pro kompressi zvuku, obrazu a videa

![[Pasted image 20221116081721.png]]


**Bezztrátová komprese:**
- Není tak učinná, jako ztrátová komprese
- Dekompresí dochází k obnově dat do původní podoby
- Využíváme pro přenos programů, textů, databází

![[Pasted image 20221116082006.png]]

**Účinnost komprese:**
- Můžeme vyjádřit kompresním poměrem nebo procentuálně
- Ovlivněno volbou kompresního algorythmu a typem komprimovaných dat


**Archivace dat:**
- Kombinování několika souborů do jednoho archivního souboru
- Software pro archivaci dat se nažívá archivační program
- Archivní formáty: .zip .rar .tar .7zip
- Využíva bezztrátovou kompresi
- Proces vytvoření archinvího souboru se nazývá archivace
- Proces získání půvedních dat se nazývá extrakce

**Další příklady komprese:**
- Komprese může být součástí souborových systémů (u Windows NTFS) - možnost ušetřit místo na disku za ceenu zpomalení disku
- Bezztrátová komprese se uplatňuje i v instalačních souborech

**Kódování audiovizálních souborů:**
- Program se obecně nazívá codec
- Většinou ztrátová komprese
- Formáty videa -> MP4, AVI, WMV
- Formáty zvuku -> MP3, WMA