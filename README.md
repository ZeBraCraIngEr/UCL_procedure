# Installation Intune[^1]

![UCLouvain logo](https://cdn.uclouvain.be/groups/cms-editors-arec/charte-graphique-uclouvain/UCLouvain_Logo_Pos_CMJN.png?itok=0Vz8FOqj)

Procédure pour passer les machines du site Saint-Louis Bruxelles sous UCLouvain. Elle se fait entièrement dans la session utilisateur.

> [!NOTE]
> :hourglass_flowing_sand: Temps estimé pour l'ensemble de la procédure: 20 minutes. Nous recommandons de vous préparer un petit café :coffee: ou thé :tea:.

> [!WARNING]
> Ce follow through est **uniquement destiné** aux membres du personnel de l'[UCLouvain][uclouvain] possèdant un Macbook.
> 
> :uk:/:us: This follow through process **only addresses to** [UCLouvain][uclouvain] members that own a Macbook.

-----------------
### Etape 1: récupérer et installer le programme d'installation
Télécharger le programme directement via [ce lien-ci][pkginstaller].

**Installation :**
1. Accepter la licence.
2. Cliquer sur `Installer`.
3. Valider les identifiants utilisateur machine :computer:.
4. Accepter l'accès aux fichiers en cliquant sur `OK`.
5. Cliquer sur `Fermer`.
6. Supprimer l'installeur en cliquant `Placer dans la corbeille`.

> [!NOTE]
> :hourglass_flowing_sand: L'installation devrait prendre moins d'une minute.

-----------------
### Etape 2: Microsoft AutoUpdate
Se lance directement après l'installation du portail. Appuyer sur `OK`.

<details>
<summary>Machine Saint-Louis</summary>

1. Cliquer sur la flèche :arrow_down_small: pour déployer et voir toutes les applications.
2. Vérification des mises à jour des programmes de la `Suite Office`, de `Microsoft AutoUpdate` et du `Portail d'entreprise`.
3. Cliquer sur `Tout mettre à jour`.
4. Fermer `Microsoft AutoUpdate`.

> [!IMPORTANT]
> Il est possible que certains liens/icones du `Dock` vers les applications de la `Suite Office` ne soient plus cliquables. Il faut les supprimer du `Dock` et les replacer.

> [!NOTE]
> :hourglass_flowing_sand: La mise à jour prend environ deux minutes pour l'entièreté de la `Suite Office`.
</details>

<details>
<summary>Machine UCLouvain</summary>

1. Cliquer sur la flèche :arrow_down_small: pour déployer et voir toutes les applications.
2. Rechercher les mises à jours.
3. Cliquer sur `Tout mettre à jour`.
4. Fermer `Microsoft AutoUpdate`.

> [!NOTE]
> La `Suite Office` n'est pas encore disponible.
</details>

-----------------
### Etape 3: Portail d'entreprise
Gestion de la machine, sécurité et cryptage des données.

<details>
<summary>Machine Saint-Louis</summary>

1. Désactiver le `FileVault` en suivant:
   ```
   Réglage Système > Confidentialité et sécurité > FileVault > Désactiver...
   ```
2. Lancer l'application `Portail d'entreprise`.
3. Connection de l'utilisateur avec les identifiants UCLouvain :bust_in_silhouette:.
4. Commencer la configuration de l'accès à L'UCLouvain.
5. Continuer.
6. Cliquer sur `Télécharger le profil`.
   1. Cliquer sur la fenêtre de `Réglages système` qui s'est ouverte.
   2. Double cliquer sur `Management Profile`.
   3. Installer en renseignant les identifiants machine.
   4. Fermer la fenêtre de `Réglages système`.
7. Attendre les vérifications des paramètres système.

> [!NOTE]
> > :hourglass_flowing_sand: Intstallation du profil de management peut prendre jusqu'à 10 minutes. De même que la vérification de l'État.
> Il est possible qu'il faille relancer la procédure une seconde fois. Pas de panique, ça ne devrait pas prendre autant de temps.

8.Terminer
9. Cliquer sur `En savoir plus` pour vérifier que seul le chiffrement de l'appareil soit demandé, puis `fermer`.
10. Modifier le mot de passe machine :computer: (Possibilité de reprendre le même pour autant qu'il est validé par les exigences de l'UCLouvain) en suivant:
   ```
   Réglage Système > Touch ID et mot de passe > Modifier...
   ```
11. Activer le chiffrement de l'appareil en suivant:
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

> **Optionnel**
> Dans le cas où l'État de la machine n'est pas `Conforme`:
> 1. Vérifier l'État (alternativement `⌥⌘S`).
>    1. Cliquer sur les 3 petits points.
>    2. Vérifier l'état.
> 2. Cliquer sur `voir plus` pour savoir quelle étape suivre pour changer l'État.

<details>
<summary>Machine UCLouvain</summary>
   
1. Lancer l'application `Portail d'entreprise`.
2. Cliquer sur `Commencer`pour configurer l'accès de l'UCLouvain.
3. Continuer.
4. Cliquer sur `Télécharger le profil`.
   1. Cliquer sur la fenêtre de `Réglages système` qui s'est ouverte.
   2. Double cliquer sur `Management Profile`.
   3. Installer en renseignant les identifiants machine.
   4. Fermer la fenêtre de `Réglages système`.
5. Terminer.
6. Modifier le mot de passe machine :computer: (Possibilité de reprendre le même pour autant qu'il est validé par les exigences de l'UCLouvain).
   ```
   Réglage Système > Touch ID et mot de passe > Modifier...
   ```
7. Activer le chiffrement de l'appareil.
   ```
   Réglage Système > Confidentialité et sécurité > FileVault > Activer...
   ```
8. Cliquer sur continuer. La création du FileVault se lance.
9. Sur `Portail d'entreprise`, cliquer sur `En savoir plus`, puis `Réessayer`. La vérification de l'État se lance.
10. Désactiver la collecte des données de Microsoft:
   ```
   Portail d'entreprise > Réglages... > Décocher "Authorisez Microsoft à collecter des données d'utilisation.".
   ```
11. Quitter l'application `Portail d'entreprise`.

> [!NOTE]
> :hourglass_flowing_sand: La vérification du status peut prendre jusqu'à 10 minutes.
</details>

-----------------
### Etape 4: Centre de gestion des logiciels
Permettra d'accéder à toutes les applications mises à disposition par l'UCLouvain via l'onglet `Logiciel`.

<details>
<summary>Machine Saint-Louis</summary>

- [ ] TODO
</details>

<details>
<summary>Machine UCLouvain</summary>
   
1. Lancer l'application `Centre de gestion des logiciels`.
2. Vérification des mises à jour automatique des logiciels.
3. Cliquer sur `Tout mettre à jour`.
4. Quitter l'application`Centre de gestion des logiciels`.
</details>


-----------------
### Etape 5: Inscrire la machine pour l'UCLouvain

1. Lancer `Munki UCLouvain From`.
2. Entrer le libellé de l'étiquette de la manière suivante:
   ```latex
   ABXX-XXX
   ```
   où X sont des chiffres.

> [!WARNING]
> Pour l'étiquette, remarquez l'utilisation du "-" et non du ".".
   
3. Entrer l'email utilisateur UCLouvain :bust_in_silhouette:.
4. Sélectionner le secteur.
5. Valider avec les identifiants machine :computer:.
6. Cliquer sur `OK`.

> [!NOTE]
> :hourglass_flowing_sand: Cela devrait prendre moins d'une minute.

-----------------
### Etape 6: Finalisation
Félicitations, c'est la fin de la procédure !! :clap::partying_face::tada:
&nbsp;
[^1]: Version 1.0.0 - 20/10/2023 - Cyril Bousmar

[//]:#
[pkginstaller]: <https://go.microsoft.com/fwlink/?linkid=853070>
[uclouvain]: <https://uclouvain.be/fr/index.html>
