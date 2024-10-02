### <a href="https://creativecommons.org/publicdomain/zero/1.0/"><img src="../images/CC-0-Violet.png" height="48"></a> Dfalm.<i>[Licence ](https://github.com/Dfalm-Original/COMFYui?tab=License-1-ov-file)</i><a href="https://fr.wikipedia.org/wiki/WTFPL"><img src="../images/WTFPL_logo.svg.png" height="48"></a>
# **-- WorkFlows --** 🚧🚧 WORK IN PROGRESS 🚧🚧
<hr>

#### A - Normalisation<br>B - WorkFlows<br>C - Misc<br>D - In Fine
----
## INTRODUCTION
Rappel de la "norme" commune : **Normalisation** pour les différents éléments<br>
Le premier élément est la Langue<br>
Pour distinguer le Français de l'Anglais je vais utiliser les icones suivantes :<br>
🔵⚪️🔴 En Français<br>
🌎🌍🌏 En Anglais

Autre exemple trivial pour le Prompt Positif je vais utiliser la couleur "vert" et pour le prompt négatif la couleur "rouge"<br>
Couleur par défaut proposée par COMFYui<br>
Lorsque ces couleurs sont spécifiques je le préciserais avec le code couleurs

---
Reminder of the common "standard" aka **Normalisation** for the different elements<br>
The first element is the Language<br>
To distinguish French from English I will use the following icons:<br>
🔵⚪️🔴 In French<br>
🌎🌍🌏 In English<br>

Another trivial example for the Positive Prompt I will use the color "green" and for the negative prompt the color "red"<br>
Default color proposed by COMFYui<br>
When these colors are specific I will specify it with the color code

---
## A - Normalisation
#### VOIR LA PAGE AD HOC :  [ <u>README</u> ](https://github.com/Dfalm-Original/COMFYui)<br>REFER TO AD HOC PAGE: [ <u>README</u> ](https://github.com/Dfalm-Original/COMFYui)


-----
-----

## B - WorkFlows
🔵⚪️🔴 Dans ce chapitre je propose des WorkFlow, les liens des exemples, des images et autres...<br>🌎🌍🌏 In this chapter I propose WorkFlow, links to examples, images and others...
<hr>

## 0) BASIC-V1.00
<img src="Defaut/images/BASIC-V1.00-notes.jpg" width="60%"><br>
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
<img src="Defaut/images/control-nom.png" width="40%"><br>
Controle le nom du fichier / Check the file name : **Nom-Fichier+Checkpoint**

- v) Sauvegarde Type de fichier & metadata - Save File type & metadata<br>
<img src="Defaut/images/Ksampler-metadata.png" width="50%"><br>
💙Permet de sauvegarder les metadatas dans un fichier "txt" externe<br>
💙Allows you to save metadata in an external "txt" file<br>
💚Permet de sauvegarder en PNG - JPG - JPEG - WEBP<br>  💚Allows you to save in PNG - JPG - JPEG - WEBP<br><img src="Defaut/images/format-image.png"><br>

- vi) Preview image<br>
<img src="Defaut/images/preview-image.png" width="40%"><br>
🗃 Noir / Black

### 🔵⚪️🔴 Tous ces elements sont communs aux differents workflows<br>  
### 🌎🌍🌏 All these elements are common to the different workflows


<hr>

## I) -A-  DEFAUT_MODEL-A_Text-2-Img+UPscalersV1.00
<img src="Defaut/images/DEFAUT_MODEL-A_Text-2-Img+UPscalersV1.00-notes.jpg" height="50%"><br>

#### 🔵⚪️🔴 Permet de faire image-to-image avec des options de *prompts* et la possibilité d'*UPScaler* l'image rendue <br>- Par defaut les deux UPscalers sont désactivés ❌<br><br>
## - U1💚/U2💜 - Upscalers ( desactives par defaut )

Le premier Upscaler **U1💚** est un Upscaler "simple" qui agrandit l'image sans post-traitement<br>
Le second Upscaler **U2💜** est un 'refiner' il utilise un Ksampler, la seed, la VAE ...

## - **🧡ON/OFF**
L'interrupteur note **🧡ON/OFF** permet d'activer / desactiver les groupes :  U1💚/U2💜 en fonction des besoin d'UPScale

