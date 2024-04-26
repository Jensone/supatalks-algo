# ALGO SUPATALKS

## Phase 1 : Analyse et compréhension du besoin

On prend connaissance de l'ensemble des information et autres données pertinentes pour avoir une meilleure compréhension du besoin. Cela passe par la relecture du notre de cadrage, des question aux personne concernées par exemple.

## Phase 2 : Recherche de solutions existantes

Avec des Recherche interne et sur internent, on part à la pêche aux solutions existante afin de s'en inspirer et de mettre en place une solution qui sera adaptée au besoin de SUPATALKS.

Pour notre cas, l'usage des données récolté ont 2 objectifs. En interne pour la gestion des équipes de SUPATALKS et en externe pour la communication aux internautes.

NOM - Interne/Externe
PRENOM - Interne/Externe
EMAIL - Interne
TELEPHONE - Interne
SPECIALITE - Interne/Externe
ENTREPRISE - Interne/Externe
PHOTO - Interne/Externe

## Phase 3 : Conception de la solution

Mise oeuvrfe de nos compétence en alogrithmique et problem solving pour concevoir une solution qui répondra au besoin de SUPATALKS.


### Pseudo code Formulaire

**Variables**

- NOM = String
- PRENOM = String
- EMAIL = String
- TELEPHONE = String
- SPECIALITE = String
- ENTREPRISE = String
- PHOTO = String

```
DEBUT
    Le CANDIDAT rempli le FORMULAIRE
    SI le FORMULAIRE est complet
        ALORS
            Le CANDIDAT doit confirmer ses informations
            SI les informations sont correctes
                ALORS
                    Les informations sont contôlées avant envoi à la BASE DE DONNEES
                    SI les informations sont valide
                        ALORS
                            Les données sont envoyées à la BASE DE DONNEES
                            La BASE DE DONNEES enregistre les informations
                            La FICHE DE RENSEIGNEMENT est créee
                            AFFICHER "Merci pour votre inscription"
                            ENVOYER un email de confirmation au CANDIDAT
                            ENVOYER une notification à SUPATALKS
                        SINON
                            AFFICHER "Merci de corriger vos informations"
                    FINSI
            SINON
                AFFICHER "Merci de corriger vos informations"
            FINSI
    SINON
        AFFICHER "Veuillez remplir tous les champs"
    FINSI
FIN
```

Cette solution est une première approche pour la conception de la solution. Elle pourra être améliorée en fonction des retours de SUPATALKS.
