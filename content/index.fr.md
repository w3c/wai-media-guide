---
title: "Rendre les médias audio et vidéo accessibles"
nav_title: "Médias audio & video"

lang: fr   # change "en" to lang code, here and 2 @@s below
last_updated: 2021-06-29  # Change to date of translation YYYY-MM-DD (month in middle)
translators:
- name: "Rémi Bétin"

permalink: /media/av/fr   # Add lang to end /link/to/page/@@
ref: /media/av/   # Do not change
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'content/index.fr.md'   # Add lang to the middle of the filename, e.g., index.@@.md

resource:
  title: "Rendre les médias audio et vidéo accessibles"
  ref: /media/av/
navigation:
  next: /media/av/users-orgs/
changelog: /media/av/changelog/
acknowledgements: /media/av/acknowledgements/

description: Traite des sous-titres, de l'audio-description de l'information visuelle, des lecteurs de média and d'autres exigences d'accessibilités.
image: /content-images/wai-media-guide/social.png

footer: >   # Translate words below, including "Date:" and "Editor:". (Do not update the date.)
   <p><strong>Date :</strong> Mis à jour le 11 janvier 2021. Première publication septembre 2019. CHANGELOG.</p>
   <p><strong>Rédactrice :</strong> <a href="http://www.w3.org/People/Shawn">Shawn Lawton Henry</a>. ACKNOWLEDGEMENTS liste les contributeurs et les crédits.</p>
   <p>Développé par le groupe de travail Éducation et promotion (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Rédigé initialement dans le cadre du projet <a href="https://www.w3.org/WAI/WCAGTA/">WCAG TA</a> financé par le <abbr title="United States">U.S.</abbr> Access Board. Révisé dans le cadre du projet <a href="https://www.w3.org/WAI/expand-access/">WAI Expanding Access</a> financé par la fondation Ford.</p>

---

Cette ressource explique comment rendre les médias accessibles, qu'ils soient produits en interne ou en sous-traitance. Elle aide à comprendre quels aspects de l'accessibilité sont nécessaires pour votre contenu audio ou vidéo spécifique, donne des conseils de gestion de projet et inclut des exigences des Règles pour l'accessibilité des contenus Web (WCAG).

Elle traite des sujets suivants :

* {:.left} [{% include image.html src="body.svg" alt="" %} Expériences utilisateurs et bénéfices pour les organisations](/media/av/users-orgs/) :<br>Comprenez les besoins des personnes en situation de handicap. Apprenez-en plus sur les bénéfices pour les organisations, et les avantages pour tous dans une multitude de situations.

* {:.left} [{% include image.html src="planning.svg" alt="" %} Planifier les médias audio et vidéo](/media/av/planning/) :<br>Planifiez la prise en compte de l'accessibilité dès le début de votre projet, pour gagner du temps et de l'argent. Par exemple, [une description intégrée](/media/av/av-content/#integrate-description) est plus simple et meilleure pour l'accessibilité et elle doit être incluse dans le script avant le tournage.

* {:.left} [{% include image.html src="av-content.svg" alt="" %} Contenu audio et contenu vidéo](/media/av/av-content/) :<br>Rendez vos nouveaux contenus audio et vidéo accessibles. Écartez les freins à l'accessibilité lors de la planification, de la rédaction du scénario, de la création des storyboards et de l'enregistrement de votre média.

* {:.left} [{% include image.html src="ad.svg" alt="" %} Audio-description de l'information visuelle](/media/av/description/) :<br>Fournissez une description pour que les personnes aveugles et d'autres qui ne peuvent pas voir correctement la vidéo aient accès à l'information visuelle nécessaire à la compréhension du contenu. Cela inclut les diagrammes, les graphiques et les textes comme les noms des intervenants, les titres et les adresses électroniques.

* {:.left} [{% include image.html src="cc.svg" alt="" %} Sous-titres](/media/av/captions/) :<br>Fournissez des sous-titres pour que les personnes sourdes ou malentendantes aient accès à une version texte de l'information audio parlée ou non-parlée nécessaire à la compréhension du contenu.

* {:.left} [{% include image.html src="transcript.svg" alt="" %} Transcriptions](/media/av/transcripts/) :<br>Fournissez une transcription, c'est-à-dire une version texte de l'information audio parlée ou non-parlée. Idéalement, réalisez une transcription descriptive qui décrit également l'information visuelle. Les transcriptions descriptives sont nécessaires pour fournir du contenu vidéo aux personnes sourdes et aveugles. ([descriptive transcript excerpt example](/WAI/media/av/transcripts/#descriptive))

* {:.left} [{% include image.html src="sign.svg" alt="" %} Langue des signes](/media/av/sign-languages/) :<br>Fournissez une version en langue des signes quand votre public en a besoin, pour que les personnes sourdes qui s'expriment nativement en langue des signes aient accès au contenu dans leur langue natale.

* {:.left} [{% include image.html src="player.svg" alt="" %} Lecteurs média](/media/av/player/) : <br>Utilisez un lecteur média compatible avec l'accessibilité.
{:.nolist.withicons.mini}

<br>

Un exemple de vidéo accessible est présent dans la page [Couleurs avec un bon contraste.<br>
{% include image.html src="contrast-still.png" alt="" class="normal video" %}](https://www.w3.org/WAI/perspective-videos/contrast/)

Cette page fournit :
* du contenu audio et vidéo prenant en compte l'accessibilité, comme un arrière-plan sonore de faible volume
* une version de la vidéo avec description de l'information visuelle intégrée dans le flux audio principal, et une description disponible sous forme de texte
* des sous-titres
* une transcription descriptive
* un lecteur média compatible avec l'accessibilité, incluant une transcription interactive.
