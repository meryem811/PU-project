@"
# PU-project

Projet du TP Processus unifié et approches agiles (INSAT).

## Conventions
- Branches : uc<N>-<nom-court>, une par UC, fusion dans main par Pull Request
- Commits : type: message (#numéro-ticket)
- Tags : v0.0-inception, v0.1-elaboration, v0.2-construction, v1.0-transition
- Milestones : Initialisation, Elaboration, Construction, Transition

## Lancer les tests
.\mvnw.cmd test
"@ | Set-Content README.md