---
title: "Sous-titres"
title_image: /content-images/wai-media-guide/cc.svg
nav_title: "Sous-titres"

lang: fr   # change "en" to lang code, here and 2 @@s below
last_updated: 2020-01-01   # Change to date of translation YYYY-MM-DD (month in middle)
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

description: Vous aide à comprendre et à créer des légendes (aussi appelées "sous-titres") pour l'accessibilité des contenus audios et vidéos.
image: /content-images/wai-media-guide/social.png

footer: >   # Translate words below, including "Date:" and "Editor:". (Do not update the date.)
   <p><strong>Date :</strong> Mise à jour : 12 septembre 2020. CHANGELOG.</p>
   <p><strong>Rédactrice :</strong> <a href="http://www.w3.org/People/Shawn">Shawn Lawton Henry</a>. ACKNOWLEDGEMENTS : liste les contributeurs et les crédits.</p>
   <p>Développé par le groupe de travail Éducation et Promotion (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Rédigé initialement dans le cadre du projet <a href="https://www.w3.org/WAI/WCAGTA/">WCAG TA</a> financé par le <abbr title="United States">U.S.</abbr> Access Board. Révisé dans le cadre du projet <a href="https://www.w3.org/WAI/expand-access/">WAI Expanding Access</a> financé par la fondation Ford.</p>

---

{::nomarkdown}
{% include box.html type="start" title="Résumé" class="" %}
{:/}

Cette page vous aide à comprendre et à créer des légendes (aussi appelées "sous-titres").

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

_Qui :_ Les légendes (aussi appelées "sous-titre intralinguistiques") fournissent du contenu pour les personnes sourdes et celles qui ne peuvent pas entendre l'audio. Elles sont aussi utilisées par les personnes qui comprennent plus facilement l'information écrite plutôt que l'audio.

{% include image.html src="captions.png" alt="" class="normal right" %}

_Quoi :_ Les légendes sont une version texte de l'information audio parlée ou non, nécessaire à la compréhension du contenu. Elles apparaissent dans le lecteur multimédia et sont synchronisées avec l'audio.

La plupart sont des "légendes fermées" qui peuvent être masquées ou activées par les personnes qui regardent la vidéo. Elles peuvent également être des "légendes fermées" qui apparaissent en continu sans possibilité de les désactiver.

### Légendes

Les termes "légendes" et "sous-titres" sont utilisés pour désigner la même chose dans différentes régions dans le monde. Cette ressource utilise les termes :
* _Légendes_ pour la même langue que l'audio parlé.
* _Sous-titres_ pour l'audio parlé traduit dans une autre langue.

Certaines régions utilisent les _sous-titres_ à la fois pour la même langue et pour la traduction. Parfois, ils sont parfois distingués sous la forme de _sous-titres intralinguistiques_ (même langue) et _sous-titres interlinguistiques_ (langue différente).

Les sous-titres sont implémentés de la même manière que les légendes. Généralement, les sous-titres/les sous-titres interlinguistiques transcrivent uniquement l'audio parlé (pour les personnes qui peuvent entendre l'audio mais qui ne connaissent pas la langue parlée). Ils peuvent être une traduction des légendes, y compris de l'information audio non parlée.  

Les légendes sont nécessaires pour l'accessibilité, alors que les sous-titres dans d'autres langues ne sont pas directement utiles à l'accessibilité.

### Les légendes en direct

