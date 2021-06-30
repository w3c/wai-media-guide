---
title: "Transcriptions"
title_image: /content-images/wai-media-guide/transcript.svg
nav_title: "Transcriptions"

lang: fr   # change "en" to lang code, here and 2 @@s below
last_updated: 2020-01-01   # Change to date of translation YYYY-MM-DD (month in middle)
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
  next:     /media/av/sign-languages/
changelog: /media/av/changelog/
acknowledgements: /media/av/acknowledgements/

description: Vous aide à comprendre et à créer des transcriptions pour rendre les contenus audios et vidéos multimédia accessibles.
image: /content-images/wai-media-guide/social.png

footer: >   # Translate words below, including "Date:" and "Editor:". (Do not update the date.)
   <p><strong>Date :</strong> Mise à jour : 9 octobre 2020. CHANGELOG.</p>
   <p><strong>Rédactrice :</strong> <a href="http://www.w3.org/People/Shawn">Shawn Lawton Henry</a>. ACKNOWLEDGEMENTS : liste les contributeurs et les crédits.</p>
   <p>Développé par le groupe de travail Éducation et Promotion (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Rédigé initialement dans le cadre du projet <a href="https://www.w3.org/WAI/WCAGTA/">WCAG TA</a> financé par le <abbr title="United States">U.S.</abbr> Access Board. Révisé dans le cadre du projet <a href="https://www.w3.org/WAI/expand-access/">WAI Expanding Access</a> financé par la fondation Ford.</p>

---

{::nomarkdown}
{% include box.html type="start" title="Résumé" class="" %}
{:/}

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

_Qui :_ Les transcriptions de base sont utilisées par les personnes sourdes, malentendantes, celle qui ont des difficultés à comprendre l'information auditive, et les autres.

**_Les transcriptions descriptives_** pour vidéos comprennent également les informations visuelles nécessaires à la compréhension du contenu.

{% include image.html src="braille.jpg" alt="" class="normal right" %}

_Qui :_ Les transcriptions descriptives sont nécessaires pour fournir un contenu audio et vidéo aux personnes à la fois sourdes et aveugles. Elles sont aussi utilisées par les personnes qui comprennent mieux l'information textuelle plutôt que l'information audio et visuelle/illustrée.
Si vous fournissez une transcription descriptive, vous avez besoin d'une transcription de base à part.

_Transcriptions interactives_ surligne les phrases de texte au moment où elles sont prononcées. Les utilisateurs peuvent sélectionner le texte dans la transcription et aller l'endroit correspondant dans la vidéo. C'est une caractéristique dU lecteur multimédia. Il utilise le fichier de légendes.

<img src="{{ "/content-images/wai-media-guide/interactive-transcript.png" | relative_url }}" alt="">

## Mon contenu multimédia nécessite-t-il une transcription ? {#checklist}

**Réponse courte : oui, les transcriptions sont nécessaires pour répondre à l'ensemble des besoins des utilisateurs**.

Dans certains cas, les transcriptions ne sont pas requises pour répondre aux standards des WCAG. _(la page Production de cette ressource introduit le [standard des WCAG](/media/av/planning/#wcag-standard).)_

{% capture boxhead %}
Contenu uniquement audio (par exemple, les podcasts):
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="checklist-ao" %}
{:/}

- Pour les contenus pré-enregistrés :
   - Les transcriptions sont **_requises_** au niveau A des WCAG.
   {:.alt}
- Pour les contenus en direct :
   - Les transcriptions se situent au niveau AAA des WCAG. Généralement il doit s'agir d'une diffusion du texte en direct. Si l'audio suit le script, vous pouvez fournir un script textuel.
   {:.alt}

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{% capture boxhead %}
Contenu uniquement vidéo (sans contenu audio) :
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="checklist-vo" %}
{:/}

- Pour le pré-enregistré :
   - La transcription descriptive **_ou_** l'audiodescription est **_requise_** au niveau A dans les WCAG.
   {:.alt}
- Pour le direct :
   - Une description des informations visuelles est nécessaire. Généralement, il s'agit d'une diffusion du texte en direct, plutôt que d'un script. Ce n'est pas requis dans les WCAG.
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

- Pour le pré-enregistré :
   - Les transcriptions se situent au niveau AAA des WCAG. (Les légendes se situent au niveau A)
   {:.alt}
- Pour le direct :
   - Une diffusion en direct séparée du lecteur multimédia est nécessaire pour les personnes qui n'ont pas accès aux légendes. Cela n'est pas requis dans les WCAG (Les légendes se situent au niveau AA.)
   {:.alt}

{::nomarkdown}
{% include box.html type="end" %}
{:/}

### Fournissez une transcription descriptive pour vos vidéos
{:.no_toc}

Des transcriptions descriptives sont nécessaires pour les personnes sourdes et aveugles et les autres. (Retrouvez un peu plus d'informations sur la page Production : [Transcriptions descriptives](/media/av/planning/#descriptive-transcripts).) De plus, **les transcriptions descriptives sont faciles et peu coûteuses à produire** en utilisant les légendes et l'audiodescription qui doivent déjà répondre aux critères du niveau AA, comme expliqué sur cette page.

## Processus – Compétences et outils

Le processus pour fournir des transcriptions est essentiellement :
1.	Obtenez une version textuelle de l'audio, appelée "transcription".
2.	Formatez la transcription.
3.	Mettez la transcription en direct, facilitez l'accès pour les utilisateurs à la transcription à partir du fichier audio ou vidéo.

### Si vous commencez avec la création des légendes

Pour les vidéos, la transcription de l'audio en texte est souvent réalisée pour créer des légendes, comme décrit sur la page [légendes](/media/av/captions/). Ensuite, le fichier de légendes est utilisé pour créer la transcription.

La création de transcriptions à partir de fichiers de légendes est facile à produire avec des compétences et des outils de base.

### Si vous commencez avec la création de la transcription

Transcrire un fichier audio prend un certain temps pour les personnes qui n'ont pas de logiciel ou les compétences adéquates. De nombreuses organisations choisissent de sous-traiter leur transcription. Vous trouverez de l'aide pour créer vous-même votre transcription sur une autre page de cette ressource : [Transcription de contenu audio en texte](/media/av/transcribing/).

Une fois que vous avez la transcription, la création de la transcription est facile à produire avec des compétences et des outils de base.

## La création de transcriptions

Si vous disposez déjà des légendes, vous pouvez utiliser ce fichier pour créer votre transcription. La plupart des outils servant à éditer les légendes fournissent une option pour exporter une transcription textuelle simple. Autrement, vous devrez supprimer les horodatages, ou les éditer comme indiqué plus bas.

Si vous ne disposez pas des légendes, vous aurez besoin une transcription des informations audios. Retrouvez plus d'informations sur une autre page de cette ressource : [Transcription de contenu audio en texte](/media/av/transcribing/).

Souvent, vous aurez besoin d'ajouter l'information visuelle à la transcription, comme le texte contenu dans la vidéo.

### Format de fichier pour la transcription

La plupart des transcriptions sur le Web sont fournies en HTML. Il n'existe pas de scénarisation pour les transcriptions. Différentes options et exemples sont décrits dans les conseils ci-dessous.

Une transcription de podcast peut consister en de simples paragraphes de texte avec l'identification des locuteurs.

{::nomarkdown}
{% include box.html type="start" title="Exemple de transcription d'un podcast d'une interview avec deux interlocuteurs (extrait)" class="" %}
{:/}

<p>Rajwinder Kaur: Bienvenue sur ce podcast.</p>
<p><strong>Shawn Henry:</strong> Merci pour cette opportunité de partager des informations sur l'accessibilité.</p>
<p>Rajwinder: Commencez peut-être par nous en dire un peu plus sur votre rôle au W3C ?</p>
<p><strong>Shawn:</strong> Je travaille au sein du Web Accessibility Initiative, W-A-I, prononcé "wey". </p>

{::nomarkdown}
{% include box.html type="end" %}
{:/}

Une transcription descriptive peut être mise sous forme de tableau pour permettre aux utilisateurs de lire facilement seulement l'information audio dans une colonne s'ils le souhaitent. Retrouvez un [exemple de transcription descriptive ci-dessous](#descriptive).

{% include excol.html type="start" id="" open="true" %}

### Rendre les transcriptions plus utiles

{% include excol.html type="middle" %}

Gardez en tête que l'objectif principal d'une transcription est de fournir des informations aux personnes qui ne peuvent pas les obtenir à partir du contenu audio et/ou vidéo. Cela vous aidera à savoir ce qu'il faut inclure et comment le réaliser. Ajoutez des informations pour rendre la transcription plus utile. Par exemple, ajoutez des titres, des liens, un résumé, et peut-être des horodatages, comme décrit plus bas. Les informations suivantes sont optionnelles :

* **Organisez l'information en paragraphes, en listes, et en sections logiques**. Si vous commencez avec un fichier de légendes, vous devrez certainement rassembler des lignes en paragraphes. Par exemple, dans les [extraits suivants](#example-descriptive-transcript-from-caption-files), 6 lignes de légendes sont regroupées en 2 paragraphes de texte (dans les cellules du tableau).

* **Ajoutez une navigation et des explications :**
   * Ajoutez des titres et des liens lorsque cela peut rendre la transcription plus utile. (Cela favorise également l'optimisation pour les moteurs de recherche (SEO). Voici un [exemple avec des liens ajoutés à une courte transcription de podcast](http://www.w3.org/WAI/highlights/200606wcag2interview.html).
   * Il est généralement bienvenu d'ajouter des explications, _tant qu'elles sont clairement distinguées de l'audio actuel_ &mdash; par exemple, les mots ajoutés au paragraphes mis entre [crochets], ou des sections séparées avec les titres "Introduction", "Transcription", "Ressouces". Voici un [exemple avec des titres ajoutés dans la longue transcription d'une présentation](http://www.w3.org/WAI/highlights/200706wcag2pres).

* **Indiquez les locuteurs en fonction du type de contenu.** Par exemple :
   * Lorsqu'il y a plusieurs locuteurs, vous pourriez utiliser des retraits négatifs de première ligne pour identifier le locuteur plus facilement.
   * Lorsque vous voulez attirer l'attention sur les réponses de la personne interviewée plutôt que sur l'intervieweur, vous pourriez mettre en gras le nom de la personne interviewée pour le faire ressortir.

* **Incluez des horodatages seulement lorsque c'est utile.** Dans de nombreux cas, ajouter des horodatages serait inutilement encombrant. Si vous les ajoutez, ils n'ont généralement pas besoin d'être aussi granulaires que les légendes, et n'ont pas besoin d'inclure les horodatages de fin.

* **Si vous commencez en produisant les légendes pour la vidéo :** La vidéo pourrait contenir des informations textuelles qui n'apparaissent pas dans les légendes, par exemple, le titre de la vidéo ou le nom et le titre des personnes qui parlent. Si vous avez aussi la description des informations visuelles, elle devrait déjà s'y trouver. Si ce n'est pas le cas, vous devrez revoir la vidéo, regarder si du texte contenu dans la vidéo apparaît dans les légendes, et, le cas échéant, l'ajouter dans la transcription.

## Où mettre les transcriptions

Les utilisateurs doivent savoir facilement qu'une transcription est disponible et comment y accéder. Par exemple, mettez la transcription elle-même ou bien un lien vers celle-ci juste en-dessous de la vidéo.

Pour le contenu multimédia de votre site Web, il est généralement préférable d'inclure la transcription sur la même page. Voici un [exemple de transcription descriptive à la fin d'une même page contenant une vidéo](https://www.w3.org/WAI/perspective-videos/captions/#transcript).

Lorsque votre contenu multimédia se situe ailleurs, vous pourriez mettre votre transcription sur une page Web à part. Voici un [exemple de transcription de podcast sur une page séparée](https://www.w3.org/WAI/highlights/200606wcag2interview.html).

{% include excol.html type="start" id="example-descriptive" %}

## Exemple de transcription descriptive à partir des fichiers de légendes

{% include excol.html type="middle" %}

Retrouvez ci-dessous un exemple de fichier de légendes utilisé pour créer une transcription descriptive.

{::nomarkdown}
{% include box.html type="start" title="Exemple de fichier de légendes d'informations audios (extrait)" class="" %}
{:/}

```
00:00:08.120 --> 00:00:10.240
Une vidéo ne résume pas à des images,

00:00:10.241 --> 00:00:12.040
elle contient aussi du son.

00:00:12.160 --> 00:00:16.280
Sans l'audio, vous devriez deviner de quoi parle ce film.

00:00:23.140 --> 00:00:24.730
Frustrant, n'est-ce pas ?

00:00:24.731 --> 00:00:26.880
De ne pas savoir ce qu'il se passe.

00:00:29.620 --> 00:00:32.840
C'est ce que vivent toutes les personnes qui ne peuvent pas entendre.
```

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include box.html type="start" title="Exemple de fichier de légendes d'informations visuelles d'une audiodescription (extrait)" class="" %}
{:/}

```
00:00:04.000 --> 00:00:07.980
<v Audiodescriptions> Un homme assis à un bureau commence à regarder une vidéo sur son ordinateur.

00:00:17.260 --> 00:00:20.780
<v Audiodescriptions> La vidéo sur son ordinateur montre une personne qui parle à la caméra.

00:00:20.780 --> 00:00:23.140
<v Audiodescriptions> Elle tourne sans audio.

00:00:26.880 --> 00:00:29.620
<v Audiodescriptions> L'homme qui regarde la vidéo a un appareil auditif.
```

{::nomarkdown}
{% include box.html type="end" %}
{:/}

<div id="descriptive"></div>

{::nomarkdown}
{% include box.html type="start" title="Exemple de transcription descriptive à partir de fichier de légendes ci-dessous (extrait)" class="" %}
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
      <td>Une vidéo ne se résume pas à des images, elle contient aussi du son. Sans l'audio, vous devriez deviner de quoi parle ce film.</td>
      <td>Un homme assis à un bureau commence à regarder une vidéo sur son ordinateur.<br></td>
    </tr>
    <tr>
      <td>[pas de son]</td>
      <td>La vidéo sur son ordinateur montre une personne qui parle à la caméra. La vidéo tourne sans audio.</td>
    </tr>
    <tr>
      <td>Frustrant, n'est-ce pas ? De ne pas savoir ce qu'il se passe. C'est ce que vivent les personnent qui ne peuvent pas entendre.</td>
      <td>L'homme qui regarde la vidéo a un appareil auditif.</td>
    </tr>
  </tbody>
</table>

{::nomarkdown}
{% include box.html type="end" %}
{:/}

**Remarquez que les lignes individuelles dans les fichiers de légendes ont été regroupées dans les cellules du tableau.**

{% include excol.html type="end" %}
