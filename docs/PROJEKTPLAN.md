# Project Sentinel – Smart Arbetsmiljösensor för Riskfyllda Yrken

## 1. Introduktion och Bakgrund
### Syfte och mål
Project Sentinel syftar till att skapa en intelligent och proaktiv säkerhetslösning för yrken med hög arbetsmiljörisk. Genom att använda avancerade IoT-sensorer och dataanalys ska systemet identifiera och varna för potentiella risker i realtid. Detta minskar antalet olyckor och skapar en tryggare arbetsmiljö.

### Problembeskrivning
Många yrkesgrupper utsätts dagligen för risker som farliga gaser, buller, temperaturväxlingar och fallolyckor. Nuvarande säkerhetsåtgärder är ofta reaktiva snarare än proaktiva. Project Sentinel adresserar detta genom att:
- Upptäcka arbetsmiljörisker i realtid.
- Automatiskt varna användare och arbetsledare vid potentiella hot.
- Analysera historiska data för att identifiera riskmönster och förebygga framtida olyckor.

### Målgrupp
- Bygg- och anläggningsbranschen
- Industri- och produktionssektorn
- Brandmän och räddningstjänst
- Sjukvårdspersonal och akutsjukvård
- Transport- och logistiksektorn

## 2. Val av Teknologi och Arkitektur

### Teknologier
**Frontend:** React Native för mobilapp (iOS & Android) 
**Backend:** Node.js med Express, PostgreSQL 
**IoT & Hårdvara:** Raspberry Pi/ESP32, LoRaWAN/LTE/WiFi

### Systemarkitektur
- **Frontend**: Mobilapplikation för realtidsdata, varningar och historisk analys.
- **Backend**: API för datainsamling och bearbetning.
- **IoT-enheter**: Sensorer för gas, temperatur, buller, fall och hjärtfrekvens.

### API och Databasstruktur
- **API-endpoints**: Autentisering, datainsamling, varningar, statistik.
- **Databas**: PostgreSQL med tabeller för användare, sensordata, incidenter.

## 3. Teamstruktur och Ansvarsområden

| Roll | Teammedlemmar | Ansvarsområden |
|------|--------------|----------------|
| **Frontend** | Hannele, Rebecka | UI/UX, mobilapp, API-integration |
| **Fullstack** | Simon, Chie, Elin, Milton | Backend, databas, API, autentisering |
| **Systemutveckling (IoT)** | Eric, Fredrik, Filip, Chengjun | Sensorer, datahantering, kommunikation |

### Samarbete
- Gemensam projektplan och dagliga standups.
- Sprintbaserad utveckling med 2-veckors iterationer.
- Veckovisa retrospektiv och sprintavslut.

## 4. Arbetsmetodik och Verktyg
- **Agil metodik:** Scrum med sprintplanering, standups, retrospektiv.
- **Kodhantering:** GitHub (pull requests, code reviews, branches).
- **Kommunikation:** Slack & Teams.
- **Sprintplanering:** Jira/Trello.

## 5. Tidsplan och Milstolpar

| Vecka | Aktivitet | Teamuppgifter |
|-------|----------|--------------|
| 10 | Kickoff, brainstorming, teamindelning | Alla team deltar i projektplanering och val av teknologier |
| 11-12 | Research, val av hårdvara, arkitekturplanering | Frontend: Skapa wireframes och UI-design; Backend: Definiera API-struktur; IoT: Testa och välja sensorer |
| 12 | Projektplan färdig & godkänd | Alla team slutför projektplan och presenterar för godkännande |
| 13-16 | Utveckling av frontend, backend och IoT-komponenter | Frontend: Implementera grundläggande UI/UX; Backend: Skapa API och databaser; IoT: Programmering av sensorer och datainsamling |
| 17-19 | Integration och testning | Frontend & Backend: API-integration; IoT & Backend: Datakommunikation mellan sensor och moln |
| 20-21 | Optimering och slutförande | Alla team arbetar med prestandaförbättringar och buggrättningar |
| 22 | Testning och kvalitetssäkring | Testning av hela systemet med verkliga scenarion |
| 23 | Demo, utvärdering och retro | Presentation av projektet och retrospektiv |

## 6. Riskanalys och Problemhantering

| Risk | Åtgärd |
|------|---------|
| Kommunikationsbrister | Regelbundna standups och synk-möten |
| Teknisk komplexitet | Modulär utveckling och iterativ testning |
| Tidspress | Prioritering av MVP och iterativ leverans |

## 7. Leveranser och Dokumentation
- **Frontend:** Mobilapp med varningar och realtidsdata.
- **Backend:** API för datainsamling och analys.
- **IoT:** Sensornätverk med realtidsövervakning.
- **Dokumentation:** README.md, API-DOCUMENTATION.md, TESTING.md, ARCHITECTURE.md.

## 8. Sammanfattning
Project Sentinel skapar en tryggare arbetsmiljö genom realtidsövervakning av riskfyllda förhållanden. Genom smarta sensorer och avancerad dataanalys erbjuder systemet en proaktiv säkerhetslösning för högriskyrken. 

Vår ambition är att genomföra ett innovativt och affärsmässigt relevant projekt som gynnar såväl användare som arbetsgivare.

