# Tip Calculator

## Présentation

Tip Calculator est une petite application Android développée avec Kotlin et Jetpack Compose.

L'application permet de calculer automatiquement le montant du pourboire à partir du prix de la facture et du pourcentage de pourboire choisi.

## Fonctionnalités

- Saisir le montant de la facture.
- Saisir le pourcentage du pourboire.
- Calculer automatiquement le pourboire.
- Arrondir le montant du pourboire grâce à un bouton.
- Afficher le résultat directement à l'écran.

## Technologies utilisées

- Kotlin
- Android Studio
- Jetpack Compose
- Material 3

## Fonctionnement

L'utilisateur entre d'abord le montant de la facture, puis le pourcentage du pourboire.

L'application calcule ensuite le pourboire avec la formule :

Montant du pourboire = Montant de la facture × Pourcentage / 100

L'utilisateur peut également activer l'option d'arrondissement pour arrondir le résultat à l'entier supérieur.

## Structure principale

- `MainActivity.kt` : contient le fonctionnement principal de l'application.
- `TipTimeLayout()` : affiche l'interface principale.
- `EditNumberField()` : permet de saisir les nombres.
- `RoundTheTipRow()` : contient l'option pour arrondir le pourboire.
- `calculateTip()` : effectue le calcul du pourboire.

## Objectif du projet

Ce projet m'a permis de pratiquer le développement d'une interface Android avec Jetpack Compose, la gestion des états avec `remember` et `mutableStateOf`, ainsi que la création de fonctions en Kotlin.

## Auteur
KONE CHEICK MOHAMED YASSINE