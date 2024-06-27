# <b>EcorcIA</b>, une application mobile pour téléphone intelligent Android

## Avec TensorFLow Lite Model Maker et Android Studio

## Introduction

Cours VIARENA - applications de la VIsion ARtificielle dans les REssources NAturelles.

Dans ce laboratoire vous allez créer une application mobile capable d'identifier
un arbre à partir de l'image de son écorce captée par la caméra d'un téléphone Android.

## Prérequis

[Connaissance d'Android Studio](http://developers.android.com/studio/preview)

<h3><b>Inspiration et droits d'auteur</b></h3>

<p>Ce laboratoire s'inspire de plusieurs oeuvres en logiciels libres qui ont été transformées dont:</p>
<ul>
  <ul>
    <li><a href="https://www.tensorflow.org/lite/guide/model_maker" target='_blank'>TensorFlow Lite Model Maker</a> - site Google / Guide TensorFlow pour mobile et objet connecté</li>
    <li><a href="https://codelabs.developers.google.com/codelabs/recognize-flowers-with-tensorflow-on-android/#0" target='_blank'>Recognize Flowers with TensorFlow Lite on Android</a> - Un Codelabs de Google Developers par Hoi Lam (auteur d'une refonte), Yash Katariya (auteur original)</li>
    <li>Code source original sur GitHUB: <a href="https://github.com/hoitab/TFLClassify" target='_blank'>https://github.com/hoitab/TFLClassify</a></li>
    <li>Copyright (c) 2019-2024, The TensorFlow Authors</li>
    <li>Copyright (c) 2021, Hoi Lam, Yash Katariya</li>
    <li>Copyright (c) 2022-2024, Claude COULOMBE, adaptation et mise à jour du code</li>
  </ul>
</ul>

<p>Le contenu de ce laboratoire est sous licence <a href="https://creativecommons.org/licenses/by/4.0/deed.fr" target='_blank'>Creative Commons Attribution 4.0 (CC BY 4.0)</a>,<br/>et les exemples de code sont sous <a href="https://www.apache.org/licenses/LICENSE-2.0" target='_blank'>licence Apache 2.0</a>.</p>

<h3><b>Données</b></h3>

<p>Les données sur les écorces d'arbres proviennent de <a href="https://data.mendeley.com/research-data/?search=barknet">BarkNet</a>, une banque en données ouvertes sous licence MIT de 23 000 photos d'écorces d'arbres en haute résolution prises avec des téléphones intelligents par une équipe d'étudiants et de chercheurs du <a href="https://www.sbf.ulaval.ca/" target='_blank'>Département des sciences du bois et de la forêt de l'Université Laval</a> à Québec.</p>

## Support

**Attention!** Ce laboratoire ne s'exécute pas dans Google Colab, ni sur un serveur distant, ni dans un carnet IPython. Il nécessite l'installation de l'environnement de programmation « Android Studio » sur votre poste de travail. De plus, vous devez disposer d'un téléphone intelligent Android relativement récent (système Android 8 ou plus récent) pour tester l'application résultante.

Vous devez être conscient que nous ne pourrons offrir aucun support technique. Aussi, ce genre d'application a un durée de vie assez courte, de l'ordre de 18 mois à 2 ans à cause de l'évolution rapide des technologies sous-jacentes. D'ailleurs nous avons dû mettre à jour le code en 2024.

- Stack Overflow: https://stackoverflow.com/questions/tagged/tensorflow-lite+android-studio

- Cours VIARENA: Vous devez comprendre que nous ne pourrons offrir aucun support technique
en dehors du support communautaire du forum de ce cours.

## Licence

Copyright (C) 2020 The Android Open Source Project<br/>
Copyright (C) 2022-2024 Claude COULOMBE

<hr style="line-height=2;"/>
Sous licence Apache License, Version 2.0 (la "Licence");

Vous ne pouvez pas utiliser ce fichier sauf en conformité avec la licence.

Vous pouvez obtenir une copie de la licence à: http://www.apache.org/licenses/LICENSE-2.0

Sauf si requis par la loi applicable ou convenu par écrit, le logiciel
distribué sous la Licence est distribué sur une BASE "TEL QUEL",
SANS GARANTIE OU CONDITION D'AUCUNE SORTE, expresse ou implicite.
Consultez la Licence pour connaître les autorisations et limitations
spécifiques à la langue dans le cadre de la Licence.
<hr style="line-height=2;"/>
Licensed under the Apache License, Version 2.0 (the "License");

You may not use this file except in compliance with the License.

You may obtain a copy of the License at: http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
<hr style="line-height=2;"/>
