---
title: "Lecteurs multimédia"
title_image: /content-images/wai-media-guide/player-nobackground.svg
nav_title: "Lecteur multimédia"

lang: fr   # change "en" to lang code, here and 2 @@s below
last_updated: 2020-10-28   # Change to date of translation YYYY-MM-DD (month in middle)
# translator: "..."
Translators:
-name: Sofia Ahmed
# contributors: "..."

permalink: /media/av/player/fr   # Add lang to end /link/to/page/@@
ref: /media/av/player/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'content/player.fr.md'   # Add lang to the middle of the filename, e.g., index.@@.md

resource:
  ref: /media/av/
navigation:
  previous: /media/av/av-content/
  next: /media/av/description/
changelog: /media/av/changelog/
acknowledgements: /media/av/acknowledgements/

description: Introduit les considérations à prendre en compte pour fournir un lecteur multimédia qui accepte l'accessibilité.
image: /content-images/wai-media-guide/social.png

footer: >   # Translate words below, including "Date:" and "Editor:". (Do not update the date.)
   <p><strong>Date :</strong> Mise à jour 10 septembre 2019. JOURNAL DES MODIFICATIONS.</p>
   <p><strong>Auteur :</strong> <a href="http://www.w3.org/People/Shawn">Shawn Lawton Henry</a>. REMERCIEMENTS : liste les contributeurs et les crédits.</p>
   <p>Développé par le Groupe de travail Education et formation (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Rédigé initialement dans le cadre du projet <a href="https://www.w3.org/WAI/WCAGTA/">WCAG TA</a> financé par le <abbr title="United States">U.S.</abbr> Access Board. Révisé dans le cadre du projet <a href="https://www.w3.org/WAI/expand-access/">WAI Expanding Acess</a> financé par la fondation Ford.</p>

---

{::nomarkdown}
{% include box.html type="start" title="Résumé" class="" %}
{:/}

Certains lecteurs multimédia ne sont pas accessibles pour les personnes handicapées. Il existe des lecteurs développés spécifiquement pour l'accessibilité. Il est généralement préférable d'utiliser un de ces lecteurs existants, plutôt que d'en développer un nouveau.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include toc.html type="start" title="Table des matières" %}
{:/}

- This will be replaced by an automatically generated TOC when using Markdown formatting.
{:toc}

{::nomarkdown}
{% include toc.html type="end" %}
{:/}

## Introduction

Les navigateurs modernes fournissent un lecteur multimédia par défaut. Les fonctionnalités limitées de la plupart de ces lecteurs n'acceptent pas l'accessibilité.

Plutôt que de développer un lecteur multimédia qui accepte l'accessibilité, la majeure partie des organisations choisissent d'utiliser un lecteur déjà existant  l'accessibilité.

Il existe des lecteurs développés spécifiquement pour l'accessibilité. Certains sont gratuits, open source, et d'autres sont commerciaux.

## Compétences requises {#skills}

L'utilisation d'un lecteur multimédia déjà existant requiert des compétences modérées en HTML.

Le développement de votre propre lecteur multimédia accessible requiert des compétences avancées en HTML et en JavaScript.

## Les fonctionnalités d'un lecteur accessible

Les lecteurs multimédia accessibles fournissent une interface utilisateur qui fonctionne sans souris, grâce à l'interface vocale, lorsque la page est agrandie, et avec des lecteurs d'écran. Par exemple, les lecteurs multimédia doivent :
* Fournir une assistance au clavier dans ([Comprendre les WCAG : Accessible au clavier](https://www.w3.org/WAI/WCAG21/Understanding/keyboard-accessible))
* Rendre l'indicateur du focus clavier visible dans ([Comprendre les WCAG : Visibilité du focus](https://www.w3.org/WAI/WCAG21/Understanding/focus-visible))
* Fournir des étiquettes claires dans ([Comprendre les WCAG : Étiquettes ou instructions](https://www.w3.org/WAI/WCAG21/Understanding/labels-or-instructions), [Information et relations](https://www.w3.org/WAI/WCAG21/Understanding/info-and-relationships))
* Avoir un contraste suffisant entre les couleurs du texte, des commandes, et des fonds dans ([Comprendre les WCAG : Contraste (minimum)](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum), [Contraste (amélioré)](https://www.w3.org/WAI/WCAG21/Understanding/contrast-enhanced), [Contraste non textuel](https://www.w3.org/WAI/WCAG21/Understanding/non-text-contrast.html))

Certains lecteurs multimédia fournissent aux utilisateurs des fonctionnalités d'accessibilité supplémentaires telles que :
* Modifier la vitesse de la vidéo
* Paramétrer la manière dont les sous-titres apparaissent (par exemple, le style, la taille, et les couleurs du texte, ainsi que la position des sous-titres)
* Lire les sous-titres à l'aide d'un lecteur d'écran et d'un outil baille
* Des transcriptions interactives

Les transcriptions interactives utilisent le fichier des sous-titres. Les transcriptions interactives mettent en surbrillance les phrases de texe au moment où elles sont dites. Les utilisateurs peuvent sélectionner le texte dans la transcription et aller au même endroit dans la vidéo.

<img src="{{ "/content-images/wai-media-guide/interactive-transcript.png" | relative_url }}" alt="">

Retrouvez plus de détails sur les fonctionnalités d'un lecteur accessible sur ce document à part : [Exigences des utilisateurs en matière d'accessibilité des contenus multimédia](https://www.w3.org/TR/media-accessibility-reqs/).

## Lecteurs déjà existants

Il existe des informations en ligne en matière d'accessibilité des lecteurs multimédia. Par exemple, [Tableau comparatif de l'accessibilité des lecteurs multimédia sur le Web _(dernière mise à jour : juillet 2016)_ {% include_cached external.html %}](http://kensgists.github.io/apt/).

Chaque lecteur multimédia fournit de la documentation sur les étapes à suivre pour les installer sur une page Web. Par exemple, [Les étapes d'installation d'<em>AblePlayer</em> {% include_cached external.html %}](https://ableplayer.github.io/ableplayer/#setup-step-1-use-html5-doctype).

### Compatibilité pour les modes de description

Les fonctionnalités de lecteur multimédia sont nécessaires pour certains modes d'audiodescription des informations visuelles, comme décrit dans la page [Description](/media/av/description/). À notre connaissance, les lecteurs multimédia suivants fournissent de telles fonctionnalités :
* Lit la description dans un fichier de données (format VTT):
   * AblePlayer : lit la description lorsqu'il y a de l'espace dans l'audio, et lorsque la vidéo doit être mise en pause ("description étendue")
   * video.js : lit la description lorsqu'il y a de l'espace dans l'audio ; ne lit **pas** la description lorsque la vidéo doit être mise en pause ("description étendue")
* Lit un fichier audio séparé avec description :
   * AblePlayer
   * OzPlayer
   * video.js : avec plug-in

_(Si vous connaissez d'autres lecteurs qui fournissent ces fonctionnalités, faites-le nous savoir via GitHub ou par courriel avec les liens sur [Aider à améliorer cette page](#helpimprove). Merci !)_
