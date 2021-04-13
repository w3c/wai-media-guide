---
title: "Audiodescription des informations visuelles"
title_image: /content-images/wai-media-guide/ad.svg

nav_title: "Description"

lang: fr   # change "en" to lang code, here and 2 @@s below
last_updated: 2020-01-01   # Change to date of translation YYYY-MM-DD (month in middle)
# translator: "..."
translators:
- name: "Sofia Ahmed"
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

description: aide à comprendre et à créer une description des informations visuelles (appelée audiodescription) pour l'accessibilité des contenus audios et vidéos.
image: /content-images/wai-media-guide/social.png

footer: >   # Translate words below, including "Date:" and "Editor:". (Do not update the date.)
   <p><strong>Date :</strong> Mise à jour : 10 septembre 2019. JOURNAL DES MODIFICATIONS.</p>
   <p><strong>Rédactrice :</strong> <a href="http://www.w3.org/People/Shawn">Shawn Lawton Henry</a>. RERMERCIEMENTS : liste les contributeurs et les crédits.</p>
   <p>Développé par le Groupe de travail Éducation et Promotion (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Rédigé initialement dans le cadre du projet <a href="https://www.w3.org/WAI/WCAGTA/">WCAG TA</a> financé par le <abbr title="United States">U.S.</abbr> Access Board. Révisé dans le cadre du projet <a href="https://www.w3.org/WAI/expand-access/">WAI Expanding Access</a> financé par la fondation Ford.</p>

---

{::nomarkdown}
{% include box.html type="start" title="Résumé" class="" %}
{:/}

Cette page vous aide à comprendre et à créer une description des informations visuelles (appelée _audiodescription_, _vidéodescription_, et _description vidéo_) pour de nouvelles vidéos ou des vidéos déjà existantes. (Cela ne concerne pas le contenu uniquement audio, tel que les podcasts.)

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

_Quoi :_ L'audiodescription décrit les informations visuelles nécessaires à la compréhension du contenu. (Par exemple, "Pat ouvre une boîte à bijoux, regarde une bague de fiançailles en diamant, et pleure".) La description est généralement une narration ajoutée à la bande sonore.

_Qui :_ La description fournit du contenu aux personnes aveugles et aux autres personnes qui ne peuvent pas voir la vidéo correctement.

_Exemple :_ [Vidéo qui comprend une audiodescription des informations visuelles (YouTube)<br>{% include image.html src="using-description.jpg" alt="" class="large video" %}](https://www.youtube.com/watch?v=F3A1VffiOH4&list=PLhDEeYUfW02Qo4r2KlzagxZxhYcZADee-&index=3)

### Terminologie
{:.no_toc}

La description des informations visuelles fournie en audio est appelée "audiodescription" dans les Règles pour l'accessibilité des contenus Web (WCAG). Dans certaines régions et certains documents, elle est appelée "vidéodescription" ou "description vidéo".

Cette ressource utilise le terme "description vidéo" à certains endroits comme une forme abrégée de "vidéo qui comprend la description des informations visuelles en audio".

## Mon contenu multimédia nécessite-t-il une description ? {#checklist}

Cette section vous indique :
* Quels sont les recommandations du standard WCAG aux niveaux A, AA, et AAA. _(Les [WCAG](/media/av/planning/#wcag-standard) sont introduites dans la page Planification de cette ressource.)_
* Quelles sont les exigences pour répondre aux besoins des utilisateurs, au-delà des WCAG. S'il n'y a pas de "A", cela veut dire que ce n'est pas requis dans les WCAG.

{% capture boxhead %}
Audio uniquement (par exemple, les podcasts):
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="checklist-ao" %}
{:/}

*   Pour les vidéos préenregistrées et en direct :
    *   La description n'est pas nécessaire car il n'y a pas d'information visuelle.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{% capture boxhead %}
Video:
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="checklist-video" %}
{:/}

**La vidéo contient-elle des informations visuelles** nécessaires à la compréhension du message communiqué par la vidéo ?

*   Si ce n'est pas le cas (par exemple, il ne s'agit que d'une personne qui parle) :
    *   La description n'est pas nécessaire. Allez sur [Informer les utilisateurs](/media/av/planning/#none).
*   Si c'est le cas :
    *   Pour les vidéos préenregistrées :
        *   La description est nécessaire pour fournir les informations visuelles importantes aux personnes aveugles et qui écoutent la vidéo.
            La description est **_recommandée_** dans les WCAG aux niveaux A ou AA.
        {:.alt}
    *   Pour les vidéos en direct :
        *   La description est nécessaire pour fournir les informations visuelles importantes aux personnes aveugles.
            La description n'est pas besoin de répondre aux recommandations des WCAG.
        {:.alt}

{::nomarkdown}
{% include box.html type="end" %}
{:/}

## Considérations à prendre en compte pour la description, compétences, et outils

Lorsque l'accessibilité est prise en compte _avant_ de commencer la production des vidéos, les coûts et les efforts sont significativement moindres pour créer une descritpion. Pour certains types de vidéos (telles que les vidéos de formation), la description des informations visuelles peut être intégrée facilement par les locuteurs au moment de la planification et de la création de la vidéo, vous n'aurez donc pas besoin d'une description à part, ce qui vous fera économiser des coûts supplémentaires.

Retrouvez des informations relatives à la planification de la description dans les _nouvelles vidéos_ sur la page "Créer du contenu audio et vidéo", dans la section [Planification de l'audiodescription des informations](/media/av/av-content/#plan-description).

Pour ajouter une description à une _vidéo déjà existante_, vous aurez besoin à la fois des compétences et des outils pour :
* l'écrire
* créer un fichier VTT avec des descritpions synchronisées

Ou :
* l'écrire
* la raconter
* l'enregistrer
* l'intégrer dans de nouveaux fichiers audios et/ou vidéos

De nombreuses organisations choisissent de sous-traiter leur description.

## Quel mode de description ?

Choisir votre mode de description dépend du contenu de la vidéo et du lecteur multimédia que vous utilisez. Tout d'abord, réglez les questions suivantes concernant votre contenu vidéo, la durée, et le lecteur :

* **Intégrée** : Pour les nouvelles vidéos, les locuteurs peuvent-ils décrire les informations visuelles pertinentes au moment où la vidéo est enregistrée ? Cela fonctionne bien avec certaines vidéos, comme les vidéos de présentation ou didactique. À titre d'exemple, allez sur la page "Création de contenus audios et vidéos", dans la section ["Description intégrée"](/media/av/av-content/#integrate-description).

* **Un lecteur multimédia accessible** : retrouvez des informations relatives aux fonctionnalités des lecteurs multimédia sur la page "Des lecteurs multimédia accessibles" sous [Lecteurs déjà existants](/media/av/player/#existing-players). Le lecteur multimédia, la plate-forme, ou le plug-in que vous utilisez fournissent-ils des fonctionnalités pour :
   * une description provenant d'un fichier texte ?
   * une bande sonore à part pour la description ?

<a id="space"> </a>
* **Espace de l'audio** : y'a-t-il suffisamment d'espace dans l'audio principal pour la description ? En d'autres mots, le nombre de pauses est-il suffisant durant la narration ou les dialogues où la description pertinente pourrait apparaître ? Par exemple,
   * Si la seule description nécessaire se trouve au début de la vidéo où un titre textuel et de la musique apparaissent, alors : oui, il y a assez d'espace.
   * Si le locuteur parle continuellement sans faire de pauses, alors : non, il n'y a pas assez d'espace pour la description.

***Utilisez les informations ci-dessus pour répondre aux questions suivantes*** pour déterminer quel mode utiliser pour la description de votre vidéo. Les options listées en premier sont généralement celles à privilégier, mais vous pouvez tout à fait choisir une autre option.

{% capture boxhead %}
Mode de description :
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="method-tree" %}
{:/}

*   Est-ce une nouvelle vidéo _et_ les locuteurs peuvent-ils décrire les informations visuelles dans l'audio principal ?
    *   Si oui, fournissez une **description intégrée** (une description à part n'est pas nécessaire),
        _**ou**_ une autre option ci-dessous.
    *   Si non, allez-vous utiliser un lecteur multimédia qui possède les fonctionnalités pour lire une description provenant d'un fichier de texte ?
        *   Si oui, fournissez une description dans un **fichier de texte synchronisé**,
            _**ou**_ une autre option ci-dessous.
        *   Si non, allez-vous utiliser un lecteur multimédia favorable à une bande sonore à part pour la description, _et_ y'a-t-il de l'espace en suffisance dans l'audio principal pour la description ?
            *   Si oui, fournissez une description dans un **fichier audio à part**,
                _**ou**_ fournissez une **description vidéo à part**.
            *   Si non, fournissez une **description vidéo à part**.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

## Options pour la création d'une description

En fonction des caractéristiques de votre vidéo, choisissez une des options ci-dessous (comme indiqué dans la section "Quel description fournir pour ma vidéo ?" ci-dessus.)

### Intégrée : création d'une description intégrée

Cette approche fonctionne pour certaines vidéos nouvelles. Voici les étapes essentielles du processus de développement d'une vidéo avec description intégrée :
1. Lors de l'écriture du scénario, assurez-vous que toutes les informations visuelles pertinentes sont reprises. Retrouvez des [Conseils pour l'écriture de descriptions ci-dessous](#writing) et des exemples dans "Du contenu audio et vidéo accessible", [La section "Une description intégrée"](/media/av/av-content/#integrate-description))
2. Avant de finaliser la vidéo, vérifier pour confirmer que toutes les informations visuelles pertinentes sont présentes dans l'audio.

### Texte : création d'une description dans un fichier de texte

Cette approche ne fonctionne que lorsque le lecteur multimédia que vous utilisez peut lire une description audio basée sur du texte lu à voix haute. De plus, soit l'espace est suffisant dans l'audio principal pour la description, soit le lecteur fournit des fonctionnalités pour mettre la vidéo sur pause lors de la description audio. Ce procédé nécessite la création d'un fichier de texte synchronisé : un minimum de compétences est requis, et des outils ne sont pas nécessaires, bien qu'ils accélèrent et facilitent la création.

Voici les étapes essentielles du processus de développement de descritpions dans un fichier de texte :
1. L'écriture des descriptions. Retrouvez des [Conseils pour l'écriture de descriptions ci-dessous](#writing).
2. Ajouter les horodatages des descriptions dans le format de fichier utilisé par le lecteur multimédia. Il s'agit généralement de [WebVTT comme dans l'exemple ci-dessous](#vtt).

(Assurez-vous que le fichier des descriptions soit inclut dans la vidéo.)

Si l'espace de l'audio principal est insuffisant pour les descriptions, fournissez aux utilisateurs des instructions pour mettre leur lecteur en pause pendant l'audiodescription. Par exemple :

{::nomarkdown}
{% include box.html type="start" title="Mettre la vidéo en pause pour l'audiodescription des informations visuelles :" class="" %}
{:/}

<img src="{{ "/content-images/wai-media-guide/player-preferences.png" | relative_url }}" alt="" class="" style="float: right; height: 7em; padding-left 7px;'">

* Sélectionnez "Préférences", puis "Descriptions".<br>
La boîte de dialogue "Préférences pour l'audiodescription" s'ouvre.
* Sous "Audiodescription textuelle", sélectionnez la case à cocher "Mettre en pause la vidéo automatiquement quand la description commence".
* Sélectionnez le bouton "Enregistrer".

{::nomarkdown}
{% include box.html type="end" %}
{:/}

### Contenu uniquement audio : création d'une description dans un fichier uniquement audio à part

Cette approche ne fonctionne que lorsque l'espace dans l'audio principal est suffisant pour la description, *et* lorsque le lecteur multimédia peut lire une bande sonore à part pour la description. Cela nécessite des compétences et un logiciel d'enregistrement et de montage de contenu audio.

Voici les étapes essentielles du processus de développement d'une description dans un fichier audio à part :
1. L'écriture ds descriptions. Retrouvez des [Conseils pour l'écriture de descriptions ci-dessous](#writing).
2. Enregistrer les descriptions. Retrouvez des [Conseils pour l'enregistrement de descriptions ci-dessous](#recording).
3. Assurez-vous que les descriptions s'activent dans les espaces audios de la vidéo principale.
4. Fournissez un fichier de sous-titres de la description. [Exemple de fichier VTT de l'audiodescription](#vtt)

(Assurez-vous que les fichiers sont intégrés au lecteur sur la page Web.)

### Vidéo avec de l'espace : création d'une description vidéo à part - Si les espaces audios sont suffisants pour les descriptions

Cela concerne les descriptions pour lesquelles l'espace dans la vidéo est insuffisant, comme décrit dans [Espace dans le contenu audio ci-dessus](#space)_. Cela nécessite des compétences et un logiciel d'enregistrement et de montage de contenu vidéo. En fonction du lecteur que vous utilisez, vous pourriez nécessiter un logiciel vidéo pou regénérer la vidéo.

Les étapes essentielles du processus de développement d'un fichier audio séparé :
1. L'écriture des descriptions. Retrouvez des [Conseils pour l'écritures de descriptions ci-dessous](#writing).
2. L'enregistrement des descriptions. Retrouvez des [Conseils pour l'enregistrement de descriptions ci-dessous](#recording).
3. La création d'un nouveau fichier audio en associant l'audio original et la nouvelle audiodescription. Retrouvez des [Conseils pour associer des fichiers audios ci-dessous](#combining).
4. Fournissez le(s) fichier(s) :
* _**Si**_ votre lecteur utilise une vidéo et des bandes sonores séparées,<br>vous avez fini.
* _**Si**_ votre lecteur utilise un seul fichier vidéo qui comprend l'audio,<br>générez la nouvelle description vidéo avec le fichier audio que vous venez de créer.

(Assurez-vous que sur la page Web où la vidéo est disponible, la version décrite utilise la version correcte que vous venez de créer.)

### Vidéo sans espace : la création d'une description vidéo à part - S'il n'y a _pas_ suffisamment de place dans l'audio pour les descriptions

S'il n'y a **pas** suffisamment de place pour toutes les descriptions _(comme décrit dans [Espace dans l'audio ci-dessus](#space))_, vous devrez développer un fichier audio à part et créer une piste visuelle. Cela nécessite des compétences et un logiciel d'enregistrement, de montage de contenu audio, et de montage de contenu vidéo.

Voici les étapes essentielles du processus de développement d'un fichier audio séparé et de création d'une piste visuelle :
1. L'écriture des descriptions. Retrouvez des [Conseils pour l'écriture de descriptions ci-dessous](#writing).
2. L'enregistrement des descriptions. Retrouvez des [Conseils pour l'enregistrement de descriptions ci-dessous](#recording).
3. La création d'un nouveau fichier audio en associant le contenu audio original et la nouvelle audiodescription. Retrouvez des [Conseils pour associer les fichiers audios ci-dessous](#combining).
4. La création d'une nouvelle vidéo :
	* _**Si**_ votre vidéo source contient des scènes plus longues _(comme décrit dans "Des contenus audios et vidéos accessibles, dans la section ["Durée pour la description"](/media/av/av-content/#time-for-description))_, recouper les scènes plus longues pour remplir les espaces visuels où vous avez besoin de faire de la place pour la description.
	* _**Si ce n'est pas le cas ou si vous faites un ajout à une vidéo déjà existante**_, vous devrez laisser une image statique dans la vidéo au moment où la description apparaît dans l'audio. <!-- (For example, this video [@@ need very good example - see GitHub](https://github.com/w3c/wai-media-guide/issues/73) pauses at 00:00 for the audio description.) -->

(Assurez-vous que sur la page Web où la vidéo est disponible, la version décrite utilise la version correcte que vous venez de créer.)

### D'autres options
{:.no_toc}

* Une description étendue avec SMIL : le seul mode de balisage pour fournir des audiodescriptions est l'utilisation de SMIL 3.0. L'assitance au SMIL est très limitée. Les implémentations nécessiteront certainement des plug-ins et/ou des approches extrêmement personnalisées.
* Fournir les fonctionnalités pour que la vidéo se mette en pause au moment de la description : cela n'est pas proposé dans la plupart des cas car un codage supplémentaire est nécessaire et l'expérience utilisateur est moins optimale.

{% include_cached excol.html type="start" id="tips" %}

## Conseils pour créer une description vous-mêmes

{% include_cached excol.html type="middle" %}

### Conseils pour l'écriture de descriptions {#writing}
{:.no_toc}

* Décrivez les éléments visuels importants à la compréhension du message communiqué par la vidéo. Imaginez que vous décrivez la vidéo à une personne qui ne peut pas la voir : que dites-vous ? Vous n'avez pas besoin de décrire chaque détail ou chaque élément apparent dans l'audio.
* Décrit objectivement, sans interprétation, censure, ou commentaire.
* Écrire une description au présent, à la voie active, et à la troisième personne du style narratif.

Retrouvez plus d'informations sur l'écriture des descriptions disponible sur le Web, par exemple : [Fiche descriptive {% include_cached external.html %}](https://dcmp.org/learn/227) and [Comment décrire {% include_cached external.html %}](http://www.descriptionkey.org/how_to_describe.html).

### Conseils pour l'enregistrement de descriptions {#recording}
{:.no_toc}

* Utilisez une voix, un style, et un débit qui se distinguent des autres voix utilisées dans la vidéo.
* Utilisez une voix neutre qui ne transmet pas d'émotions.
* Lors de l'enregistrement d'un seul fichier avec des descriptions synchronisées, prononcez les descriptions au même moment que le contenu visuel, ou juste avant le contenu visuel. Ne faites pas apparaitre la description après le contenu visuel.
* Allez sur [aide pour le contenu audio](/media/av/av-content/#audio).

### Conseils pour associer des fichiers audios {#combining}
{:.no_toc}

* Faites apparaitre les descriptions au même moment que le contenu visuel, ou juste avant celui-ci. Ne faites pas apparaitre la description après.

* Faites en sorte que la description soit plus claire que les autres bruits. Au moment d'associer les descriptions avec le contenu audio principal, baissez le volume de l'audio principal au moment de l'apparition de la description et augmentez le volume de l'audio de la description. Lorsque la description est finie, baissez le volume de l'audio de la description et augmentez le volume de l'audio principal à son réglage normal. Répétez ce processus (appelé "ducking") pour chaque moment de description.

{% include_cached excol.html type="end" %}

### Fichier VTT
{:.no_toc}

{::nomarkdown}
{% include box.html type="start" title="Exemple de fichier VTT de l'audiodescription" class="" id="vtt" %}
{:/}

```
WEBVTT

00:00:04.000 --> 00:00:07.980
<v Audiodescriptions>Un homme assis à un bureau commence à regarder une vidéo sur son ordinateur.

00:00:17.260 --> 00:00:20.780
<v Audiodescriptions>La vidéo sur son ordinateur montre une personne qui parle à la caméra.

00:00:20.780 --> 00:00:23.140
<v Audiodescriptions>Elle fonctionne sans audio.

00:00:26.880 --> 00:00:29.620
<v Audiodescriptions>L'homme qui regarde la vidéo a un appareil auditif.
```

{::nomarkdown}
{% include box.html type="end" %}
{:/}
