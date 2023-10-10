---
title: "Transcriptions"
title_image: /content-images/wai-media-guide/transcript.svg
nav_title: "Transcriptions"

lang: fr   # change "en" to lang code, here and 2 @@s below
last_updated: 2021-07-01   # Change to date of translation YYYY-MM-DD (month in middle)
translators:
- name: "Sofia Ahmed"
- name: "Rémi Bétin"
contributors: 
- name: "Sandra Velarde Gonzalez (ETNIC)"

permalink: /media/av/transcripts/fr   # Add lang to end /link/to/page/@@
ref: /media/av/transcripts/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'content/transcripts.fr.md'   # Add lang to the middle of the filename, e.g., index.@@.md

resource:
  ref: /media/av/
navigation:
  previous: /media/av/captions/
  next:     /media/av/transcribing/
changelog: /media/av/changelog/
acknowledgements: /media/av/acknowledgements/

description: Vous aide à comprendre et à créer des transcriptions pour rendre les contenus audios et vidéos multimédia accessibles.
image: /content-images/wai-media-guide/social.png

footer: >   # Translate words below, including "Date:" and "Editor:". (Do not update the date.)
   <p><strong>Date:</strong> Mise à jour : 12 avril 2021. Première publication en septembre 2019. CHANGELOG.</p>
   <p><strong>Rédactrice :</strong> <a href="http://www.w3.org/People/Shawn">Shawn Lawton Henry</a>. ACKNOWLEDGEMENTS liste les contributeurs et les crédits.</p>
   <p>Développé par le groupe de travail Éducation et promotion (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Rédigé initialement dans le cadre du projet <a href="https://www.w3.org/WAI/WCAGTA/">WCAG TA</a> financé par le <abbr title="United States">U.S.</abbr> Access Board. Révisé dans le cadre du projet <a href="https://www.w3.org/WAI/expand-access/">WAI Expanding Access</a> financé par la fondation Ford.</p>

---

{::nomarkdown}
{% include box.html type="start" title="Résumé" class="" %}
{:/}

Les transcriptions de base sont une version texte de l’information parlée ou non parlée nécessaire pour comprendre le contenu. Les transcriptions descriptives incluent également une description textuelle des informations visuelles nécessaires pour comprendre le contenu. Les transcriptions descriptives sont nécessaires pour fournir un contenu vidéo aux personnes sourdes et aveugles.

Cette page vous aide à comprendre et à créer des transcriptions.

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

Les transcriptions de base sont une version textuelle des informations audios vocales et non vocales nécessaires à la compréhension du contenu.

_Qui :_ Les transcriptions de base sont utilisées par les personnes sourdes, malentendantes, celle qui ont des difficultés à traiter l'information auditive, et d'autres.

**_Les transcriptions descriptives_** pour vidéos comprennent également les informations visuelles nécessaires à la compréhension du contenu.

{% include image.html src="braille.jpg" alt="" class="normal right" %}

_Qui :_ Les transcriptions descriptives sont nécessaires pour fournir un contenu audio et vidéo aux personnes à la fois sourdes et aveugles. Elles sont aussi utilisées par les personnes qui comprennent mieux l'information textuelle que l'information audio et visuelle/illustrée.

Vous fournirez idéalement une transcription descriptive, et vous n'aurez alors pas besoin d'une transcription de base à part.

_Les transcriptions interactives_ surlignent les phrases de texte au moment où elles sont prononcées. Les utilisateurs peuvent sélectionner du texte dans la transcription et atteindre cet instant dans la vidéo. Il s'agit d'une fonctionnalité du lecteur multimédia. Elle utilise le fichier de sous-titres.

<img src="{{ "/content-images/wai-media-guide/interactive-transcript.png" | relative_url }}" alt="">

## Mon contenu multimédia nécessite-t-il une transcription ? {#checklist}

**Réponse courte : oui, les transcriptions descriptives sont nécessaires pour répondre aux besoins d'une large palette d'utilisateurs**.

Dans certains cas, les transcriptions ne sont pas requises pour répondre aux standards des WCAG. _(la page Planifier de cette ressource introduit le [standard des WCAG](/media/av/planning/#wcag-standard).)_

{% capture boxhead %}
Contenu seulement audio (par exemple, les podcasts) :
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="checklist-ao" %}
{:/}

- Pour les contenus pré-enregistrés :
   - Les transcriptions sont **_requises_** au niveau A des WCAG.
   {:.alt}
- Pour les contenus en direct :
   - Les transcriptions se situent au niveau AAA des WCAG. Généralement il doit s'agir d'une diffusion du texte en direct. Si l'audio suit un scénario, vous pouvez fournir le texte du scénario.
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

- Pour les vidéos pré-enregistrées :
   - Une transcription descriptive **_ou_** une audio-description est **_requise_** au niveau A dans les WCAG.
   {:.alt}
- Pour les vidéos en direct :
   - Une description des informations visuelles est nécessaire. Généralement, il s'agit d'une diffusion du texte en direct, plutôt que d'une transcription. Ce n'est pas requis dans les WCAG.
   {:.alt}

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{% capture boxhead %}
Vidéo avec du contenu audio :
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="checklist-va" %}
{:/}

- Pour les vidéos pré-enregistrées :
   - Les transcriptions se situent au niveau AAA des WCAG. (les sous-titres se situent au niveau A.)
   {:.alt}
- Pour les vidéos en direct :
   - Une flux en direct séparé du lecteur multimédia est nécessaire pour les personnes qui n'ont pas accès aux sous-titres. Cela n'est pas requis dans les WCAG (Les sous-titres se situent au niveau AA.)
   {:.alt}

{::nomarkdown}
{% include box.html type="end" %}
{:/}

<br>

**Extraits des WCAG** avec des accentuations, des ajouts entre [crochets] et des liens vers plus d'informations dans "Comprendre les WCAG" :
* [A 1.2.1 Contenu seulement audio ou vidéo](https://www.w3.org/WAI/WCAG21/Understanding/audio-only-and-video-only-prerecorded.html) (pré-enregistré) : pour des médias pré-enregistrés seulement audio et pré-enregistrés seulement vidéo...
    * Contenu pré-enregistré seulement audio : fournir une version de remplacement pour un média temporel [transcription] présentant une information équivalente au contenu seulement audio.
    * Contenu pré-enregistré seulement vidéo : fournir, soit une version de remplacement pour un média temporel [transcription descriptive] ***ou*** une piste audio  [de description] (présentant une information équivalente) pour un contenu pré-enregistré seulement vidéo.
* [AAA 1.2.8 Version de remplacement pour un média temporel](https://www.w3.org/WAI/WCAG21/Understanding/media-alternative-prerecorded.html) (pré-enregistrée) :  fournir une version de remplacement pour un média temporel [transcription], pour tout contenu de type média synchronisé pré-enregistré et pour tout média pré-enregistré seulement vidéo..
* [AAA 1.2.9 Seulement audio](https://www.w3.org/WAI/WCAG21/Understanding/audio-only-live.html) (en direct) : fournir une version de remplacement pour un média temporel [flux textuel en direct ou transcription], donnant une information équivalente pour un contenu seulement audio en direct.

### Fournissez une transcription descriptive pour vos vidéos
{:.no_toc}

Les transcriptions descriptives sont nécessaires pour les personnes sourdes et aveugles et d'autres. (Retrouvez davantage de contexte dans la page Planifier : [Transcriptions descriptives](/media/av/planning/#descriptive-transcripts).) De plus, **les transcriptions descriptives sont faciles et peu coûteuses à produire** en utilisant les sous-titres et l'audio-description qui doivent déjà répondre aux critères du niveau AA, comme expliqué sur cette page.

## Processus – Compétences et outils {#process-skills-and-tools}

Le processus pour fournir des transcriptions consiste généralement à :
1.	Obtenir une version textuelle de l'audio, appelée "transcription".
2.	Formater la transcription.
3.	Mettre la transcription en ligne, et faciliter l'accès des utilisateurs à la transcription à partir du fichier audio ou vidéo.

### Si vous débutez dans la création de sous-titres

Pour les vidéos, la transcription de l'audio en texte est souvent réalisée pour créer des sous-titres, comme décrit sur la page [sous-titres](/media/av/captions/). Ensuite, le fichier de sous-titres est utilisé pour créer la transcription.

La création de transcriptions à partir de fichiers de sous-titres est facile à produire avec des compétences et des outils Web de base.

### Si vous débutez dans la transcription

Transcrire un fichier audio prend un certain temps pour les personnes qui n'ont pas un logiciel ou les compétences adéquates. De nombreuses organisations choisissent de sous-traiter leur transcription. Vous trouverez des conseils pour créer vous-même votre transcription dans une autre page de cette ressource : [Transcription de contenu audio en texte](/media/av/transcribing/).

Une fois la transcription en main, créer le fichier de transcription est simple avec des compétences et des outils Web de base.

## Créer des transcriptions

Si vous disposez déjà des sous-titres, vous pouvez utiliser ce fichier pour créer votre transcription. La plupart des outils servant à éditer des sous-titres fournissent une option pour exporter une transcription en texte brut. Sans quoi vous devrez supprimer les horodatages, ou les éditer comme indiqué plus bas.

Si vous ne disposez pas de sous-titres, vous aurez besoin d'une transcription des informations audios. Ce point est traité dans une autre page de cette ressource : [Transcription de contenu audio en texte](/media/av/transcribing/).

Les sous-titres sont généralement rédigés pour être vus avec la vidéo visuelle. Les transcriptions doivent inclure les informations visuelles importantes pour ceux qui ne voient pas la vidéo. Quand vous utilisez des sous-titres pour créer des transcriptions, **vous aurez généralement besoin d'ajouter à la transcription l'information visuelle**, comme le texte contenu dans la vidéo et l'identification des locuteurs.

### Format de fichier pour la transcription

La plupart des transcriptions sur le Web sont fournies en HTML. Il n'existe pas de style établi pour les transcriptions. Différentes options et exemples sont décrits à travers les conseils qui suivent.

Une transcription de podcast peut consister en de simples paragraphes de texte avec l'identification des locuteurs.

{::nomarkdown}
{% include box.html type="start" title="Exemple de transcription d'un podcast d'une interview avec deux interlocuteurs (extrait)" class="" %}
{:/}

<p>Rajwinder Kaur : Bienvenue sur ce podcast.</p>
<p><strong>Shawn Henry :</strong> Merci pour cette opportunité de partager des informations sur l'accessibilité.</p>
<p>Rajwinder : Commencez peut-être par nous en dire un peu plus sur votre rôle au sein de W3C ?</p>
<p><strong>Shawn :</strong> Je travaille au sein de l'initiative pour l'accessibilité du Web, W-A-I, que l'on prononce "wey".</p>

{::nomarkdown}
{% include box.html type="end" %}
{:/}

Une transcription descriptive peut être mise sous forme de tableau pour permettre aux utilisateurs de lire avec facilité dans une colonne la seule information audio s'ils le souhaitent. Retrouvez un [exemple de transcription descriptive ci-dessous](#descriptive).

{% include excol.html type="start" id="" open="true" %}

### Rendre les transcriptions plus utiles

{% include excol.html type="middle" %}

Gardez en tête que l'objectif principal d'une transcription est de fournir des informations aux personnes qui ne peuvent pas les obtenir à partir du contenu audio et/ou vidéo. Cela vous aidera à savoir ce qu'il faut inclure et comment le réaliser. Ajoutez des informations pour rendre la transcription plus utile. Par exemple, ajoutez des titres, des liens, un résumé, et peut-être des horodatages, comme décrit plus bas. Les informations suivantes sont optionnelles et non des obligations.

* **Organisez l'information en paragraphes, listes et sections logiques**. Si vous partez d'un fichier de sous-titres, vous devrez certainement rassembler plusieurs lignes en paragraphes. Par exemple, dans les [extraits suivants](#example-descriptive-transcript-from-caption-files), 6 lignes de sous-titres sont regroupées en 2 paragraphes de texte (dans les cellules du tableau).

* **Ajoutez une navigation et des éclaircissements :**
   * Ajoutez des titres et des liens quand cela peut rendre la transcription plus facile à utiliser. (Cela favorise également l'optimisation pour les moteurs de recherche (SEO)). Voici un [exemple avec des liens ajoutés à une courte transcription de podcast](http://www.w3.org/WAI/highlights/200606wcag2interview.html).
   * Il est généralement acceptable d'ajouter des éclaircissements, _tant qu'il est clair qu'ils ne font pas partie de l'audio_ &mdash; par exemple, des mots ajoutés aux paragraphes mis entre [crochets], ou des sections séparées par des les titres "Introduction", "Transcription", "Ressouces". Voici un [exemple avec des titres ajoutés dans la longue transcription d'une présentation](http://www.w3.org/WAI/highlights/200706wcag2pres).

* **Identifiez les locuteurs en fonction du type de contenu.** Par exemple :
   * Lorsqu'il y a plusieurs locuteurs, vous pourriez utiliser des retraits négatifs de première ligne pour repérer plus facilement un locuteur.
   * Lorsque vous voulez attirer l'attention sur les réponses de la personne interviewée plutôt que sur l'intervieweur, vous pourriez mettre en gras le nom de la personne interviewée pour le faire ressortir plus clairement.

* **Incluez des horodatages seulement lorsque c'est utile.** Dans de nombreux cas, ajouter des horodatages serait inutilement encombrant. Si vous les ajoutez, ils n'ont généralement pas besoin d'être aussi granulaires que les sous-titres, et n'ont pas besoin d'inclure les horodatages de fin.

* **Si vous commencez à partir de sous-titres de vidéo :** La vidéo pourrait contenir des informations textuelles qui n'apparaissent pas dans les sous-titres ; par exemple, le titre de la vidéo ou le nom et le titre des personnes qui parlent. Si vous possédez aussi la description des informations visuelles, cela devrait déjà s'y trouver. Si ce n'est pas le cas, vous devrez revoir la vidéo et regarder si du texte contenu dans la vidéo est absent des sous-titres, et, le cas échéant, l'ajouter dans votre transcription.

## Où placer les transcriptions

Faites en sorte que les utilisateurs puissent facilement savoir qu'une transcription est disponible et y accéder. Par exemple, placez la transcription elle-même ou  un lien vers celle-ci juste en-dessous de la vidéo.

Pour le contenu multimédia de votre site Web, il est généralement préférable d'inclure la transcription sur la même page. Voici un [exemple de transcription descriptive à la fin d'une même page contenant une vidéo](https://www.w3.org/WAI/perspective-videos/captions/#transcript).

Lorsque votre contenu multimédia est hébergé ailleurs, vous pourriez placer votre transcription sur une page Web à part. Voici un [exemple de transcription de podcast sur une page séparée](https://www.w3.org/WAI/highlights/200606wcag2interview.html).

{% include excol.html type="start" id="example-descriptive" %}

## Exemple de transcription descriptive à partir de fichiers de sous-titres

{% include excol.html type="middle" %}

Retrouvez ci-dessous un exemple de fichier de sous-titres utilisé pour créer une transcription descriptive.

{::nomarkdown}
{% include box.html type="start" title="Exemple de fichier de sous-titres d'informations audios (extrait)" class="" %}
{:/}

```
00:00:08.120 --> 00:00:10.240
Une vidéo ne se résume pas à des images,

00:00:10.241 --> 00:00:12.040
c'est aussi du son.

00:00:12.160 --> 00:00:16.280
Sans l'audio, vous devriez deviner de quoi parle ce film.

00:00:23.140 --> 00:00:24.730
Frustrant, n'est-ce pas ?

00:00:24.731 --> 00:00:26.880
De ne pas savoir ce qu'il se passe.

00:00:29.620 --> 00:00:32.840
C'est ce que vivent tous ceux qui ne peuvent pas entendre.
```

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include box.html type="start" title="Exemple de fichier de sous-titres d'une audio-description d'informations visuelles (extrait)" class="" %}
{:/}

```
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

<div id="descriptive"></div>

{::nomarkdown}
{% include box.html type="start" title="Exemple de transcription descriptive à partir des fichiers de sous-titres ci-dessus (extrait)" class="" %}
{:/}

<table>
  <thead>
    <tr>
      <th width="65%">Audio</th>
      <th>Visuel</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Une vidéo ne se résume pas à des images, c'est aussi du son. Sans l'audio, vous devriez deviner de quoi parle ce film.</td>
      <td>Un homme assis à un bureau commence à regarder une vidéo sur son ordinateur.<br></td>
    </tr>
    <tr>
      <td>[pas de son]</td>
      <td>La vidéo sur son ordinateur montre une personne qui parle à la caméra. La vidéo est lue sans audio.</td>
    </tr>
    <tr>
      <td>Frustrant, n'est-ce pas ? De ne pas savoir ce qu'il se passe. C'est ce que vivent tous ceux qui ne peuvent pas entendre.</td>
      <td>L'homme qui regarde la vidéo a un appareil auditif.</td>
    </tr>
  </tbody>
</table>

{::nomarkdown}
{% include box.html type="end" %}
{:/}

**Remarquez que les lignes individuelles dans les fichiers de sous-titres ont été regroupées dans les cellules du tableau.**

{% include excol.html type="end" %}
