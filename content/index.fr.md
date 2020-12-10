---
title: "Des contenus audios et vidéos accessibles"
nav_title: "Contenus audios et vidéos"

lang: fr   # change "en" to lang code, here and 2 @@s below
last_updated: 2020-10-20   # Change to date of translation YYYY-MM-DD (month in middle)
translator:
-name : Sofia Ahmed
# contributors: "..."

permalink: /media/av/fr   # Add lang to end /link/to/page/@@
ref: /media/av/   # Do not change
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'content/index.fr.md'   # Add lang to the middle of the filename, e.g., index.@@.md

resource:
  title: "Des contenus audios et vidéos accessibles"
  ref: /media/av/
navigation:
  next: /media/av/planning/
changelog: /media/av/changelog/
acknowledgements: /media/av/acknowledgements/

description: comprend les sous-titres, la description audio d'informations visuelles, les lecteurs multimédias, et d'autres critères d'accessibilité.
image: /content-images/wai-media-guide/social.png

footer: >   # Translate words below, including "Date:" and "Editor:". (Do not update the date.)
   <p><strong>Date :</strong> Mise à jour 18 novembre 2019. CHANGELOG.</p>
   <p><strong>Rédactrice :</strong> <a href="http://www.w3.org/People/Shawn">Shawn Lawton Henry</a>. RERMERCIEMENTS liste les contributeurs et les crédits.</p>
   <p>Développé par le Groupe de travail Éducation et formation (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Rédigé initialement dans le cadre du projet <a href="https://www.w3.org/WAI/WCAGTA/">WCAG TA</a> financé par le <abbr title="United States">U.S.</abbr> Access Board. Révisé dans le cadre du projet <a href="https://www.w3.org/WAI/expand-access/">WAI Expanding Acess</a> financé par la fondation Ford.</p>

---


{::nomarkdown}
{% include box.html type="start" title="Résumé" class="" %}
{:/}

Rendre accessible les contenus audios et vidéos est essentiel pour les personnes en situation de handicap, et avantageux pour les organisations. Selon votre contenu multimédia, vous pourriez devoir recourir à des **sous-titres** (une version textuelle de l'audio qui apparaît de manière synchronisée dans le lecteur multimédia), une **transcription** (une version textuelle de l'audio, disponible séparément), une **audiodescription des informations visuelles** (généralement une ressource audio supplémentaire qui décrit le contenu visuel important), **ou d'autres** fonctionnalités d'accessibilité.  

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

## Avant toute chose, comprendre les besoins utilisateur

Avant d'entrer dans les détails et les descriptions, il est utile de comprendre l'expérience utilisateur des personnes handicapées. Vous comprendrez ainsi la raison d'être des recommandations en matière d'accessibilité pour les contenus multimédias abordées dans cette ressource. Par exemple, une personne sourde ne peut pas entendre l'audio, vous devez donc fournir les informations audios importantes sous une autre forme.

* De nombreuses personnes **sourdes** sont capables de lire correctement. Elles accèdent aux informations à partir de **transcriptions** ou de **sous-titres**. Certaines personnes préfèrent la **langue des signes**.
* Certaines personnes **malentendantes** préfèrent écouter l'audio pour entendre une partie du contenu, et lisent les **sous-titres** pour combler ce qu'ils n'ont pas pu entendre correctement.
* Certaine personnes qui présentent des **difficultés à comprendre les informations auditives** utilisent aussi des **sous-titres**. De nombreuses personnes utilisent des **transcriptions** pour pouvoir lire à leur rythme.
* Certaines personnes **aveugles** ou malvoyantes peuvent à peine voir, ou ne pas voir du tout les vidéos. Elles utilisent **une audiodescription des informations visuelles** pour comprendre ce qu'il se passe visuellement.
* Certaines personnes **sourdes et aveugles** utilisent un lecteur d'écran et le braille pour lire les **transcriptions descriptives** qui comprennent les informations audiovisuelles sous forme de texte.
* Certaines personnes **ne peuvent pas se concentrer et comprendre l'information auditive ou visuelle** en présence d'animations. Pour la plupart des vidéos, elles ont également besoin de **transcriptions descriptives**.
* Certaines personnes ne peuvent pas utiliser leurs mains et **utilisent un logiciel de reconnaissance vocale** pour se servir de leur ordinateur, mais aussi du **lecteur multimédia**. Les personnes **aveugles** ont également besoin que le lecteur multimédia puisse fonctionner sans souris.
* Certaines personnes utilisent plusieurs fonctionnalités d'accessibilité simultanément. Par exemple, une personne pourrait avoir besoin de sous-titres, d'une description textuelle des informations visuelles, et d'une audiodescription.

_(Vous trouverez des informations supplémentaires sur les pages suivantes : [Comment les personnes handicapées utilisent le Web](/people-use-web/) et [Besoins des utilisateurs en matière d'accessibilité multimédia](https://www.w3.org/TR/media-accessibility-reqs/).)_

## Comment rendre les contenus audios et vidéos accessibles ?

[{% include image.html src="planning.svg" alt="Préparation des contenus audios et vidéos" class="mini right" %}](/media/av/planning/)

Cette ressource vous aide à comprendre comment rendre vos contenus multimédias accessibles, que vous en sous-traitiez la production ou non. Pour **comprendre de quelles fonctionnalités spécifiques d’accessibilité vos contenus audios et vidéos ont besoin **, pour un accompagnement dans la gestion de votre projet, et pour obtenir des informations concernant les standards des Règles pour l'accessibilité des contenus Web (WCAG), allez sur [Préparation de contenus audios et vidéos](/media/av/planning/).

[{% include image.html src="av-content.svg" alt="Contenus audios et vidéos" class="mini right" %}](/media/av/av-content/)

Lors de la création de votre **nouveau** contenu audio ou vidéo, différents obstacles à l'accessibilité doivent être évités, tels que les clignotements, qui risquent de provoquer des crises d'épilepsie, et le bruit de fond, qui nuit à la concentration. Ils sont expliqués dans [Des contenus audios et vidéos](/media/av/av-content/).

[{% include image.html src="player.svg" alt="Lecteurs multimédia" class="mini right" %}](/media/av/player/)

La plupart des lecteurs multimédias présents par défaut dans les navigateurs offrent des fonctionnalités limitées en termes d’accessibilité. Certains lecteurs tiers sont conçus spécifiquement pour l'accessibilité. Obtenez plus d'informations sur [Lecteurs multimédias](/media/av/player/).

Vous trouverez des recommandations spécifiques pour d'autres aspects de l'accessibilité de vos contenus multimédias sur les pages suivantes :

* {:.left} [{% include image.html src="ad.svg" alt="" %} Audiodescription des informations visuelles](/media/av/description/) &mdash; La description fournit du contenu aux personnes aveugles et aux personnes qui ne peuvent pas voir la vidéo correctement. Elle décrit les informations visuelles nécessaires à la compréhension du contenu.

* {:.left} [{% include image.html src="cc.svg" alt="" %} Sous-titres](/media/av/captions/) &mdash; Les sous-titres fournissent du contenu aux personnes sourdes et malentendantes. Les sous-titres sont des versions textuelles des informations audios verbales et non-verbales nécessaires à la compréhension du contenu. Ils sont synchronisés avec l'audio et apparaissent généralement dans un lecteur multimédia lorsque les utilisateurs les activent.

* {:.left} [{% include image.html src="transcript.svg" alt="" %} Transcriptions](/media/av/transcripts/) &mdash; Les transcriptions de base constituent une version textuelle des informations audios verbales et non-verbales nécessaires à la compréhension du contenu. Les <em>transcriptions descriptives</em> comprennent également la description textuelle des informations visuelles nécessaires à la compréhension du contenu. Les transcriptions descriptives sont nécessaires pour rendre accessible un contenu vidéo à des personnes à la fois sourdes et aveugles.

* {:.left} [{% include image.html src="sign.svg" alt="" %} Langues des signes](/media/av/sign-languages/) &mdash; Les langues des signes utilisent les mouvements des mains et des bras, des expressions faciales, et des positions du corps pour transmettre l'information. Pour de nombreuses personnes sourdes, la langue des signes est leur langue maternelle, et certains ne comprennent pas bien le langage écrit. (La langue des signes n'est pas obligatoire dans la plupart des réglementations.)
{:.nolist.withicons.mini}

## Exemple de vidéo

Un exemple de vidéo accessible est disponible sur la page [Des couleurs bien contrastées.<br>
{% include image.html src="contrast-still.png" alt="" class="Vidéo normale" %}](https://www.w3.org/WAI/perspective-videos/contrast/)

Cette page fournit :
* des contenus audios et vidéos qui répondent aux critères en matière d'accessibilité, tels qu'un faible arrière-plan sonore
* une version de la vidéo avec la description des informations visuelles intégrées à la vidéo principale, et la description disponible sous forme de texte
* des sous-titres
* une transcription descriptive
* un lecteur multimédia comprenant des fonctionnalités accessibles, dont une transcription interactive

## Avantages pour les organisations et les particuliers {#benefits}

Les organisations qui rendent leurs contenus audios et vidéos accessibles peuvent bénéficier d'avantages tels que :
* Une augmentation des visites et de l'utilisation de leur site Web par des personnes porteuses ou non de handicaps, par exemple, dans les [situations décrites ci-dessous](#situations).
* Une meilleure expérience utilisateur pour tous, et une meilleure satisfaction client.
* Un meilleur référencement par les moteurs de recherche.

Les avantages pour les organisations sont décrits dans ces autres ressources :
* Le cas d'affaire comprend les **données d'étude de cas** provenant de l'ajout des transcriptions, et plus d'informations sur comment l'accessibilité peut [augmenter vos parts de marché](https://www.w3.org/WAI/business-case/#increase-market-reach).
* Les avantages des transcriptions et des sous-titres à l'université sont décrits dans un [**témoignage d'utilisateur / histoire d'une étudiante malentendante suivant des cours en ligne](https://www.w3.org/WAI/people-use-web/user-stories/#onlinestudent).
* Certains avantages que présentent les sous-titres sont illustrés par une [**Vidéo** d'une minute sur les sous-titres.<br>
{% include image.html src="captions-video-still.jpg" alt="" class="normal video" %}](https://www.w3.org/WAI/perspective-videos/captions/)

### Utilisation par des personnes avec ou sans handicaps {#situations}

Rendre les contenus audios et vidéos accessibles est **essentiel pour les personnes handicapées**, et **utile à tous** dans diverses situations.

Par exemple, les transcriptions peuvent être :
* Parcourues ou lues plutôt que vues ou écoutées. Cette option est bien plus facile et rapide pour de nombreux utilisateurs. Il arrive que certaines personnes veuillent d'abord parcourir la transcription avant de décider si elles veulent ou non démarrer le contenu multimédia.
* Utilisées sans nécessiter le téléchargement les fichiers de la vidéo. Par exemple, pour économiser des données mobiles.
* Utilisées hors ligne, imprimées, ou converties en braille.

Les sous-titres peuvent, quant à eux, être utilisés :
* Dans des environnements bruyants où les utilisateurs ne peuvent pas entendre l'audio. Par exemple, dans un bar, un aéroport, ou un concert.
* Dans des environnements calmes où les utilisateurs ne peuvent pas mettre de son. Par exemple, dans une bibliothèque, les transports en commun, ou lorsque d'autres personnes dorment.
* Par les personnes qui ne comprennent pas bien la langue parlée et qui ont meilleure maîtrise de la langue écrite. Par exemple, des personnes dont la langue en question n'est pas leur langue maternelle.
* Par les personnes qui apprennent à lire, y compris les personnes qui apprennent une nouvelle langue.
* Pour mieux comprendre le contenu étant donné que les utilisateurs peuvent entendre à la fois l'information dans un format audio et la voir sous forme de texte. Par exemple, selon une [Étude de recherche sur les sous-titres et les transcriptions {% include_cached external.html %}](https://www.3playmedia.com/2019/02/21/8-benefits-of-transcribing-captioning-videos/) 71 % des étudiants _sans_ trouble de l'audition utilisent les sous-titres, principalement pour les aider à se concentrer et à retenir l'information.

Cette ressource vous aide à rendre votre contenu multimédia plus facile à utiliser dans toutes ces situations, par des personnes avec et sans handicaps. La page suivante vous permet de commencer à   **[Organiser du contenu audio et vidéo accessible](/media/av/planning/)**.
