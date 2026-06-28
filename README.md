# Kiyotaka's Food — Gestionnaire de Commandes 🍔📦

TL;DR
Application de gestion de commandes multiplateforme pour l'écosystème Kiyotaka's Food. Interface d'administration pour centraliser, suivre et traiter les commandes en temps réel, développée principalement en Flutter avec une intégration Supabase.

---

## 🚀 Résumé du projet
Kiyotaka's Food — Gestionnaire de Commandes est une application destinée aux équipes opérationnelles (cuisine, préparation, livraison) pour :
- visualiser les commandes en temps réel,
- mettre à jour les statuts (en préparation, prête, livrée),
- synchroniser instantanément les changements entre appareils (mobile, desktop, web).

Ce projet démontre la capacité à construire une app robuste, cross‑platform et connectée à une base de données temps réel.

---

## 🛠️ Stack technique
- Framework : Flutter (Dart) — application multiplateforme (Android, iOS, Web, Windows, macOS, Linux)
- Backend / Realtime : Supabase (PostgreSQL + Realtime)
- Composants natifs : C++, CMake, Swift, C (modules natifs / intégrations présents)
- Outils : pub, Flutter CLI, linter (analysis_options.yaml)

---

## ✨ Fonctionnalités clés
- Affichage et actualisation en temps réel des commandes
- Gestion des états de commande (Nouvelle → En cours → Préparée → Livrée)
- Notifications côté application lors des changements critiques
- Interface responsive adaptée aux écrans mobiles et desktop
- Synchronisation fiable via Supabase

---

## 📂 Structure du dépôt
Racine (extraits)
- android/, ios/, linux/, macos/, windows/, web/ — configurations plateformes
- lib/ — code Dart/Flutter (UI, logique métier, services)
- assets/ — images et ressources
- test/ — tests unitaires / d'intégration
- pubspec.yaml, analysis_options.yaml — dépendances & règles de style

---

## ⚙️ Installation & Exécution (développement)
Pré-requis : Flutter SDK, accès au projet Supabase.

1. Cloner
   git clone https://github.com/fresnel2006/gestionnaire-des-commandes-kiyotaka-s-food.git
2. Installer les dépendances
   flutter pub get
3. Créer un fichier d'environnement `.env` (ou config équivalente) avec les clés Supabase :

   SUPABASE_URL=https://xxxxx.supabase.co
   SUPABASE_ANON_KEY=eyJxxxxxxxxxxxxxxxx

   (Ne pas committer ce fichier)
4. Lancer en debug (ex. sur Android ou Web)
   flutter run -d chrome
   ou
   flutter run -d android

Build release (exemples) :
- Android : flutter build apk
- Web : flutter build web
- Windows : flutter build windows

---

## ✅ Tests
- Lancer les tests :
  flutter test

(Compléter les tests unitaires / d'intégration au fur et à mesure. Le dossier `test/` contient les suites existantes.)

---

## 🔒 Sécurité & bonnes pratiques
- Ne jamais committer de clés (ajouter au .gitignore si nécessaire)
- Utiliser les rôles/permissions Supabase pour limiter l'accès aux données
- Respecter les règles de lint définies dans `analysis_options.yaml`

---

## 📈 Ce que ce projet démontre (pour les recruteurs)
- Développement d'applications cross‑platform avec Flutter
- Intégration de bases temps réel (Supabase / Postgres)
- Capacité à interfacer des composants natifs (C++/CMake/Swift)
- Approche orientée produit : priorisation UX et fiabilité en production
- Mise en place de pratiques de qualité (lint, tests, structure modulaire)

---

## 🖼️ Capture d'écran / Démo
(Insérer ici des captures ou un GIF / lien vers une vidéo de démonstration pour valoriser l'UI.)

---

## 🤝 Contribuer
Contributions et retours bienvenus. Ouvrir une issue ou proposer une PR avec une description claire du changement.

---

## 📫 Contact
fresnel2006 — https://github.com/fresnel2006
Email: (ajoute ton email ici) — LinkedIn: (insérer lien)

---

## Licence
Indiquer la licence choisie (ex. MIT). Si aucune licence, ajouter : "Aucune licence spécifiée — contactez le mainteneur pour les usages commerciaux."