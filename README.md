# curseforge-instance-fabric-sodium-default

## **Introduction**

### **Qu'est-ce que c'est ?**

Ce dépôt contient une instance ***CurseForge*** compatible avec ***MultiMC*** basée sur la [liste de mod](#liste-des-mods) spécialement préparée par nos soins et adaptée au jeu sur Herobrine.fr.

## **Installation**

***MultiMC*** et ***CurseForge*** sont des *launchers alternatifs* au launcher Minecraft Vanilla. Ils sont rapides à installer et ont tous deux la plupart des des fonctionnalités du launcher original. Les tutoriels suivants montrent comment installer l'instance sur ces deux lauchers.

Télécharger  la dernière [release](https://github.com/HB-Modding-Crew/curseforge-instance-fabric-sodium-default/releases) de l'instance.

![Alt text](images/instance_download.png?raw=true "Créer une profil")

### **CurseForge**

***CurseForge*** est uniquement adressé *aux gens qui jouent avec des mods* et permet de rechercher des mods directement dans le launcher pour les ajouter à son instance en un clic.

Vous devez avoir installé ***CurseForge*** au préalable. Ca se passe [ici](https://download.curseforge.com).

Pour installer l'instance avec ***CurseForge***:

1) Ouvrir ***CurseForge***
2) Appuyer sur "Créer un profile" en haut à droite de la fenêtre

![Alt text](images/curse_forge_install_new_profile.png?raw=true "Créer une profil")

3) Appuyer sur "import" et sélectionner l'instance téléchargée.

![Alt text](images/curse_forge_install_import_profile.png?raw=true "Créer une profil")

### **MultiMC**

***MultiMC*** permet d'avoir plusieurs *instances plus customisables* que CurseForge, pas obligatoirement avec des mods. Pour la gestion des mods, ***MultiMC*** offre l'avantage laisser l'utilisateur désactiver un mod sans avoir à le supprimer.

Vous devez avoir installé ***MulticMC*** au préalable. Ca se passe [ici](https://multimc.org).

Pour installer l'instance avec ***MultiMC***:

1) Ouvrir ***MultiMC***
2) Créer une instance

![Alt text](images/mmc_install_new_profile.png?raw=true "Créer une profil")

3) Importer un zip et sélctionner l'instance téléchargée

![Alt text](images/mmc_install_import_profile.png?raw=true "Créer une profil")

---
## **Options de jeu alternatives**

### **Version optifine**

Historiquement, Optifine à toujours été obligatoire sur Herobrine.fr, et cela pour faire fonctionner son pack de texture.

Sodium est aujourd'hui une alternative plus performante si on ajoute d'autre mods pour palier aux manques de certaines fonctionalités.

