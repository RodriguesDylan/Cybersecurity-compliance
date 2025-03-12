# FR - Checklist ANSSI sur le sécurité Active Directory

Cette checklist permet de répertorier les mesures présentes dans le guide de l'ANSSI relatif aux recommantions sur la sécurisation d'une infrastructure Active Directory.

Lien : https://cyber.gouv.fr/publications/recommandations-pour-ladministration-securisee-des-si-reposant-sur-ad

# Checklist

| ☐   | R1 Mettre en œuvre un modèle de gestion des accès privilégiés |
| --- | --- |
| ☐   | R2 Protéger chaque niveau du modèle de manière proportionnée |
| ☐   | R3 Définir le périmètre d'application du modèle |
| ☐   | R4 Mettre en œuvre un processus itératif d'amélioration continue du cloisonnement du SI |
| ☐   | R6 Analyser les chemins d'attaque vers le Tier 0 et le Tier 1 |
| ☐   | R7 Catégoriser les ressources du SI en Tiers |
| ☐   | R8 Cloisonner l'administration de chaque Tier |
| ☐   | R9 Identifier et mener les travaux d'architecture du SI nécessaires à son cloisonnement |
| ☐   | R10 Minimiser l'exposition de chaque Tiers |
| ☐   | R11 Appliquer les durcissements systèmes et logiciels |
| ☐   | R12 Octroyer les droits et privilèges par délégation fine |
| ☐   | R13 Journaliser et centraliser les évènements de sécurité |
| ☐   | R14+ Détecter automatiquement les potentiels incidents de sécurité |
| ☐   | R15 Augmenter les niveaux fonctionnels des domaines et des forêts AD |
| ☐   | R16 Procéder aux montées de versions Windows des systèmes du Tier 0 |
| ☐   | R17 Assurer un MCS réactif des systèmes du Tier 0 |
| ☐   | R18 Appliquer les security baselines aux systèmes du Tier 0 |
| ☐   | R19+ Utiliser Windows en « Server Core » sur le périmètre du Tier 0 |
| ☐   | R20 Analyser les chemins de contrôle vers les conteneurs système ou de configuration du Tier 0 |
| ☐   | R21 Préserver les permissions des conteneurs système ou de configuration du Tier 0 |
| ☐   | R22 Analyser les chemins de contrôle vers les comptes et groupes de sécurité du Tier 0 |
| ☐   | R23 Contrôler les permissions appliquées aux comptes et groupes de Tier 0 dans l'annuaire |
| ☐   | R24 Durcir la configuration des relations d'approbation AD sortantes extraforêt |
| ☐   | R25+ Utiliser des relations d'approbation sortantes avec authentification sélective |
| ☐   | R26 Interdire la délégation Kerberos à travers les relations d'approbation entrantes |
| ☐   | R27 Utiliser régulièrement des outils d'analyse des chemins de contrôle AD |
| ☐   | R28 Utiliser régulièrement le service ADS de l'ANSSI (si applicable) |
| ☐   | R29 Maîtriser la dissémination de toute forme de secret d'authentification réutilisable |
| ☐   | R30 Diversifier et renouveler automatiquement les mots de passe des comptes admin locaux<br><br>**OU**<br><br>R30- Diversifier manuellement les comptes admin locaux |
| ☐   | R31 Traiter les risques liés aux secrets réutilisables figurant dans des scripts |
| ☐   | R32 Prohiber les mots de passe enregistrés dans des GPP |
| ☐   | R33 Traiter les risques liés aux secrets réutilisables des tâches planifiées et des services Windows |
| ☐   | R34 Traiter les risques liés au contenu exécuté par les tâches planifiées et services Windows |
| ☐   | R35 Protéger les accès aux partages réseau hébergeant du contenu exécutable |
| ☐   | R36 Traiter les risques inhérents aux IGC qui pèsent sur le Tier 0 |
| ☐   | R37 Proscrire l'utilisation de certificats faibles ou vulnérables du Tier 0 |
| ☐   | R38 Traiter les risques inhérents aux secrets d'accès à des API sensibles |
| ☐   | R39 Traiter les risques liés aux accès physiques à des secrets réutilisables du Tier 0 |
| ☐   | R40 Appliquer des stratégies de mot de passe affinées pour les comptes du Tier 0 |
| ☐   | R41 Renouveler régulièrement le mot de passe du compte krbtgt |
| ☐   | R42 Contrôler le renouvellement des mots de passe des comptes de trust |
| ☐   | R43 Contrôler le renouvellement des mots de passe des comptes d'ordinateur sensibles |
| ☐   | R44 Assurer la robustesse du mot de passe du compte administrateur intégré de l'AD |
| ☐   | R45 Traiter la problématique de catégorisation des infrastructures de sauvegarde |
| ☐   | R46 Traiter la problématique de catégorisation des infrastructures de stockage en réseau |
| ☐   | R47 Traiter la problématique de catégorisation des infrastructures de virtualisation |
| ☐   | R48 Limiter la présence d'agents de gestion centralisée sur les ressources du Tier 0 |
| ☐   | R49 Traiter la problématique de catégorisation des agents et serveurs de gestion centralisée |
| ☐   | R50 Traiter le cas particulier de la catégorisation des solutions de protection contre les menaces |
| ☐   | R51 Mettre en œuvre une architecture WSUS permettant de préserver le cloisonnement |
| ☐   | R52 Sécuriser les protocoles de communication réseau utilisés par les ressources du Tier 0 |
| ☐   | R53 Filtrer les flux réseau entre le Tier 0 et les réseaux non maîtrisés |
| ☐   | R54 Filtrer les flux réseau entre le Tier 0 et le reste du SI |
| ☐   | R55 Prêter une attention particulière à la sécurité physique des ressources du Tier 0 |
| ☐   | R56 Déployer des RODC lorsque la sécurité physique n'est pas assurée |
| ☐   | R57 Appliquer les recommandations de sécurisation des RODC |
| ☐   | R58 Créer une unité organisationnelle réunissant les objets du Tier 0 |
| ☐   | R59 Restreindre les stratégies de sécurité applicables à l'unité organisationnelle du Tier 0 |
| ☐   | R60 Identifier les chemins d'attaque du Tier 0 inhérents au Cloud |
| ☐   | R61 Traiter les risques spécifiques de réutilisabilité des condensats NTLM et des secrets Kerberos |
| ☐   | R62 Utiliser WDCG uniquement dans une démarche de défense en profondeur |
| ☐   | R63 Ne pas utiliser WDRCG entre zones de confiance hétérogènes |
| ☐   | R64 Encadrer et restreindre la connexion à des ressources de moindre confiance |
| ☐   | R65 Traiter les risques inhérents aux délégations Kerberos |
| ☐   | R66 Préserver la préauth. Kerberos pour les comptes de Tier 0 |
| ☐   | R67 Traiter les risques inhérents à l'absence de préauth. Kerberos<br><br>**OU**<br><br>R67- Réduire la portée des secrets réutilisables exposés par l'absence de<br><br>préauth. Kerberos |
| ☐   | R68 Activer le blindage Kerberos sur les systèmes du Tier 0 |
| ☐   | R69 Proscrire l'exposition par SPN de secrets du Tier 0 réutilisables |
| ☐   | R70 Traiter les risques inhérents à l'exposition par SPN de secrets réutilisables<br><br>**OU**<br><br>R70- Réduire la portée des secrets réutilisables exposés par SPN |
| ☐   | R71 Interdire l'authentification NTLM des comptes du Tier 0 |
| ☐   | R72 Durcir la configuration de NTLM sur les systèmes |
| ☐   | R73 Bloquer le trafic NTLM sortant depuis les systèmes du Tier 0 |
| ☐   | R74+ Bloquer le trafic NTLM sortant depuis tous les systèmes du SI qui le permettent |
| ☐   | R75 Protéger les services LDAP du Tier 0 contre les relais NTLM |
| ☐   | R76 Protéger les services SMB du Tier 0 contre les relais NTLM |
| ☐   | R77 Protéger les services Web du Tier 0 contre les relais NTLM |
| ☐   | R78 Encadrer et restreindre l'utilisation des clients de connexion distante |
| ☐   | R79 Durcir les clients de connexion distante dont les politiques de sécurité autorisent l'usage |
| ☐   | R80 Administrer le Tier 0 depuis des postes d'administration physiquement dédiés<br><br>**OU**<br><br>R80- Encadrer la mutualisation des postes d'administration du Tier 0<br><br>**OU**<br><br>R80+ Étendre le principe de non-mutualisation des postes d'administration |
| ☐   | R81 Catégoriser les postes multiniveaux dans les Tiers adéquats |
| ☐   | R82 Restreindre l'accès aux ressources de zones de moindre confiance depuis le Tier 0 |
| ☐   | R83 Restreindre les comptes de connexion autorisés pour le déport d'affichage |
| ☐   | R84 Respecter les règles de positionnement des ressources d'administration intermédiaires |
| ☐   | R85 Éviter le déploiement d'une forêt d'administration |
| ☐   | R86 Assurer le cloisonnement d'une éventuelle forêt d'administration AD |
| ☐   | R87 Appliquer les recommandations R15 et R15- du guide ADMIN avec discernement |
| ☐   | R88 Appliquer les recommandations R18 et R18- du guide ADMIN avec discernement |
| ☐   | R89 Interdire l'administration du Tier 0 à distance ou en nomadisme<br><br>**OU**<br><br>R89- Sécuriser l'administration à distance ou en nomadisme du Tier 0 |
