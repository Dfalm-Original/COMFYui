### <a href="https://creativecommons.org/publicdomain/zero/1.0/"><img src="https://raw.githubusercontent.com/Dfalm-Original/COMFYui/main/images/CC-0-Violet.png" height="48"></a> Dfalm.<i>[Licence ](https://github.com/Dfalm-Original/COMFYui?tab=License-1-ov-file)</i><a href="https://fr.wikipedia.org/wiki/WTFPL"><img src="https://raw.githubusercontent.com/Dfalm-Original/COMFYui/main/images/WTFPL_logo.svg.png" height="48"></a>
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

## [RESUME DES WORKFLOWS - WORKFLOWS SUMMARY ](Dfalm_Workflows.md)

0) <u>[BASIC](BASIC.md)</u> - Presentation et bases -- Presentation and basics
1) <u>[DEFAUT_MODEL-A_Text-2-Img+UPscalers](DEFAUT_MODEL-A.md)</u> - Pour generer 'text-to-image' -- To generate 'text-to-image'
2) <u>[DEFAUT_MODEL-B_Load-ImgZ+UPscalers](DEFAUT_MODEL-B.md)</u> - Pour generer 'image(s)-to-image' -- To generate 'image(s)-to-image'
3) <u>[DEFAUT_MODEL-C_Text-2-Img+LoadImage+UPscalers](DEFAUT_MODEL-C.md)</u> - Combine le Modele A et le Modele B -- Combine Model A and Model B
4) <u>[DEFAUT_MODEL-D_Text-2-Img+LoadImage+UPscalers](DEFAUT_MODEL-D.md)</u> - Ameliore le Modele B -- Amelioration of B Model

### 🆙) <u>[Upscalers](Upscalers.md)</u>

## 🚧🚧 WORK IN PROGRESS 🚧🚧

#### 🚨🚨 ATTENTION CE N'EST PAS UNE VERSION FINALE !! VERSION ALPHA 🚨🚨
#### 🚨🚨 ATTENTION THIS IS NOT A FINAL VERSION !! ALPHA VERSION 🚨🚨
5) <u> [INFINITE ZOOM](Infinite-Zoom.md) </u>- Permet de faire des Animation / Video de Zoom Infini -- Allows you to make Infinite Zoom Animation/Video<br><br>
> (  exemple 1 : [CIVITAI](https://civitai.com/images/34925284) // exemple 2 : [Youtube](https://youtube.com/shorts/W1ugyeAG0Ys)  )<br> 

6) <u> [Re-COMBINE 2 images](Combine.md)</u>- Permet de recombiner 2 images pour en faire une nouvelle -- Allows you to recombine 2 images to make a new one<br>
#### 🚨🚨 ATTENTION CE N'EST PAS UNE VERSION FINALE !! VERSION ALPHA 🚨🚨
#### 🚨🚨 ATTENTION THIS IS NOT A FINAL VERSION !! ALPHA VERSION 🚨🚨
## 🚧🚧 WORK IN PROGRESS 🚧🚧 


<hr>

-----
-----

# 🚧🚧 WORK IN PROGRESS 🚧🚧
## 🚨🚨 ATTENTION CE N'EST PAS UNE VERSION FINALE !! VERSION ALPHA 🚨🚨
## 🚨🚨 ATTENTION THIS IS NOT A FINAL VERSION !! ALPHA VERSION 🚨🚨
# 🚧🚧 WORK IN PROGRESS 🚧🚧
<hr>
<hr>

# 🔵⚪️🔴 Permet de faire des Zooms infinis <br>🌎🌍🌏 Allows infinite zooms
[ CLICK TO DOWNLOAD PNG WORKFLOW ]<br>
<a href="Infinite-Zoom/Dfalm_Infinite_Zoom.png"><img src="Infinite-Zoom/Dfalm_Infinite_Zoom.png" width="40%"></a><br>

# Vue d'ensemble - Overview
<img src="Infinite-Zoom/Dfalm_Infinite_Zoom-notes.jpg" width="60%"><br>
1) Nom du fichier + Repertoire - File name + Directory
2) Rotation ( Angle en Degre° ) - Rotation (Angle in Degrees)
3) Zoom ( facteur de zoom ) - Zoom (zoom factor)
4) Taille de l'image L/H - Image size W/H
5) Prompt positif - Positive prompt
6) MAIN : Checkpoint, Lora, seed
7) INITIATEUR : 1/ Creer une Image 2/ Generer le Zoom - NITIATOR: 1/ Create an Image 2/ Generate the Zoom
<br>

