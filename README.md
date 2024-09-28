#### <span style="color:green">Script in French pending translations into English and other languages</span>

# **Divers WorkFlow + Tutos + Config + Misc COMFYui**
<hr>

## Normalisation
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
- PREVIEW
- 1 Variables : En vert / In Green
- 2 Prompts : Couleur / color
- 3 CONTROLS
- 4 Ksampler
- 5 DESACTIVE
- 6 CLIP ENCODE
- 7 CONTROL DE VARIABLES

-----
-----

## WorkFlow
Dans ce chapitre je propose des WorkFlow, les liens des exemples, des images et autres...

----
----

## Misc
Divers à déterminer

Ce **README** est une simple présentation<br>
( *Plus de détails dans un fichier spécifique* )

##  !!!! ATTENTION !!!!

COMING SOON

-----
-----

<font color="#001100">
<h1 id="attention">🗃️ NORMALISATION </h1></font>

## Permier / First :  Langue / Language
<h1>🔵⚪️🔴 En Français</h1>
<h1>🌎🌍🌏 In English</h1>

----
- ## PREVIEW
A Gauche 🔵⚪️🔴 En Français // In Right 🌎🌍🌏 In English<br>
In Left 🔵⚪️🔴 In French // A Droite 🌎🌍🌏 En Anglais
<br>
<img src="images/preview.png">

----
- ## 1 Variables : En vert / In Green :
<img src="images/variables.png">

>### ⌨️ PARAMETRER A DETERMINER PAR L'UTILISATEUR
>#### C'est une variable à renseigner ou un interrupteur à choix

>### ⌨️ SETTING TO BE DETERMINED BY THE USER
>#### This is a variable to be filled in or a switch of choice

- Couleur / Color : 0 255 0
<br>

----
- ## 2 Prompts : Couleur / color
<img src="images/prompts.png">

>#### 📗 PROMPT positif // positive
>#### 📕 PROMPT négatif // negative

Couleurs par défaut / Default Colors<br>
 Vert / Green ⏬ ------------------------ Rouge /Red ⏬<br>
<img src="images/Prompt-positif2.png" width="25%" height="25%">
<img src="images/Prompt-negatif2.png" width="25%" height="25%">

----
- ## 3 CONTROLS
Il s'agit d'un / Is a : "Show Text 🐍"<br>
<img src="images/show-text.png">

J'utilise deux couleurs / I use 2 colors
- CYAN : 0-255-200 <br>
<img src="images/controlcyan.png">

- Safran : 220-200-30<br>
<img src="images/controlsafran.png">

🔵⚪️🔴 J'utilise les 'controls' pour verifier des variables de retour et donner des informations ; les deux couleurs sont employes en fonction de l'usage (d'autre couleurs peuvent etre utilisees en complement)<br>
*Par exemple un coefficient multiplicateur pour un UPScale<br>
Ou le nom complet de l'image lorsqu'on concatene le nom du tenseur et du lora au nom choisis par l'utilisateur*<br>

🌎🌍🌏I use 'controls' to check return variables and give information; the two colors are used depending on the usage (other colors can be used in addition)<br>
*For example a multiplier coefficient for a UPScale<br>
Or the full name of the image when we concatenate the name of the tensor and the lora to the name chosen by the user*<br>

----
- ## 4 Ksampler
<img src="images/ksampler.png">

Pour un plus grand contraste j'utilise la couleur rouge --
For greater contrast I use the color red<br>200-75-75<br>
<img src="images/ksampler-work.png" width="25%" height="25%">

----
- ## 5 DESACTIVE
<img src="images/inutile.png">

En NOIR (couleur par defaut) / In BLACK (default color)

<img src="images/noir-defaut.png" width="25%" height="25%">
<br>
Noeud minimisé / Minimised node<br>
<img src="images/null.png">

🔵⚪️🔴 Les noeuds non pertinents qui peuvent encombrer la lecteure et la comprehension du workflow<br>
Ou des noeuds "operateurs" genre "boite noire" qui font une serie d'action complexe utile au workflow mais dispensable pour l'UTILISATEUR<br>
🌎🌍🌏 Irrelevant nodes that can clutter the reader and the understanding of the workflow<br>
Or "operator" nodes like "black box" that make a series of complex actions useful to the workflow but dispensable for the USER

----
- ## 6 CLIP ENCODE
<img src="images/clip-remplace.png">

🔵⚪️🔴 Pour le prompt je separe le "CLIP Text Encode (Prompt) en deux parties<br>
Je convertis le "texte en entree/input"<br>
🌎🌍🌏 For the prompt I separate the "CLIP Text Encode (Prompt) into two parts<br>
I convert the "text to input"
<br>
<img src="images/cip-encode-widdget.png" width="25%" height="25%">

🔵⚪️🔴 Je relie l'entree a un "String Literal" (par defaut) dans lequel sera renseigne le texte du Prompt<br>
🌎🌍🌏 I connect the input to a "String Literal" (by default) in which the text of the Prompt will be entered
<br>
<img src="images/prompt-string-literal.png">

🔵⚪️🔴 J'applique le code couleur ; VERT pour le Prompt positif et ROUGE pour le Prompt negatif<br>
🌎🌍🌏 I apply the color code; GREEN for the positive Prompt and RED for the negative Prompt

----
- ## 7 CONTROL DIMENSION
- <img src="images/control-largeur.png">


- <img src="images/control-hauteur.png">

🔵⚪️🔴 J'utilse deux contrôles de variables pour controler la taille de l'image ce sont les couleurs par defaut :<br>
🌎🌍🌏 I use two variable controls to control the size of the image these are the default colors:<br>
Largeur / Width : bleu_pale<br>
Hauteur / Height : brown (maron)<br>
<img src="images/couleurs.png" width="25%" height="25%">

----
- ## 8 MISC

🔵⚪️🔴 Pour la preview image j'utilise egalement la couleur noire et uniquement "PREVIEW IMAGE"<br>
Je conseille d'utiliser les "SD" Prompt generator et Prompt Saver pour diverses raisons

🌎🌍🌏 For the preview image I also use black color and only "PREVIEW IMAGE"<br>
I recommend using the "SD" Prompt generator and Prompt Saver for various reasons

VIEILLES VERSIONS DE COMFYui :
https://github.com/comfyanonymous/ComfyUI/tags<br>
COMFYui Manger : https://github.com/ltdrdata/ComfyUI-Manager?tab=readme-ov-file

github : https://github.com/Dfalm-Original<br>
Youtube : https://www.youtube.com/@Dfalm
