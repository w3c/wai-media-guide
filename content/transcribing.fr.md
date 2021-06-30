---
title: "Transcrire un contenu audio en texte"
nav_title: "Transcrire un contenu audio en texte"

lang: fr   # change "en" to lang code, here and 2 @@s below
last_updated: 2020-01-02   # Change to date of translation YYYY-MM-DD (month in middle)
translators:
- name: "Sofia Ahmed"
- name: "Rémi Bétin"
contributors: 
- name: "Sandra Velarde Gonzalez (ETNIC)"

permalink: /media/av/transcribing/fr   # Add lang to end /link/to/page/@@
ref: /media/av/transcribing/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'content/transcribing.fr.md'   # Add lang to the middle of the filename, e.g., index.@@.md

resource:
  ref: /media/av/
navigation:
  previous: /media/av/sign-languages/
  next:     /media/av/acknowledgements/
changelog: /media/av/changelog/
acknowledgements: /media/av/acknowledgements/

description: Fournit de l'aide pour transcrire un contenu audio en texte -- pour créer des légendes et des transcriptions pour l'accessibilité des contenus multimédia audios et vidéos.
image: /content-images/wai-media-guide/social.png

footer: >   # Translate words below, including "Date:" and "Editor:". (Do not update the date.)
   <p><strong>Date :</strong> Mise à jour : 10 septembre 2019. CHANGELOG.</p>
   <p><strong>Rédacteur :</strong> <a href="http://www.w3.org/People/Shawn">Shawn Lawton Henry</a>. ACKNOWLEDGEMENTS : liste les contributeurs et les crédits.</p>
   <p>Développé par le groupe de travail Éducation et Promotion (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Rédigé initialement dans le cadre du projet <a href="https://www.w3.org/WAI/WCAGTA/">WCAG TA</a> financé par le <abbr title="United States">U.S.</abbr> Access Board. Révisé dans le cadre du projet <a href="https://www.w3.org/WAI/expand-access/">WAI Expanding Access</a> financé par la fondation Ford.</p>

---

{::nomarkdown}
{% include box.html type="start" title="Résumé" class="" %}
{:/}

Cette page fournit de l'aide pour transcrire un contenu audio en texte pour des légendes et des transcriptions, pour ceux qui souhaitent le faire par eux-mêmes.

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
{:.no_toc}

Une transcription optimale requiert de savoir quelles informations audios non vocales devraient être incluses dans la transcription. Cela relève plus de l'art que de la science — par exemple, il n'est pas toujours facile de savoir quelles informations audios non vocales il faut inclure et comment il faut les communiquer dans le texte.

Idéalement, si vous disposez de ressources, engagez des professionnels pour réaliser votre transcription. Si vous n'en disposez pas, ne soyez pas découragé de devoir fournir des transcriptions ou des légendes. Cette page vous aide à le faire vous-même.

Dans certains cas, du texte est déjà disponible dans un script. Vous devrez probablement apporter quelques retouches pour qu'il  corresponde exactement au contenu audio final.

## Comment transcrire

Vous pouvez simplement écouter l'audio et taper ce que vous entendez. Cela est généralement fastidieux car vous devez arrêter et relancer l'audio de nombreuses fois. Il existe un logiciel qui vous aide à ralentir l'audio et qui vous fournit des boutons de pause faciles à utiliser.
<!-- There are some free services online. They tend to have lower accuracy. You can purchase speech recognition software and train it to be more accurate with your voice. This may be a viable option for things like regular podcasts that usually have a single speaker. -->

Vous pouvez commencer avec un fichier de texte généré automatiquement. Il existe de nombreux logiciels et services de reconnaissance vocale. Leurs niveaux de précision divergent. Il arrive souvent que le texte ne corresponde pas à l'audio parlé — et d'une manière qui en modifie le sens (ou d'une manière embarrassante). Par exemple, le simple fait d'oublier le mot "pas" peut faire en sorte que les légendes contredisent le contenu audio en question.

{::nomarkdown}
{% include box.html type="start" title="Exemple légendes automatiques mal transcrites (qui peut provoquer un incendie)" class="simple aside"  %}
{:/}

{% include image.html src="food-fire.jpg" alt="" class="normal right" %}
  _Texte parlé :_<br>&quot;Grillez à feu vif pendant <strong>4 à 5 minutes</strong>. Vous ne devez <strong>pas</strong> préchauffer le four.&quot;<br>
  _Légende automatique :_<br>&quot;Grillez à feu vif pendant <strong>45 minutes</strong>. Vous devez <strong>préchauffer</strong> le four.&quot;

{::nomarkdown}
{% include box.html type="end" %}
{:/}

Prévoyez du temps pour la correction de la transcription générée automatiquement.

Retrouvez plus de détails sur les options et les outils pour transcrire sur : Transcriptions sur le Web, [Comment obtenir ou produire des transcriptions {% include_cached external.html %}](http://www.uiaccess.com/transcripts/transcripts_on_the_web.html#justdoit).

Retrouvez quelques informations à propos des outils de sous-titrage sur la page Légendes/Sous-titres de cette ressource : [Outils de sous-titrage](/media/av/captions/#caption-tools).

## Que transcrire

Généralement, vous transcrivez tout le contenu parlé et l'audio vocal non pertinent (tels que : les pleurs de bébé, les feux d'artifice qui s'allument, les sabots de cheval qui s'approchent). Gardez en tête que l'objectif principal est de **fournir les informations que vous entendez aux personnes qui ne peuvent pas entendre l'audio**. Cela vous aidera à savoir quels sons transcrire, et lesquels ne sont pas nécessaires. Les conseils suivants sont des pratiques courantes et non des obligations.

### Pratiques de base

* **Identifiez les locuteurs** de manière pertinente. Souvent, il est préférable d'utiliser le nom complet la première fois et le nom simple ensuite  &mdash; soit le prénom, soit le nom de famille en fonction de la formalité.

* Vous pouvez **inclure les informations pertinentes à propos du contenu parlé**. Par exemple :<br>
	<em>( en serrant les dents ):</em><br>
	Je déteste cet ordinateur !

* Mettez les **sons non vocaux** entre parenthèses, en minuscule, en italique, avec une espace avant et après. Par exemple :<br>
	 <em>( l'ordinateur éclate en morceaux et des pièces glissent sur le sol )</em>

* Lorsqu'un **locuteur n'apparaît pas à l'écran**, vous pouvez mettre son intervention en italique. Par exemple :<br>
	<em>José : quel était ce bruit affreux ?</em><br>
	Zoe: Tu ne veux pas le savoir.<br>
	<em>Jose: Eh bien, je viens pour savoir.</em>

* **Incluez la musique de fond seulement si** c'est important pour comprendre le contenu de la vidéo. Utilisez des descriptions objectives qui indiquent l'humeur ; évitez les mots subjectifs, tels que "beau". Si les paroles d'une musique sont importantes, ajoutez une note de musique au début et à la fin de chaque sous-titre. Mettez les informations relatives à la musique en italique. Par exemple :<br>
	<em>♪ musique effrayante, sur le thème des Dents de la mer ♪</em>

* Ne mettez pas d'emphase sur un mot en utilisant des **lettres en majuscule**, sauf pour indiquer qu'ils s'agit de cris. Par exemple : <br>
	Jose: TU AS BOUSILLÉ MON NOUVEL ORDINATEUR PORTABLE !

### Transcrivez avec précision et fidèlité

* **N'apportez pas de modifications ou d'adaptations au texte**. Transcrivez exactement ce qui est dit.
   * par exemple, il n'est pas approprié de corriger les fautes de grammaire ou autres.
   * Ne censurez pas. Par exemple, si des mots désagréables sont prononcés, incluez-les dans les légendes. Si l'audio est modifié de manière à taire une phrase (par exemple, l'audio "bipé"), reflétez-le aussi dans les légendes, par exemple, <em> --bip-- </em>
   * Ne fournissez pas d'explications supplémentaires dans les légendes. (Vous pouvez en fournir quelques unes dans la transcription, le cas échéant.)

* Détaillez de manière appropriée :
   * Pour certains contenus, tels que les dépositions judicaires, transcrivez tout mot pour mot, y compris les mots tels que "hum", "ah", et les répétitions de phrases.
   * Pour la plupart des contenus Web, il est acceptable de laisser le texte non subtantiel pour rendre les légendes plus compréhensibles &mdash; tout en respectant les conseils ci-dessus. Par exemple, <em>si le locuteur dit :</em><br> Cet ordinateur est entrain (toux, toux) désolé – euhhh qu'est-ce que je disais..?, ah oui – Cet ordinateur est entrain de m'agacer.<br>
<em>Vous pouvez sous-titrer :</em><br>
 Cet ordinateur est entrain de m'agacer.
   * Si du contenu parlé n'est pas pertinent, indiquez qu'il a été exclu des légendes. Par exemple :<br>
	<em>[les participants parlent de la météo pendant que le présentateur redémarre son ordinateur.]</em>

* Si vous ne comprenez pas ce qui est dit, transcrivez :<br>
[incompréhensible]

## Plus d'informations sur les légendes

Pour les légendes :

* Les légendes font une ou deux lignes. Généralement, il est préférable de n'avoir que 32 caractères par ligne.
* Mettez une nouvelle phrase sur une nouvelle ligne.
* Si vous devez diviser une phrase en plusieurs segments, divisez-la à une phrase logique.

Les sous-titres comprennent également le moment auquel chaque phrase va être prononcée. La plupart des gens utilisent des outils pour produire et affiner les légendes.

Retrouvez plus d'informations sur les légendes sur une autre page de cette ressource : [Légendes/Sous-titres](/media/av/captions/).

## Plus d'informations sur les transcriptions

Retrouvez plus d'informations sur les transcriptions sur une autre page de cette ressource : [Transcriptions](/media/av/transcripts/).
