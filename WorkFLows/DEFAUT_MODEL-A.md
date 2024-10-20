### <a href="https://creativecommons.org/publicdomain/zero/1.0/"><img src="https://raw.githubusercontent.com/Dfalm-Original/COMFYui/main/images/CC-0-Violet.png" height="48"></a> Dfalm.<i>[Licence ](https://github.com/Dfalm-Original/COMFYui?tab=License-1-ov-file)</i><a href="https://fr.wikipedia.org/wiki/WTFPL"><img src="https://raw.githubusercontent.com/Dfalm-Original/COMFYui/main/images/WTFPL_logo.svg.png" height="48"></a>
# **-- WorkFlows --**
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

0) <u>[BASIC](BASIC.md)</u> - Presentation et bases -- Presentation and basics
1) <u>[DEFAUT_MODEL-A_Text-2-Img+UPscalers](DEFAUT_MODEL-A.md)</u> - Pour generer 'text-to-image' -- To generate 'text-to-image'
2) <u>[DEFAUT_MODEL-B_Load-ImgZ+UPscalers](DEFAUT_MODEL-B.md)</u> - Pour generer 'image(s)-to-image' -- To generate 'image(s)-to-image'
3) <u>[DEFAUT_MODEL-C_Text-2-Img+LoadImage+UPscalers](DEFAUT_MODEL-C.md)</u> - Combine le Modele A et le Modele B -- Combine Model A and Model B
4) <u>[DEFAUT_MODEL-D_Text-2-Img+LoadImage+UPscalers](DEFAUT_MODEL-D.md)</u> - Ameliore le Modele B -- Amelioration of B Model

### 🆙) <u>[Upscalers](Upscalers.md)</u>

## 🚧🚧 WORK IN PROGRESS 🚧🚧

