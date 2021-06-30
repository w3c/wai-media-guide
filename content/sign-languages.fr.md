---
title: "Langues des signes"
title_image: /content-images/wai-media-guide/sign.svg
nav_title: "Langues des signes"

lang: fr   # change "en" to lang code, here and 2 @@s below
last_updated: 2020-01-02   # Change to date of translation YYYY-MM-DD (month in middle)
translators:
- name: "Sofia Ahmed"
- name: "Rémi Bétin"
contributors:
- name : "Sandra Velarde Gonzalez (ETNIC)"

permalink: /media/av/sign-languages/fr   # Add lang to end /link/to/page/@@
ref: /media/av/sign-languages/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'content/sign-languages.fr.md'   # Add lang to the middle of the filename, e.g., index.@@.md

resource:
  ref: /media/av/
navigation:
  previous: /media/av/transcripts/
  next:     /media/av/transcribing/
changelog: /media/av/changelog/
acknowledgements: /media/av/acknowledgements/

description: Vous aide à comprendre et à créer une interprétation en langue des signes pour l'accessibilité des contenus audios et vidéos.
image: /content-images/wai-media-guide/social.png

footer: >   # Translate words below, including "Date:" and "Editor:". (Do not update the date.)
   <p><strong>Date :</strong> Mise à jour : 10 septembre 2019. CHANGELOG.</p>
   <p><strong>Rédactrice :</strong> <a href="http://www.w3.org/People/Shawn">Shawn Lawton Henry</a>. ACKNOWLEDGEMENTS : liste les contributeurs et les crédits.</p>
   <p>Développé par le groupe de travail Éducation et Promotion (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Rédigé initialement dans le cadre du projet <a href="https://www.w3.org/WAI/WCAGTA/">WCAG TA</a> financé par le <abbr title="United States">U.S.</abbr> Access Board. Révisé dans le cadre du projet <a href="https://www.w3.org/WAI/expand-access/">WAI Expanding Access</a> financé par la fondation Ford.</p>

---

{::nomarkdown}
{% include box.html type="start" title="Résumé" class="" %}
{:/}

Cette page vous aide à comprendre et à créer une interprétation en langue des signes pour du contenu audio et vidéo.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include toc.html type="start" title="Table des matières" %}
{:/}

- This will be replaced by an automatically generated TOC when using Markdown formatting.
{::options toc_levels="2,3" /}
{:toc}

{::nomarkdown}
{% include toc.html type="end" %}
{:/}

## Introduction

{% include image.html src="signing-person.jpg" alt="" class="normal right" %}

Les langues des signes utilisent les mouvements des mains et des bras, les expressions faciales, et les positions du corps pour transmettre un sens.

La langue des signes est la langue maternelle de nombreuses personnes sourdes. Certaines d'entre elles ne savent pas lire ou comprendre le langage écrit correctement &mdash; notamment à la vitesse de la plupart des sous-titres.

Certaines personnes voudront voir la langue des signes et les sous-titres en même temps.

Toutes les personnes sourdes ne connaissent pas la langue des signes, en particulier si elles deviennent sourdes ou malentendantes sur le tard. Certaines personnes lisent sur les lèvres pour comprendre la parole, ceci dit, cela n'entre pas dans les critères d'accessibilité.

Les langues des signes diffèrent selon les régions et les pays. Par exemple, la langue des signes américaine (ASL), la langue des signes britannique (BSL), et la langue des signes australienne (l'Auslan) sont toutes différentes.

Certains efforts sont fait pour fournir une langue des signes automatique à partir du texte ; cependant, les avatars qui simulent l'interprétation de la langue des signes ne sont pas suffisamment robustes.

## Réglementations standards

La langue des signes n'est pas requise dans la plupart des réglementations pour l'accessibilité Web.
Le standard des WCAG situent la langue des signes au niveau AAA. _(La page "Production" de cette ressouce introduit le [standard des WCAG](/media/av/planning/#wcag-standard).)_

## Compétences et outils

Pour inclure des alternatives à la langue des signes, vous aurez besoin de personnes, de compétences, et d'outils pour :
* faire l'interprétation de la langue des signes
* l'enregistrer
* la monter avec le fichier audio ou vidéo

## Exemple

Exemple de langue des signes dans une vidéo :[Publicité du NHS 111 en langue des signes britannique (BSL) (Youtube)<br>{% include image.html src="sign-example.jpg" alt="" class="large video" %}](https://www.youtube.com/watch?v=TCq3ru9HQSc)

## Création d'alternatives à la langue des signes

Utilisez des couleurs faciles à distinguer - _production, enregistrement_
: il est généralement préférable que les couleurs du fond et de l'habit de l'interprète en langue des signes soient prononcées et contrastent avec sa couleur de peau.

Utilisez une bonne luminosité - _production, enregistrement_
: Prévoyez une bonne luminosité pour rendre l'interprète correctement visible.

Filmez l'espace consacré à la langue des signes dans son intégralité  - _enregistrement_
: Pour la plupart des langues des signes, l'espace consacré à la langue des signes s'étend de bien plus bas que la taille jusqu'au dessus de la tête et au moins à une largeur de coude de chaque côté.

Assurez-vous que l'interprète de la langue des signes soit suffisamment grand - _post-production_
: les téléspectateurs doivent être capables de voir correctement tous les mouvements et les expressions faciales.

Évitez de dissimuler du contenu important - _post-production_
: positionnez l'interprète de la langue des signes de manière à éviter de dissimuler des informations importantes dans la vidéo. Il se trouve habituellement en bas à droite. Si votre vidéo contient des informations telles qu'un bandeau déroulant d'actualité, positionnez l'interprète de la langue des signes par-dessus : Idéalement, lorsque la vidéo a été réalisée, la position de l'interprète était prévue, comme indiqué sur une autre page de cette ressource : [Production pour la langue des signes - storyboarding, enregistrement](/media/av/av-content/#plan-for-sign-language--storyboarding-recording).

Rendez la (les) vidéo(s) facile à découvrir et à utiliser
: Facilitez l'accès à la vidéo avec la langue des signes et à la vidéo sans langue des signes.
: Par exemple, juste sous le lecteur multimédia, incluez un grand bouton d'activation et/ou une image libellées pour la (les) vidéo(s) avec la langue des signes.<br><img src="{{ "/content-images/wai-media-guide/sign-button.png" | relative_url }}" alt="" style="max-width: 162px">
{:.paragraph-like}

Il existe des ressources sur le Web qui fournissent des informations supplémentaires sur la création d'alternatives à la langue des signes. Par exemple :
* [Interprétation en langue des signes sur le HBBTV (PDF){% include_cached external.html %}](http://pagines.uab.cat/hbb4all/sites/pagines.uab.cat.hbb4all/files/sign_language_interpreting_in_hbbtv.pdf) comprend des informations spécifiques sur des aspects tels que collaborer avec des interprètes en langue des signes et les types de présentation à l'écran
* Des conseils pour la production de livres sur la langue des signes comprend [Une présentation de la langue des signes {% include_cached external.html %}](http://www.sign-lang.uni-hamburg.de/signingbooks/deliver/d31/deliv_31_part3-2.html#3.2.2.6) et [Édition {% include_cached external.html %}](http://www.sign-lang.uni-hamburg.de/signingbooks/sbrc/grid/d71/guide13.htm)
