---
title: "Sous-titres"
title_image: /content-images/wai-media-guide/cc.svg
nav_title: "Sous-titres"

lang: fr   # change "en" to lang code, here and 2 @@s below
last_updated: 2021-06-30   # Change to date of translation YYYY-MM-DD (month in middle)
translators:
- name: "Sofia Ahmed"
- name: "Rémi Bétin"
contributors:
- name: "Sandra Velarde Gonzalez (ETNIC)"

permalink: /media/av/captions/fr  # Add lang to end /link/to/page/@@
ref: /media/av/captions/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'content/captions.fr.md'   # Add lang to the middle of the filename, e.g., index.@@.md

resource:
  ref: /media/av/
navigation:
  previous: /media/av/description/
  next:     /media/av/transcripts/
changelog: /media/av/changelog/
acknowledgements: /media/av/acknowledgements/

description: Vous aide à comprendre et à créer des sous-titres pour l'accessibilité des contenus audios et vidéos.
image: /content-images/wai-media-guide/social.png

footer: >   # Translate words below, including "Date:" and "Editor:". (Do not update the date.)
   <p><strong>Date :</strong> Mise à jour : 24 février 2021. Première publication en septembre 2019 CHANGELOG.</p>
   <p><strong>Rédactrice :</strong> <a href="http://www.w3.org/People/Shawn">Shawn Lawton Henry</a>. ACKNOWLEDGEMENTS liste les contributeurs et les crédits.</p>
   <p>Développé par le groupe de travail Éducation et promotion (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Rédigé initialement dans le cadre du projet <a href="https://www.w3.org/WAI/WCAGTA/">WCAG TA</a> financé par le <abbr title="United States">U.S.</abbr> Access Board. Révisé dans le cadre du projet <a href="https://www.w3.org/WAI/expand-access/">WAI Expanding Access</a> financé par la fondation Ford.</p>

---

{::nomarkdown}
{% include box.html type="start" title="Résumé" class="" %}
{:/}

Les sous-titres fournissent du contenu aux personnes sourdes et malentendantes. Les sous-titres sont une version texte de l'information parlée ou non parlée nécessaire pour comprendre le contenu. Ils sont synchronisés avec l'audio et généralement affichés dans le lecteur multimédia quand les utilisateurs les activent.

Cette page vous aide à comprendre et à créer des sous-titres.

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

_Qui :_ Les sous-titres (aussi appelés "sous-titres intralinguistiques") fournissent du contenu pour les personnes sourdes et celles qui ne peuvent pas entendre l'audio. Elles sont aussi utilisées par les personnes qui comprennent plus facilement l'information écrite plutôt que l'audio.

{% include image.html src="captions.png" alt="" class="normal right" %}

_Quoi :_ Les sous-titres sont une version texte de l'information audio parlée ou non, nécessaire à la compréhension du contenu. Ils apparaissent dans le lecteur multimédia et sont synchronisées avec l'audio.

La plupart sont des "sous-titres codés" qui peuvent être masquées ou activées par les personnes qui regardent la vidéo. Ils peuvent également être des "sous-titres décodés" qui apparaissent en continu sans possibilité de les désactiver.

### Sous-titres

Les termes anglais <em lang="en">captions</em> et <em lang="en">subtitles</em> sont utilisés pour désigner la même chose dans différentes régions dans le monde. Dans sa version originale en anglais, cette ressource utilise les termes :
* _<em lang="en">Captions</em>_ pour la même langue que l'audio parlé.
* _<em lang="en">Subtitles</em>_ pour l'audio parlé traduit dans une autre langue.

Certaines régions utilisent le mot _sous-titres_ à la fois pour la même langue que l'audio parlé et pour la traduction. Parfois, ils sont parfois distingués sous la forme de _sous-titres intralinguistiques_ (même langue) et _sous-titres interlinguistiques_ (langue différente).

Les sous-titres intralinguistiques (en anglais <em lang="en">captions</em>) sont implémentés de la même manière que les sous-titres interlinguistiques (en anglais <em lang="en">subtitles</em>). Généralement, les sous-titres interlinguistiques transcrivent uniquement l'audio parlé (pour les personnes qui peuvent entendre l'audio mais qui ne connaissent pas la langue parlée). Ils peuvent être une traduction des sous-titres intralinguistiques, en incluant l'information audio non parlée.  