#### 🚨🚨 ATTENTION CE N'EST PAS UNE VERSION FINALE !! VERSION ALPHA 🚨🚨
#### 🚨🚨 ATTENTION THIS IS NOT A FINAL VERSION !! ALPHA VERSION 🚨🚨
5) <u> [INFINITE ZOOM](Infinite-Zoom) </u>- Permet de faire des Animation / Video de Zoom Infini -- Allows you to make Infinite Zoom Animation/Video<br><br>
> (  exemple 1 : [CIVITAI](https://civitai.com/images/34925284) // exemple 2 : [Youtube](https://youtube.com/shorts/W1ugyeAG0Ys)  )<br> 

6) <u> [Re-COMBINE 2 images](Combine)</u>- Permet de recombiner 2 images pour en faire une nouvelle -- Allows you to recombine 2 images to make a new one<br>
#### 🚨🚨 ATTENTION CE N'EST PAS UNE VERSION FINALE !! VERSION ALPHA 🚨🚨
#### 🚨🚨 ATTENTION THIS IS NOT A FINAL VERSION !! ALPHA VERSION 🚨🚨
## 🚧🚧 WORK IN PROGRESS 🚧🚧 


<hr>
## 0) BASIC
[ CLICK TO DOWNLOAD PNG WORKFLOW ]<br>
<a href="Defaut/BASIC.png"><img src="Defaut/images/BASIC-V1.00-notes.jpg" width="60%"></a><br>

🔵⚪️🔴  Remplace le workflow **"default"**<br>  🌎🌍🌏 Replaces **"default"** workflow<br>
<img src="Defaut/images/default.png" width="30%"><br>

## 🔵⚪️🔴 VOIR LE WORKFLOW EN DETAIL  [ CLICK ] [BASIC](BASIC.md)<br>🌎🌍🌏 SEE THE WORKFLOW IN DETAIL [ CLICK ] [BASIC](BASIC.md)

### - Pour les UPScaler voir le chapitre idoine / UPScaler go to : <u>🆙 [Upscalers](Upscalers.md) </u>

<hr>

## I) -A-  DEFAUT_MODEL-A_Text-2-Img+UPscalers
[ CLICK TO DOWNLOAD PNG WORKFLOW ]<br>
<a href="Defaut/DEFAUT_MODEL-A_Text-2-Img+UPscalers.png"><img src="Defaut/images/DEFAUT_MODEL-A_Text-2-Img+UPscalersV1.00-notes.jpg" height="50%"></a><br>  


## 🔵⚪️🔴 Permet de faire *text-to-image* avec des options de *prompts* et la possibilité d'*UPScaler* l'image rendue <br>- Par defaut les deux UPscalers sont désactivés ❌<br><br>
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

## 🌎🌍🌏 Allows you to do image-to-image with *prompts* options and the ability to *UPScaler* the rendered image <br>- By default both UPscalers are disabled ❌<br><br>
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


## - Pour les UPScaler voir le chapitre idoine / UPScaler go to : <u>4️⃣ Upscalers </u>

<hr>

## II) -B- DEFAUT_MODEL-B_Load-ImgZ+UPscalers
[ CLICK TO DOWNLOAD PNG WORKFLOW ]<br>
<a href="Defaut/DEFAUT_MODEL-B_Load-ImgZ+UPscalers.png"><img src="Defaut/images/DEFAUT_MODEL-B_Load-ImgZ+UPscalersV1.00-notes.jpg" height="50%"></a><br>

## 🔵⚪️🔴 Permet d'Upscaler des images avec 2 Upscalers<br>
#### ( Par defaut l'UPscaler "Hires/Lent" U2💜 est désactivé ❌ )
### Toutes les Options restent comnunes [ [BASIC](BASIC.md) ] :

## 🌎🌍🌏 Allows to Upscale images with 2 Upscalers<br>
#### ( By default the "Hires/Lent" U2💜 UPscaler is disabled ❌ )
### All Options remain common [ [BASIC](BASIC.md) ] :

## 🔵⚪️🔴 VOIR LE WORKFLOW EN DETAIL  [ CLICK ] [DEFAUT_MODEL-B_Load-ImgZ+UPscalers](DEFAUT_MODEL-B.md)<br>🌎🌍🌏 SEE THE WORKFLOW IN DETAIL [ CLICK ] [DEFAUT_MODEL-B_Load-ImgZ+UPscalers](DEFAUT_MODEL-B.md)

### - Pour les UPScaler voir le chapitre idoine / UPScaler go to : <u>🆙 [Upscalers](Upscalers.md) </u>

<hr>

## III) - C - DEFAUT_MODEL-C_Text-2-Img+LoadImage+UPscalers 
[ CLICK TO DOWNLOAD PNG WORKFLOW ]<br>
<a href="Defaut/DEFAUT_MODEL-C_Text-2-Img+LoadImage+UPscalers.png"><img src="Defaut/images/DEFAUT_MODEL-C_Text-2-Img+LoadImage+UPscalersV1.00.jpg" height="50%">

### 🐞 BUG TRIVIAL 🐞 : - Bug Section
## 🔵⚪️🔴 Combine le Modele A et le Modele B<br>
A - Permet de faire *text-to-image* avec des options de *prompts* <br>
B - Permet de faire du *image-to-image* avec des options de *prompts* avec l'option '**denoise**' ( **💙 D** )<br>
### Toutes les Options restent comnunes [ [BASIC](BASIC.md) ] :

## 🌎🌍🌏 Combines Model A and Model B<br>
A - Allows you to do *text-to-image* with *prompts* options <br>
B - Allows you to do *image-to-image* with *prompts* options with the '**denoise**' option ( **💙 D** )<br>
### All Options remain common [ [BASIC](BASIC.md) ] :

## 🔵⚪️🔴 VOIR LE WORKFLOW EN DETAIL  [ CLICK ] [DEFAUT_MODEL-C_Text-2-Img+LoadImage+UPscalers](DEFAUT_MODEL-C.md) <br>🌎🌍🌏 SEE THE WORKFLOW IN DETAIL [ CLICK ] [DEFAUT_MODEL-C_Text-2-Img+LoadImage+UPscalers](DEFAUT_MODEL-C.md)

### - Pour les UPScaler voir le chapitre idoine / UPScaler go to : <u>🆙 [Upscalers](Upscalers.md) </u>

<hr>

## IV) - D - DEFAUT_MODEL-D_Text-2-Img+LoadImage+UPscalers + Boucle (Loop)
[ CLICK TO DOWNLOAD PNG WORKFLOW ]<br>
<a href="Defaut/DEFAUT_MODEL-D_Text-2-Img+LoadImage+UPscalers.png"><img src="Defaut/images/DEFAUT_MODEL-D_Text-2-Img+LoadImage+UPscalers-notes.jpg" height="50%">

### 🐞 BUG TRIVIAL 🐞 : - Bug Section
## 🔵⚪️🔴 Modele C Ameliore <br>
Rajoute une boucle (❤️Loop) et permet de re-injecter l'image generer pour la retravailler
- Option 5 : 💜 [5]  <b>Image Receiver</b>
### Toutes les Options restent comnunes au [ [ modele C ](DEFAUT_MODEL-C.md) ] & au modele [ [BASIC](BASIC.md) ] :

## 🌎🌍🌏 Improved Model C <br>
Adds a ❤️Loop and allows to re-inject the generated image to rework it
- Option 5 : 💜 [5]  <b>Image Receiver</b>
### All Options remain common to the [ [ C model ](DEFAUT_MODEL-C.md) ] & to the [ [BASIC](BASIC.md) ] model:

## 🔵⚪️🔴 VOIR LE WORKFLOW EN DETAIL  [ CLICK ] [DEFAUT_MODEL-D_Text-2-Img+LoadImage+UPscalers](DEFAUT_MODEL-D.md) <br>🌎🌍🌏 SEE THE WORKFLOW IN DETAIL [ CLICK ] [DEFAUT_MODEL-D_Text-2-Img+LoadImage+UPscalers](DEFAUT_MODEL-D.md)

### - Pour les UPScaler voir le chapitre idoine / UPScaler go to : <u>🆙 [Upscalers](Upscalers.md) </u>

<hr>

## 🆙) Upscalers :
### Hires - Lent / Slow  

Il y a deux Upscalers, un rapide et un "lent" qui fait du refiner

## 🔵⚪️🔴 VOIR LES DETAILS  [ CLICK ] [Upscalers](Upscalers.md)<br>🌎🌍🌏 SEE DETAILS [ CLICK ] [Upscalers](Upscalers.md)


## ℹ️ INFORMATION : 
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
### <a href="https://creativecommons.org/publicdomain/zero/1.0/"><img src="https://raw.githubusercontent.com/Dfalm-Original/COMFYui/main/images/CC-0-Violet.png" height="48"></a> Dfalm.<i>[Licence ](https://github.com/Dfalm-Original/COMFYui?tab=License-1-ov-file)</i><a href="https://fr.wikipedia.org/wiki/WTFPL"><img src="https://raw.githubusercontent.com/Dfalm-Original/COMFYui/main/images/WTFPL_logo.svg.png" height="48"></a>
<p><img alt="Github" src="http://Dfalm.fr/ComfyUI/Git-Logo-Dfalm.png" width="48"> github : <a href="https://github.com/Dfalm-Original/COMFYui" target="_blank">https://github.com/Dfalm-Original/COMFYui</a></p>
<p><img alt="Youtube" src="http://Dfalm.fr/ComfyUI/youtube+logoToon.png" width="48"> Youtube : <a href="https://www.youtube.com/@Dfalm" target="_blank">https://www.youtube.com/@Dfalm</a></p>