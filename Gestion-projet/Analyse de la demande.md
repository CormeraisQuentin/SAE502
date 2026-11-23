# Première lecture du projet - KerLogis

Projet : Analyse de risques et maquette d'infrastructure
Entreprise : KerLogis
Équipe : KerSecure
Version : 0.1 - Première lecture
Date : 23 Novembre 2026
Statut : Document de travail - A compléter

## 1. Présentation générale du client
KerLogis est une entreprise spécialisée dans la logistique et le transport régional, notamment pour la grande distribution et le commerce en ligne.

Elle possède actuellement deux sites :
Brest et Lorient

Un troisième site doit ouvrir à Rennes dans six mois.

L'entreprise comporte 65 collaborateurs et l'activité est plus importante entre novembre et janvier.

L'infrastructure informatique actuelle fonctionne sur un serveur physique qui est ancien, ce serveur héberge des services critiques.

## 2. Problématiques identifiées

A partir du cahier des charges, plusieurs problèmes majeurs ont été trouvés :

- Aucune supervision de l'infrastructure
- Aucune centralisation de logs
- Matériel et systèmes anciens
- Difficultés pour maintenir l'infrastructure
- Infrastructure peu évolutive pour un nouveau site
- Pas de restauration de sauvegarde prévue

## 3. Premiers pas DevCloud

Nous allons étudier : 
- La mise en place d'une supervision et centralisation des logs
- L'automatisation des déploiement et configuration
- Intégration d'une chaine CI/CD
- Les possibilités d'hébergement sur un Cloud public.

# 4. Questions à étudier

Nous nous posons plusieurs questions : 
-  Quel est le budget ?
-  Quels sont les services prioritaires ?
-  Il y a t-il des contraintes à propos du Cloud (politique entreprise) ?
-  Quels sont les besoins réels en supervision ?
-  Quels service pourraient être migré ?

## 4. Périmètre provisoire

Le périmètre technique définitif n'est pas encore validé. Périmètre a voir avec le Product Owner lors des échanges.
