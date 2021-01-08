---
title: "Making Audio and Video Media Accessible"
nav_title: "Audio & Video Media"

lang: en   # change "en" to lang code, here and 2 @@s below
last_updated: 2021-01-21  # Change to date of translation YYYY-MM-DD (month in middle)
# translator: "..."
# contributors: "..."

permalink: /media/av/   # Add lang to end /link/to/page/@@
ref: /media/av/   # Do not change
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'content/index.md'   # Add lang to the middle of the filename, e.g., index.@@.md

resource:
  title: "Making Audio and Video Media Accessible"
  ref: /media/av/
navigation:
  next: /media/av/users-orgs/
changelog: /media/av/changelog/
acknowledgements: /media/av/acknowledgements/

description: Covers captions/subtitles, audio description of visual information, media players, and other accessibility requirements.
image: /content-images/wai-media-guide/social.png
 
footer: >   # Translate words below, including "Date:" and "Editor:". (Do not update the date.)
   <p><strong>Date:</strong> Updated @@ January 2021. CHANGELOG.</p>
   <p><strong>Editor:</strong> <a href="http://www.w3.org/People/Shawn">Shawn Lawton Henry</a>. ACKNOWLEDGEMENTS lists contributors and credits.</p>
   <p>Developed by the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Originally drafted as part of the <a href="https://www.w3.org/WAI/WCAGTA/">WCAG TA Project</a> funded by the <abbr title="United States">U.S.</abbr> Access Board. Revised as part of the <a href="https://www.w3.org/WAI/expand-access/">WAI Expanding Access project</a> funded by the Ford Foundation.</p>

---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This resource explains how to make media accessible, whether you develop it yourself or outsource it. It helps you figure out which accessibility aspects your specific audio or video needs, provides project management guidance, and includes requirements from the Web Content Accessibility Guidelines (WCAG) standard.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

* {:.left} [{% include image.html src="body.svg" alt="" %} User Experiences and Benefits to Organizations](/media/av/users-orgs/):<br>Understand the needs of people with disabilities. Learn about benefits to organizations, and benefits to everyone in a variety of situations.

* {:.left} [{% include image.html src="planning.svg" alt="" %} Planning Audio and Video Media](/media/av/planning/):<br>Plan for accessibility from the very start of your project, to save time and money. For example, [integrated description](/media/av/av-content/#integrate-description) is easier and better for accessibility, and it needs to be included in the script before filming.

* {:.left} [{% include image.html src="av-content.svg" alt="" %} Audio Content and Video Content](/media/av/av-content/):<br>Make new the audio and video content accessible. Avoid accessibility barriers **when scripting, storyboarding, and recording content**.

* {:.left} [{% include image.html src="ad.svg" alt="" %} Audio Description of Visual Information](/media/av/description/):<br>Provide description so that people who are blind and others who cannot see the video adequately get the visual information needed to understand the content. This includes things like charts, graphs, and text such as speaker names, titles, and e-mail addresses.

* {:.left} [{% include image.html src="cc.svg" alt="" %} Captions/Subtitles](/media/av/captions/):<br>Provide captions (also called “subtitles”) so that people who are Deaf and hard-of-hearing get a text version of the speech and non-speech audio information needed to understand the content.

* {:.left} [{% include image.html src="transcript.svg" alt="" %} Transcripts](/media/av/transcripts/):<br>Provide a transcrip, that is, a text version of the speech and non-speech audio information. Ideally, make it a descriptive transcript that also includes text description of the visual information. Descriptive transcripts are required to provide video content to people who are both Deaf and blind. ([descriptive transcript excerpt example](/WAI/media/av/transcripts/#descriptive))

* {:.left} [{% include image.html src="sign.svg" alt="" %} Sign Languages](/media/av/sign-languages/):<br>Provide sign language when your audience needs it, so that Deaf people whose native language is sign get the content in their native language.

* {:.left} [{% include image.html src="player.svg" alt="" %} Media Players](/media/av/player/):<br>Use a media player that supports accessibility.
{:.nolist.withicons.mini}

<hr>

**Example:**

An example accessible video is on the [Colors with Good Contrast page.<br>
{% include image.html src="contrast-still.png" alt="" class="normal video" %}](https://www.w3.org/WAI/perspective-videos/contrast/)

That page provides:
* audio and video content with accessibility considerations, such as low background audio
* a version of the video with description of visual information integrated in the main audio, and description available as text
* captions
* a descriptive transcript
* a media player with accessibility support, including an interactive transcript
