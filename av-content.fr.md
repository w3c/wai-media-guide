---
title: "Contenu audio et contenu vidéo"
title_image: /content-images/wai-media-guide/av-content.svg
nav_title: "Contenu audio et contenu vidéo"

lang: fr   # change "en" to lang code, here and 2 @@s below
last_updated: 2020-10-27   # Change to date of translation YYYY-MM-DD (month in middle)
# translator: "..."
# contributors: "..."

permalink: /media/av/av-content/fr   # Add lang to end /link/to/page/@@
ref: /media/av/av-content/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'content/av-content.fr.md'   # Add lang to the middle of the filename, e.g., index.@@.md

resource:
  ref: /media/av/
navigation:
  previous: /media/av/planning/
  next:     /media/av/player/
changelog: /media/av/changelog/
acknowledgements: /media/av/acknowledgements/

description: Décrit les considérations pour l'accessibilité lors de la planification, de la création du scénario et du story-board, de l'enregistrement, et de la production de contenus audios et vidéos.  
image: /content-images/wai-media-guide/social.png

footer: >   # Translate words below, including "Date:" and "Editor:". (Do not update the date.)
   <p><strong>Date :</strong> Mise à jour 1 October 2020. JOURNAL DES MODIFICATIONS.</p>
   <p><strong>Auteur :</strong> <a href="http://www.w3.org/People/Shawn">Shawn Lawton Henry</a>. REMERCIEMENT liste les contributeurs et les crédits.</p>
   <p>Développé par le Groupe de travail Education et formation (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Rédigé initialement dans le cadre du projet <a href="https://www.w3.org/WAI/WCAGTA/">WCAG TA</a> financé par le <abbr title="United States">U.S.</abbr> Access Board. Révisé dans le cadre du projet <a href="https://www.w3.org/WAI/expand-access/">WAI Expanding Acess</a> financé par la fondation Ford.</p>

---

{::nomarkdown}
{% include box.html type="start" title="Résumé" class="" %}
{:/}

Cette page décrit les considérations pour l'accessibilité lors de la planification, de la création du scénario et du story-board, de l'enregistrement, et de la production de contenus audios et vidéos.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::options toc_levels="2,3" /}
{::nomarkdown}
{% include toc.html type="start" title="Table des matières" %}
{:/}

- This will be replaced by an automatically generated TOC when using Markdown formatting.
{:toc}

{::nomarkdown}
{% include toc.html type="end" %}
{:/}

## Introduction
{:.no_toc}

Cette page décrit les considérations pour l'accessibilité lors de la planification, de la création du scénario et du story-board, de l'enregistrement, et de la production de contenus audios et vidéos.

Certaines des recommandations ci-dessous sont liées aux critères repris dans les Règles pour l'accessibilité des contenus Web (WCAG) et contiennent des liens vers une ressource à part. _(La page sur la planification de cette ressource introduit le [standard WCAG](/media/av/planning/#wcag-standard).)_ Other guidance is good practice.

## Audio

### Créez un contenu audio de haute qualité – _planification de l'enregistrement_

* Utilisez des micros de haute qualité et un logiciel d'enregistrement.
* Si possible, enregistrez dans un pièce isolée de tout bruit externe.
* Evitez les pièces aux surfaces dure, telles que le parquet ou le carrelage.

### Utilisez un arrière-plan sonore de faible volume  – _enregistrement, postproduction_ (WCAG AAA)

Lorsque le son principal est une personne qui parle et qu'il y a une musique de fond, réglez les niveaux de manière à ce que les personnes atteintes de troubles auditifs ou cognitifs puissent facilement distinguer le contenu parlé de la musique de fond.

