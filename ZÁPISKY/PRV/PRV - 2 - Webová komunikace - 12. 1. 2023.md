---
parent: ProgramoveVybaveni
nav_order: 2
---
# PRV - 2 - Webová komunikace - 12. 1. 2023
- Celosvětový systém propojených počítačových sítí
- Počítače komunikují pomocí rodiny protokolů TCP/IP
- Základní služby internetu:
	- HTTP/HTTPS - webové stránky
	- SMTP, POP3, IMAP - email
	- FTP - přenos souborů
	- Telnet - vzdálený přístup
	- DNS - překlad doménových jmen

## World Wide Web
 - Označení pro aplikace internetového protokolu HTTP
 - Propojená soustava hypertextových dokumentů
 - Dokument jsou adresovány pomicí URL
 - Webové standardy vyvíjí World Wide Web Consolium (W3C)

## Hypertext
- Nelineární text - opak klasické knihy
- Hypertext je systém provázány hyperlinky - z různých míst je možné se odkazovat na další místa hypertextu
- Klasický ve službe WWW
- Může obsahovat text, obrázky, audio, skripty...

## URL
- Uniform recourse locator
- Slouží ke specifikaci zdrojů informací
	- http://www.vosvdf.cz:80/cmsb/index.php?p=81
		- služba: http
		- server: www.vosvdf.cz
		- port: 80
		- dokument: /cmsb/.index.php
		- parametry: p=81

## Protokol HTTP(S)
- Hypertext transfer protocol
- Používá se pro výměnu dat mezi klientem a webowým serverem
	- klient - webový prohlížeč
	- webový server - program, který odpovídá klientovy(apache, iis...)4
- HTTPS = zabespečená varianta protokolu HTTP
- Funguje  způsobem dotaz-odpověd

## HTML
- Hypertext markup language
- značkovací jazyk pro tvorbu webových stránek
- Interpretováno prohlížečem
- Často doplňován jazyky CSS, JavaScript - spolu tvoří webový front-end

## Statická webové stránka
- Tvořena statickým obsahem
- Doručena uživateli presně tak, jak je uležena
- NA stránce se obsah nemění pokud ho manuálně nezmění správce
- Většinou sestavený pouze z HTML, CSS a JS

## Dynamcká webová stránka
- Tvořena dynamicky při každém dotazu
- Umožňují nám např. vytvářet účty, komentovat, nakupovat
- označovány jako webové aplikace
- Většinou sestaveny pomocí: HTML, CSS, JS, MySQL, PHP, Apache