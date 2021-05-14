---
title: "Production des contenus audios et vidéos"
title_image: /content-images/wai-media-guide/planning.svg
nav_title: "Production"

lang: fr   # change "en" to lang code, here and 2 @@s below
last_updated: 2020-10-26   # Change to date of translation YYYY-MM-DD (month in middle)
translator:
- name: Sofia Ahmed

permalink: /media/av/planning/fr   # Add lang to end /link/to/page/@@
ref: /media/av/planning/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'content/planning.fr.md'   # Add lang to the middle of the filename, e.g., index.@@.md

resource:
  ref: /media/av/
navigation:
  previous: /media/av/
  next:     /media/av/av-content/
changelog: /media/av/changelog/
acknowledgements: /media/av/acknowledgements/

description: vous aide à prévoir comment rendre vos contenus audios et vidéos accessibles, que vous les sous-traitiez ou que vous les créiez en interne.  
image: /content-images/wai-media-guide/social.png

footer: >   # Translate words below, including "Date:" and "Editor:". (Do not update the date.)
   <p><strong>Date :</strong> Mise à jour 12 septembre 2020. CHANGELOG.</p>
   <p><strong>Auteur :</strong> <a href="http://www.w3.org/People/Shawn">Shawn Lawton Henry</a>. RERMERCIEMENTS : liste les contributeurs et les crédits.</p>
   <p>Développé par le groupe de travail Education et formation (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Rédigé initialement dans le cadre du projet <a href="https://www.w3.org/WAI/WCAGTA/">WCAG TA</a> financé par le <abbr title="United States">U.S.</abbr> Access Board. Révisé dans le cadre du projet <a href="https://www.w3.org/WAI/expand-access/">WAI Expanding Acess</a> financé par la fondation Ford.</p>

---

{::nomarkdown}
{% include box.html type="start" title="Résumé" class="" %}
{:/}

Cette page vous aide à :
* **comprendre quels aspects d'accessibilité sont nécessaires à vos contenus audios et vidéos spécifiques** (des sous-titres, une description, une transcription, etc.)
* gérer des projets et prévoir ce qu'il faut créer en interne et ce qu'il faut sous-traiter
* comprendre les **standards** pour les contenus audios et vidéos dans les Règles pour l'accessibilité des contenus Web (WCAG)

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include toc.html type="start" title="Table des matières" %}
{:/}

- This will be replaced by an automatically generated TOC when using Markdown formatting.
{::options toc_levels="2" /}
{:toc}

{::nomarkdown}
{% include toc.html type="end" %}
{:/}

## Introduction
{:.no_toc}

Pour du contexte, allez sur la page d'instruction de cette ressource  _[Rendre du contenu audio et vidéo accessible](/media/av/)_, pour :
* de courtes explications sur les sous-titres, les transcriptions, la description, la langue des signes, et l'accessibilité des lecteurs multimédia
* des expériences d'utilisateurs pour vous aider à comprendre le "pourquoi" les recommandations

Les caractéristiques d'accessibilité que vous fournissez avec votre contenu multimédia seront probablement influencés par :
* les besoins des utilisateurs
* les réglementations gouvernementales et autres exigences de réglementation
* le budget et les contraintes de temps

L'objectif de cette ressource est de vous aider à connaître les réglementations et de vous encourager à répondre à tous les besoins des utilisateurs.

## Check-lists pour les contenus audios et vidéos {#checklist}