G ) Genere l'image - Generate the image<br>
RG) Random Step / cfg pour creer de l'aleatoire - To generate randomness<br>
B ) Boucle de zoom - Zoom loop<br>
Z ) Zoom de l'image - Zoom image<br>
C1 ) Controles de l'image + redimensionnement <br>
RZ ) Zoom Random Step / cfg pour creer de l'aleatoire - To generate randomness<br>
MATH/TRIGO ) Effectue la roation de l'image en respectant le ratio d'origine - Rotate the image respecting the original ratio<br>
C2 ) Controles de l'image Finale - Final image controls<br>
CR ) Controle et Forcage de la taille de l'image - Control and force the image size<br>
S ) Sauvegarde de l'image et options - Save the image and options<br>
COMPTEUR ) Compte le nombre d'images generees pour le zoom - Counts the number of images generated for zooming<br>

# DETAILS <br>
### 1) Nom du fichier + Repertoire - File name + Directory<br>
<img src="Infinite-Zoom//images/1Nom.png" width="30%"><br>
🔵⚪️🔴 Le nom et le type d'image est automatiquement permutee entre l'image "initiale" et les images generees pour le zoom : voir <b>S) Sauvegarde de l'image et options</b><br>
🌎🌍🌏 The image name and type is automatically swapped between the "initial" image and the images generated for zooming: see <b>S) Image saving and options</b><br>

### 2) Rotation ( Angle en Degre° )  - Rotation (Angle in Degrees) <br>
<img src="Infinite-Zoom//images/2Rotation.png" width="40%"><br>
Accepte les Angles negatifs et les virgules<br>
Accepts negative angles and commas<br>
### 3) Zoom ( facteur de zoom ) - Zoom (zoom factor)<br>
<img src="Infinite-Zoom//images/3Zoom.png" width="30%"><br>
Accepte les virgules
### 4) Taille de l'image L/H - Image size W/H<br>
<img src="Infinite-Zoom//images/4Taille.png" width="40%"><br>
Permet de faire du portrait, paysage ou 1/1 et tous autres formats
### 5) Prompt positif - Positive prompt<br>
<img src="Infinite-Zoom//images/5Prompt.png" width="50%"><br>
Toutes les options de Prompts
## 🔵⚪️🔴⚠️ATTENTION⚠️
### 10 CHOIX <font color="#00FF55"> PROMPT :<br>
(0) Vanille<br>
(1) Magic<br>
(2) Super Random<br>
[3] Magic + Super Random (defaut)</font><br>

<font color="#FF00A5">
BATCH PROMPT   :<br>
(4) Vanille<br>
(5) Magic<br>
(6) Super Random<br>
(7) Magic + Super Random
</font>

<font color="#0044AA">RANDOM
<br>
(8) Super Random<br>
(9) Super Random + Magic
</font>

## 🌎🌍🌏⚠️ATTENTION⚠️
### 10 CHOICES <font color="#00FF55"> PROMPT:<br>
(0) Vanilla<br>
(1) Magic<br>
(2) Super Random<br>
[3] Magic + Super Random (default)</font><br>
<font color="#FF00A5"> BATCH PROMPT:<br>
(4) Vanilla<br>
(5) Magic<br>
(6) Super Random<br>
(7) Magic + Super Random </font>
<font color="#0044AA">RANDOM <br>
(8) Super Random<br>
(9)Super Random + Magic </font>


### 6) MAIN : Checkpoint, Lora, seed<br>
<img src="Infinite-Zoom//images/6Main.png" width="40%"><br>
Choisir le Tenseur (Checkpoint), le Lora et la Seed

### 7) INITIATEUR  - INITIATOR:
1/ Creer la premiere Image - Create first Image<br>
2/ Generer le Zoom - Generate the Zoom<br>
<img src="Infinite-Zoom//images/7Init.png" width="40%"><br>
🔵⚪️🔴 Permet de creer une premiere image ou d'en regenerer une nouvelle<br>
Une fois satisfait il faut permuter sur le choix (2) pour generer le Zoom<br>
🌎🌍🌏 Allows you to create a first image or regenerate a new one<br>
Once satisfied, you must switch to choice (2) to generate the Zoom<br>
## ⚠️ ATTENTION : Suivre les instructions -- Follow Instructions ⚠️
<img src="Infinite-Zoom//images/Instructions.png" width="40%"><br>

### G ) Genere l'image<br>
<img src="Infinite-Zoom//images/Genere.png" width="70%"><br>
Par defaut : <b>SAMPLER</b> : dpm_2 -- <b>Scheduleur</b> : sgm_uniform<br>


### RG ) Random Step / cfg pour creer de l'aleatoire<br>
<img src="Infinite-Zoom//images/RG.png" width="30%"><br>
Permet de cadrer - Restrict  step / cfg<br>
Step entre - Between { 3 ; 6 } -- cfg entre - Between {8.0 ; 15.0 }

