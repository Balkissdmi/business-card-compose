# Business Card (Jetpack Compose)

Application Android simple qui affiche une carte de visite en **Jetpack Compose**.

## Aperçu

L’écran est découpé en 2 sections :

- **Section 1 (Identité)** : logo + nom + titre
- **Section 2 (Coordonnées)** : téléphone + lien/handle + email (avec icônes)

## Technologies

- Android
- Kotlin
- Jetpack Compose (Material 3)

## Prérequis

- **Android Studio** (version récente recommandée)
- Un émulateur Android ou un téléphone avec le **mode développeur** activé

## Installation / Lancement

1. Cloner le projet

```bash
git clone https://github.com/<ton-username>/<ton-repo>.git
```

2. Ouvrir dans Android Studio

- `File` > `Open...`
- Sélectionne le dossier du projet

3. Synchroniser Gradle

- Android Studio lance en général la sync automatiquement
- Sinon : `File` > `Sync Project with Gradle Files`

4. Lancer l’application

- Clique sur **Run** (triangle vert)
- Choisis un **émulateur** ou ton **téléphone**

## Structure du code

- UI principale : `app/src/main/java/com/example/businesscard/MainActivity.kt`
  - `BusinessCardScreen()` : écran complet
  - `IdentitySection()` : logo + nom + titre
  - `ContactSection()` / `ContactRow()` : lignes de contact avec icônes

## Ressources (logo)

Le logo est placé dans :

- `app/src/main/res/drawable/android_logo.png`

Si tu veux remplacer le logo :

- remplace le fichier dans `res/drawable/`
- garde le nom `android_logo.png` (ou change le nom et adapte `R.drawable...` dans le code)

## Personnalisation

Dans `MainActivity.kt`, tu peux modifier :

- Le nom : `name = "Balkiss Doulemi"`
- Le titre : `title = "Student Developer"`
- Téléphone : `phone = "+21621489633"`
- Email : `email = "balkiss.dmi13@gmail.com"`
- Handle : `handle = "@balkiss"`

## Build APK (optionnel)

- `Build` > `Build Bundle(s) / APK(s)` > `Build APK(s)`

## Auteur

- **Balkiss Doulemi**