## - **⚪️L** (Lora)
L'option **⚪️L** permet d'ajouter un Lora lors de la generation de l'images<br>- Par defaut l'option est desactivee<br>

## - **🔴S** Sauvegarde / Save  
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

#### 🌎🌍🌏 Allows you to do image-to-image with *prompts* options and the ability to *UPScaler* the rendered image <br>- By default both UPscalers are disabled ❌<br><br>
## - U1💚/U2💜 - Upscalers (disabled by default)

The first Upscaler **U1💚** is a "simple" Upscaler that enlarges the image without post-processing<br>
The second Upscaler **U2💜** is a 'refiner' it uses a Ksampler, the seed, the VAE ...

## - **🧡ON/OFF**
The switch note **🧡ON/OFF** allows you to activate / deactivate the groups: U1💚/U2💜 depending on the UPScale needs

## - **⚪️L** (Lora)
The **⚪️L** option allows you to add a Lora when generating the images<br>- By default the option is disabled<br>

## - **🔴S** Save / Save
Save / Save **🔴S** Ref: *0️⃣BASIC-V1.00

## **🔘P** (Prompt)
Prompt **🔘P**<br>
There is a "Prompt" option Classic / Batch & Vanilla / Improved"
Allows you to choose 4 Options<br>
1 Prompt Classic 'Vanilla'<br>
2 Prompt Classic + Bonus = improved by a series of words --**💗P**--<br>
3 Prompt File "Batch"<br>
-> *1 Line = 1 Prompt*<br>
4 Prompt File "Batch" + Bonus = enhanced by a series of words --**💗P**--<br>
-> *1 Line = 1 Prompt* + "Enhanced Bonus"<br>


## - Pour les UPScaler voir le chapitre idoine : <u>4️⃣ Upscalers </u>

<hr>

## II) -B- DEFAUT_MODEL-B_Load-ImgZ+UPscalersV1.00
<img src="Defaut/images/DEFAUT_MODEL-B_Load-ImgZ+UPscalersV1.00-notes.jpg" height="50%"><br>

#### 🔵⚪️🔴 Permet d'Upscaler des images avec 2 Upscalers<br>- Par defaut l'UPscaler "Hires/Lent" U2💜 est désactivé ❌<br><br>

## - U1💚/U2💜 - Upscalers
Le premier Upscaler **U1💚** est un Upscaler "simple" qui agrandit l'image sans post-traitement<br>
Le second Upscaler **U2💜** est un 'refiner' il utilise un Ksampler, la seed, la VAE ...<br> Desactive par defaut

## - **💛i** (Load-s Images)
L'option **💛i** permet de choisir entre différentes options d'images : Load Images<br>
<img src="Defaut/images/loads-images.png" width="30%"><br>
💚 - La première option est l'option '**classic**' lecture / load image simple : 1 image<br>
💙 - La deuxième option est '**load image batch**' permet de prendre toutes les images d'un repertoire<br>
💛 - La troisieme option est '**load image from URL**' permet d'utiliser une images 'direct' depuis l'adresse Web sans avoir besoin de la telecharger pour l'utiliser dans l'option [1] - 💚<br>

### Toutes les Options restent comnunes :
#### - **🧡ON/OFF**
#### - **⚪️L** (Lora)
#### - **🔘P** (Prompt)
#### - **🔴S** Sauvegarde / Save<br>

#### 🌎🌍🌏 Allows you to Upscale images with 2 Upscalers<br>- By default the "Hires/Lent" U2💜 UPscaler is disabled ❌<br><br>

## - U1💚/U2💜 - Upscalers
The first Upscaler **U1💚** is a "simple" Upscaler that enlarges the image without post-processing<br>
The second Upscaler **U2💜** is a 'refiner' it uses a Ksampler, the seed, the VAE ...<br> Disabled by default

## - **💛i** (Load-s Images)
The **💛i** option allows you to choose between different image options: Load Images<br>
<img src="Defaut/images/loads-images.png" width="30%"><br>
💚 - The first option is the '**classic**' option, read / load single image: 1 image<br>
💙 - The second option is '**load image batch**', allows you to take all the images from a directory<br>
💛 - The third option is '**load image from URL**', allows you to use an image 'direct' from the web address without having to download it to use it in option [1] - 💚<br>

