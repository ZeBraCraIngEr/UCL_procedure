# Installation Intune[^1]

![UCLouvain logo](https://cdn.uclouvain.be/groups/cms-editors-arec/charte-graphique-uclouvain/UCLouvain_Logo_Pos_CMJN.png?itok=0Vz8FOqj)

Cette procédure permet de passer une machine depuis l’environnement de Saint-Louis vers celui de l’UCLouvain.

Elle doit être effectuée dans votre session d’utilisateur.

Veuillez-suivre la procédure étape par étape. Dans le cas où vous rencontreriez un problème, cela permettra de noter l’endroit précis où le problème est survenu, et permettra une résolution plus efficace.

> [!NOTE]
> :hourglass_flowing_sand: Temps estimé pour l'ensemble de la procédure: 40 minutes. Nous recommandons de vous préparer un petit café :coffee: ou thé :tea:.

> [!WARNING]
> Ce follow through est **uniquement destiné** aux membres du personnel de l'[UCLouvain][uclouvain] possèdant un Macbook.
> 
> :uk:/:us: This follow through process **only addresses to** [UCLouvain][uclouvain] members that own a Macbook.

-----------------
### Etape 1: récupérer et installer le programme d'installation

> [!NOTE]
> :hourglass_flowing_sand: L'installation devrait prendre **moins d'une minute**.

Télécharger le programme directement via [ce lien-ci][pkginstaller].

**Installation :**
1. Accepter la licence.
2. Cliquer sur `Installer`.
3. Valider les identifiants utilisateur machine :computer:.
4. Accepter l'accès aux fichiers en cliquant sur `OK`.
5. Cliquer sur `Fermer`.
6. Supprimer l'installeur en cliquant `Placer dans la corbeille`.

-----------------
### Etape 2: Microsoft AutoUpdate

> [!NOTE]
> :hourglass_flowing_sand: Devrait prendre une minute. Dans le cas où la Suite Office est déjà installée, l’étape prendre un peu plus de temps.

Se lance directement après l'installation du portail. Appuyer sur `OK`.

1. Cliquer sur la flèche :arrow_down_small: pour déployer et voir toutes les applications.
2. Vérification des mises à jour des programmes de la Suite Office, de Microsoft AutoUpdate et du Portail d'entreprise.
3. Cliquer sur `Tout mettre à jour`.
4. Fermer `Microsoft AutoUpdate`.

> [!IMPORTANT]
> Il est possible que certains liens/icones du `Dock` vers les applications de la `Suite Office` ne soient plus cliquables. Il faut les supprimer du `Dock` et les replacer.

-----------------
### Etape 3: Portail d'entreprise
Gestion de la machine, sécurité, cryptage des données et installation de la suite office.

> [!NOTE]
> :hourglass_flowing_sand: En fonction des cas, cette étape prendra entre **10 et 20 minutes**.

1. Désactiver le `FileVault` en suivant:
   ```
   Réglage Système > Confidentialité et sécurité > FileVault > Désactiver...
   ```
2. Lancer l'application `Portail d'entreprise`.

> [!WARNING]
> Il est possible qu'il faille se connecter avec les identifiants UCLouvain :bust_in_silhouette:.
   
3. Cliquer sur `Commencer` la configuration de l'accès à L'UCLouvain.
4. Cliquer sur `Continuer`.
5. Cliquer sur `Télécharger le profil`.
   1. Cliquer sur la fenêtre de `Réglages système` qui s'est ouverte.
   2. Double cliquer sur `Management Profile`.
   3. Cliquer sur `Installer`.
   4. Utiliser les identifiants machine :computer:.
   5. Fermer la fenêtre de `Réglages système`.
6. Attendre les vérifications des paramètres système.

> [!WARNING]
> Il est possible qu'il faille relancer la procédure une seconde fois. Pas de panique, ça ne devrait pas prendre autant de temps.

7. Cliquer sur `Terminer`.
8. Cliquer sur `En savoir plus` pour vérifier que seul le chiffrement de l'appareil soit demandé, puis `fermer`.
9. Modifier le mot de passe machine :computer: (Possibilité de reprendre le même pour autant qu'il est validé par les exigences de l'UCLouvain) en suivant:
   ```
   Réglage Système > Touch ID et mot de passe > Modifier...
   ```
10. Activer le chiffrement de l'appareil en suivant:
   ```
   Réglage Système > Confidentialité et sécurité > FileVault > Activer...
   ```
11. Cliquer sur `continuer`. La création du FileVault se lance.
12. Sur `Portail d'entreprise`, cliquer sur `En savoir plus`, puis `Réessayer`. La vérification de l'État se lance.
13. Désactiver la collecte des données de Microsoft en suivant:
   ```
   Portail d'entreprise > Réglages... > Décocher "Authorisez Microsoft à collecter des données d'utilisation.".
   ```
14. Quitter l'application `Portail d'entreprise`.
15. Redémarrer la machine.

-----------------
### Etape 4: Centre de gestion des logiciels
Permettra d'accéder à toutes les applications mises à disposition par l'UCLouvain via l'onglet `Logiciel`.

> [!NOTE]
> :hourglass_flowing_sand: Cette étape ne devrait prendre que **5 minutes**.
   
1. Lancer l'application `Centre de gestion des logiciels`.
2. Vérification des mises à jour automatique des logiciels.
3. Cliquer sur `Tout mettre à jour`.
4. Quitter l'application`Centre de gestion des logiciels`.

-----------------
### Etape 5: Inscrire la machine pour l'UCLouvain

> [!NOTE]
> :hourglass_flowing_sand: Cela devrait prendre **moins d'une minute**.

1. Lancer `Munki UCLouvain From`.
2. Entrer les identifiants machine :computer:.
3. Entrer le libellé de l'étiquette se trouvant sur la machine de la manière suivante:
   ```
   ABXX-XXX
   ```
   où X sont des chiffres.

> [!WARNING]
> Remarquez l'utilisation du signe `-` et non du signe `.`
   
3. Entrer l'email utilisateur UCLouvain :bust_in_silhouette:.
4. Sélectionner le secteur `SIAB`.
5. Cliquer sur `OK`.

-----------------
### Etape 6: Finalisation
Félicitations, c'est la fin de la procédure !! :clap: :partying_face: :tada:
&nbsp;
[^1]: Version 1.0.0 - 20/10/2023 - Cyril Bousmar

[//]:#
[pkginstaller]: <https://go.microsoft.com/fwlink/?linkid=853070>
[uclouvain]: <https://uclouvain.be/fr/index.html>
