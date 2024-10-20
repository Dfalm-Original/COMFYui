### <a href="https://creativecommons.org/publicdomain/zero/1.0/"><img src="https://raw.githubusercontent.com/Dfalm-Original/COMFYui/main/images/CC-0-Violet.png" height="48"></a> Dfalm.<i>[Licence ](https://github.com/Dfalm-Original/COMFYui?tab=License-1-ov-file)</i><a href="https://fr.wikipedia.org/wiki/WTFPL"><img src="https://raw.githubusercontent.com/Dfalm-Original/COMFYui/main/images/WTFPL_logo.svg.png" height="48"></a>
# ** 🚧🚧 WORK IN PROGRESS 🚧🚧  --**
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

# 🚧🚧 WORK IN PROGRESS 🚧🚧
## 🚨🚨 ATTENTION CE N'EST PAS UNE VERSION FINALE !! VERSION ALPHA 🚨🚨
## 🚨🚨 ATTENTION THIS IS NOT A FINAL VERSION !! ALPHA VERSION 🚨🚨
# 🚧🚧 WORK IN PROGRESS 🚧🚧
<hr>
<hr>

# 🔵⚪️🔴 
# Permet de combiner 2 images ensemble
## IMAGE 1🔵 avec IMAGE 2🔴
[ CLICK TO DOWNLOAD PNG WORKFLOW ]<br>
<a href="Combine/COMBINE-4TYPES_Images+UPscalers.png"><img src="Combine/COMBINE-4TYPES_Images+UPscalers-notes.jpg" width="50%">

### Toutes les Options restent comnunes au [ [ modele C ](DEFAUT_MODEL-C.md) ] & au modele [ [BASIC](BASIC.md) ] :
❤️C - Commun / Common<br>
💚U1 / 💜U2 - Upsacalers 1 & 2 <br>

<img src="Combine/images/commun.png" width="20%"><br>

# G ) GUIDANCE 
<img src="Combine/images/guidance.png" width="40%"><br>

## 🔵⚪️🔴 CHOIX DE GUIDANCE
### [1] Pas de prompt pour guider<br>
### (2) On ajoute le prompt
( Voir options de prompt )


## 🌎🌍🌏 GUIDANCE CHOICE
### [1] No prompt to guide<br>
### (2) We add the prompt
( See prompt options )


## <u>Parametres individuels de chaque image</u> : 
A ) SOURCE DE L'IMAGE 4 CHOIX :
- 1 Load Image
- 2 Image From URL
- 3 Reicever ( image generee / reinjecte)
- 4 Painter

B ) INTENSITE DE L'IMAGE<br>
**0.00** = n'est pas prise en compte <br>
**1.00** = 100 %<br>
Conseil ne pas dépasser 90% ( 0.90 ) au-dela de 0.90 l'image a tendance a "deriver"<br>

<img src="Combine/images/Choix-Image-Force_FR.png" width="40%"><br>
# 🌎🌍🌏
# Allows you to combine 2 images together
## IMAGE 1🔵 with IMAGE 2🔴
## <u>Individual settings for each image</u>:
A ) IMAGE SOURCE 4 CHOICES:
- 1 Load Image
- 2 Image From URL
- 3 Reicever (generated / reinjected image)
- 4 Painter

B ) IMAGE INTENSITY
**0.00** = not taken into account<br>
**1.00** = 100%<br>
Advice do not exceed 90% (0.90) beyond 0.90 the image tends to "drift"<br>
<img src="Combine/images/Choix-Image-Force_EN.png" width="40%"><br>



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