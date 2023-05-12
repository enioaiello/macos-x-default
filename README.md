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

- Pages [télécharger la version pour 10.13.6 est antérieur ici](https://drive.google.com/file/d/1OGG6yHOIAsZZYPcR434KsZ0qzmvJYwaq/view?usp=sharing)
- Numbers [télécharger la version pour 10.13.6 est antérieur ici](https://drive.google.com/file/d/1OGG6yHOIAsZZYPcR434KsZ0qzmvJYwaq/view?usp=sharing)
- Keynote [télécharger la version pour 10.13.6 est antérieur ici](https://drive.google.com/file/d/1OGG6yHOIAsZZYPcR434KsZ0qzmvJYwaq/view?usp=sharing)
- iMovie [télécharger la version pour 10.13.6 est antérieur ici](http://www.mediafire.com/file/1q5cob8ghtglii0/Apple+iMovie+v10.1.6+Final+Patched.zip/file)
- Garageband [télécharger la version pour 10.13.6 est antérieur ici](https://garageband.fr.malavida.com/mac/)
- Xcode [télécharger la version pour 10.13.6 est antérieur ici](https://developer.apple.com/xcode/resources/)

### ✅ Logiciels recommandés

Utiliser [macapps](https://macapps.link) pour télécharger tout ces logiciels.\
Si vous avez besoins d'Office, téléchargez la dernière version compatible pour votre **macOS** sur [MacAdmin](https://macadmins.software/), une fois installé, ne l'exécutez pas. Utilisez ensuite [ce patch](https://github.com/alsyundawy/Microsoft-Office-For-MacOS), prenez la version adaptée à votre système. Si vous avez un système trop ancien, cliquez [ici](#installer-les-anciennes-versions-des-logiciels).

### 📥 Installer les anciennes versions des logiciels
> Cette partie n'est pas encore complète, cependant, vous pouvez déjà commencer à lire !

Si c'est un logiciel dit **FOSS**, continuez. Sinon passez cette étape.\
Accédez à [FOSSHUB](https://www.fosshub.com/) et sélectionnez votre **logiciel**. Que ce soit via la catégorie de votre logiciel ou bien via la barre de recherche. Ensuite, une fois votre logiciel sélectionné, sélectionnez votre système d'exploitation (ici macOS), votre type de processeur (généralement sur les Macs il s'agit d'architecture **x86** ou **ARM64**). Puis sélectionnez la dernière version compatible avec votre système d'exploitation.
> Si vous n'êtes pas sûr de votre système d'exploitation actuelle, allez dans le menu pomme et sélectionnez l'option **à propos de ce Mac**, généralement il s'agit du premier élément en partant du haut.

> Si vous ne savez pas quelles versions prendre pour votre système d'exploitation, cherchez simplement `[nom application] last version for [votre version de macos]`.

## Désactiver la protection
Si un programme est détecté comme "endommagé" par macOS, exécutez simplement cette commande :
```
xattr -cr [emplacement de l'application ou glissez et déposez la simplement sur la commande]
```

## Télécharger les fonds d'écrans
> Recommandation : Créez un dossier nommé "Fonds d'écrans" dans votre dossier personnel ou dans votre dossier **Images**. Ensuite déposez le dossier dans vos préférences systèmes afin de simplifier le chagement de fonds d'écrans.

Téléchargez les fonds d'écrans [ici](https://enioaiello.github.io/background-library). Appliquez celui de votre choix.
