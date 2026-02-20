💼 Business Card – Jetpack Compose

Application Android développée avec Jetpack Compose (Material 3) qui affiche une carte de visite moderne et responsive.

Ce projet a été réalisé dans le cadre d’un TP pratique afin de maîtriser les bases de Compose :
📐 Layouts – 🎨 Material 3 – 🧩 Composables – 📱 UI structurée.

📱 Aperçu de l’application

L’interface est organisée en deux sections principales :

🔹 1️⃣ Identity Section

Logo Android

Nom complet

Titre / Rôle

🔹 2️⃣ Contact Section

Numéro de téléphone

Email

Handle / lien

Icônes Material alignées avec chaque information

L’écran est construit avec des Column, Row, Spacer et Modifier pour assurer un alignement propre et un espacement cohérent.

🛠 Technologies utilisées

📱 Android

💻 Kotlin

🎨 Jetpack Compose

🧱 Material 3

🧩 Architecture simple basée sur des Composables réutilisables

⚙️ Prérequis

Android Studio (version récente recommandée)

SDK Android installé

Émulateur Android ou téléphone physique avec mode développeur activé


🚀 Installation & Lancement

1️⃣ Cloner le projet

git clone https://github.com/Balkissdmi/business-card-compose.git

2️⃣ Ouvrir dans Android Studio

File → Open

Sélectionner le dossier du projet

3️⃣ Synchroniser Gradle

La synchronisation démarre automatiquement.
Sinon :

File → Sync Project with Gradle Files
4️⃣ Lancer l’application

Cliquer sur ▶ Run

Choisir un émulateur ou un appareil connecté

🏗 Structure du code

📂 app/src/main/java/com/example/businesscard/

MainActivity.kt → Point d’entrée de l’application

BusinessCardScreen() → Composable principal

IdentitySection() → Affichage du logo + nom + titre

ContactSection() → Bloc contenant les coordonnées

ContactRow() → Ligne de contact avec icône + texte

🖼 Ressources

Logo placé dans :

app/src/main/res/drawable/android_logo.png

Pour le modifier :

Remplacer l’image dans res/drawable

Adapter le nom dans R.drawable.nom_image si nécessaire

🎨 Personnalisation

Dans MainActivity.kt, tu peux modifier :

name = "Balkiss Doulemi"

title = "IT Student & Mobile Developer"

phone = "+216 21 489 633"

email = "balkiss.dmi13@gmail.com"

handle = "@balkiss"

📦 Générer un APK

Build → Build Bundle(s) / APK(s) → Build APK(s)

L’APK sera généré dans le dossier app/build/outputs/apk/.

🎯 Objectifs pédagogiques

✔ Comprendre la structure d’une app Compose

✔ Utiliser Material 3

✔ Gérer les layouts (Column / Row / Alignment)

✔ Créer des composables réutilisables

✔ Structurer un projet Android proprement


👩‍💻 Auteur

Balkiss Doulemi
🎓 IT Student
📱 Mobile Development Enthusiast
🔗 GitHub : https://github.com/Balkissdmi
