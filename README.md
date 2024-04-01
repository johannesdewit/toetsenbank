# README

Een vergaarplaats \[*repository*\] waarmee een toetsenbank opgezet kan worden als een [Obsidian](https://obsidian.md)-kluis. Op dit moment is dit een *template repository* waarmee men zelf een toetsenbank voor een schoolvak op kan zetten.
## Een toetsenbank opzetten
1. Gebruik de template-functie van GitHub of download de bestanden om de inhoud van deze vergaarplaats in een map op je computer te krijgen.
2. Open de kluis in Obsidian.
3. Pas de README aan zodat het bij jouw specifieke toepassing past.
## Mapopbouw
### toetsenbank
In de toetsenbank kunnen we twee soorten gegevens opslaan: vragen en toetsen. Vragen zijn de individuele toetsvragen en toetsen zijn hele toetsen. Toetsvragen slaan we op zodat we deze kunnen gebruiken om nieuwe toetsen te maken.

In principe zijn alle unieke bestandsnamen toegestaan omdat `tags` gebruikt worden om de toetsvragen te ordenen. Een unieke *unix-timestamp* wordt als alias toegevoegd als unieke ID.
### sjablonen
In de map `/sjablonen` vindt je de sjablonen waarmee een vraag of toets toegevoegd kan worden aan de toetsenbank. Gebruik deze sjablonen zodat we de gegeven consistent op kunnen slaan.

In Obsidian kun je een sjabloon invoegen wanneer je een nieuw bestand hebt aangemaakt via het opdrachtenpaneel. Kijk voor de sneltoetsen in de instellingen van Obsidian.
### postvak
Het postvak wordt gebruikt om nog niet verwerkte toetsen e.d. op te slaan. Deze bestanden moeten bijvoorbeeld nog omgeschreven worden naar losse vragen.
## Vooruitblik
Graag zou ik de volgende functionaliteit nog toe willen voegen:
- Samenstellen en exporteren van toetsen vanuit de toetsenbank.
- Bijhouden toetsafname.
- Validatie van de gegevens.
## Verdere uitleg
### Obsidian?
[Obsidian](https://obsidian.md) is een gratis programma waarin [markdown](https://www.markdownguide.org/)bestanden kunnen worden bewerkt. Het is lichtgewicht en beschikbaar op alle platforms. Daarnaast hou je zelf altijd toegang tot de onderliggende bestanden waardoor je altijd toegang houdt tot je gegevens, ook als je niet langer Obsidian wenst te gebruiken. Daarnaast is de functionaliteit van het programma gemakkelijk uit te breiden met plug-ins.