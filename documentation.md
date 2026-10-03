
# Git Lab Projekt
## Besikrivning av projekten
Projekten syftar tillämpa grunderna i att använda Git
## Projekts mål
-skapa ett lokalt Git-arkiv
-spåra ändringar
-skapa organiserad commits
## Verktyg som används
-Git
-Visual Studio Code
-Markdown
## Projekt Status 
Projekt befinner sig för närvarande i det inledande utvecklingsskedet
## Git Arbetsflöde
-skapa filer och gör ändringar.
-förbered ändringarna med Git.
-skapa en commit med ett tydligt meddelande.
granska projekthistoriken.
## Git Commands
-git init
-git add
-git commit
-git log
# Projektdokumentation 
## Projektbeskrivning
Detta projekt skapades och utvecklades med hjälp av Git för att hantera och spåra ändringar
## Projektmål
- Lär dig grunderna i Git
- Att etablera ett lokalt lager
- Spåra ändringar med hjälp av Commit
- organisering av projektets utvecklingsfaser
## Verktyg som används
- Git
- Visual Studio Code
- Markdown
## Arbetsfaser
### Första etappen
- Skapa ett lokalt Git-arkiv
### Fas två
- Organisera projektmål och använda verktyg
### Fas tre
- Updatera dokumentation och spåra ändringar med hjälp av Git
## Bilder 
![Screenshot 1](pic/Skärmbild%202026-09-24%20220903.png)
![Screenshot 2](pic/Skärmbild%202026-09-24%20223206.png)
## Labbmiljö & Nätverk

Labben genomfördes med en Linux-VM och en Windows-VM.
Nätverksanslutningen mellan virtuella maskiner verifierades med
ping och nätverksinställningarna kontrollerades via kommandoraden.

### Nätverk

| System | Operativsystem | Nätverkskontroll |
|---|---|---|
| Linux-VM | Linux/Ubuntu | ping och ip addr show |
| Windows-VM | Windows | ping och ipconfig /all |

## Kommandoradsgenomförande

### Linux (Bash)

Följande moment genomfördes i Linux:

- Skapa mappen `/var/systementor/konsultdata`.
- Skapa filen `anteckningar.txt`.
- Skapa användargruppen `konsulter`.
- Tilldela gruppen `konsulter` till mappen och filen.
- Kontrollera behörigheterna med `ls -la`.
- Kontrollera nätverksanslutningen med `ping`.
- Kontrollera nätverkskortets information med `ip addr show`.

### Windows (PowerShell)

Följande moment genomfördes i Windows:

- Skapa mappen `C:\Systementor\KonsultData`.
- Kontrollera behörigheter och ACL med `Get-Acl`.
- Kontrollera nätverksanslutningen med `Test-Connection` eller `ping`.
- Kontrollera nätverksinställningarna med `ipconfig /all`.

## Git & Versionshantering

Projektet versionshanteras med Git och lagras i ett GitHub-repository.

Arbetsflödet består av att skapa och ändra filer, kontrollera ändringar,
skapa commits och kontrollera projektets historik med `git log --oneline`.

Exempel på Git-kommandon:

```bash
git status
git add .
git commit -m "Beskrivning av ändringen"
git log --oneline
## AI-logg och Utvärdering

AI användes som stöd under arbetet med dokumentationen och Git.

### Prompt

Jag använde AI för att få hjälp med att strukturera dokumentationen,
förklara Git-kommandon och kontrollera att dokumentationen innehöll
de delar som krävdes i uppgiften.

### AI-utdata

AI gav förslag på struktur, formuleringar och förklaringar av olika
Git- och kommandoradsrelaterade moment.

### Kritisk granskning

AI:s förslag kontrollerades mot instruktionerna för uppgiften och mot
de egna genomförda momenten. Jag använde inte automatiskt alla förslag,
utan kontrollerade informationen innan den lades in i dokumentationen.