Les check-lists reprises ci-dessous concernent les contenus uniquement audios, les contenus vidéos, et les contenus préenregistrés et en direct. Ils comprennent :
* Ce qui est requis par le standard des Règles pour l'accessibilité des contenus Web (WCAG) aux niveaux A, AA, et AAA.  _(Les [WCAG](#wcag-standard) sont expliquées ci-dessous.)_
* Ce qui est nécessaire pour répondre aux besoins des utilisateurs, au-delà des WCAG. (Si aucun A n'est attribué, c'est que le contenu n'est pas requis dans les WCAG.)

Les liens ci-dessous mènent à des pages Web liées à cette ressource qui contiennent des détails sur la compréhension et l'application de chaque recommandation.

{::nomarkdown}
{% include box.html type="start" title="Tous les contenus audios et vidéos" class="highlighted" id="checklist-all" %}
{:/}

- **[Contenu audio](/media/av/av-content/#audio) (A)** : est accessible (par exemple, au regard de ce qui est dit et de l'enregistrement)
- **[Contenu vidéo](/media/av/av-content/#video) (A)** : est accessible (par exemple, il ne provoque pas de crises)
- **[Lecteur multimédia](/media/av/player/) (A)** : est compatible avec l'accessibilité
{:.alt}

{::nomarkdown}
{% include box.html type="end" %}
{:/}

### <img src="{{ "/content-images/wai-media-guide/audio.svg" | relative_url }}" alt="" style="height:1.3em"> Check-lists des contenus uniquement audios

Cette section concerne les contenus uniquement audios, comme les podcasts qui ne contiennent pas de vidéo.
{% capture boxhead %}
<img src="{{ "/content-images/wai-media-guide/recorded.svg" | relative_url }}" alt="" style="height:1em"> Contenus uniquement audios préenregistrés
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="checklist-ap" %}
{:/}

-   **[Transcription](/media/av/transcripts/) (A)** à part de l'audio
-   **[Sous-titres](/media/av/captions/)** synchronisés avec l'audio
-   **[Langue(s) des signes](/media/av/sign-languages/)**
{:.alt}

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{% capture boxhead %}
<img src="{{ "/content-images/wai-media-guide/live.svg" | relative_url }}" alt="" style="height:1em"> Contenus uniquement en direct
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="checklist-la" %}
{:/}

-   **[Transcription](/media/av/transcripts/) (AAA)** &mdash; diffusion ou transcription en direct
-   **[Sous-titres](/media/av/captions/)**
-   **[Langue(s) des signes](/media/av/sign-languages/)**
{:.alt}

{::nomarkdown}
{% include box.html type="end" %}
{:/}

### <img src="{{ "/content-images/wai-media-guide/video.svg" | relative_url }}" alt="" style="height:1.3em"> Check-lists des contenus vidéos

{% capture boxhead %}
<img src="{{ "/content-images/wai-media-guide/recorded.svg" | relative_url }}" alt="" style="height:1em"> Vidéos préenregistrées
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="checklist-vp" %}
{:/}

**La vidéo contient-elle une conversation ou un autre audio** nécessaires à la compréhension du contenu ?

-   Si oui,
    -   **[Sous-titres](/media/av/captions/)** **(A)**
    -   **[Transcription des informations audios](/media/av/transcripts/) (AAA)**
    -   **[Langue(s) des signes](/media/av/sign-languages/) (AAA)**
    {:.alt}
