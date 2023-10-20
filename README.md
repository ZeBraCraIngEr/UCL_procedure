# Installation Intune
### Etape 1: récupérer le programme d'installation
1. Se connecter à la session `sinfo`.
2. Brancher la clé USB contenant l'installateur de Intune[^1].
3. Transférer `CompanyPortal-Installer.pkg` sur le bureau de la machine.
4. Ejecter la clé USB.
5. Lancer l'installation.
6. Suppression du package d'installation.

> [!NOTE]
> L'installation devrait prendre moins d'une minute.

### Etape 2: Microsoft AutoUpdate
Se lance directement après l'installation du portail.
##### Machine Saint-Louis
1. Vérification des mises à jour des programmes de la `Suite Office`, de `Microsoft AutoUpdate` et du `Portail d'entreprise`.
2. Tout mettre à jour.
3. Fermer `Microsoft AutoUpdate`.

> ⚠️ IMPORTANT ⚠️
> Il est possible que certains liens/icones du `Dock` vers les applications de la `Suite Office` ne soient plus cliquables. Il faut les supprimer et les replacer.

> ℹ️ NOTE ℹ️
> La mise à jour prend environ deux minutes pour l'entièreté de la `Suite Office`.

##### Machine UCLouvain
TODO


### Etape 3: Portail d'entreprise
A lancer dans la session de l'utilisateur.
> ‼️ ATTENTION ‼️
> Il est impératif de redémarrer l'ordinateur avant de procéder aux étapes suivantes.

##### Machine Saint-Louis
1. Désactiver le `FileVault`.
2. Lancer le programme.
3. Connection de l'utilisateur.
4. Commencer la configuration de l'accès à L'UCLouvain (fidèle au document).
5. Vérifier le statut dans l'onglet du programme. Cliquer sur les 3 petits points et vérifier le statut.
6. Cliquer sur `voir plus` pour savoir quelle étape suivre pour changer le statut.
7. Activer le `FileVault`.

> ℹ️ NOTE ℹ️
> Il est possible qu'il faille vérifier plusieurs fois le statut. Dans le cas d'une nouvelle vérification, celui-ci prend un peu de temps avant de changer.

##### Machine UCLouvain
TODO

> ℹ️ NOTE ℹ️
> Intstallation du profil de management prend environs 10 minutes
> La vérification du status prend également 10 minutes.


[^1]: [Lien de téléchargement du fichier ][pkginstaller]

# Metadata
| Version | 1.0.0                                      |
|---------|--------------------------------------------|
| Date    | 20/10/2023                                 |
| Author  | Cyril Bousmar (cyril.bousmar@uclouvain.be) |

[//]:#
[pkginstaller]: <https://go.microsoft.com/fwlink/?linkid=853070>