### All Options remain common:
#### - **🧡ON/OFF**
#### - **⚪️L** (Lora)
#### - **🔘P** (Prompt)
#### - **🔴S** Save

## - Pour les UPScaler voir le chapitre idoine : <u>4️⃣ Upscalers </u>

<hr>

## III) - C - DEFAUT_Text-2-Img+UPscalersV1.1.3-Valerie
<img src="Defaut/images/DEFAUT_MODEL-C_Text-2-Img+LoadImage+UPscalers-notes.jpg" height="50%">

#### 🔵⚪️🔴 Combine le Modele A et le Modele B<br>
A - Permet de faire image-to-image avec des options de *prompts* <br>
### Toutes les Options restent comnunes :
#### - **🧡ON/OFF**
#### - **⚪️L** (Lora)
#### - **🔘P** (Prompt)
#### - **🔴S** Sauvegarde / Save    
#### - **💛i** (Load-s Images)

## - **⚫️C** Choix de generation d'image
Choisir entre 4 options :
- [1] <b>text 2 image </b> -  Ksampler "calcul" de l'image <br>
- [2]  <b>Load-Image </b>: une seule image <br>
- [3]  <b>Load Batch image </b> / répertoire  <br>
- [4]  <b>Load Image From URL </b>: depuis 'internet' <br>

## - **💙 D** Denoise
Permet de modifier le '**denoise**' pour les options 2 3 et 4<b> ( *Load-Image - Load Batch image - Load Image From URL* )
Le '**denoise**' est force a **1** pour l'option **[1]**

## - U1💚/U2💜 - Upscalers ( desactives par defaut )
Le premier Upscaler **U1💚** est un Upscaler "simple" qui agrandit l'image sans post-traitement<br>
Le second Upscaler **U2💜** est un 'refiner' il utilise un Ksampler, la seed, la VAE ...<br>

## - **🧡ON/OFF**
L'interrupteur note **🧡ON/OFF** permet d'activer / desactiver les groupes :  U1💚/U2💜 en fonction des besoin d'UPScale

## - **⚪️L** (Lora)
L'option **⚪️L** permet d'ajouter un Lora lors de la generation de l'images<br>- Par defaut l'option est desactivee<br>

## - Sauvegarde / Save  
Sauvegarde / Save **🔴S** Ref : *0️⃣BASIC-V1.00

## - **💛i** (Load-s Images)
L'option **💛i** permet de choisir entre différentes options d'images : Load Images<br>
<img src="Defaut/images/loads-images.png" width="30%"><br>
💚 - La première option est l'option '**classic**' lecture / load image simple : 1 image<br>
💙 - La deuxième option est '**load image batch**' permet de prendre toutes les images d'un repertoire<br>
💛 - La troisieme option est '**load image from URL**' permet d'utiliser une images 'direct' depuis l'adresse Web sans avoir besoin de la telecharger pour l'utiliser dans l'option [1] - 💚<br>

#### 🌎🌍🌏 Combine Model A and Model B<br>
A - Allows image-to-image with *prompts* options <br>
### All Options remain common:
#### - **🧡ON/OFF**
#### - **⚪️L** (Lora)
#### - **🔘P** (Prompt)
#### - **🔴S** Sauvegarde / Save
#### - **💛i** (Load-s Images)

## - **⚫️C** Image generation choice
Choose between 4 options:
- [1] <b>text 2 image</b> - Ksampler "calculation" of the image <br>
- [2] <b>Load-Image</b>: a single image <br>
- [3] <b>Load Batch image</b> / directory <br>
- [4] <b>Load Image From URL</b>: from 'internet' <br>

## - **💙 D** Denoise
Allows to modify the '**denoise**' for options 2 3 and 4<b> ( *Load-Image - Load Batch image - Load Image From URL* )
The '**denoise**' is forced to **1** for option **[1]**

## - U1💚/U2💜 - Upscalers ( disabled by default )
The first Upscaler **U1💚** is a "simple" Upscaler that enlarges the image without post-processing<br>
The second Upscaler **U2💜** is a 'refiner' it uses a Ksampler, the seed, the VAE ...<br>

