# Python Pandas experimentation on r/place history data 2022

## Introduction
This is my experimintation on using pandas to analyse large amount of data, 160,353,104 rows by 4 column to be exact. 

Expect long run times

## Python and requirements
This project requires Python 3.10.4, and the additional libraries will be in 'requirements.txt'. The project is made in Jupyter notebook. 

You will need to run the command 'pip -r requirements.txt' to install all additional libraries into your enviroment

You will also need to download the main dataset used from here: https://placedata.reddit.com/data/canvas-history/2022_place_canvas_history.csv.gzip 
This must be placed in the root folder

## Project structure

**Results** The results will be printed to csv files in './results'. 

**Chunks** The chunks will be printed to csv files in './tmp/'. 



## Git tutorial (in Norwegian)

**Git clone:** Bruk ‘git clone %repo%’ for å klone et git-prosjekt til din lokale datamaskin. Erstatt %repo% med en link til GitHub eller GitLab-mappen. 


**Git checkout:** For å opprette en ny branch; skriv kommandoen ‘git checkout -b "my-branch", der "my-branch" er navnet på den nye branchen.

Dersom en ønsker å bytte branch, kan dette gjøres ved å kjøre kommandoen ‘git checkout "my-branch", der "my-branch" er navnet på den branchen du ønsker å bytte til.

Merk at en bør være i riktig branch før en begynner å gjøre endringer. Dette er ikke et absolutt krav, men gjør prosessen mye enklere. 


**Sende endringer til GitHub/GitLab:** Når du er i ønsket branch og er ferdig med å gjøre endringer, kan du sende dette til GitLab eller GitHub. Følgende kommandoer bør kjøres i riktig rekkefølge, og en bør ikke foreta noen endringer i løpet av denne prosessen:


'git pull' oppdaterer den branchen man er i 


'git add .' legger alle filene med endringer i en pakke som skal sendes til Git 


'git stage .' fryser filene som er lagt i pakken


'git commit -m "my-message"' ferdigstiller pakken. Bytt ut "my-message" med en beskrivende kommentar som forklarer hva som er gjort av endringer


'git push' sender den ferdigstilte pakken til GitHub eller GitLab-serveren


Dersom du ønsker å sende opp en ny branch som enda ikke eksisterer i GitHub eller GitLab-repository, er det nødvendig å kjøre kommandoen 'git push -u origin "my-branch", der "my-branch" er navnet på den branchen du nettopp laget.
