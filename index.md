---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
title: "Making Audio and Video Media Accessible &mdash; Introduction"   # Do not translate "title:". Do translate the text after "title:".
nav_title: "Audio & Video Media" # A short title that is used in the navigation
doc-note-type: draft
lang: en   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2019-06-11   # Put the date of this translation YYYY-MM-DD (with month in the middle)
# translator: "@@"   # Replace @@ with name or names separated with a comma
# contributors: "@@"   # Replace @@ with name(s) or delete this line
permalink: /design-develop/media/   # Add the language shortcode to the end; for example /fundamentals/accessibility-intro/fr
ref: /design-develop/media/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'index.md'   # Add the language shortcode to the middle of the filename, for example index.fr.md
footer: >   # Translate all the words below, including "Date:" and "Editor:". 
navigation:
  next: /design-develop/media/planning/
---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This Web Accessibility Initiative (WAI) resource helps you make your media:
* accessible to people with disabilities
* meet international standards

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include toc.html type="start" title="Page Contents" %}
{:/}

- This will be replaced by an automatically generated TOC when using Markdown formatting.
{::options toc_levels="2" /}
{:toc}

{::nomarkdown}
{% include toc.html type="end" %}
{:/}

## Elements of Accessible Video and Audio Media

The following elements make media accessible to people who cannot hear, people who cannot see, and others. Some media needs all of these elements, and others need only a transcript.

* **Captions/Subtitles** &mdash; Captions (also called "intralingual subtitles") provide content to people who are Deaf and others who cannot hear the audio. Captions are a text version of the speech and non-speech audio information needed to understand the content. _Subtitles_ are the spoken audio translated into another language.
* **Transcripts** &mdash; Basic transcripts are a text version of the speech and non-speech audio information needed to understand the content. _Descriptive transcripts_ also include visual information needed to understand the content. Descriptive transcripts are required to provide content to people who are both Deaf and blind.
* **Audio Description** &mdash; Audio description provides content to people who are blind and others who cannot see the video adequately. It describes visual information needed to understand the content.
* **Sign Language** &mdash; Sign languages use hand and arm movements, facial expressions, and body positions to convey meaning. For most people who are Deaf, sign language is their native language, and some do not understand written language well.
* **Media player** &mdash; Media players have different levels of accessibility support. For example, some provide a separate audio track for description and some use the caption file to provide an _interactive transcript_.
* **Video and Audio Content** &mdash; There are also accessibility requirements for the video or audio content itself. For example, in videos, avoid flashing that can cause seizures.

## Making Media Accessible

This resource walks you through understanding accessible media, whether you are outsourcing it or creating it in-house.
* [Planning Media Accessibility](https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/planning/) &mdash; helps you **figure out what your specific video or audio needs,** and links to standards.
* [Video and Audio Content](https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/media-content/)
* [Audio Description of Visual Information](https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/description/)
* [Captions/Subtitles](https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/captions/)
* [Transcripts](https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/transcripts/)
* [Accessible Media Player](https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/player/)

## Example

An example accessible video is [Video Captions](https://www.w3.org/WAI/perspective-videos/captions/). That page provides:
* video and audio content with accessibility considerations, such as low background audio
* an audio described version of the video
* captions
* a descriptive transcript
* a media player with accessibility support, including an interactive transcript

## Additional Benefits

Accessible video and audio is **essential for people with disabilities**, and is **useful for everyone** in a variety of situations.

For example, transcripts can be:
* Skimmed or read rather than watched or listened to. This is significantly easier and quicker for many users. Sometimes people want to skim the transcript first before deciding whether or not to play the media.
* Used without needing to download video files. For example, to save data on mobile.
* Used offline, printed, or converted to Braille.
* Better indexed by search engines.

And captions can be:
* Used in loud environments where users cannot hear the audio. For example, a bar, an airport, and another.
* Used in quiet environments where users cannot turn on sound. For example, a library, when others are sleeping, and another.
* Used by people who cannot understand the spoken language well and can understand the written language better. For example, people who are not native speakers of the language.
* Used by people to help them learn to read. For example, children, adults, and people learning a new language.
* Used to better understand content since users can hear the information in audio and see it in text at the same time. For example, {some data like [this](https://www.3playmedia.com/2019/02/21/8-benefits-of-transcribing-captioning-videos/)}.

Some benefits of captions are illustrated in this 1-minute <a href="https://www.w3.org/WAI/perspective-videos/captions/">Video on  Captions <img src="{{ "/content-images/captions-video-still.jpg" | relative_url }}" alt="" style="float: right; margin-left: 2rem; clear:right; width: 30%; max-width: 220px"></a>.
