### <a href="https://creativecommons.org/publicdomain/zero/1.0/"><img src="../images/CC-0-Violet.png" height="48"></a> Dfalm.<i>[Licence ](https://github.com/Dfalm-Original/COMFYui?tab=License-1-ov-file)</i><a href="https://fr.wikipedia.org/wiki/WTFPL"><img src="../images/WTFPL_logo.svg.png" height="48"></a>
# ** 🚧🚧 WORK IN PROGRESS 🚧🚧 -- Zoom Infini --**
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
<img src="Infinite-Zoom/images/auto-queue.png" width="50%"><br>

.
.
.
.
.
.
.
.
.


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
## 🐞 BUG TRIVIAL 🐞  
#### 🔵⚪️🔴  Specifique au 'MODEL-C' ( DEFAUT_MODEL-C_Text-2-Img+LoadImage+UPscalers )
#### 🌎🌍🌏  Specific to 'MODEL-C' ( DEFAULT_MODEL-C_Text-2-Img+LoadImage+UPscalers )

🔵⚪️🔴 Il y a un BUG  resolu : C'est un conflit entre ** text-to-image** VS **image-to-image** : <u>erreur VAE</u><br>
🌎🌍🌏 There is a BUG fixed: It is a conflict between ** text-to-image** VS ** image-to-image** : <u>VAE error</u><br><br>
<img src="Defaut/images/FLUX-bug-VAE.png" width="40%">

🔵⚪️🔴  2 Solutions : Pour contourner le probleme il faut desactiver/activer la VAE  <br>  
<u>Solution 1</u> : Manuellement desactiver/activer le "groupe" ad-hoc : **[ 🐞 TEXT-to-IMAGE / IMAGE-to-IMAGE 🐞 ]**<br>
🌎🌍🌏 2 Solutions : To get around the problem, you have to deactivate/activate the VAE <br>
<u>Solution 1</u>: Manually deactivate/activate the ad-hoc "group": **[ 🐞 TEXT-to-IMAGE / IMAGE-to-IMAGE 🐞 ]**<br>
<img src="Defaut/images/DEFAUT_MODEL-C_Text-2-Img+LoadImage+UPscalersV1.01-notes.jpg" width="40%"><br>
✅ ACITIVE = TEXT-to-IMAGE  // ❌ DESACTIVE = IMAGE-to-IMAGE

🔵⚪️🔴 <u>Solution 2</u> : Automatiquement = ne rien faire<br>  J'ai ajoute un noeud auto *mutte / demutte* qui actionne automatiquement la solution 1<br>
( Mais il y a un inconvenient 📑 )<br>
Lancer la queue normalement une erreur va apparaitre : [ KSampler ] ou [ VAEENCODE ]<br>
🌎🌍🌏 <u>Solution 2</u>: Automatically = do nothing<br> I added an auto node *mutte / demutte* which automatically activates solution 1<br>
( But there is a drawback 📑 )<br>
Launch the queue normally an error will appear: [ KSampler ] or [ VAEENCODE ]<br>
<img src="Defaut/images/ERROR-Ksampler.png" width="40%"><img src="Defaut/images/ERROR-VAE.png" width="40%"><br>

🔵⚪️🔴 Il suffit de relancer la queue pour que ça fonctionne correctement
### 📑 L'erreur se reproduira au premier changement text-to-image 🔂 image-to-text

🌎🌍🌏 Just restart the queue for it to work properly
### 📑 The error will reoccur on the first text-to-image change 🔂 image-to-text

### 🔵⚪️🔴 <u> EXPLICATION</u> L’interrupteur "auto mutte" fonctionne avec un cycle de retard<br>🌎🌍🌏 <u>EXPLANATION</u> The "auto mute" switch operates with a delay cycle<br>
<img src="Defaut/images/ERROR-auto-correction.png" width="40%"><br>
🔵⚪️🔴 Si la VAE est dans un etat (ON📲/📴OFF) et qu'on permutte la generation d'image text-to-image 🔂 image-to-text<br>  
Lorsqu'on a va generer la nouvelle image avec le nouveau choix( image-to-text 🔂 text-to-image ) la VAE est n'est pas dans l'etat correct (📴OFF/ON📲)<br>
1) Ca provoque l'erreur [ KSampler ] ou [ VAEENCODE ]<br>  
2) L'etat de la VAE bascule dans l'etat correct (ON📲/📴OFF) : on peut desormais generer l'image

🌎🌍🌏 If the VAE is in a state (ON📲/📴OFF) and we switch the image generation text-to-image 🔂 image-to-text<br>
When we are going to generate the new image with the new choice (image-to-text 🔂 text-to-image) the VAE is not in the correct state (📴OFF/ON📲)<br>
1) This causes the error [ KSampler ] or [ VAEENCODE ]<br>
2) The state of the VAE switches to the correct state (ON📲/📴OFF): we can now generate the image

### 🔵⚪️🔴 Soit on desactive/active manuellement soit en automatique avec une erreur non bloquante<br>🌎🌍🌏 Either manually deactivate/activate or automatically with a non-blocking error
<br>


### AUTRES BUGS :<br>VOIR LA PAGE AD HOC :  [ <u>README - Section Bugs</u> ](https://github.com/Dfalm-Original/COMFYui)<br>REFER TO AD HOC PAGE:[ <u>README - Bugs Section </u>](https://github.com/Dfalm-Original/COMFYui)

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