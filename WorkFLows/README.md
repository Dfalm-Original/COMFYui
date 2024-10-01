### <a href="https://creativecommons.org/publicdomain/zero/1.0/"><img src="../images/CC-0-Violet.png" height="48"></a> Dfalm.<i>[Licence ](https://github.com/Dfalm-Original/COMFYui?tab=License-1-ov-file)</i><a href="https://fr.wikipedia.org/wiki/WTFPL"><img src="../images/WTFPL_logo.svg.png" height="48"></a>
# **-- WorkFlows --** 🚧🚧 WORK IN PROGRESS 🚧🚧
<hr>

#### A - Normalisation<br>B - WorkFlows<br>C - Misc<br>D - In Fine
----
## INTRODUCTION
Dans ce chaptire je vais mettre en place une "norme" commune : **Normalisation** pour les différents éléments<br>
Le premier élément est la Langue<br>
Pour distinguer le Français de l'Anglais je vais utiliser les icones suivantes :<br>
🔵⚪️🔴 En Français<br>
🌎🌍🌏 In English

Autre exemple trivial pour le Prompt Positif je vais utiliser la couleur "vert" et pour le prompt négatif la couleur "rouge"<br>
Couleur par défaut proposée par COMFYui<br>
Lorsque ces couleurs sont spécifiques je le préciserais avec le code couleurs

---
In this chapter I will set up a common "standard" aka **Normalisation** for the different elements<br>
The first element is the Language<br>
To distinguish French from English I will use the following icons:<br>
🔵⚪️🔴 In French<br>
🌎🌍🌏 In English<br>

Another trivial example for the Positive Prompt I will use the color "green" and for the negative prompt the color "red"<br>
Default color proposed by COMFYui<br>
When these colors are specific I will specify it with the color code

---
## A - Normalisation
VOIR LA PAGE AD HOC :  [README ](https://github.com/Dfalm-Original/COMFYui)
<br>
REFER TO AD HOC PAGE: [README ](https://github.com/Dfalm-Original/COMFYui)

-----
-----

## B - WorkFlow
🔵⚪️🔴 Dans ce chapitre je propose des WorkFlow, les liens des exemples, des images et autres...<br>🌎🌍🌏 In this chapter I propose WorkFlow, links to examples, images and others...
<hr>

0) Basic
#### BASIC-V1.00
<img src="Defaut/images/BASIC-V1.00.png" width="60%"><br>
🔵⚪️🔴  Remplace le workflow **"default"**<br>  🌎🌍🌏 Replaces **"default"** workflow<br>
<img src="Defaut/images/default.png" width="30%"><br>

### Differents elements / Elements & Nodes<br>
### 🔵⚪️🔴 Tous les elements communs aux workflow <br>🌎🌍🌏 Commons elements from differents workflow
- i) Nom du fichier💗 / Nom du repertoire💜 -- File name💗 / Path💜<br>  
<img src="Defaut/images/fichier-repertoire.png" width="50%"><br>
- ii) Reglages / Settings <br>
<img src="Defaut/images/Start-lora.png" width="50%"><br>

1 - Lora<br>
2 - CheckPoint<br>
3 - **No-VAE** - la VAE n'est pas exploitee ici = Aucune influence / inutile de la renseigner<br>
4 - Modele SD / SDXL<br>  
<img src="Defaut/images/sd-sdxl.png"><br>
5 - **No-Seed** la seed est exploitee plus bas **9️⃣** = Aucune influence / inutile de la renseigner<br>Seed is exploited below **9️⃣** = No influence / no need to setup up it<br>
6 - Parametrages 'classiques' d'un Ksampler / 'Classic' parameters of a Ksampler:<br>**steps + cfg + sampler + scheduler** ...<br>
7 - Largeur-Hauteur / Width-Eight<br>
8 - Batch Size<br>
9 - Seed **9️⃣** "**EveryWhere**"<br>

- iii) Prompts<br>
<img src="Defaut/images/prompts.png" width="50%"><br>
Vert = Positif / Green = Positive -- Rouge = Negatif / Red = Negative<br>

- iv) Control<br>
<img src="Defaut/images/control-nom.png" width="50%"><br>
Controle le nom du fichier / Check the file name : **Nom-Fichier+Checkpoint**

- v) Sauvegarde Type de fichier & metadata - Save File type & metadata<br>
<img src="Defaut/images/Ksampler-metadata.png" width="50%"><br>
💙Permet de sauvegarder les metadatas dans un fichier "txt" externe<br>
💙Allows you to save metadata in an external "txt" file<br>
💚Permet de sauvegarder en PNG - JPG - JPEG - WEBP<br>  💚Allows you to save in PNG - JPG - JPEG - WEBP<br><img src="Defaut/images/format-image.png"><br>

- vi) Preview image<br>
<img src="Defaut/images/preview-image.png" width="50%"><br>
🗃 Noir / Black