### B ) Boucle de zoom<br>
<img src="Infinite-Zoom//images/Boucle.png" width="40%"><br>
Image qui sera re-injecter pour generer une nouvelle image pour le zoom<br>

### Z ) Zoom de l'image<br>
<img src="Infinite-Zoom//images/Zoomer.png" width="40%"><br>
Modele d'Upscale par defaur <b> 2xHigurashi_V1_compact_270k</b> est rapide et efficace<br>
Par defaut : <b>SAMPLER</b> : dpmpp_2 -- <b>Scheduleur</b> : sgm_uniform<br>
Les autres options sont a discretion<br>

### C1 ) Controles de l'image + redimensionnement<br>
<img src="Infinite-Zoom//images/Controls1.png" width="40%"><br>
Ce sont des controles de la taille de l'image et du crop pour le zoom<br>
These are image size and crop controls for zooming<br>

### RZ ) Zoom Random Step / cfg pour creer de l'aleatoire<br>
<img src="Infinite-Zoom//images/Randomize-Zoom.png" width="40%"><br>
Permet de cadrer - Restrict step / cfg<br>
Step entre - Between { 3 ; 7 } -- cfg entre - Between{8.0 ; 13.0 }<br>

### MATH/TRIGO ) Effectue la rotation de l'image en respectant le ratio d'origine -- Rotates the image respecting the original ratio<br>
<img src="Infinite-Zoom//images/Math-Trigo.png" width="60%"><br>
🔵⚪️🔴 C'est la partie dans laquelle l'image subi une rotation et conserve ses proportions initiales<br>
Ne pas depasser +/-10° d'angle sinon la rotation est trop brutale<br>
🌎🌍🌏 This is the part in which the image is rotated and keeps its initial proportions<br>
Do not exceed +/-10° angle otherwise the rotation is too abrupt<br>
<h2>ℹ️ SOURCE : <a href="https://math.stackexchange.com/questions/3181876/how-to-find-sides-of-rectangle-that-is-inscribed-in-other-rectangle">How to find sides of rectangle<br> that is inscribed in other rectangle ?</a></h2>

### C2 ) Controles de l'image Finale<br>
<img src="Infinite-Zoom//images/2Rotation.png" width="40%"><br>
Controle la taille de l'image finale par rapport aux dimension initialement renseignees 4) Taille de l'image L/H

### CR ) Controle et Forcage de la taille de l'image<br>
<img src="Infinite-Zoom//images/CROP.png" width="40%"><br>
🔵⚪️🔴 A cause des virgules flotantes parfois la taille de l'image peut varier donc on :<br>
Controle et force le redimensionnement de l'image aux dimensions initiales 4) Taille de l'image L/H<br>
🌎🌍🌏 Due to floating points sometimes the image size can vary so we:<br>
Control and force the image to be resized to the initial dimensions 4) Image size W/H<br>

### S ) Sauvegarde de l'image et options<br>
<img src="Infinite-Zoom//images/Sauve.png" width="30%"><br>
🔵⚪️🔴  La sauvegarde de l'image et ses options<br>
Permet de sauvegarder un fichier "txt" dans lequel il y a des metadata<br>
L'image "initiale" est sauvee en PNG avec le prompt / workflow embarque<br>
Le nom de l'image initiale PNG est : <b>"INITIAL+TEST_'<i>FICHIER</i>'.png"</b><br>
Les images de Zoom sont automatiquement permutees en JPG<br>
Le nom de l'image zoom JPG est : <b>"ZOOM_'<i>FICHIER</i>'.jpg"</b><br>

🌎🌍🌏 Saving the image and its options<br>
Allows you to save a "txt" file in which there is metadata<br>
The "initial" image is saved in PNG with the embedded prompt / workflow<br>
The name of the initial PNG image is:<b>"INITIAL+TEST_'<i>FICHIER</i>'.png"</b><br>
Zoom images are automatically switched to JPG<br>
The name of the JPG zoom image is: <b>"ZOOM_'<i>FICHIER</i>'.jpg"</b>br>

### ℹ️ <u>VOIR GIT-UB / FOLLOW GIT-HUB</u> : [save-image-extended-comfyui](https://github.com/audioscavenger/save-image-extended-comfyui)<br>


### COMPTEUR ) Compte le nombre d'images generees pour le zoom - Counts the number of images generated for zooming<br>
<img src="Infinite-Zoom//images/compteur.png" width="40%"><br>
Fait ce qui est indique<br>
Do what is instructed<br>

-----
-----

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