Sodium offre de meilleurs performances, mais une instance avec les mêmes mods fonctionnant avec optifine est disopible: 
- [Herobrine CurseForge et MultiMC Fabric Optifine](https://github.com/HB-Modding-Crew/curseforge-instance-fabric-optifine-default#curseforge-instance-fabric-optifine-default)

### **Launcher vanilla**

Vous pouvez aussi télécharger les mods (voir dans la  [liste de mod](#liste-des-mods)) à la main pour utiliser le launcher minecraft vanilla.

ATTENTION: Certains mods personalisés pour (Ex: ChatHead) et des Pack de Ressource personnalisés ne sont pour l'instant trouvables que dans l'instance. Un lien sera bientôt ajouté pour les télécharger ici.

ATTENTION BIS: Le support pour l'installation manuelle ne sera pas prioritaire. Vous pouvez tout de même signalé tout bug que vous trouverez.

---
## **Liste des mods**

### **Seulement dans l'instance sodium:**

Mods obligatoires pour jouer sur Herobrine.fr avec Sodium:

| Mod | Description | Problèmes connu |
|:---:|:---:|:---:|
| [Sodium](https://www.curseforge.com/minecraft/mc-mods/sodium) | Mod de performances. | Demande les mods listés ci-après pour fonctionner avec le ressource pack d'Herobrine.fr et plus généralement, avoir les mêmes customisations de rendu qu'Optifine. |
| [Indium](https://www.curseforge.com/minecraft/mc-mods/indium) | Add-on pour Sodium qui permet à d'autres mods qui modifient le rendu de fonctionner sans incompatibilité. |  |
| [CIT Resewn](https://www.curseforge.com/minecraft/mc-mods/cit-resewn) | Implémente la fonctionnalité Custom Item Texture de Optifine pour faire fonctionner le ressource pack. |  |
| [Iris Shaders](https://www.curseforge.com/minecraft/mc-mods/irisshaders) | Permet d'utiliser des shaders faits pour Optifine avec Sodium. | Certains shaders ne fonctionnent pas encore. |
| [Continuity](https://www.curseforge.com/minecraft/mc-mods/continuity) | Implémente la fonctionnalité Connected Texture Mapping pour faire fonctionner le ressource pack. |  |
| [LambDynamicLights](https://www.curseforge.com/minecraft/mc-mods/lambdynamiclights) | Ajoute les lumières dynamiques à la manière d'optifine. |  |
| [Ok Zoomer](https://www.curseforge.com/minecraft/mc-mods/ok-zoomer) | Permet de zoomer comme avec optifine. Le zoom est cependant customisable. |  |

### **Général:**

| Mod | Description | Problèmes connu |
|:---:|:---:|:---:|
| [Fabric API](https://www.curseforge.com/minecraft/mc-mods/fabric-api) | Utilitaire pour le fonctionnement de beaucoup de mods. |  |
| [Better Ping Display](https://www.curseforge.com/minecraft/mc-mods/better-ping-display) | Permet d'afficher le ping des différents joueurs en ligne sous forme numérique. |  |
| [Better F3](https://www.curseforge.com/minecraft/mc-mods/betterf3) | Permet de customiser l'interface F3. |  |
| [Bobby](https://www.curseforge.com/minecraft/mc-mods/bobby) | Permet de voir plus loin que la render distance maximum du serveur. |  |
| [CameraOverhaul](https://www.curseforge.com/minecraft/mc-mods/cameraoverhaul) | Permet d'avoir de légers effets de caméra rendant plus réalistes les mouvements de test. |  |
| [Cloth Config API](https://www.curseforge.com/minecraft/mc-mods/cloth-config-forge) | Bibliothèque permettant à certains mods d'avoir un menu de configuration. |  |
| [CustomSkinLoader](https://www.curseforge.com/minecraft/mc-mods/customskinloader) | Permet de voir les skins transparents. |  |
| [Enhanced Block Entities](https://www.curseforge.com/minecraft/mc-mods/enhanced-block-entities) | Améliore les certains blocks comme les coffres. On peut les voir de plus loin et ils font moins laguer. |  |
| [Entity Culling](https://www.curseforge.com/minecraft/mc-mods/entityculling) | Permet d'optimiser le rendu en ignorant les zones les blocks que le joueur ne voit pas. |  |
| [First-person Model](https://www.curseforge.com/minecraft/mc-mods/first-person-model) | Permet de s'immerger en se voyant à la première personne. |  |
| [Item Model Fix](https://www.curseforge.com/minecraft/mc-mods/item-model-fix) | Améliore l'apparence des items. |  |
| [Mod Menu](https://www.curseforge.com/minecraft/mc-mods/modmenu) | Permet de lister l'ensemble des mods chargés par le jeu et d'accéder à d'éventuels paramètres. |  |
| [Not Enought Animations](https://www.curseforge.com/minecraft/mc-mods/not-enough-animations) | Ajoute ou améliore certaines animations du joueur (Ex: Ramer, recharger l'arbalète...). | Problèmes de texture pour certains items tenus en main en première personne (Ex: Grande torche avec 2 pixels transparents). |
| [Perspective Mod Redux](https://www.curseforge.com/minecraft/mc-mods/perspective-mod-redux) | Permet de passer en mode troisième personne et de faire des rotations sans que la tête du personnage bouge. |  |
| [Presence Footstep](https://www.curseforge.com/minecraft/mc-mods/presence-footsteps) | Les sons des pas sont améliorés, customisables. |  |
| [TRansliterationLib](https://www.curseforge.com/minecraft/mc-mods/transliterationlib) | Permet de faire fonctionner Cloth Config API. |  |
| Chat head HB | Une version modifiée du mod Chat Head adaptée à Herobrine.fr. Permet de voir la tête du personnage qui a parlé avant sa ligne dans le chat. Bientôt dispobible en téléchargement individuel. |  |
| [Dynamic Sound Filters](https://www.curseforge.com/minecraft/mc-mods/dynamic-sound-filters) | Rend les sons du jeu plus réaliste en ajoutant de la réverberation. | La réverberation peut paraitre trop présente dans certains cas. Cela est réglable grâce au mod menu. |
| [Mythickeys](https://github.com/ASangarin/MythicKeys/releases) | Mod pour interagir avec le serveur et pouvoir lui envoyer des inputs. Permet de changer la touche de double saut sur Herobrine.fr. |  |