Précisément, faites en sorte que l'arrière-plan sonore soit 20 décibels en dessous du contenu parlé d'avant-plan (avec une exception pour les sons occasionels qui ne durent qu'une ou deux secondes).  

Evitez les sons qui peuvent distraire ou déranger, tels que les sons aigus et répétitifs.  

<span style="color:#585858; font-style:italic;">Retrouvez plus d'informations sur [Comprendre le CS 1.4.7 : Arrière-plan sonore de faible volume ou absent (AAA)](https://www.w3.org/WAI/WCAG21/Understanding/low-or-no-background-audio.html).</span>

### Parlez clairement et lentement – _locuteurs_

Parlez clairement. C'est important pour les personnes qui souhaitent comprendre le contenu, et pour les sous-titres.

Parlez aussi lentement autant que cela soit approprié. Cela permettra aux auditeurs de mieux comprendre, et d'améliorer la synchronisation pour les sous-titres et la langue des signes.  

### Donnez aux auditeurs le temps de comprendre l'information – _locuteurs, postproduction_

Faites des pauses entre les différents sujets.

### Utilisez un langage clair – _scénario_

Evitez ou expliquez le jargon, les acronymes, et les idiomes. Par exemple, les expressions telles que "mettre la barre plus haut" peuvent être interprétées littéralement par certaines personnes souffrant de troubles cognitifs et celles-ci peuvent être perdues.

### Fournissez une redondance pour les caractéristiques sensorielles – _scénario_ (WCAG A)

Rendez votre information accessible aux personnes qui ne peuvent pas voir ou entendre.

Par exemple, au lieu de dire :
<blockquote>Fixez cela à l'extrémité verte.</blockquote>
Dites :
<blockquote>Fixez le petit anneau à l'extrémité verte, qui est l'extrémité la plus grande.</blockquote>

<span style="color:#585858; font-style:italic;">Retrouvez plus d'informations qui concernent principalement les pages Web, mais qui sont pertinentes pour les contenus audios et vidéos, sur [Comprendre le SC 1.3.3 : Caractéristiques sensorielles (A)](https://www.w3.org/WAI/WCAG21/Understanding/sensory-characteristics.html).</span>

## Vidéo

### Evitez les crises – _story-board, postproduction_ (WCAG A)

Evitez tout élément qui clignote plus de trois fois par seconde.

<span style="color:#585858; font-style:italic;">Retrouvez plus d'informations surMore information is in [Comprendre le CS 2.3.2 : Trois flashs (AAA)](https://www.w3.org/WAI/WCAG21/Understanding/three-flashes.html) et [Comprendre le CS 2.3.1: Pas plus de trois flashs ou sous le seuil critique (A)](https://www.w3.org/WAI/WCAG21/Understanding/three-flashes-or-below-threshold.html)</span>

### Prenez en compte la visibilité du locuteur – _story-board, enregistrement, postproduction_

Certaines personnes utilisent les mouvement de la bouche pour comprendre le langage. Lorsque c'est possible, assurez-vous que le visage du locuteur soit visible et bien éclairé.

### Rendez le texte superposé lisible – _story-board, postproduction_ (WCAG AA, AAA)

Pour tout texte, prenez en considération la famille de police, la taille, et le contraste entre le texte et le fond.

<span style="color:#585858; font-style:italic;">Retrouvez plus d'informations surMore information is in [Comprendre le CS 1.4.3 : Contraste (minimum) (AA)](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum.html) et [Comprendre le CS 1.4.6 : Contraste (amélioré) (AAA)](https://www.w3.org/WAI/WCAG21/Understanding/contrast-enhanced).</span>

### Planification pour la langue des signes – _story-board, enregistrement_ (WCAG AAA)

Parfois, les langues des signes sont fournies en superposition dans le coin en bas à droite des vidéos. Par exemple : [NHS 111 British Sign Language (BSL) Advert (YouTube)<br>{% include image.html src="sign-example.jpg" alt="" class="normal video" %}](https://www.youtube.com/watch?v=TCq3ru9HQSc)

Veillez à ce que la vidéo ne comprenne pas d'information importante qui pourrait être cachée par la superposition de la langue des signes.

Pour d'autres recommandations comprenant l'enregistrement, allez sur une autre page de cette ressource : [Langues des signes](/media/av/sign-languages/)

### Planification pour audiodescription des informations visuelles – _story-board, enregistrement_  (WCAG A, AA) {#plan-description}

La _description_ fournit du contenu pour les personnes aveugles et d'autres personnes qui ne peuvent pas voir la vidéo correctement. Elle décrit l'information visuelle nécessaire à la compréhension du contenu.

Planification pour soit :
* Intégrer une description des informations visuelles que les utilisateurs ont besoin de comprendre au sein du contenu audio principal,<br>_**ou**_
* Enregistrer du temps supplémentaire pour les scènes qui nécessitent une description des informations visuelles.

#### Intégrez une description

Pour de nombreuses vidéos, la meilleure façon de se charger de l'audiodescription est de ne pas en avoir besoin du toutFor many videos, the best way to handle audio description is not to need it at all &mdash; ce qui veut dire que toutes les informations visuelles nécessaires aux utilisateurs pour comprendre le contenu est intégré à l'audio principal. En planifiant d'avance, cela est relativement facile pour de nombreux types de vidéos sur le Web, telles que les vidéos de présentation ou d'instruction. Par exemple :

<table>
  <tr>
    <th scope="col">Au lieu que le locuteur dise :</th>
    <th scope="col">Le locuteur peut dire :</th>
  </tr>
  <tr>
    <td>Comme vous pouvez le voir sur ce graphique, les ventes ont augmenté au second quadrimestre depuis le premier quadrimestre.</td>
    <td>Ce graphique montre que les ventes ont augmenté significativement, de 1 million au premier quadrimestre, à 1,3 millions au second quadrimestre.</td>
  </tr>
  <tr>
    <td>Fouettez le mélange jusqu'à qu'il ressemble à ceci.</td>
    <td>Fouettez le tout jusqu'à ce que l'huile, le vinaigre, et les épices soient bien mélangés.</td>
  </tr>
  <tr>
    <td>Fixez cela à l'extrémité verte.</td>
    <td>Fixez le petit anneau à l'extrémité verte, qui est l'extrémité la plus grande.</td>
  </tr>
</table>

Retrouvez les recommandations sur ce qu'il faut inclure sur la page "Créer une audiodescription pour les informations visuelles",[Conseils pour écrire une section de description](/media/av/description/#writing).

#### La durée de la description

Pour certains types de vidéos, la description des informations visuelles ne peut pas être effectuée subtilement par les locuteurs de la vidéo principale, car cela rendrait la vidéo par défaut bien plus longue ou trop lourde. Pour ces vidéos, la description sera disponible à part.

Lorsque la description est relativement courte, prévoyez de l'espace dans l'audio pour l'ajouter.

Lorsque la description est plus longue et que vous voulez laisser de l'espace dans la vidéo principale, vous pouvez enregistrer un lapse de temps supplémentaire dans la scène pour intégrer la description sans devoir mettre la scène sur pause. En d'autres termes, la même scène est plus courte dans la vidéo principale. Dans la version décrite, cette même scène est légèrement plus longue au début et à la fin. Par exemple :

<table>
  <tr>
    <th scope="col">Narration</th>
    <th scope="col">Durée de la scène dans la vidéo principale</th>
    <th scope="col">Durée de la scène dans la vidéo décrite</th>
    <th scope="col">Description</th>
  </tr>
  <tr>
    <td><q>Les sous-titres sont également pratiques pour les personnes qui veulent regarder une vidéo dans des environnements bruyants.</q></td>
    <td>3&nbsp;secondes</td>
    <td>7&nbsp;secondes</td>
    <td>Un homme regarde une vidéo sous-titrée avec un groupe de personnes qui discutent à côté de lui.</td>
  </tr>
  <tr>
    <td><q>Ou lorsque vous devez être extrêmement calme.</q></td>
    <td>2&nbsp;secondes</td>
    <td>5&nbsp;secondes</td>
    <td>Il s'avère qu'ils sont dans une bibliothèque. La bibliotécaire fait signe au groupe de se taire.</td>
  </tr>
</table>

Retrouvez un exemple de ceci avec la vidéo : [L'accessibilité Web illustrée : les sous-titres de vidéo](/perspective-videos/captions/). La vidéo principale dure 48 secondes. La version décrite dure 1 minute et 18 secondes, pourtant, il n'y a aucune pause dans l'aspect visuel de la vidéo.

#### En savoir plus sur la description

Vous trouverez plus d'informations sur une autre page de cette ressource : [Audiodescription des informations visuelles](/media/av/description/).