-   Si non, [informer les utilisateurs](#none).

**La vidéo contient-elle des informations visuelles** nécessaires à la compréhension du contenu ?

-   Si oui,
    -   **[Audiodescription des informations visuelles](/media/av/description/) (A/AA)**
    -   **[Transcription descriptive](//media/av/transcripts/) (AAA)** *(Si vous disposez d'une transcription descriptive, vous n'avez pas besoin d'une transcription supplémentaire de l'information uniquement audio des questions précédentes.)*
    {:.alt}
-   Si non, [informer les utilisateurs](#none).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{% capture boxhead %}
<img src="{{ "/content-images/wai-media-guide/live.svg" | relative_url }}" alt="" style="height:1em"> Vidéos en direct
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="checklist-lv" %}
{:/}

**La vidéo contient-elle une conversation ou un autre audio** nécessaires à la compréhension du contenu ?

-   Si oui,
    -   **[Sous-titres](/media/av/captions/) (AA)**
    -   **[Langue(s) des signes](/media/av/sign-languages/)**
    -   Texte disponible pour les lecteurs d'écran (et les équipements braille)
    {:.alt}
-   Si non, [informer les utilisateurs](#none).

**La vidéo contient-elle des informations visuelles** nécessaires à la compréhension du contenu ?
-   Si oui,
    -   Description des informations visuelles importantes dans un texte disponible pour les lecteurs d'écran (et les équipements braille)
    {:.alt}
-   Si non, [informer les utilisateurs](#none).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

### Informer les utilisateurs lorsque le texte supplémentaire n'est pas nécessaire {#none}

Si votre vidéo ne nécessite pas de sous-titres (parce qu'elle ne contient pas de contenu audio substantiel) ou de description (parce qu'elle ne contient pas de contenu visuel substantiel), il est préférable de prévenir les utilisateurs. Autrement, ils pourraient croire que vous avez involontairement oublié de les fournir.

Les utilisateurs qui ont besoin de sous-titres vont les consulter, vous pouvez donc fournir un fichier de sous-titres qui contient uniquement les indications pertinentes, telles que "[musique de fond]". Sinon, vous pouvez également fournir un texte informatif avec la vidéo, tel que :  

{::nomarkdown}
{% include box.html type="start" class="" %}
{:/}

Les sous-titres ne sont pas nécessaires : le seul son dans cette vidéo est une musique de fond.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include box.html type="start" class="" %}
{:/}

La description n'est pas nécessaire : les seules images dans cette vidéos ne font qu'appuyer ce qui est dit ; les images ne fournissent pas d'informations supplémentaires.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

### Fournir à la fois des sous-titres et une transcription {#captions-and-transcript}

Il est préférable de fournir des sous-titres et une transcription à part.

Pour les vidéos, les sous-titres permettent aux personnes sourdes ou malentendantes de voir le contenu visuel et de lire les sous-titres en même temps.

Pour le contenu uniquement audio, les sous-titres permettent aux personnes malentendantes de saisir les nuances de l'audio et de compléter ce qu'ils n'ont pas entendu en lisant les sous-titres.   

Les transcriptions sont nécessaires pour fournir l'accès aux personnes sourdes et aveugles et qui utilisent le braille. Les transcriptions sont également utilisées par les personnes sans handicaps, comme indiqué dans la page d'introduction de cette ressource nommée sous [Avantages pour les organisations et les particuliers](/media/av/#benefits).

### Transcriptions descriptives

Les transcriptions descriptives pour vidéos :

* sont nécessaires pour la plupart des vidéos pour qu'elles soient accessibles par les personnes sourdes et aveugles
* répondent à de nombreux besoins en accessibilité, y compris pour les personnes qui présentent des difficultés à comprendre l'information auditive et les personnes qui n'arrivent pas à se concentrer et à saisir l'information visuelle lors de changements d'images.
* sont utilisés par les personnes _sans_ handicaps, et représentent un avantage pour votre organisation (retrouvez des exemples sur la page d'introduction sous [Avantages pour les organisations et les particuliers](/media/av/#benefits)
* **sont faciles et peu coûteux à créer** en utilisant des sous-titres et descriptions que vous avez déjà pour atteindre le niveau AA

**Les sous-titres et les transcriptions utilisent le même texte. Une fois que vous avez le premier, il est relativement facile de créer l'autre.**

### D'autres langues

La traduction de l'audio vers d'autres langues peut être fournie :
*  sous forme de texte, en utilisant le format de légendes (appelées sous-titres ou sous-titres interlinguistiques)
*  sous forme d'audio, habituellement à part (pour les personnes qui ne peuvent pas lire les sous-titres)
* sous forme de langue des signes

## Gestion de projet

<!-- maybe better image in future iteration: <img src="{{ "/content-images/wai-media-guide/in-or-out.png" | relative_url }}" alt="" style="float: right; margin-left: 2rem; clear:right; width: 30%; max-width: 220px"> -->

Comprend des conditions d'accessibilité dans vos :
* Besoins du projet - interne et externe
* Demandes de propositions ou appels d'offre
* Contrats

Voici un exemple de charge de travail pour créer une vidéo accessible, avec des précisions sur qui crée le contenu. Les liens renvoient à d'autres pages de cette ressource.

{::nomarkdown}
{% include box.html type="start" title="Exemple de charge de travail et de responsabilités" class="" %}
{:/}

1. Penchez-vous sur l'accessibilité dans le **[contenu de la vidéo](/media/av/av-content/)** au fur et à mesure que vous planifiez et produisez la vidéo.<br>_Par :_ des scénaristes, des vidéastes, des producteurs, et autres.

2. Créez une **[version descriptive de la vidéo](/media/av/description/)** en même temps que la vidéo principale, si besoin.<br>_Par :_ Généralement les mêmes personnes qui produisent la vidéo principale produisent également la version descriptive.

3. Créez des **[sous-titres](/media/av/captions/)** pour la vidéo principale et pour la version descriptive.<br>_Par :_ Généralement, s'il s'agit d'une vidéo professionnelle, les producteurs fournissent les sous-titres. Parfois, pour des créations de vidéos en interne, les sous-titres sont sous-traités.

4. Créez une **[transcription descriptive](/media/av/transcripts/)** en utilisant le texte des fichiers de sous-titres.<br>_Par :_ Souvent, les transcriptions sont créées en interne pour les sous-titres.

5. Mettez la vidéo à disposition dans un **[lecteur multimédia accessible](/media/av/player/)** (généralement, dans un lecteur favorable à l'accessibilité existant).<br>_Par :_ Habituellement, des développeurs Web internes.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

### Accessibilité des ressources {#in-or-out}

Pour vous aider à **la production votre travail interne et sous-traité**, les pages de cette ressource reprennent les considérations, les compétences, et les outils nécessaires à la création de contenu multimédia accessible dans ces sections :
* [Descritpion des considérations, des compétences, et des outils](/media/av/description/#description-considerations-skills-and-tools)
* [Sous -titres, compétences, et outils](/media/av/captions/#skills-and-tools) et [Les sous-titres automatiques ne suffisent pas](/media/av/captions/#automatic-captions-are-not-sufficient)
* [Transcriptions, processus - compétence et outils](/media/av/transcripts/#process---skills-and-tools)
* [Lecteurs multimédia, compétences et outils](/media/av/player/#skills)
* [Langues des signes, compétences et outils](/media/av/sign-languages/#skills-and-tools)

Au moment de prévoir et d'établir le budget pour un contenu multimédia accessible, il est souvent utile de présenter les **avantages aux organisations**, tels que l'optimisation pour les moteurs de recherche (SEO), une meilleure expérience utilisateur pour tous, une meilleure satisfaction client, et plus encore, comme indiqué dans la page d'introduction sous [Avantages pour les organisations et les particuliers](/media/av/#benefits).

## Standard WCAG

Les Règles pour l'accessibilité des contenus Web (WCAG) sont introduites dans une ressource à part : [WCAG : vue d'ensemble](/standards-guidelines/wcag/).

{::nomarkdown}
{% include box.html type="start" class="" %}
{:/}

Cette ressource utilise en grande partie la terminologie WCAG, à quelques différences près :
* "médias temporels" dans les WCAG = "contenu audio et vidéo" dans cette ressource
* "[alternative pour les médias temporels dans les WCAG](https://www.w3.org/TR/WCAG#alt-time-based-mediadef)" = "transcription" pour le contenu uniquement audio et la "transcription descriptive" pour vidéos dans cette ressource
{::nomarkdown}
{% include box.html type="end" %}
{:/}

Les WCAG reprennent les recommandations concernant les contenus audios et vidéos de niveaux A, AA, et AAA. (Retrouvez plus d'informations dans une ressource à part : [Comprendre les niveaux de conformité](https://www.w3.org/WAI/WCAG21/Understanding/conformance.html#levels).) La plupart des contenus multimédia doivent atteindre le niveau AA, selon les réglementations en vigueur. Cela comprend les contenus A et AA indiqués dans les tableaux ci-dessous.

Les critères d'accessibilité pour les vidéos et les audios diffèrent selon qu'ils sont :
* préenregistrés ou en direct
* des vidéos avec audio, des vidéos sans audio (contenu vidéo uniquement), ou un contenu uniquement audio
Les liens apparaissant dans les tableaux ci-dessous mènent vers une page située dans une ressource à part : Comprendre les WCAG 2.1.

### Préenregistrés
{:.no_toc}

<table class="quiet">
<tr>
<th scope="col">&nbsp;</th>
<th scope="col">Transcription <span class="normal-weight">(y compris le contenu auditif et visuel)</span></th>
<th scope="col">Sous-titres</th>
<th scope="col">Audiodescription <span class="normal-weight">(si le contenu visuel n'est pas disponible en audio)</span></th>
<th scope="col">Langue des signes</th>
</tr>
<tr>
  <th scope="row">Contenu uniquement audio</th>
  <td><strong><a href="https://www.w3.org/WAI/WCAG21/Understanding/audio-only-and-video-only-prerecorded">A 1.2.1</a></strong></td>
  <td>&nbsp;</td>
  <td>&nbsp;</td>
  <td>&nbsp;</td>
</tr>
<tr>
<th scope="row">Contenu uniquement vidéo</th>
<td><strong><a href="https://www.w3.org/WAI/WCAG21/Understanding/audio-only-and-video-only-prerecorded">A 1.2.1</a></strong> (transcription <em><strong>ou</strong></em> bande sonore)<br>
<a href="https://www.w3.org/WAI/WCAG21/Understanding/media-alternative-prerecorded">AAA 1.2.8</a></td>
<td>&nbsp;</td>
<td><strong><a href="https://www.w3.org/WAI/WCAG21/Understanding/audio-only-and-video-only-prerecorded">A 1.2.1</a></strong> (bande-son <em><strong>ou</strong></em> transcription)</td>
<td>&nbsp;</td>
</tr>
<tr>
  <th scope="row">Vidéo avec audio</th>
  <td><a href="https://www.w3.org/WAI/WCAG21/Understanding/media-alternative-prerecorded">AAA 1.2.8</a></td>
  <td><strong><a href="https://www.w3.org/WAI/WCAG21/Understanding/captions-prerecorded">A 1.2.2</a></strong></td>
  <td><strong><a href="https://www.w3.org/WAI/WCAG21/Understanding/audio-description-or-media-alternative-prerecorded">A 1.2.3</a></strong>&nbsp;(audiodescription <em><strong>ou</strong></em> transcription)<br>
    <strong><a href="https://www.w3.org/WAI/WCAG21/Understanding/audio-description-prerecorded">AA 1.2.5</a></strong><br>
    <a href="https://www.w3.org/WAI/WCAG21/Understanding/extended-audio-description-prerecorded">AAA 1.2.7</a></td>
  <td><a href="https://www.w3.org/WAI/WCAG21/Understanding/sign-language-prerecorded">AAA 1.2.6</a></td>
</tr>
</table>

### En direct
{:.no_toc}

<table class="quiet">
<tr>
<th scope="col">&nbsp;</th>
<th scope="col">Transcription</th>
<th scope="col">Sous-titres</th>
<th scope="col">Audiodescription</th>
<th scope="col">Langue des signes</th>
</tr>
<tr>
  <th scope="row">Contenu uniquement audio</th>
  <td><a href="https://www.w3.org/WAI/WCAG21/Understanding/audio-only-live">AAA 1.2.9</a> (diffusion en direct <em><strong>ou</strong></em>transcription exacte en direct)</td>
  <td>&nbsp;</td>
  <td>&nbsp;</td>
  <td>&nbsp;</td>
</tr>
<tr>
<th scope="row">Contenu uniquement vidéo</th>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
  <th scope="row">Vidéo avec audio</th>
  <td>&nbsp;</td>
  <td><strong><a href="https://www.w3.org/WAI/WCAG21/Understanding/captions-live">AA 1.2.4</a></strong></td>
  <td>&nbsp;</td>
  <td>&nbsp;</td>
</tr>
</table>

### Plus d'informations à propos des standards
{:.no_toc}

Pour en savoir plus sur les critères WCAG pour les contenus multimédia, allez sur [Comprendre la Règle 1.2 : moyens d'expression temporels](https://www.w3.org/WAI/WCAG21/Understanding/time-based-media).

Retrouvez d'autres critères WCAG liés aux contenus audios et vidéos :
* Dans cette ressource :
  * [Du contenu audio et vidéo accessible](/media/av/av-content/)
  * [Fonctionnalités du lecteur multimédia](/media/av/player/#player-accessibility-functionality)
* Dans comprendre les WCAG :
   * [2.2.2 Pause, Stop, Masquer](https://www.w3.org/WAI/WCAG21/Understanding/pause-stop-hide) (Niveau A) Pour déplacer, clignoter, défier, ou des informations de mise à jour automatique, toutes les conditions suivantes sont remplies :...
   * [1.4.2 Contrôle du son](https://www.w3.org/WAI/WCAG21/Understanding/audio-control) (Niveau A) Si du son sur une page Web est audible automatiquement pendant plus de 3 secondes, un mécanisme est disponible pour le mettre en pause, l'arrêter, ou pour en contrôler le volume...

Vos contenus audios et vidéos pourraient faire l'objet de recommandations supplémentaires, par exemple sous des réglementations gouvernementales. Certaines sont reprises dans [Réglementations et législation sur l'accessibilité Web](/policies/).
