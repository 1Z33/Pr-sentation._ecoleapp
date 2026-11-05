ECOLEAPP · PRÉSENTATION01 / 10

Document confidentiel · accès sur engagement

## Conditions de visite

**1. Propriété.** Le système EcoleApp, son cahier des charges, son architecture, ses modules, ses parcours et cette présentation sont la propriété exclusive d'EcoleApp (ecoleapp.org). Tous droits réservés.

**2. Usage limité.** L'accès est accordé à titre personnel, pour évaluer le projet. Il ne confère aucune licence ni aucun droit d'exploitation.

**3. Interdictions.** Il est interdit de copier, reproduire, capturer (écran, photo, vidéo), extraire le code ou les contenus, décompiler, adapter ou republier tout ou partie de cette présentation.

**4. Idées protégées.** Les concepts décrits ici (architecture multi-établissements, marque blanche, importation intelligente Excel, authentification par QR code, gestion de fin d'année, regroupement familial) ne peuvent être reproduits, imités ou proposés à un tiers, sous une forme identique ou voisine.

**5. Confidentialité.** Les informations vues ici ne doivent être transmises à aucun tiers sans accord écrit préalable.

**6. Traçabilité.** Votre nom, votre organisation et l'heure d'accès sont affichés en filigrane sur chaque écran. En cas de fuite, cette mention permet de remonter à la source.

**7. Sanctions.** Toute violation peut entraîner la fin de l'accès et des poursuites selon le droit applicable.

Nom completOrganisation

[ ] J'ai lu les conditions et je m'engage à les respecter.

Cahier des charges v1.0 · novembre 2026

# EcoleApp

Une plateforme, plusieurs établissements, une gestion scolaire centralisée.

Application web SaaS pour les écoles maternelles, primaires et secondaires de la République démocratique du Congo. Faites défiler pour parcourir la ville des écoles.

Architecture multi-établissements

## Une même base, des écoles séparées

Chaque école possède ses utilisateurs, ses élèves, ses classes, ses finances et ses paramètres. L'isolation multi-tenant interdit tout mélange de données.

En marque blanche, chacune reprend sa propre identité : nom, logo, couleurs, support, domaine ou sous-domaine dédié. Regardez les bandes changer de couleur d'une école à l'autre.

Huit profils, huit permissions

## Chacun voit ce qui le concerne

- **Super administrateur**plateforme, abonnements, audit
- **Administrateur**toute la vie de l'établissement
- **Directeur ou préfet**supervision pédagogique
- **Secrétaire**dossiers, inscriptions, imports
- **Comptable ou caissier**frais, reçus, soldes
- **Enseignant**notes, présences, devoirs
- **Parent ou tuteur**résultats, absences, paiements
- **Élève**notes, horaires, bulletins

Sur le terrain

## Pensé pour la vraie vie d'une école

Directions, salles de classe, rencontres avec les parents : trois mondes que la plateforme relie. Suivi pédagogique, présences, frais, bulletins, messages WhatsApp aux familles.

Images d'illustration.

Le quotidien de l'école

## Tout ce qui fait tourner un établissement

- **Notes et bulletins**évaluations, moyennes, classements, appréciations
- **Présences**absences et retards, visibles aussi des parents
- **Emplois du temps**par classe et par enseignant
- **Frais et reçus**paiements partiels, soldes, dettes, échéances
- **WhatsApp**messages préparés pour les familles
- **Rapports**statistiques en PDF, Excel et CSV

Importation intelligente Excel

## Des centaines d'élèves en une opération

Colonnes reconnues, doublons repérés, enfants regroupés par téléphone commun, matricules générés. Essayez sur six lignes d'exemple.

Données fictives, fichier non analysé.

Authentification par QR code

## Un code, un seul premier accès

Le QR est unique, lié au domaine de l'école, temporaire, inutilisable après activation.

1. Compte utilisateur créé
2. QR unique généré et transmis
3. Lecture à la première connexion
4. Validité et unicité vérifiées
5. Mot de passe personnel, puis authentification supplémentaire

Fin d'année scolaire

## Chaque élève reçoit sa décision

L'historique des inscriptions est conservé, l'année est clôturée, la suivante activée, les statistiques et documents produits.

- Passe en classe supérieure
- Redouble
- Sort d'une classe terminale

Ordre de construction

## Des fondations aux différences

- **P1**établissements, utilisateurs, élèves, classes, pédagogie, finance, isolation
- **P2**import Excel, familles, espaces parent et élève, rapports, WhatsApp, marque blanche
- **P3**QR code, fin d'année, historique, domaines
- **P4**performances, tableaux de bord, Mobile Money

Next.js · React · TypeScript · Tailwind\
Python · FastAPI · PostgreSQL · SQLAlchemy · Alembic\
Docker · Dokploy

ecoleapp.org · © 2026 EcoleApp. Document confidentiel, accès tracé.

Votre établissement

## Mettons EcoleApp en place dans votre école.

Dites-nous qui vous êtes. Nous vous répondons directement sur WhatsApp, vous montrons la plateforme et préparons l'installation avec vous.

1. Échange sur les besoins de votre école
2. Configuration : classes, frais, identité visuelle
3. Importation de vos élèves et parents depuis Excel
4. Comptes, accès et prise en main

Nom de l'écoleNombre d'élèves, environ [Écrire sur WhatsApp](https://wa.me/243972519906)

+243 97 251 99 06 · [ecoleapp.org](https://ecoleapp.org)