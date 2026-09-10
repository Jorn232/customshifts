# CustomShifts dashboard

Openbare codeversie van het CustomShifts Work-dashboard. De interface groepeert gesprekken per werkgebied en biedt zoeken en doorklikken.

## Bestanden

- `index.html`: zelfstandige Nederlandstalige dashboardinterface, zonder installatie of buildstap.
- `AGENTS.md`: korte context en afspraken voor gerichte wijzigingen.

Open `index.html` in een browser om de interface te bekijken. De openbare versie bevat bewust een lege lijst `chats`. Privégesprekstitels, links, samenvattingen, geheugenbestanden en Sites-configuratie worden niet in deze repository opgeslagen.

## Relatie met het live dashboard

Het bestaande privé-dashboard wordt gehost via Sites en bevat de echte gesprekken. Deze repository bevat alleen een opgeschoonde codekopie. Een commit hier publiceert niet automatisch naar Sites. Wijzigingen moeten gecontroleerd worden overgenomen in de privéversie, waarbij de bestaande chatgegevens behouden blijven.

## Efficiënt onderhouden

Lees eerst dit overzicht en alleen de relevante gewijzigde regels. Gebruik Git-diffs om ongewijzigde code niet steeds opnieuw te analyseren. GitHub-opslag zelf verlaagt het tokengebruik niet en voert geen ChatGPT-geheugensynchronisatie uit. De bestaande geplande taak voor het privé-dashboard staat los van deze repository.