Les légendes en direct sont généralement produites par des professionnels du sous-titrage en temps réel (également appelés professionnels de l'accès à la communication par la traduction en temps réel (CART)). Les légendes en direct peuvent être effectuées sur place ou à distance, ce qui signifie que la personne qui fait le sous-titrage ou le CART ne se trouve pas là où a lieu l'action en direct ; elles peuvent sous-titrer en écoutant l'audio depuis un téléphone portable ou une connection internet.

Si vous avez des sous-titres en direct et que vous voulez poster un enregistrement, vous devrez probablement effectuer quelques retouches pour en assurer l'exactitude.

Le reste de cette page concerne la création de légendes pour les contenus multimédias pré-enregistrés.

### Transcriptions interactives à partir des légendes
{:.no_toc}

Les fichiers de légendes sont utilisés par certains lecteurs multimédias pour fournir des _transcriptions interactives_. Celles-ci surlignent les phrases de texte lorsqu'elles sont prononcées. Les utilisateurs peuvent sélectionner du texte dans la transcription et aller au même endroit dans la vidéo. Certains lecteurs fournissent une fonctionnalité de transcription interactive.

<img src="{{ "/content-images/wai-media-guide/interactive-transcript.png" | relative_url }}" alt="">

### Notes
{:.no_toc}

Pour une accessibilité optimale, fournissez un fichier de légendes séparé pour la description audio.

**Les légendes et les transcriptions comprennent le même texte, les unes pouvant donc être utilisées pour créer les autres.**

## Mon contenu multimédia nécessite-t-il des sous-titres ? {#checklist}

Cette section vous indique :
* Ce qui est requis par le standard des WCAG aux niveaux A, AA, et AAA.
 _([Les WCAG](/media/av/planning/#wcag-standard) sont introduites dans la page Production de cette ressource.)_
* Ce qui est nécessaire pour satisfaire les besoins des utilisateurs, au-delà des WCAG. S'il n'y a pas de "A", alors ce n'est pas requis par les WCAG.

{% capture boxhead %}
Contenu uniquement audio (par exemple, les podcasts):
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="checklist-ao" %}
{:/}

*   Pour le pré-enregistré :
    *   Les légendes sont utiles pour les personnes qui sont malentendantes pour comprendre les subtilités de l'audio et combler ce qu'elles n'ont pas bien entendu en lisant les légendes.<br>Les légendes ne sont pas requises pour répondre aux WCAG. (Transcriptions sont au niveau A.)
    {:.alt}
*   En direct :
    *   Les légendes sont utiles pour les personnes malentendantes pour comprendre les subtilités de l'audio et combler ce qu'ils n'entendent pas bien en lisant les légendes.<br>Retrouvez des informations sur une diffusion du texte en direct ou un script de l'audio disponible en direct dans les WCAG au niveau AAA.
    {:.alt}

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{% capture boxhead %}
Contenu uniquement vidéo (pas de contenu audio):
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="checklist-vo" %}
{:/}

*   Pour le pré-enregistré et le direct :
    *   Les légendes ne sont pas nécessaires parce qu'il n'y a pas d'information audio.

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
    *   Les légendes ne sont pas nécessaires car le contenu audio n'est pas important. Plus d'informations sur [informer les utilisateurs](/media/av/planning/#none).
*   Si oui :
    *   Pour le pré-enregistré :
        *   Les légendes sont nécessaires pour fournir du contenu audio aux personnes sourdes ou malentendantes.  
            Les légendes sont _**requises**_ dans les WCAG au niveau A.
        {:.alt}
    *   Pour le direct :
        *   Les légendes sont nécessaires pour fournir du contenu audio aux personnes sourdes ou malentendantes.  
            Les légendes sont _**requises**_ dans les WCAG au niveau AA.
        {:.alt}

{::nomarkdown}
{% include box.html type="end" %}
{:/}

## Compétences et outils

La création de légendes nécessite de taper à l'ordinateur l'audio ("transcription") et de le formater dans un fichier à l'aide d' horodatages. La transcription d'un fichier audio est relativement difficile et prend un certain temps pour les personnes qui n'ont pas de logiciel et de compétences requises pour un tel exercice. Le format de fichier pour les légendes est simple, cependant, ajouter les horodatages est fastidieux, particulièrement sans un logiciel ou un service de création de fichiers de légendes.  

La création de légendes de haute qualité nécessite de savoir quelles informations audios non vocales devraient être comprises dans les légendes. Cela relève plus de l'art que de la science --- par exemple, il n'est pas toujours évident d'identifier les informations audios non vocales à inclure et de savoir comment les communiquer sous forme de texte.

Même la correction d'un fichier de légendes peut prendre un certain temps si la personne n'a pas l'habitude de le faire.

Par contre, les personnes qui ont un logiciel, des compétences et de l'expérience dans le développement de légendes, peuvent les créer bien plus rapidement.

Pour ces raisons, de nombreuses organisations choisissent de sous-traiter la création de leurs légendes.

## Les légendes automatiques ne suffisent pas

Les légendes générées automatiquement ne répondent pas aux besoins des utilisateurs ou aux critères d'accessibilité, sauf s'il a été vérifié qu'ils sont tout à fait fidèles à l'audio. Généralement, ils nécessitent d'importantes révisions.

Il existe des outils qui utilisent une technologie de reconnaissance vocale pour transformer une bande sonore en fichier de légendes synchronisées. Par exemple, des sites Web de vidéos connus fournissent des légendes automatiques synchronisées. Cependant, le texte des légendes contient souvent des erreurs et ne paraît pas en même temps que l'audio ; parfois cela change le sens (ou cela est gênant). Par exemple, oublier un seul mot tel que "pas" peut rendre les légendes contredisent contenu de l'audio en question.

{::nomarkdown}
{% include box.html type="start" title="Exemple de légendes automatiques mal transcrites (qui peut provoquer un incendie)" class="simple aside"  %}
{:/}

{% include image.html src="food-fire.jpg" alt="" class="normal right" %}
  _Texte parlé :_<br>&quot;Grillez à feu vif pendant <strong>4 à 5 minutes</strong>. Ne préchauffez <strong>pas</strong> le four.&quot;<br>
  _Légende automatique :_<br>&quot;Grillez à feu vif pendant <strong>45 minutes</strong>. <strong>Préchauffez</strong> le four.&quot;

{::nomarkdown}
{% include box.html type="end" %}
{:/}

Les légendes automatiques peuvent être utilisées comme un point de départ pour la création de légendes et de transcriptions fidèles à l'audio.

## La création de légendes

### Format de fichier de légendes

Le format le plus connu pour les légendes sur le Web est le [WebVTT](https://www.w3.org/TR/webvtt/): Le Web Video Text Tracks Format (le format des pistes de texte vidéo sur le Web).

{::nomarkdown}
{% include box.html type="start" title="Exemple de fichier VTT dont les locuteurs sont identifiés" class="" %}
{:/}

```
WEBVTT

00:11.000 --> 00:13.000
<v Rajwinder Kaur>Bienvenue sur le podcast.

00:13.000 --> 00:17.000
<v Shawn Henry>Merci pour cette opportunité de partager des informations sur l'accessibilité.

00:17.000 --> 00:20.000
<v Rajwinder>Commencez peut-être par nous en dire un peu plus sur votre rôle au W3C.

00:20.000 --> 00:24.000
<v Shawn>Je travaille au sein du Web Accessibility Initiative, le W-A-I, prononcé "wey".
```

{::nomarkdown}
{% include box.html type="end" %}
{:/}

Voici d'autre formats de légendes : le Timed Text Markup Language ([TTML](https://www.w3.org/TR/ttml2/)) et le [SRT](https://matroska.org/technical/specs/subtitles/srt.html).

### Les outils de sous-titrage

La plupart des gens ont recours à un logiciel ou à des services pour les aider à créer des légendes. Il existe plusieurs programmes logiciels de sous-titrage ou services en ligne gratuits.

Plusieurs outils gratuits ou payants créent des légendes que vous pouvez utiliser comme point de départ. Par exemple, un site Web de vidéos connu inclut des légendes automatiques et des outils pour vous permettre d'éditer les légendes. **Vous devrez éditer les légendes automatiques par soucis de précision**

Si vous disposez déjà de la transcription de l'audio sous forme de texte, il existe des outils gratuits qui génèrent un fichier de légendes avec des horodatages. Vous devrez l'éditer à cause des sauts de page comme décrit dans une autre page de cette ressource, Transcrire du contenu audio en texte : [Plus d'informations sur les légendes](/media/av/transcribing/#more-on-captions).

La plupart des outils servant à éditer les légendes peuvent exporter une transcription textuelle simple.

<img src="{{ "/content-images/wai-media-guide/caption-editing.png" | relative_url }}" alt="" style="width: 50%; max-width: 500px"><br>_La capture d'écran montre un outil servant à éditer des légendes, en bas de la vidéo._

### Transcription de contenu audio en texte

Retrouvez plus d'aide sur comment taper sur une autre page de cette ressource : [Transcription de contenu audio en texte](/WAI/media/av/transcribing/).

## Position et style des légendes

Il existe des options pour aider les auteurs à déterminer la position et le style des légendes. Les supports dans les navigateurs et les autres lecteurs multimédia sont incohérents et parfois peu fiables. La plupart des vidéos Web utilisent simplement de style de présentation du lecteur par défaut, soit généralement des caractères blancs dans un bandeau noir.

Certains lecteurs multimédias permettent aux utilisateurs de paramétrer leurs préférences pour déterminer comment et où les légendes vont apparaître, en ce compris le style et la taille du texte, ainsi que la position des légendes.
