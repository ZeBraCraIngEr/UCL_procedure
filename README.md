# Installation Intune
Toutes ces étapes se font dans la session utilisateur.
> [!NOTE]
> Temps estimé de la procédure: 20 minutes.


### Etape 1: récupérer le programme d'installation
Il est possible de télécharger le programme directement via ce lien-ci[^1].

Alternativement, via une clé USB:
1. Brancher la clé USB contenant l'installateur de Intune.
2. Transférer `CompanyPortal-Installer.pkg` sur le bureau de la machine.
3. Ejecter la clé USB.

Une fois l'installation terminée, supprimer le package d'installation.

> [!NOTE]
> L'installation devrait prendre moins d'une minute.


### Etape 2: Microsoft AutoUpdate
Se lance directement après l'installation du portail.

##### Machine Saint-Louis
  
1. Vérification des mises à jour des programmes de la `Suite Office`, de `Microsoft AutoUpdate` et du `Portail d'entreprise`.
2. Tout mettre à jour.
3. Fermer `Microsoft AutoUpdate`.

> [!IMPORTANT]
> Il est possible que certains liens/icones du `Dock` vers les applications de la `Suite Office` ne soient plus cliquables. Il faut les supprimer et les replacer.

> [!NOTE]
> La mise à jour prend environ deux minutes pour l'entièreté de la `Suite Office`.


##### Machine UCLouvain
//TODO


### Etape 3: Portail d'entreprise

> [!WARNING]
> Il est impératif de redémarrer l'ordinateur avant de procéder aux étapes suivantes.

##### Machine Saint-Louis
1. Désactiver le `FileVault`.
```
Réglage Système > Confidentialité et sécurité > FileVault > Désactiver...
```
2. Lancer le programme.
3. Connection de l'utilisateur.
4. Commencer la configuration de l'accès à L'UCLouvain (fidèle au document).
   1. Continuer.
   2. Télécharger le profil.
   3. Cliquer sur la fenêtre de `réglages système` qui s'est ouverte.
   4. Double cliquer sur `Management Profile`.
   5. Installer.
5. Activer le chiffrement de l'appareil (alternativement, cliquer sur `Comment résoudre cela`).
```
Réglage Système > Confidentialité et sécurité > FileVault > Activer...
```

**Optionnel**
Dans le cas où l'État de la machine n'est pas `Conforme`:
1. Vérifier l'État (alternativement `⌥⌘S`).
   1. Cliquer sur les 3 petits points.
   2. Vérifier l'état.
3. Cliquer sur `voir plus` pour savoir quelle étape suivre pour changer l'État.


> [!NOTE]
> Il est possible qu'il faille vérifier plusieurs fois l'État. Dans le cas d'une nouvelle vérification, celui-ci prend un peu de temps avant de changer.

##### Machine UCLouvain
//TODO

> [!NOTE]
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