## - **🧡ON/OFF**
The switch notes **🧡ON/OFF** allows you to activate/deactivate the groups: U1💚/U2💜 depending on UPScale's needs

## - **⚪️L** (Lora)
The **⚪️L** option allows you to add a Lora when generating the images<br>- By default the option is disabled<br>

## - Save / Save
Save / Save **🔴S** Ref: *0️⃣BASIC-V1.00

## - **💛i** (Load-s Images)
The **💛i** option allows you to choose between different image options: Load Images<br>
<img src="Defaut/images/loads-images.png" width="30%"><br>
💚 - The first option is the '**classic**' option, read / load simple image : 1 image<br>
💙 - The second option is '**load image batch**' allows you to take all the images from a directory<br>
💛 - The third option is '**load image from URL**' allows you to use an image 'direct' from the web address without having to download it to use it in option [1] - 💚<br>

## - Pour les UPScaler voir le chapitre idoine : <u>4️⃣ Upscalers </u>

<hr>

## IV) Upscalers 4️⃣:
### Hires - Lent / Slow  
#### -- Desactive par defaut // Disabled by default
<img src="Defaut/images/upscaler-hires.png" width="60%">

#### 🔵⚪️🔴  Modifier le coeeficient multiplicateur <br>
-Par défaut (3)  
-- Choisir le model "Upscaler"<br>
#### ℹ️ Le coefficient multiplicateur est indépendant du choix du modele upscaler<br>
<u>EXEMPLE</u> : On peut utiliser le modele **8x** *_NMKD-Superscale_150000_G* avec un coefficient de **3** <br>
Inversement on peut utiliser un coefficient de 4 avec le modele **2x***Higurashi_v1_compact_270k*<br>

Il est préférable que le coefficient multiplicateur soit inferieur a celui du modele<br>  
On peut utiliser de cette manière des coefficient impair<br>

J'ai choisi arbitrairement d'utiliser des coefficients entiers : la primitive "MULTIPLICATEUR" ne permet pas les nombres a virgule ( Libre a vous de le modifier - La Dfalm.<i>[Licence ](https://github.com/Dfalm-Original/COMFYui?tab=License-1-ov-file)</i> le permet )<br>


#### 🌎🌍🌏 Modify the multiplier coefficient <br>
-By default (3)<br>
-- Choose the "Upscaler" model<br>
#### ℹ️ The multiplier coefficient is independent of the choice of the upscaler model<br>
<u>EXAMPLE</u>: We can use the model **8x** *_NMKD-Superscale_150000_G* with a coefficient of **3** <br>
Conversely, we can use a coefficient of 4 with the model **2x***Higurashi_v1_compact_270k*<br>

It is preferable that the multiplier coefficient is lower than that of the model<br>
We can use odd coefficients in this way<br>

I arbitrarily chose to use integer coefficients: the primitive "MULTIPLIER" does not allow numbers with a comma (You are free to modify it - The Dfalm.<i>[License ](https://github.com/Dfalm-Original/COMFYui?tab=License-1-ov-file)</i> allows it )<br>


## 📥 Telecharger des modeles / download models :
 [OPEN UPSCALER](https://openmodeldb.info) : https://openmodeldb.info

#### INSTALLER LES MODELES DANS / INSTALL MODELS IN

.\ComfyUI\Models\upscale_models

-----
-----

<h1>C - MISC</h1>

### Conseil / Advice
🔵⚪️🔴 Pour la preview image j'utilise egalement la couleur noire et uniquement "PREVIEW IMAGE"<br>
Je conseille d'utiliser les "SD" Prompt generator et Prompt Saver 1️⃣ pour diverses raisons

🌎🌍🌏 For the preview image I also use black color and only "PREVIEW IMAGE"<br>
I recommend using the "SD" Prompt generator and Prompt Saver 1️⃣ for various reasons

1️⃣ SD Prompt Reader Node : https://github.com/receyuki/comfyui-prompt-reader-node<br>

# BUG

### VOIR LA PAGE AD HOC :  [ <u>README - Section Bugs</u> ](https://github.com/Dfalm-Original/COMFYui)<br>REFER TO AD HOC PAGE:[ <u>README - Bugs Section </u>](https://github.com/Dfalm-Original/COMFYui)

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
