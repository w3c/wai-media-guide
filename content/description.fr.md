---
title: "Audiodescription des informations visuelles"
title_image: /content-images/wai-media-guide/ad.svg

nav_title: "Description"

lang: fr   # change "en" to lang code, here and 2 @@s below
last_updated: 2021-06-29   # Change to date of translation YYYY-MM-DD (month in middle)
translators:
- name: "Sofia Ahmed"
- name: "Rémi Bétin"
contributors:
- name: "Sandra Velarde Gonzalez (ETNIC)"

permalink: /media/av/description/fr   # Add lang to end /link/to/page/@@
ref: /media/av/description/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'content/description.fr.md'   # Add lang to the middle of the filename, e.g., index.@@.md

resource:
  ref: /media/av/
navigation:
  previous: /media/av/player/
  next:     /media/av/captions/
changelog: /media/av/changelog/
acknowledgements: /media/av/acknowledgements/

description: Aide à comprendre et à créer une description des informations visuelles (appellée audiodescription) pour l'accessibilité des contenus audios et vidéos.
image: /content-images/wai-media-guide/social.png

footer: >   # Translate words below, including "Date:" and "Editor:". (Do not update the date.)
   <p><strong>Date :</strong> Mise à jour : 19 janvier 2021. Première publication septembre 2019. CHANGELOG.</p>
   <p><strong>Rédactrice :</strong> <a href="http://www.w3.org/People/Shawn">Shawn Lawton Henry</a>. ACKNOWLEDGEMENTS liste les contributeurs et les crédits.</p>
   <p>Développé par le groupe de travail Éducation et promotion (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Rédigé initialement dans le cadre du projet <a href="https://www.w3.org/WAI/WCAGTA/">WCAG TA</a> financé par le <abbr title="United States">U.S.</abbr> Access Board. Révisé dans le cadre du projet <a href="https://www.w3.org/WAI/expand-access/">WAI Expanding Access</a> financé par la fondation Ford.</p>

---

{::nomarkdown}
{% include box.html type="start" title="Résumé" class="" %}
{:/}

La description des informations visuelles est appelée **_audiodescription_**, **_vidéodescription_**, ou **_vidéo décrite_** dans différents domaines.

La description fournit du contenu aux personnes aveugles et aux autres personnes qui ne peuvent pas voir la vidéo convenablement. Elle décrit l'information visuelle nécessaire à la compréhension du contenu, notamment le texte affiché dans la vidéo.

Cette page aide à comprendre et à créer une description des informations visuelles pour vos vidéos nouvelles et existantes. (La description ne s'applique pas aux médias seulement audio, tels que les podcasts.)

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

_Quoi :_ L'audiodescription décrit les informations visuelles nécessaires à la compréhension du contenu. (Par exemple, "Pat ouvre une boîte à bijoux, regarde une bague de fiançailles en diamant, et pleure".) Selon le type de vidéo et de lecteur multimédia, la description peut être :
* intégrée dans le scénario principale et enregistrée (ce qui fonctionne bien pour certaines vidéos de formation, mais pas pour la plupart des récits).
* une narration ajoutée à la piste audio principale et fournie dans une version alternative de la vidéo (pour les récits).
* fournie dans un fichier texte ou en tant que flux audio séparé (si supporté par le lecteur multimédia)

_Qui :_ La description fournit du contenu aux personnes aveugles et aux autres personnes qui ne peuvent pas voir la vidéo correctement.

_Exemples :_

* [Vidéo de formation avec la description intégrée dans le discours du formateur (YouTube)<br>{% include image.html src="eg-integrated-description.png" alt="" class="normal video" %}](https://www.youtube.com/watch?v=JUfmCvdzqbM)

* [Vidéo alternative d'un reportage comprenant une audiodescription avec une voix différente (YouTube)<br>{% include image.html src="using-description.jpg" alt="" class="normal video" %}](https://www.youtube.com/watch?v=F3A1VffiOH4)

<p style="color:#686868; line-height:100%; font-size:0.875rem;">Ces vidéos sont également disponibles depuis le site de W3C : <a href="https://www.w3.org/2020/10/TPAC/w3cx-challenging-assumptions.html#talk" style="color:#686868">vidéo de formation (page Web)</a>, <a href="http://media.w3.org/wai/perspective-videos/text-to-speech-ad.mp4" style="color:#686868">reportage vidéo (taille du fichier MP4 28 Mo)</a>.</p>

### Terminologie
{:.no_toc}

La description des informations visuelles fournie en audio est appelée "audiodescription" dans les Règles pour l'accessibilité des contenus Web (WCAG). Dans certaines régions et certains documents, elle est appelée "vidéodescription" ou "vidéo décrite".

Cette ressource utilise le terme "vidéo décrite" à certains endroits comme une forme abrégée de "vidéo qui comprend la description des informations visuelles en audio".

## Mon contenu multimédia nécessite-t-il une description ? {#checklist}

Cette section vous indique :
* Quelles sont les exigences du standard WCAG aux niveaux A, AA, et AAA. _(Les [WCAG](/media/av/planning/#wcag-standard) sont introduites dans la page Planifier de cette ressource.)_
* Qu'est-ce il nécessaire de faire pour répondre aux besoins des utilisateurs, au-delà des WCAG. S'il n'y a pas de "A", cela signifie que ce point n'est pas requis dans les WCAG.

{% capture boxhead %}
Audio seulement (par exemple, les podcasts) :
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="checklist-ao" %}
{:/}

*   Pour les vidéos pré-enregistrées et en direct :
    *   La description n'est pas nécessaire car il n'y a pas d'information visuelle.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{% capture boxhead %}
Vidéo :
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="checklist-video" %}
{:/}

**La vidéo contient-elle des informations visuelles** nécessaires à la compréhension du message communiqué par la vidéo ?

*   Si non (par exemple, il ne s'agit que d'une personne qui parle) :
    *   Une description n'est pas nécessaire. Pensez à [informer les utilisateurs](/media/av/planning/#none).
*   Si oui :
    *   Pour les vidéos pré-enregistrées :
        *   Une description est nécessaire pour fournir les informations visuelles importantes aux personnes aveugles qui écoutent la vidéo.
        *   Une description **_ou_** une [transcription descriptive](//media/av/transcripts/) est **_exigée_** par les WCAG au niveau A.
        *   Une description est **_exigée_** par les WCAG au niveau AA.
        {:.alt}
    *   Pour les vidéos en direct :
        *   Une description est nécessaire pour fournir les informations visuelles importantes aux personnes aveugles.
        *    Une description n'est pas nécessaire pour répondre aux exigences des WCAG.
        {:.alt}

{::nomarkdown}
{% include box.html type="end" %}
{:/}

<br>

**Extraits des WCAG** avec des accentuations, des ajouts entre [crochets] et des liens vers plus d'informations dans "Comprendre les WCAG" :
* [A 1.2.1 Contenu seulement audio ou video](https://www.w3.org/WAI/WCAG21/Understanding/audio-only-and-video-only-prerecorded.html) (pré-enregistré) : Pour... des médias pré-enregistrés seulement vidéo : soit une version de remplacement pour un média temporel [transcription descriptive] ***ou*** une piste audio [ou description] présentant une information équivalente pour un contenu pré-enregistré seulement vidéo.
* [A 1.2.3 Audio-description ou version de remplacement pour un média temporel](https://www.w3.org/WAI/WCAG21/Understanding/audio-description-or-media-alternative-prerecorded.html) (pré-enregistré) : une version de remplacement pour un média temporel [transcription] ***ou*** une audio-description du contenu vidéo pré-enregistré pour un média synchronisé...
* [AAA 1.2.5 Audio-description](https://www.w3.org/WAI/WCAG21/Understanding/audio-description-prerecorded.html) (pré-enregistrée) : fournir une audio-description pour tout contenu vidéo pré-enregistré, sous forme de média synchronisé.
* [AAA 1.2.7 Audio-description étendue](https://www.w3.org/WAI/WCAG21/Understanding/extended-audio-description-prerecorded.html) (pré-enregistrée) : lorsque les blancs présents dans le fond sonore ne sont pas suffisants pour permettre à l'audio-description de transmettre le sens de la vidéo, fournir une audio-description étendue pour tout contenu vidéo pré-enregistré sous la forme de média synchronisé.

## Considérations à prendre en compte pour la description, compétences, et outils

Lorsque l'accessibilité est prise en compte _avant_ de commencer la production des vidéos, les coûts et les efforts sont significativement moindres pour créer une description. Pour certains types de vidéos (telles que les vidéos de formation), la description des informations visuelles peut être intégrée facilement par les locuteurs au moment de la planification et de la création de la vidéo ; vous n'aurez donc pas besoin d'une description à part, ce qui vous fera économiser des coûts supplémentaires.

Retrouvez des informations relatives à la planification de la description dans les _nouvelles vidéos_ sur la page "Créer du contenu audio et vidéo", dans la section [Prévoyez l’audiodescription des informations visuelles](/media/av/av-content/#plan-description).

Pour ajouter une description à une _vidéo déjà existante_, vous aurez selon les cas besoin de compétences et des outils pour :
* la rédiger
* créer un fichier VTT avec des descriptions synchronisées

Ou :
* la rédiger
* la raconter
* l'enregistrer
* l'intégrer dans de nouveaux fichiers audios et/ou vidéos

De nombreuses organisations choisissent de sous-traiter la création de leur description.

## Quelle méthode de description ?

Choisir votre méthode de description dépend du contenu de votre vidéo et du lecteur multimédia que vous utilisez. Tout d'abord, réglez les questions suivantes concernant votre contenu vidéo, la durée, et le lecteur :

* **Intégrée** : Pour les nouvelles vidéos, les locuteurs peuvent-ils décrire les informations visuelles pertinentes au moment où la vidéo est enregistrée ? Cela fonctionne bien avec certaines vidéos, comme les vidéos de présentation ou les vidéos didactiques. À titre d'exemple, allez sur la page "Création de contenus audios et vidéos", dans la section ["Description intégrée"](/media/av/av-content/#integrate-description).

* **Lecteur multimédia accessible** : retrouvez des informations relatives aux fonctionnalités des lecteurs multimédia sur la page "Des lecteurs multimédia accessibles" sous [Lecteurs existants](/media/av/player/#existing-players). Le lecteur multimédia, la plate-forme, ou le plug-in que vous utilisez fournissent-ils des fonctionnalités pour :
   * une description provenant d'un fichier texte ?
   * une piste audio à part pour la description ?

<a id="space"> </a>
* **Espace dans l'audio** : y a-t-il suffisamment d'espace dans l'audio principal pour la description ? En d'autres termes, les pauses sont-elles suffisantes dans la narration ou les dialogues au moment où la description pertinente apparaîtra ? Par exemple,
   * Si la seule description nécessaire se trouve au début de la vidéo où on trouve un titre textuel et de la musique de fond, alors : oui, il y a assez d'espace.
   * Si le locuteur parle continuellement sans faire de pauses, alors : non, il n'y a pas assez d'espace pour la description.

***Utilisez les informations ci-dessus pour répondre aux questions suivantes*** et déterminer quel méthode utiliser pour la description de votre vidéo. Les options listées en premier sont généralement celles à privilégier, mais vous pouvez tout à fait choisir une autre option.

{% capture boxhead %}
Méthode de description :
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="method-tree" %}
{:/}

*   Est-ce une nouvelle vidéo _et_ les locuteurs peuvent-ils décrire les informations visuelles dans l'audio principal ?
    *   Si oui, fournissez une **description intégrée** (une description à part n'est pas nécessaire),
        _**ou**_ une autre option ci-dessous.
    *   Si non, allez-vous utiliser un lecteur multimédia qui possède des fonctionnalités pour lire une description provenant d'un fichier de texte ?
        *   Si oui, fournissez une description dans un **fichier de texte synchronisé**,
            _**ou**_ une autre option ci-dessous.
        *   Si non, allez-vous utiliser un lecteur multimédia favorable à une piste audio séparée pour la description, _et_ y a-t-il assez d'espace dans l'audio principal pour la description ?
            *   Si oui, fournissez une description dans un **fichier audio à part**,
                _**ou**_ fournissez une **description vidéo à part**.
            *   Si non, fournissez une **description vidéo à part**.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

## Options pour créer une description

En fonction des caractéristiques de votre vidéo, choisissez une des options ci-dessous &mdash; comme indiqué dans la section "Quelle description fournir pour ma vidéo ?" ci-dessus.

### Intégrée : créer une description intégrée

Cette approche fonctionne pour certaines vidéos nouvelles. Voici les étapes essentielles du processus de développement d'une vidéo avec description intégrée :
1. Lors de l'écriture du scénario, assurez-vous que toutes les informations visuelles pertinentes sont reprises. Retrouvez des [Conseils pour rédiger des descriptions ci-dessous](#writing) et des exemples dans "Contenu audio et vidéo accessible", [section "Intégrez une description"](/media/av/av-content/#integrate-description))
2. Avant de finaliser la vidéo, vérifiez et confirmez que toutes les informations visuelles pertinentes sont présentes dans l'audio.

### Texte : créer une description dans un fichier texte

Cette approche ne fonctionne que lorsque le lecteur multimédia que vous utilisez peut lire une description audio basée sur du texte lu à voix haute. De plus, soit l'espace est suffisant dans l'audio principal pour la description, soit le lecteur fournit des fonctionnalités pour mettre la vidéo sur pause lors de la description audio. Ce procédé nécessite de créer un fichier texte synchronisé &mdash; un minimum de compétences est requis ; des outils ne sont pas nécessaires, bien qu'ils accélèrent et facilitent la création.

Voici les étapes essentielles du processus de création de descriptions dans un fichier texte :
1. Rédigez les descriptions. Retrouvez des [Conseils pour rédiger des descriptions ci-dessous](#writing).
2. Ajoutez les horodatages des descriptions dans le format de fichier utilisé par le lecteur multimédia. Il s'agit généralement de [WebVTT comme dans l'exemple ci-dessous](#vtt).

(Assurez-vous que le fichier des descriptions est inclut avec la vidéo.)

Si l'espace de l'audio principal est insuffisant pour les descriptions, fournissez aux utilisateurs des instructions pour mettre leur lecteur en pause pendant l'audiodescription. Par exemple :

{::nomarkdown}
{% include box.html type="start" title="Mettre la vidéo en pause pour l'audiodescription des informations visuelles :" class="" %}
{:/}

<img src="{{ "/content-images/wai-media-guide/player-preferences.png" | relative_url }}" alt="" class="" style="float: right; height: 7em; padding-left 7px;'">

* Sélectionnez "Préférences", puis "Descriptions".<br>
La boîte de dialogue "Préférences pour l'audiodescription" s'ouvre.
* Sous "Audiodescription textuelle", sélectionnez la case à cocher "Automatiquement mettre en pause la vidéo quand la description commence".
* Cliquez sur le bouton "Enregistrer".

{::nomarkdown}
{% include box.html type="end" %}
{:/}

### Contenu seulement audio : créer une description dans un fichier seulement audio à part

Cette approche ne fonctionne que lorsque l'espace dans l'audio principal est suffisant pour la description, *et* lorsque le lecteur multimédia peut lire une piste sonore à part pour la description. Cela nécessite des compétences et un logiciel d'enregistrement et de montage de contenu audio.

Voici les étapes essentielles du processus de développement d'une description dans un fichier audio à part :
1. Rédigez les descriptions. Retrouvez des [Conseils pour rédiger des descriptions ci-dessous](#writing).
2. Enregistrez les descriptions. Retrouvez des [Conseils pour enregistrer des descriptions ci-dessous](#recording).
3. Assurez-vous que les descriptions s'activent dans les espaces audios de la vidéo principale.
4. Fournissez un fichier de sous-titres de la description. [Exemple de fichier VTT de l'audiodescription](#vtt)

(Assurez-vous que les fichiers sont intégrés au lecteur sur la page Web.)

### Vidéo avec de l'espace : créer une vidéo décrite à part - si les espaces audios sont suffisants pour les descriptions

Cette option s'applique lorsque les descriptions peuvent s'insérer dans les espaces de la vidéo, comme décrit dans [Espace dans le contenu audio ci-dessus](#space)_. Elle nécessite des compétences et un logiciel d'enregistrement et de montage de contenu vidéo. En fonction du lecteur que vous utilisez, vous pourriez avoir besoin d'un logiciel vidéo pour regénérer la vidéo.

Voici les étapes essentielles du processus de création d'un fichier audio séparé :
1. Rédigez les descriptions. Retrouvez des [Conseils pour la rédaction de descriptions ci-dessous](#writing).
2. Enregistrez les descriptions. Retrouvez des [Conseils pour enregistrer des descriptions ci-dessous](#recording).
3. Créez un nouveau fichier audio en associant l'audio original et la nouvelle audiodescription. Retrouvez des [Conseils pour associer des fichiers audios ci-dessous](#combining).
4. Fournissez le(s) fichier(s) :
* _**Si**_ votre lecteur utilise des pistes vidéo et audio séparées,<br>vous avez fini.
* _**Si**_ votre lecteur utilise un seul fichier vidéo qui inclut l'audio,<br>générez la nouvelle  vidéo décrite avec le fichier audio que vous venez de créer.

(Assurez-vous que sur la page Web où la vidéo est disponible, la version décrite utilise la version correcte que vous venez de créer.)

### Vidéo sans espace : créer une vidéo décrite à part - s'il n'y a _pas_ suffisamment d'espace dans l'audio pour les descriptions

S'il n'y a **pas** suffisamment d'espace pour toutes les descriptions _(comme décrit dans [Espace dans le contenu audio ci-dessus](#space))_, vous devrez développer un fichier audio à part et créer une piste visuelle. Cette option nécessite des compétences et un logiciel d'enregistrement audio, de montage de contenu audio, et de montage de contenu vidéo.

Voici les étapes essentielles du processus de création d'un fichier audio séparé et de création d'une piste visuelle :
1. Rédigez des descriptions. Retrouvez des [Conseils pour rédiger des descriptions ci-dessous](#writing).
2. Enregistrez les descriptions. Retrouvez des [Conseils pour enregistrer des descriptions ci-dessous](#recording).
3. Créez un nouveau fichier audio en associant le contenu audio original et la nouvelle audiodescription. Retrouvez des [Conseils pour associer les fichiers audios ci-dessous](#combining).
4. Créez une nouvelle vidéo :
	* _**Si**_ votre vidéo source est constituée de longues scènes _(comme décrit dans "Contenus audios et vidéos accessibles, dans la section ["Prévoir du temps pour la description"](/media/av/av-content/#time-for-description))_, coupez des scènes plus longues pour combler l'espace visuel aux moments de la description.
	* _**Si ce n'est pas le cas ou si vous éditez une vidéo déjà existante**_, vous aurez besoin de conserver une image statique dans la vidéo lorsque description sera lue dans l'audio. <!-- (For example, this video [@@ need very good example - see GitHub](https://github.com/w3c/wai-media-guide/issues/73) pauses at 00:00 for the audio description.) -->

(Assurez-vous que, sur la page Web où la vidéo est disponible, la version décrite utilise la version correcte que vous venez de créer.)

### D'autres options
{:.no_toc}

* Une description étendue avec SMIL &mdash; SMIL 3.0 est la seule méthode de balisage pour fournir des audiodescriptions étendues. Le support de SMIL est très limité. Les implémentations nécessiteront certainement des plug-ins et/ou des approches extrêmement personnalisées.
* Fournir des fonctionnalités pour que la vidéo se mette en pause au moment de la description : cela n'est pas suggéré dans la plupart des cas car un développement supplémentaire est nécessaire et l'expérience utilisateur est sous-optimale.

{% include_cached excol.html type="start" id="tips" %}

## Conseils pour créer une description vous-mêmes

{% include_cached excol.html type="middle" %}

### Conseils pour rédiger des descriptions {#writing}
{:.no_toc}

* Décrivez les éléments visuels importants pour la compréhension du message communiqué par la vidéo. Imaginez que vous décriviez la vidéo à une personne qui ne peut pas la voir &mdash; que diriez-vous ? Vous n'avez pas besoin de décrire chaque détail ou chaque élément apparaissant dans l'audio.
* Décrivez objectivement, sans interprétation, censure, ou commentaire.
* Écrivez une description au temps présent, à la forme active, et à la troisième personne.

Généralement, tout le texte présent dans la vidéo devrait être inclus dans l'audio principal (description intégrée) ou dans une description distincte. Par exemple, le texte du titre au début de la vidéo, les liens et les adresses électroniques affichés à la fin, les textes avec les noms des locuteurs, et le texte présent dans la présentation. Il n'est pas indispensable d'inclure le texte sous forme de verbatims (exactement mot pour mot), mais toute l'information transmise par le texte doit être disponible dans l'audio principal, dans une description à part, ou clairement mise à disposition avec la vidéo.

Retrouvez sur le Web davantage de conseils sur la rédaction des descriptions, par exemple : [Fiche de conseils pour la description {% include_cached external.html %}](https://dcmp.org/learn/227) and [Comment décrire {% include_cached external.html %}](http://www.descriptionkey.org/how_to_describe.html).

### Conseils pour enregistrer des descriptions {#recording}
{:.no_toc}

* Utilisez une voix, un style, et un débit qui se distinguent des autres voix utilisées dans la vidéo.
* Utilisez une voix neutre qui ne transmet pas d'émotions.
* Lors de l'enregistrement d'un seul fichier avec des descriptions synchronisées, prononcez les descriptions au même moment que le contenu visuel, ou juste avant le contenu visuel. Ne placez pas la description après le contenu visuel.
* Consultez des [conseils pour le contenu audio](/media/av/av-content/#audio).

### Conseils pour associer des fichiers audios {#combining}
{:.no_toc}

* Placez les descriptions au même moment que le contenu visuel, ou juste avant celui-ci. Ne placez pas la description après le contenu visuel.

* Faites en sorte que la description soit clairement haut dessus des autres bruits. Au moment d'associer les descriptions avec le contenu audio principal, baissez le volume de l'audio principal quand la description est prononcée et augmentez le volume de la description. Lorsque la description est finie, baissez le volume de la description et augmentez le volume de l'audio principal à son réglage normal. Répétez ce processus (appelé "ducking") pour chaque occurence de la description.

{% include_cached excol.html type="end" %}

### Fichier VTT
{:.no_toc}

{::nomarkdown}
{% include box.html type="start" title="Exemple de fichier VTT d'audiodescription" class="" id="vtt" %}
{:/}

```
WEBVTT

00:00:04.000 --> 00:00:07.980
<v Audio-descriptions>Un homme assis à un bureau commence à regarder une vidéo sur son ordinateur.

00:00:17.260 --> 00:00:20.780
<v Audio-descriptions>La vidéo sur son ordinateur montre une personne qui parle à la caméra.

00:00:20.780 --> 00:00:23.140
<v Audio-descriptions>La vidéo est lue sans audio.

00:00:26.880 --> 00:00:29.620
<v Audio-descriptions>L'homme qui regarde la vidéo a un appareil auditif.
```

{::nomarkdown}
{% include box.html type="end" %}
{:/}