### 🔵⚪️🔴 Tous ces elements sont communs aux differents workflows<br>  
### 🌎🌍🌏 All these elements are common to the different workflows


<hr>
I) WorkFlows par defaut :

#### -A-  DEFAUT_MODEL-A_Text-2-Img+UPscalersV1.00
<img src="Defaut/images/DEFAUT_MODEL-A_Text-2-Img+UPscalersV1.00-notes.jpg" height="50%"><br>

🔵⚪️🔴 Permet de faire image-to-image avec des options de *prompts* et la possibilité d'*UPScaler* l'image rendue <br>- Par defaut les deux UPscalers sont désactivés<br><br>
## - U1💚/U2💜

Le premier Upscaler **U1💚** est un Upscaler "simple" qui agrandit l'image sans post-traitement<br>
Le second Upscaler **U2💜** est un 'refiner' il utilise un Ksampler, la seed, la VAE ...

## - **🧡ON/OFF**
L'interrupteur note **🧡ON/OFF** permet d'activer / desactiver les groupes :  U1💚/U2💜 en fonction des besoin d'UPScale

## - **⚪️L** (Lora)
L'option **⚪️L** permet d'ajouter un Lora lors de la generation de l'images<br>- Par defaut l'option est desactivee<br>

## - Sauvegarde / Save  
Sauvegarde / Save **🔴S** Ref : *0️⃣BASIC-V1.00

## **🔘P** (Prompt)
Prompt **🔘P**<br>
Il y a une option "Prompt" Classique / Batch & Vanille / Ameliore"  
Permet de choisir 4 Options<br>
1 Prompt Classique 'Vanille'<br>
2 Prompt Classique + Bonus = amélioré par une série de mots --**💗P**--<br>
3 Prompt Fichier "Batch"<br>
-> *1 Ligne = 1 Prompt*<br>
4 Prompt Fichier "Batch" + Bonus = amélioré par une série de mots --**💗P**--<br>
 -> *1 Ligne = 1 Prompt* + "Bonus amélioré"<br>


#### - Pour les UPScaler voir le chapitre idoine : <u>4️⃣ Upscalers </u>

<hr>

#### -B- DEFAUT_MODEL-B_Load-ImgZ+UPscalersV1.00
<img src="Defaut/images/DEFAUT_MODEL-B_Load-ImgZ+UPscalersV1.00.jpg" height="50%">
Permet d'Upscaler des images
<hr>

#### - C - DEFAUT_Text-2-Img+UPscalersV1.1.3-Valerie
<img src="Defaut/images/DEFAUT_MODEL-C_Text-2-Img+LoadImage+UPscalers.jpg" height="50%">


IV) Upscalers :
### Hires - Lent / Slow  
#### -- Desactive par defaut // Disabled by default
<img src="Defaut/images/upscaler-hires.png" height="50%">

#### 🔵⚪️🔴  Modifier le coeeficient multiplicateur <br>
-Par défaut (3)  
-- Choisir le model "Upscaler"<br>
#### ℹ️ Le coefficient multiplicateur est indépendant du choix du modele upscaler<br>
<u>EXEMPLE</u> : On peut utiliser le modele **8x** *_NMKD-Superscale_150000_G* avec un coefficient de **3** <br>
Inversement on peut utiliser un coefficient de 4 avec le modele **2x***Higurashi_v1_compact_270k*<br>

Il est préférable que le coefficient multiplicateur soit inferieur a celui du modele<br>  
On peut utiliser de cette manière des coefficient impair<br>

