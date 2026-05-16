---
title: "Politique de confidentialité — DIMA - Analyzer"
date: 2026-05-15
author: Bertrand Boyer
tags: [LMI,désinformation,DISARM,cognitive warfare]
---

## Politique de confidentialité — DIMA (Digital Influence Manipulation Analyzer)

**Date d'effet :** mai 2026  
**Extension développée par :** M82 Project — [https://m82-project.org](https://m82-project.org)  
**Contact :** contact@m82-project.org

---

## Résumé

DIMA est une extension de navigateur qui fonctionne **entièrement en local** sur votre appareil. Elle **ne collecte, ne stocke, ne transmet et ne partage aucune donnée personnelle**, quel que soit le contexte d'utilisation.

---

## Données collectées

**Aucune.**

DIMA ne collecte aucune donnée personnelle, aucune donnée de navigation, aucun identifiant, aucune adresse IP et aucun cookie. L'extension n'effectue aucun appel réseau, aucune requête vers un serveur externe et ne communique avec aucune API tierce.

## Fonctionnement de l'extension

DIMA analyse le contenu textuel des pages web que vous visitez afin de détecter d'éventuelles techniques de manipulation cognitive, selon la matrice DIMA développée par le M82 Project. Cette analyse est réalisée :

- **Localement**, directement dans votre navigateur ;
- **En temps réel**, au chargement de la page ;
- **Sans transmission** d'aucune information vers l'extérieur.

L'extension compare également l'URL visitée à des bases de données de sites suspects intégrées dans l'extension elle-même. Ces bases de données sont embarquées dans le code de l'extension et ne nécessitent aucune connexion réseau.

## Stockage local

DIMA utilise l'API `storage` du navigateur uniquement pour conserver vos préférences d'affichage (comme l'état d'ouverture du panneau). Ces données restent strictement sur votre appareil et ne sont jamais transmises.

## Permissions demandées

- **activeTab** : permet à l'extension d'accéder au contenu de l'onglet actif pour l'analyser.
- **storage** : permet de sauvegarder vos préférences localement.
- **Accès à toutes les URLs** (`host_permissions: <all_urls>`) : nécessaire pour que l'analyse puisse s'exécuter sur n'importe quelle page web visitée. Cette permission ne sert qu'à l'injection du script d'analyse local ; aucune donnée n'est extraite ni envoyée.

## Partage de données avec des tiers

**Aucun partage.** Aucune donnée n'est collectée, donc aucune donnée n'est partagée, vendue, échangée ou transmise à quelque tiers que ce soit.

## Analyse, suivi et publicité

DIMA n'intègre aucun outil d'analyse (analytics), aucun traceur, aucun pixel de suivi et aucune publicité.

## Code source

DIMA est un projet open source. Le code source complet est librement consultable et vérifiable sur le dépôt GitHub du M82 Project, sous licence Apache 2.0.

## Modifications de cette politique

En cas de modification de cette politique de confidentialité, la version mise à jour sera publiée sur cette page avec une nouvelle date d'effet. L'architecture fondamentale de DIMA — traitement local sans collecte de données — constitue un principe de conception non négociable du projet.

## Contact

Pour toute question relative à cette politique de confidentialité ou au fonctionnement de l'extension :

- **Email :** contact@m82-project.org  
- **Site web :** [https://m82-project.org](https://m82-project.org)
- **Code source :** [https://github.com/M82-project](https://github.com/M82-project)

---

## Privacy Policy — DIMA (Digital Influence Manipulation Analyzer)

**Effective date:** May 2026  
**Extension developed by:** M82 Project — [https://m82-project.org](https://m82-project.org)  
**Contact:** contact@m82-project.org

---

## Summary

DIMA is a browser extension that operates **entirely locally** on your device. It **does not collect, store, transmit, or share any personal data** under any circumstances.

---

## Data collected

**None.**

DIMA does not collect any personal data, browsing data, identifiers, IP addresses, or cookies. The extension makes no network requests, contacts no external servers, and communicates with no third-party APIs.

## How the extension works

DIMA analyzes the text content of web pages you visit to detect potential cognitive manipulation techniques, based on the DIMA matrix developed by the M82 Project. This analysis is performed:

- **Locally**, directly within your browser;
- **In real time**, upon page load;
- **Without transmitting** any information externally.

The extension also compares visited URLs against databases of suspicious sites embedded within the extension itself. These databases are bundled in the extension code and require no network connection.

## Local storage

DIMA uses the browser's `storage` API solely to save your display preferences (such as the panel's open/closed state). This data remains strictly on your device and is never transmitted.

## Permissions requested

- **activeTab**: allows the extension to access the content of the active tab for analysis.
- **storage**: allows local saving of your preferences.
- **Access to all URLs** (`host_permissions: <all_urls>`): required so that analysis can run on any web page you visit. This permission is used solely for injecting the local analysis script; no data is extracted or sent.

## Third-party data sharing

**None.** No data is collected, therefore no data is shared, sold, traded, or transmitted to any third party.

## Analytics, tracking, and advertising

DIMA does not include any analytics tools, trackers, tracking pixels, or advertisements.

## Source code

DIMA is an open-source project. The complete source code is freely available for review on the M82 Project's GitHub repository, under the Apache 2.0 license.

## Changes to this policy

If this privacy policy is updated, the revised version will be published on this page with a new effective date. DIMA's fundamental architecture — local processing with no data collection — is a non-negotiable design principle of the project.

## Contact

For any questions regarding this privacy policy or the extension's operation:

- **Email:** contact@m82-project.org  
- **Website:** [https://m82-project.org](https://m82-project.org)
- **Code:** [https://github.com/M82-project](https://github.com/M82-project)
