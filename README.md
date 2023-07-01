![img](./macos.png)
# 👋 Bienvenue sur macOS

## ➡️ Étapes après l'installation
- Télécharger **Pages**, **Numbers**, **Keynote**, **iMovie**, **GarageBand**, **Xcode**
- Télécharger les mises à niveau **macOS**
- Effectuer les commandes qui suivent sur [cette partie](#commandes)
- Télécharger les [fonds d'écrans](https://enioaiello.github.io/background-library)

## 🤖 Commandes
Réinitialiser le Dock
```
defaults delete com.apple.dock; killall Dock
```
Réinitiliaser le Launchpad
```
defaults write com.apple.dock ResetLaunchPad -bool true; killall Dock
```

## 🎈 Installer les logiciels de bases
### ✨ Logiciel de base

> Si vous avez une installation fraîche de macOS récente, téléchargez les logiciels suivants via le **Mac App Store**.

📥 **Logiciels a installer**
- Pages
- Numbers
- Keynote
- iMovie
- GarageBand
- Xcode

> Si vous avez un système d'exploitation qui n'est plus compatible avec les dernières mises à jour d'applications, utilisez les prochains liens.

📥 **Logiciels à installés (avec leurs liens)**

- Pages [télécharger la version pour 10.13.6 et antérieur ici](https://drive.google.com/file/d/1OGG6yHOIAsZZYPcR434KsZ0qzmvJYwaq/view?usp=sharing)
- Numbers [télécharger la version pour 10.13.6 et antérieur ici](https://drive.google.com/file/d/1OGG6yHOIAsZZYPcR434KsZ0qzmvJYwaq/view?usp=sharing)
- Keynote [télécharger la version pour 10.13.6 et antérieur ici](https://drive.google.com/file/d/1OGG6yHOIAsZZYPcR434KsZ0qzmvJYwaq/view?usp=sharing)
- iMovie [télécharger la version pour 10.13.6 et antérieur ici](http://www.mediafire.com/file/1q5cob8ghtglii0/Apple+iMovie+v10.1.6+Final+Patched.zip/file)
- Garageband [télécharger la version pour 10.13.6 et antérieur ici](https://garageband.fr.malavida.com/mac/)
- Xcode [télécharger la version pour 10.13.6 et antérieur ici](https://developer.apple.com/xcode/resources/)

### ✅ Logiciels recommandés

Utiliser [macapps](https://macapps.link) pour télécharger tout ces logiciels.\
Si vous avez besoins d'Office, téléchargez la dernière version compatible pour votre **macOS** sur [MacAdmin](https://macadmins.software/), une fois installé, ne l'exécutez pas. Utilisez ensuite [ce patch]([https://github.com/alsyundawy/Microsoft-Office-For-MacOS](https://gist.github.com/zthxxx/9ddc171d00df98cbf8b4b0d8469ce90a)), prenez la version adaptée à votre système. Si vous avez un système trop ancien, cliquez [ici](#installer-les-anciennes-versions-des-logiciels).

### 📥 Installer les anciennes versions des logiciels
> Cette partie n'est pas encore complète, cependant, vous pouvez déjà commencer à lire !

Si c'est un logiciel dit **FOSS**, continuez. Sinon passez cette étape.\
Accédez à [FOSSHUB](https://www.fosshub.com/) et sélectionnez votre **logiciel**. Que ce soit via la catégorie de votre logiciel ou bien via la barre de recherche. Ensuite, une fois votre logiciel sélectionné, sélectionnez votre système d'exploitation (ici macOS), votre type de processeur (généralement sur les Macs il s'agit d'architecture **x86** ou **ARM64**). Puis sélectionnez la dernière version compatible avec votre système d'exploitation.
> Si vous n'êtes pas sûr de votre système d'exploitation actuelle, allez dans le menu pomme et sélectionnez l'option **à propos de ce Mac**, généralement il s'agit du premier élément en partant du haut.

> Si vous ne savez pas quelles versions prendre pour votre système d'exploitation, cherchez simplement `[nom application] last version for [votre version de macos]`.

## 🛡️ Désactiver la protection
Si un programme est détecté comme "endommagé" par macOS, exécutez simplement cette commande :
```
xattr -cr [emplacement de l'application ou glissez et déposez la simplement sur la commande]
```

## 🔗 Télécharger les fonds d'écrans
> Recommandation : Créez un dossier nommé "Fonds d'écrans" dans votre dossier personnel ou dans votre dossier **Images**. Ensuite déposez le dossier dans vos préférences systèmes afin de simplifier le chagement de fonds d'écrans.
Téléchargez  les fonds d'écrans [ici](https://enioaiello.github.io/background-library). Appliquez celui de votre choix.

## 🎨 Icônes Big Sur
Si vous êtes sur macOS 11 et suppérieur, vous aurez sans doutes besoins de changer certaines icônes d'**anciens logiciels** qui sont sans doutes bloqués sur des versions ultérieures.\
Voici le lien pour changer les icônes : [https://macosicons.com/](https://macosicons.com/)\
Une fois votre icône téléchargée, ouvrez la avec **Aperçu** puis copiez l'icône.\
Et pour finir, ouvrez les informations de votre application (avec le raccourcis : **Cmd + I**) et cliquez sur l'icône de l'application puis collez la avec **Cmd + V**.

## 💽 Recevoir des mises à jour sur les anciens Mac
Vous pouvez utiliser [OpenCore Legacy Patcher](https://github.com/dortania/OpenCore-Legacy-Patcher) pour patcher d'anciens Macs enfin de pouvoir utiliser **Big Sur** et ultérieur sur de anciens Macs.
> ⚠️ **Les performances ne sont pas optimales sur ce patch pour certains Macs, comme par exemple les drivers vidéos de l'iMac 2011 (signalé par kik07l)**
### 💻 Mac pour commencer

Si vous voulez un Mac pas trop cher et qui fait encore très bien le travail, j'utilises un **MacBook Pro mid2012** entièrement patché sous **Ventura 13.4.1** avec **OpenCore Legacy Patcher** et cela marche très bien, tout est pris en charge ! 

### 🔰 Recommandations pour tout faire tourner
- Au moins 8 Go de RAM
- Un SSD de 256 Go
- Un processeur Intel Core i5