J'ai choisi arbitrairement d'utiliser des coefficients entiers : la primitive "MULTIPLICATEUR" ne permet pas les nombres a virgule ( Libre a vous de le modifier - La Dfalm.<i>[Licence ](https://github.com/Dfalm-Original/COMFYui?tab=License-1-ov-file)</i> le permet )<br>

## 📥 Telecharger des modeles / download models :
 [OPEN UPSCALER](https://openmodeldb.info) : https://openmodeldb.info

#### INSTALLER LES MODELES DANS / INSTALL MODELS IN

.\ComfyUI\Models\upscale_models

----
----

## C - Misc
Divers à déterminer

Ce **README** est une simple présentation<br>
( *Plus de détails dans un fichier spécifique* )


-----
-----

<font color="#001100">
<h1 id="attention"> A - NORMALISATION  🗃️ </h1></font>

## Permier / First :  Langue / Language
<h1>🔵⚪️🔴 En Français</h1>
<h1>🌎🌍🌏 In English</h1>

----
- ## PREVIEW
A Gauche 🔵⚪️🔴 En Français // In Right 🌎🌍🌏 In English<br>
In Left 🔵⚪️🔴 In French // A Droite 🌎🌍🌏 En Anglais
<br>
[ CLICK TO DOWNLOAD PNG WORKFLOW ]<br>
<a href="../images/NORME.png"><img src="../images/preview.png"></a>

----

----

<h1>B - WORKFLOW</h1>
Coming soon...


----

<h1>C - MISC</h1>

### Conseil / Advice
🔵⚪️🔴 Pour la preview image j'utilise egalement la couleur noire et uniquement "PREVIEW IMAGE"<br>
Je conseille d'utiliser les "SD" Prompt generator et Prompt Saver 1️⃣ pour diverses raisons

🌎🌍🌏 For the preview image I also use black color and only "PREVIEW IMAGE"<br>
I recommend using the "SD" Prompt generator and Prompt Saver 1️⃣ for various reasons

### BUGS imprevu / unexpected
🔵⚪️🔴 Pour une raison non determinee il semble y avoir des problemes de performances avec "SD Parameter Generator" 1️⃣<br>
Une astuce consiste a ne pas utiliser la "seed" du noeud, j'utilise (de preference) "Seed Everywhere" 2️⃣

🌎🌍🌏 For some reason there seems to be performance issues with "SD Parameter Generator" 1️⃣<br>
A tip is to not use the node "seed". I use (preferably) "Seed Everywhere" 2️⃣<br>
<br>
Couleur / Color : 255 - 150 - 30<br>
<img src="../images/seed-everywhere.png">

1️⃣ SD Prompt Reader Node : https://github.com/receyuki/comfyui-prompt-reader-node<br>
2️⃣ cg-use-everywhere : https://github.com/chrisgoringe/cg-use-everywhere

# BUG
🔵⚪️🔴  <u>Bug trivial</u> : parfois la VAE ou la Seed ou les deux sont "déconnectées"<br>
Le noeud "Everywhere" 2️⃣ ne transmet pas la VAE/seed

🌎🌍🌏 <u>Trivial bug</u>: sometimes VAE or Seed or both are "disconnected"<br>
The "Everywhere" node 2️⃣ does not transmit VAE/seed

<img src="../images/BUG-everywhere-BUG.png" width="30%">


## RESOLUTION : 🔵⚪️🔴  / 🌎🌍🌏
### [F5] rafraichissement du navigateur<br>[F5] browser refresh


Puis vérifier que les liens sont actifs / Then check that the links are active :
<img src="../images/Everywhere-Seed.png"><br>

<img src="../images/everywhere-VAE.png"><br>

2️⃣ cg-use-everywhere : https://github.com/chrisgoringe/cg-use-everywhere

---
<h1>D - In Fine</h1>

## Liens Utiles - Links usefull :
VIEILLES VERSIONS / OLDS VERSION  <b>COMFYui</b> :
https://github.com/comfyanonymous/ComfyUI/tags<br>
INDISPENSABLE : <b>COMFYui Manger</b> : https://github.com/ltdrdata/ComfyUI-Manager

### Beginner’s Guide to ComfyUI
By Andrew : https://stable-diffusion-art.com/comfyui/
### Unlock the Power of ComfyUI: A Beginner's Guide with Hands-On Practice
And "RUN WORKFLOW" online : https://www.runcomfy.com/tutorials/comfyui-beginners-guide
### ComfyUI WIKI
Your Ultimate Companion for Mastering Stable Diffusion ComfyUI : https://comfyui-wiki.com

----
### Credit
ComfyUI/[ComfyUI](https://github.com/comfyanonymous/ComfyUI) - A powerful and modular stable diffusion GUI.

**And, for all ComfyUI custom node developers**

🙏 Un grand merci au / Special Thanks to the  : <b>GOAT [ltdrdata](https://github.com/ltdrdata)</b><br>
[ComfyUI ltdrdata:FORK](https://github.com/comfyanonymous/ComfyUI)<br>
[ComfyUI-Manager](https://github.com/ltdrdata/ComfyUI-Manager)<br>
[ComfyUI-Impact-Pack](https://github.com/ltdrdata/ComfyUI-Impact-Pack)<br>
[ComfyUI-Inspire-Pack](https://github.com/ltdrdata/ComfyUI-Inspire-Pack)<br>
[ComfyUI-extension-tutorials](https://github.com/ltdrdata/ComfyUI-extension-tutorials)

----
----
### <a href="https://creativecommons.org/publicdomain/zero/1.0/"><img src="../images/CC-0-Violet.png" height="64"></a> Dfalm.<i>[Licence ](https://github.com/Dfalm-Original/COMFYui?tab=License-1-ov-file)</i><a href="https://fr.wikipedia.org/wiki/WTFPL"><img src="../images/WTFPL_logo.svg.png" height="64"></a>
<p><img alt="Github" src="http://Dfalm.fr/ComfyUI/Git-Logo-Dfalm.png" width="48"> github : <a href="https://github.com/Dfalm-Original/COMFYui" target="_blank">https://github.com/Dfalm-Original/COMFYui</a></p>
<p><img alt="Youtube" src="http://Dfalm.fr/ComfyUI/youtube+logoToon.png" width="48"> Youtube : <a href="https://www.youtube.com/@Dfalm" target="_blank">https://www.youtube.com/@Dfalm</a></p>
