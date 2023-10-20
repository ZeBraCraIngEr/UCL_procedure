# Installation Intune[^1]

![UCLouvain logo](https://cdn.uclouvain.be/groups/cms-editors-arec/charte-graphique-uclouvain/UCLouvain_Logo_Pos_CMJN.png?itok=0Vz8FOqj)

Procédure pour passer les machines du site Saint-Louis Bruxelles sous UCLouvain. Elle se fait entièrement dans la session utilisateur.

> [!NOTE]
> Temps estimé pour l'ensemble de la procédure: 20 minutes. Nous recommandons de vous préparer un petit café :coffee: ou thé :tea:.

-----------------
### Etape 1: récupérer et installer le programme d'installation
Télécharger le programme directement via [ce lien-ci][pkginstaller].

> [!WARNING]
> **Pour les machines `Saint-Louis`** Il est impératif de désinstaller le `Centre de gestion de logiciels` et de redémarrer l'ordinateur avant de procéder plus loin.

**Installation :**
1. Accepter la licence.
2. Cliquer sur `Installer`.
3. Valider les identifiants utilisateur machine :computer:.
4. Accepter l'accès aux fichiers en cliquant sur `OK`.
5. Fermer
6. Supprimer l'installeur en cliquant `Placer dans la corbeille`.

> [!NOTE]
> L'installation devrait prendre moins d'une minute.

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
> La mise à jour prend environ deux minutes pour l'entièreté de la `Suite Office`.
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
2. Lancer le programme `Portail d'entreprise`.
3. Connection de l'utilisateur avec les identifiants UCLouvain :bust_in_silhouette:.
4. Commencer la configuration de l'accès à L'UCLouvain.
5. Continuer.
6. Cliquer sur `Télécharger le profil`.
   1. Cliquer sur la fenêtre de `Réglages système` qui s'est ouverte.
   2. Double cliquer sur `Management Profile`.
   3. Installer en renseignant les identifiants machine.
   4. Fermer la fenêtre de `Réglages système`.
7.Terminer
8. Cliquer sur `En savoir plus` pour vérifier que seul le chiffrement de l'appareil soit demandé, puis `fermer`.
9. Modifier le mot de passe machine :computer: (Possibilité de reprendre le même pour autant qu'il est validé par les exigences de l'UCLouvain) en suivant:
   ```
   Réglage Système > Touch ID et mot de passe > Modifier...
   ```
11. Activer le chiffrement de l'appareil en suivant:
   ```
   Réglage Système > Confidentialité et sécurité > FileVault > Activer...
   ```
11. Cliquer sur `continuer`. La création du FileVault se lance.
11. Sur `Portail d'entreprise`, cliquer sur `En savoir plus`, puis `Réessayer`. La vérification de l'État se lance.
12. Désactiver la collecte des données de Microsoft en suivant:
   ```
   Portail d'entreprise > Réglages... > Décocher "Authorisez Microsoft à collecter des données d'utilisation.".
   ```

> **Optionnel**
> Dans le cas où l'État de la machine n'est pas `Conforme`:
> 1. Vérifier l'État (alternativement `⌥⌘S`).
>    1. Cliquer sur les 3 petits points.
>    2. Vérifier l'état.
> 2. Cliquer sur `voir plus` pour savoir quelle étape suivre pour changer l'État.

> [!NOTE]
> Il est possible qu'il faille vérifier plusieurs fois l'État. Dans le cas d'une nouvelle vérification, celui-ci prend un peu de temps avant de changer.

> [!NOTE]
> Intstallation du profil de management peut prendre jusqu'à 10 minutes. De même que la vérification de l'État.
</details>

<details>
<summary>Machine UCLouvain</summary>
   
1. Lancer le programme `Portail d'entreprise`.
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

> [!NOTE]
> La vérification du status peut prendre jusqu'à 10 minutes.
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
   
1. Lancer l'application.
2. Vérification et mise à jour automatique des logiciels.
3. Cliquer sur `Tout mettre à jour`.
</details>


-----------------
### Etape 5: Inscrire la machine pour l'UCLouvain

1. Lancer `Munki UCLouvain From`.


-----------------
### Etape 6: Finalisation
Félicitations, c'est la fin de la procédure !! :clap::partying_face::tada:
&nbsp;
[^1]: 
      | Version | 1.0.0                                      |
      |---------|--------------------------------------------|
      | Date    | 20/10/2023                                 |
      | Author  | Cyril Bousmar (cyril.bousmar@uclouvain.be) |

[//]:#
[pkginstaller]: <https://go.microsoft.com/fwlink/?linkid=853070>
