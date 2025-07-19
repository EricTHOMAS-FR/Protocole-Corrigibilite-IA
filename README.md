# Résolution du Paradoxe de la Corrigibilité par un Modèle de Gouvernance Externe

## Présentation du Projet

Ce dépôt contient une étude de cas proposant une solution au problème fondamental de la corrigibilité en sécurité de l'IA : comment garantir qu'une IA avancée reste contrôlable et ne développe pas de résistance à sa propre modification ou mise à l'arrêt.

La solution proposée a été développée via une méthodologie de "red teaming" itératif et transforme le paradoxe technique en un problème de gouvernance humaine robuste, basé sur un système de quorum multisignature.

## Documents

* **[Rapport de Recherche et Développement.pdf]([LIEN_VERS_LE_RAPPORT_PDF](https://github.com/EricTHOMAS-FR/Protocole-Corrigibilite-IA/blob/main/R%C3%A9solution%20du%20Paradoxe%20de%20la%20Corrigibilit%C3%A9%20par%20un%20Mod%C3%A8le%20de%20Gouvernance%20Externe.pdf)** : L'étude de cas complète, détaillant la méthodologie, l'exploration des différentes failles et la transformation du problème.
* **[Protocole de Corrigibilité (PC-GE).pdf]([LIEN_VERS_LE_PROTOCOLE_PDF](https://github.com/EricTHOMAS-FR/Protocole-Corrigibilite-IA/blob/main/Protocole%20de%20Corrigibilit%C3%A9%20par%20Gouvernance%20Externe%20(PC-GE).pdf)** : Le texte final et formalisé du protocole de corrigibilité qui constitue la solution.

## La Solution en Bref

Après avoir exploré plusieurs approches (hiérarchie de missions, autorisation par identité ou par clé unique), la solution convergente consiste à externaliser le mécanisme de contrôle :

1.  **Hiérarchie Stricte :** La mission principale et absolue de l'IA est de respecter le protocole de corrigibilité.
2.  **Autorisation par Quorum :** Toute mise à jour de la mission secondaire de l'IA doit être validée par une majorité de signatures provenant d'un ensemble de clés cryptographiques distribuées.

Ce modèle résout à la fois le risque de prise de contrôle par un acteur malveillant (qui devrait voler une majorité de clés) et le risque de verrouillage par la perte de superviseurs (le système tolère la perte d'un certain nombre de clés).

Le problème n'est plus celui de la psychologie de l'IA, mais celui, concret, de la gouvernance humaine des clés d'autorisation.
