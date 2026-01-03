# De AI-Fluisteraar: Prompt Bibliotheek 🧠✨

Welkom bij de officiële repository behorend bij het boek **"De AI-Fluisteraar"**.

In deze repository vind je de **7 Meester-templates** en **[de Golden-prompts]([url](https://github.com/genevangampelaere/ai-fluisteraar/blob/main/GoldenPrompts.md))** die in het boek worden besproken. Dit zijn geen simpele chat-vragen, maar geavanceerde prompt-engineering frameworks die zijn ontworpen om Large Language Models (zoals GPT-4, Claude 3.5 en Gemini) aan te sturen met maximale precisie.

> **Motto:** *"Stop met chatten. Begin met engineeren."*

---

## 📚 Over deze Bibliotheek

Deze prompts zijn ontworpen om de veelvoorkomende beperkingen van AI (hallucinaties, luiheid, gebrek aan nuance) te omzeilen. Ze maken gebruik van technieken zoals:

* **Role-Based Constraints** (Beperkingen opleggen)
* **Chain-of-Verification** (Feiten checken)
* **Structured Thinking** (Redeneren in stappen)
* **Meta-Prompting** (AI de AI laten aansturen)

---

## 🚀 Hoe gebruik je deze prompts?

1. Kies het template hieronder dat past bij je doel.
2. Kopieer de tekst in het codeblok.
3. Vervang alles wat tussen **`[vierkante haken]`** staat door jouw specifieke context.
4. Plak het in je favoriete AI-tool en druk op Enter.

---

## 📂 De Templates

### 1. De Expert-Constraint Formule 👷‍♂️

*Gebruik dit voor specifieke taken waar je de kwaliteit van een senior professional verwacht en clichés wilt vermijden.*

```text
Rol: Je bent een [Specifieke Rol, bijv. Senior Tech Recruiter] met [Aantal] jaar ervaring in [Vakgebied].
Taak: [Beschrijf hier de taak, bijv. Schrijf een vacaturetekst].

HARDE CONSTRAINTS (Niet negeren):
* [Beperking 1: bijv. Maximaal 300 woorden]
* [Beperking 2: bijv. Gebruik GEEN clichés zoals 'duizendpoot']
* [Beperking 3: bijv. Focus op feiten, niet op emotie]

Zachte Voorkeuren:
* [Voorkeur 1: bijv. Gebruik een directe, actieve schrijfstijl]
* [Voorkeur 2: bijv. Spreek de lezer aan met 'je']

Output Format:
* [Bijv. Een Markdown tabel / Een bullet-point lijst / Een JSON-bestand]

```

### 2. De 'Truth-Serum' Prompt (Anti-Hallucinatie) 🕵️‍♀️

*Gebruik dit om vragen te laten beantwoorden op basis van je eigen documenten/data, zonder dat de AI dingen verzint.*

```text
[CONTEXT]
[Plak hier je tekst, beleidsdocument, rapport of data]

[FOCUS]
Beantwoord de vraag UITSLUITEND op basis van de tekst onder [CONTEXT].
* Als het antwoord niet in de tekst staat, antwoord je letterlijk met: "Deze informatie staat niet in de verstrekte context."
* Gebruik geen algemene kennis of aannames.

[VOORBEELDEN]
*Vraag:* [Voorbeeldvraag die niet in tekst staat]
*Fout antwoord:* [Een gok]
*Goed antwoord:* "Deze informatie staat niet in de verstrekte context."

[TAAK]
[Stel hier je vraag over de tekst]

```

### 3. Het Structured Thinking Protocol (STP) 🧠

*Gebruik dit voor complexe redeneervragen, strategisch advies en het vermijden van 'Systeem 1' (impulsieve) antwoorden.*

```text
Voordat je mijn vraag beantwoordt, doorloop je verplicht de volgende stappen. Schrijf de output van elke stap uit.

[FASE 1: UNDERSTAND]
* Herformuleer mijn probleem in je eigen woorden.
* Identificeer de grootste risico's of valkuilen in deze vraag.
* Wat is het *echte* doel achter mijn vraag?

[FASE 2: ANALYZE]
* Breek het probleem op in sub-componenten.
* Noteer kritieke aannames die we maken.
* Zoek naar tegenstrijdigheden in de informatie.

[FASE 3: STRATEGIZE]
* Schets 3 radicaal verschillende oplossingsrichtingen.
* Evalueer de trade-offs (voor- en nadelen) van elke richting.

[FASE 4: EXECUTE]
* Kies de beste strategie uit Fase 3.
* Geef nu pas het definitieve antwoord, onderbouwd door de analyse.

Mijn Vraag: [Jouw complexe vraag]

```

### 4. De Strategische Raad van Bestuur (+ Zekerheidscheck) 👔

*Gebruik dit om tunnelvisie te voorkomen bij besluitvorming door meerdere perspectieven te dwingen.*

```text
Taak: Analyseer [Jouw Idee/Beslissing] vanuit de volgende perspectieven.

[PERSPECTIEF 1: De Pessimistische CFO]
* Focus puur op kosten, financiële risico's en ROI op korte termijn. Wees kritisch.

[PERSPECTIEF 2: De Visionaire Product Manager]
* Focus op gebruikerservaring, innovatie en kansen op lange termijn.

[PERSPECTIEF 3: De Ethische Advocaat]
* Focus op privacy, compliance, reputatie en duurzaamheid.

[SYNTHESE & ZEKERHEID]
Breng de perspectieven samen in een eindadvies en gebruik dit format:
1. Het Advies: [Je conclusie]
2. Confidence Score (0-100%): Hoe zeker ben je van dit advies?
3. Cruciale Aannames: Welke informatie mis je die de score zou verhogen?

```

### 5. De Chain-of-Verification (CoVe) 🔎

*Gebruik dit voor feiten-checks en technische analyses om de nauwkeurigheid te verhogen.*

```text
Taak: [Jouw vraag of onderwerp]

Stap 1: Eerste Concept
Schrijf je eerste antwoord op de vraag.

Stap 2: Fact-Check Vragen
Genereer 5 verificatievragen die bedoeld zijn om fouten of hallucinaties in je antwoord uit Stap 1 bloot te leggen.

Stap 3: Verificatie
Beantwoord elke vraag uit Stap 2 onafhankelijk en feitelijk.

Stap 4: Definitieve Versie
Herschrijf je antwoord uit Stap 1 op basis van de inzichten uit Stap 3. Dit is je eindproduct.

```

### 6. De Refinement Loop (Kwaliteits-Boost) 💎

*Gebruik dit voor het verbeteren van teksten zoals e-mails, blogs of rapporten (van 'zilver' naar 'goud').*

```text
[RONDE 1: DRAFT]
Schrijf een eerste versie van [Het type tekst, bijv. een sales e-mail].

[RONDE 2: CRITIQUE]
Review de tekst uit Ronde 1. Identificeer 3 specifieke zwakke punten.
*Let op: wees hard. Zoek naar clichés, passief taalgebruik of vage argumenten.*

[RONDE 3: POLISH]
Herschrijf de tekst en los de 3 punten uit Ronde 2 op. Maak de tekst scherper, directer en overtuigender.

```

### 7. De Meta-Prompt (God-Mode) 🤯

*Gebruik dit als je een doel hebt, maar zelf niet weet hoe je de perfecte prompt moet schrijven.*

```text
Instructie:
Ik wil het volgende doel bereiken: [JOUW DOEL]

Jouw taak is om de PERFECTE PROMPT te schrijven die ik aan jou kan geven om dit doel te bereiken.

Stap 1: Analyse
* Analyseer wat de cruciale elementen zijn (context, constraints, format, tone of voice).
* Identificeer waar standaard prompts vaak falen.

Stap 2: Constructie
* Schrijf de optimale prompt voor mij. Gebruik technieken zoals 'Role-Prompting' en 'Chain-of-Thought'.
* Zorg voor placeholders [zoals deze] waar ik specifieke info moet invullen.

Stap 3: Uitvoering
* Vraag mij om de ontbrekende informatie (de placeholders).
* Zodra ik antwoord, voer je die perfecte prompt uit.

```

---

## 📖 Over de Auteur

**Gene Vangampelaere** is Microsoft 365 Solution Architect, docent aan Howest en Microsoft MVP. Hij is de auteur van de bestseller *Slimmer met AI* en het vervolg *De AI-Fluisteraar*. Zijn missie is om complexe technologie toegankelijk en direct toepasbaar te maken.

🔗 [Website](https://www.vangampelaere.be/slimmermetai) | [LinkedIn](https://www.linkedin.com/in/genevangampelaere)

---

*Disclaimer: Deze prompts zijn 'open source'. Voel je vrij om ze te gebruiken, aan te passen en te delen. Een verwijzing naar het boek wordt gewaardeerd!*