Les sous-titres intralinguistiques sont nécessaires pour l'accessibilité, alors que les sous-titres dans d'autres langues ne sont pas directement utiles à l'accessibilité.

### Les sous-titres en direct

Les sous-titres en direct sont généralement produits par des professionnels du sous-titrage en temps réel (également appelés professionnels de la traduction en temps réel des communications (CART)). Les sous-titres en direct peuvent être effectués sur place ou à distance. Cela signifie que la personne qui fait le sous-titrage/CART ne se trouve pas nécessairement là où a lieu l'action en direct ; elles peuvent créer les sous-titres en écoutant l'audio depuis un téléphone portable ou une connexion Internet.

Si vous avez des sous-titres en direct et que vous postez un enregistrement, vous devrez probablement effectuer quelques retouches pour en assurer l'exactitude.

Le reste de cette page concerne la création de sous-titres pour les contenus multimédias pré-enregistrés.

### Transcriptions interactives à partir des sous-titres
{:.no_toc}

Les fichiers de sous-titres sont utilisés par certains lecteurs multimédias pour fournir des _transcriptions interactives_. Celles-ci surlignent les phrases de texte lorsqu'elles sont prononcées. Les utilisateurs peuvent sélectionner du texte dans la transcription et atteindre cet instant dans la vidéo. Certains lecteurs fournissent une fonctionnalité de transcription interactive.

<img src="{{ "/content-images/wai-media-guide/interactive-transcript.png" | relative_url }}" alt="">

### À noter
{:.no_toc}

Pour une accessibilité optimale, fournissez un fichier de sous-titres séparé pour la description audio.

**Les sous-titres et les transcriptions contiennent le même texte, les unes pouvant donc être utilisées pour créer les autres.**

## Mon contenu multimédia nécessite-t-il des sous-titres ? {#checklist}

Cette section vous indique :
* Ce qui est requis par le standard des WCAG aux niveaux A, AA, et AAA. _([Les WCAG](/media/av/planning/#wcag-standard) sont introduites dans la page Planifier de cette ressource.)_
* Ce qui est nécessaire pour satisfaire les besoins des utilisateurs, au-delà des WCAG. S'il n'y a pas de "A", alors ce n'est pas requis par les WCAG.

{% capture boxhead %}
Contenu seulement audio (par exemple, les podcasts) :
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="checklist-ao" %}
{:/}

*   Pour un contenu pré-enregistré :
    *   Les sous-titres sont utiles pour les personnes malentendantes pour comprendre les subtilités de l'audio et combler ce qu'elles n'ont pas bien entendu en lisant les sous-titres.<br>Les sous-titres ne sont pas requis pour répondre aux WCAG. (Les transcriptions sont de niveau A.)
    {:.alt}
*   Pour un contenu diffusé en direct :
    *   Les sous-titres sont utiles pour les personnes malentendantes pour comprendre les subtilités de l'audio et combler ce qu'elles n'entendent pas bien en lisant les sous-titres.<br>La mise à disposition d'un flux textuel en direct ou d'un scénario fidèle à l'audio est demandée par les WCAG au niveau AAA.
    {:.alt}

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{% capture boxhead %}
Contenu seulement vidéo (pas de contenu audio) :
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="checklist-vo" %}
{:/}

*   Pour un contenu pré-enregistré et en direct :
    *   Les sous-titres ne sont pas nécessaires parce qu'il n'y a pas d'information audio.

{::nomarkdown}
{% include box.html type="end" %}
{:/}


{% capture boxhead %}
Vidéo avec du contenu audio :
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="checklist-va" %}
{:/}

