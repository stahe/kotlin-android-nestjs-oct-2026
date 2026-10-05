# Un exemple de client / serveur - Kotlin Android / NestJS (2026)

Ce dépôt signale le cours **« Un exemple de client / serveur - Kotlin Android / NestJS (2026) »**, publié à l'adresse :

**https://stahe.github.io/kotlin-android-nestjs-oct-2026/**

## Présentation

Ce document porte vers une application Android native l'application pédagogique **RdvMedecins** (prise de rendez-vous chez le médecin), déjà déclinée dans les cours consacrés à Angular, React, Vue.js et Flutter. Il en propose ici une version **Android** : un client écrit en **Kotlin** avec **Jetpack Compose** (Material 3), qui s'appuie sur un serveur **NestJS** (TypeScript) exposant une API JSON protégée par authentification JWT (rôles ADMIN / USER).

Le document suit pas à pas la progression du cours [Un exemple de client / serveur - Flutter / NestJS (2026)](https://stahe.github.io/flutter-nestjs-sept-2026/), dont il reprend le serveur, la base de données et l'architecture du client : chaque notion de Jetpack Compose est reliée à son équivalent Flutter. Les bases du langage Kotlin sont présentées dans le [cours Kotlin](https://stahe.github.io/kotlin-oct-2026/).

Le cours couvre :

- la mise en place de l'environnement de travail (Android Studio, SDK Android, Gradle, création d'un projet Compose, émulateur et téléphone Android) ;
- l'installation et le lancement du serveur NestJS de l'application (base MySQL, configuration, tests avec un navigateur et avec Postman) ;
- une introduction à Android et à Jetpack Compose (activité, fonctions `@Composable`, état et recomposition, `CompositionLocal`, coroutines, cycle de vie et `ViewModel`) ;
- l'étude commentée, fichier par fichier, du client Kotlin de l'application RdvMedecins (OkHttp, kotlinx.serialization, SharedPreferences, Material 3) ;
- l'exécution de l'application sur un émulateur et sur un téléphone, avec les pièges propres au mobile (adresse du serveur, `adb reverse`, trafic HTTP en clair, rotation de l'écran, écrans étroits), la production d'un APK, et un aperçu de Kotlin Multiplatform ;
- une conclusion sur ce qui a été construit et les pistes pour aller plus loin.

## Auteurs

- **Auteur principal :** IA Claude (Anthropic)
- **Réviseur :** [Serge Tahé](https://stahe.github.io)