La vidéo contient-elle des informations audios nécessaires à la compréhension du message véhiculé par la vidéo ?

*   Si non (par exemple, il s'agit juste d'une musique de fond) :
    *   Les sous-titres ne sont pas nécessaires car il n'y a pas de contenu audio important. Pensez à [informer les utilisateurs](/media/av/planning/#none).
*   Si oui :
    *   Pour un contenu pré-enregistré :
        *   Les sous-titres sont nécessaires pour délivrer le contenu audio aux personnes sourdes ou malentendantes.
            Les sous-titres sont _**requis**_ dans les WCAG au niveau A.
        {:.alt}
    *   Pour une vidéo en direct :
        *   Les sous-titres sont nécessaires pour délivrer le contenu audio aux personnes sourdes ou malentendantes.
            Les sous-titres sont _**requis**_ dans les WCAG au niveau AA.
        {:.alt}

{::nomarkdown}
{% include box.html type="end" %}
{:/}

<br>

**Extraits des WCAG** avec des liens vers plus d'informations dans "Comprendre les WCAG" :
* [A 1.2.2 Sous-titres](https://www.w3.org/WAI/WCAG21/Understanding/captions-prerecorded.html) (pré-enregistrés) : fournir des sous-titres pour tout contenu audio pré-enregistré dans un média synchronisé...
* [AA 1.2.4 Sous-titres](https://www.w3.org/WAI/WCAG21/Understanding/captions-live.html) (en direct) : fournir une audio-description pour tout contenu vidéo pré-enregistré, sous forme de média synchronisé.

## Compétences et outils

La création de sous-titres nécessite de taper à l'ordinateur l'audio ("transcription") et de le formater dans un fichier avec des horodatages. La transcription d'un fichier audio est relativement difficile et prend un certain temps pour les personnes qui n'ont pas le logiciel et les compétences requises pour un tel exercice. Le format de fichier pour les sous-titres est simple, mais ajouter les horodatages est fastidieux, particulièrement sans un logiciel ou un service de création de fichiers de sous-titres.

La création de sous-titres de haute qualité nécessite de savoir quelles informations audios non vocales doivent être incluses dans les sous-titres. Cela relève plus de l'art que de la science &mdash; par exemple, il n'est pas toujours évident d'identifier les informations audios non vocales à inclure et de savoir comment les communiquer sous forme de texte.

Même la correction d'un fichier de sous-titres peut prendre un certain temps pour des personnes qui ne le font pas régulièrement.

En revanche, les personnes qui ont le logiciel, les compétences et de l'expérience dans la création de sous-titres, peuvent les créer bien plus rapidement.

Pour ces raisons, de nombreuses organisations choisissent de sous-traiter la création de leurs sous-titres.

## Les sous-titres automatiques ne suffisent pas

Les sous-titres générés automatiquement ne répondent pas aux besoins des utilisateurs ou aux exigences d'accessibilité, sauf s'il a été vérifié qu'ils sont tout à fait fidèles à l'audio. Généralement, ils nécessitent d'importantes révisions.

Il existe des outils qui utilisent une technologie de reconnaissance vocale pour transformer une bande sonore en un fichier de sous-titres synchronisées. Par exemple, certaines sites Web de vidéos connus fournissent des sous-titres automatiques synchronisées. Cependant, le texte des sous-titres contient souvent des erreurs et ne correspond pas à l'audio ; parfois d'une façon qui en change le sens (ou est embarrassante). Par exemple, oublier un seul mot tel que "pas" peut créer une contradiction entre les sous-titres et le contenu réel de l'audio.

{::nomarkdown}
{% include box.html type="start" title="Exemple de sous-titres automatiques mal transcrits (pouvant provoquer un incendie)" class="simple aside"  %}
{:/}

{% include image.html src="food-fire.jpg" alt="" class="normal right" %}
  _Texte énoncé :_<br>&quot;Grillez à feu vif pendant <strong>4 à 5 minutes</strong>. Ne préchauffez <strong>pas</strong> le four.&quot;<br>
  _Sous-titre automatique :_<br>&quot;Grillez à feu vif pendant <strong>45 minutes</strong>. <strong>Préchauffez</strong> le four.&quot;

{::nomarkdown}
{% include box.html type="end" %}
{:/}

Les sous-titres automatiques peuvent être utilisés comme un point de départ pour la création de sous-titres et de transcriptions fidèles à l'audio.

## Créer des sous-titres

### Format d'un fichier de sous-titres

Le format le plus connu pour les sous-titres sur le Web est le [WebVTT](https://www.w3.org/TR/webvtt/) : le <i lang="en">Web Video Text Tracks Format</i> (format des pistes de texte vidéo sur le Web).

{::nomarkdown}
{% include box.html type="start" title="Exemple de fichier VTT dont les locuteurs sont identifiés" class="" %}
{:/}

```
WEBVTT

00:11.000 --> 00:13.000
<v Rajwinder Kaur>Bienvenue sur ce podcast.

00:13.000 --> 00:17.000
<v Shawn Henry>Merci pour cette opportunité de partager des informations sur l'accessibilité.

00:17.000 --> 00:20.000
<v Rajwinder>Commencez peut-être par nous en dire un peu plus sur votre rôle au sein de W3C ?

00:20.000 --> 00:24.000
<v Shawn>Je travaille au sein de l'initiative pour l'accessibilité du Web, W-A-I, que l'on prononce "wey".
```

{::nomarkdown}
{% include box.html type="end" %}
{:/}

D'autres formats de sous-titres existent : le <i lang="en">Timed Text Markup Language</i> ([TTML](https://www.w3.org/TR/ttml2/)) et le [SRT](https://matroska.org/technical/specs/subtitles/srt.html).

### Outils de sous-titrage

La plupart des personnes ont recours à un logiciel ou à des services pour les aider à créer des sous-titres. Il existe plusieurs logiciels de sous-titrage et services en ligne gratuits.

Plusieurs outils gratuits et payants génèrent des sous-titres automatiques que vous pouvez utiliser comme point de départ. Par exemple, un site Web de vidéos connu inclut des sous-titres automatiques et des outils pour vous permettre d'éditer les sous-titres. **Vous devrez éditer les sous-titres automatiques pour en assurer l'exactitude.**

Si vous disposez déjà d'une transcription de l'audio sous forme de texte, il existe des outils gratuits qui génèrent un fichier de sous-titres avec des horodatages. Vous devrez l'éditer pour ajuster les sauts de ligne, comme précisé dans une autre page de cette ressource, <em>Transcrire un contenu audio en texte</em> : [Plus d'informations sur les sous-titres](/media/av/transcribing/#more-on-captions).

La plupart des outils d'édition de sous-titres permettent d'exporter une transcription en texte brut.

<img src="{{ "/content-images/wai-media-guide/caption-editing.png" | relative_url }}" alt="" style="width: 50%; max-width: 500px"><br>_La capture d'écran montre un outil servant à éditer des sous-titres, dans une zone en-dessous de la vidéo._

### Transcrire du contenu audio en texte

Retrouvez des conseils spécifiques sur ce qu'il faut taper dans une autre page de cette ressource : [Transcrire un contenu audio en texte](/WAI/media/av/transcribing/).

## Positionner et styliser les sous-titres

Des options existent pour aider les auteurs à déterminer la position et le style des sous-titres. Le support par les navigateurs et les autres lecteurs multimédia est variable et parfois peu fiable. La plupart des vidéos sur le Web utilisent simplement le style de présentation par défaut du lecteur, c'est-à-dire généralement des caractères blancs dans un bandeau noir.

Certains lecteurs multimédia permettent aux utilisateurs de paramétrer où et comment les sous-titres vont apparaître, notamment le style du texte, la taille des caractères, les couleurs, et la position des sous-titres.