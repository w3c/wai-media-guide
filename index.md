---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
title: "Make Video & Audio Accessible"   # Do not translate "title:". Do translate the text after "title:".
nav_title: "Make Video & Audio Accessible" # A short title that is used in the navigation
lang: en   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2019-04-10   # Put the date of this translation YYYY-MM-DD (with month in the middle)
# translator: "@@"   # Replace @@ with name or names separated with a comma
# contributors: "@@"   # Replace @@ with name(s) or delete this line
permalink: /design-develop/media-guide/   # Add the language shortcode to the end; for example /fundamentals/accessibility-intro/fr
ref: /design-develop/media-guide/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'index.md'   # Add the language shortcode to the middle of the filename, for example index.fr.md
footer: >   # Translate all the words below, including "Date:" and "Editor:". 
---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This multi-page resource helps you make video and audio (such as podcasts) accessible.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include toc.html type="start" title="Page Contents" %}
{:/}

- This will be replaced by an automatically generated TOC when using Markdown formatting.
{:toc}

{::nomarkdown}
{% include toc.html type="end" %}
{:/}

<!--
<ul>
  <li><a href="@@">Elements of Accessible Video and Audio</a></li>
  <li><a href="@@">Accessibility Requirements</a></li>
  <li><a href="@@">Additional Benefits</a></li>
  <li><a href="@@">Automatic Captions are Not Sufficient </a></li>
</ul>
-->

## Elements of Accessible Video and Audio

<p>To make your video and audio accessible to people with disabilities, provide captions, transcripts,  audio description, and optionally sign language &mdash; based on the content.</p>
<dl>
  <dt>Captions</dt>
  <dd>
    <p>Captions provide content to people who are Deaf and others who cannot hear the audio. They are also used by people who process written information better than audio.</p>
    <p>Captions are a text version of the speech and non-speech audio information needed to understand the content. They are displayed within the media player and  are synchronized with the audio.</p>
    <p>Most are "closed captions" that can be hidden or shown by people watching the video. They can  be "open captions" that are always displayed and cannot be turned off.</p>
    <p><strong><em>Subtitles</em></strong> are the spoken audio translated into another language. They are implemented like captions. Subtitles can be only the spoken audio (for people who can hear the audio) or can be a translation of the caption content including non-speech audio information.</p>
    <p><em>[image: example static image from Perspectives Video on Captions showing captions.]</em></p>
  </dd>
  <dt>Transcripts</dt>
  <dd>
    <p>[Basic transcripts] are a text version of the speech and non-speech audio information needed to understand the content.</p>
    <p>Some media players can synch the transcript with the video, so that text phrases are highlighed as they are spoken. With these interactive transcripts, users can select text in the transcript and go to that point in the video.</p>
    <p><em>[image like <a href="https://w3c.github.io/wai-media-intro/img/xcr_perspectives-d998a967.png">https://w3c.github.io/wai-media-intro/img/xcr_perspectives-d998a967.png</a> ]</em> </p>
    <p><strong><em>[Descriptive transcripts]</em></strong> also include visual information needed to understand the content.</p>
    <p>[Descriptive transcripts] are required to provide content to people who are both Deaf and blind. They are also used by people who process text information better than audio and video.</p>
    <p><em>[optional image: person interacting with dynamic Braille display, nott looking at video in background]</em></p>
  </dd>
  <dt>Audio Description</dt>
  <dd>
    <p>Audio description provides content to people who are blind and others who cannot see the video adequately. <s>It is also used by people who process text better than visual information such as graphs.</s></p>
  </dd>
  <dd>
    <p>Audio description describes visual information needed to understand the content. It is usually narration added to the soundtrack. Alternatively, it can be provided as a text track that can be read by screen reader software.</p>
    <p>For some types of video (such as some training videos), audio description  can be seamlessly integrated into the  video as it is developed.</p>
    <p>Usually two video options are provided: a video without audio description, and a separate video with audio description.</p>
    <p><em>[optional image: blind person listening to video]</em></p>
  <dt>Sign Language</dt>
  <dd>
    <p>Sign languages use hand and arm movements, facial expressions, and body positions to convey meaning. For most people who are Deaf, sign language is their native language, and some do not read written language well. Note that there are different sign languages in different regions and countries; for example, American Sign Language (ASL), British Sign Language (BSL), and Auslan (Australian Sign Language) are all different.</p>
    <p>Sign language is not required to meet most minimum accessibility standards.</p>
    <p><em>[optional image: person signing]</em></p>
  </dd>
  <p><strong>Video and Audio Content:</strong> There are also accessibility requirements for the video or audio content itself. For example, in videos,  avoid flashing that can cause seizures.</p>
</dl>

## Accessibility Requirements
<p>Providing a descriptive transcript for  videos (or basic transcript for audio-only) meets a wide range of accesibility needs.</p>
<p>To meet Web Content Accessibility Guidelines (WCAG) Level AA, <em>most</em> videos need to include:</p>
<ul>
  <li>Captions (<a href="https://www.w3.org/WAI/WCAG21/Understanding/media-equiv-captions">WCAG Success Criteria 1.2.2</a>)</li>
  <li>Audio Description (<a href="https://www.w3.org/WAI/WCAG21/Understanding/media-equiv-audio-desc-only">WCAG Success Criteria 1.2.5</a>)</li>
</ul>
<p>Requirements are different based on the content and whether they are live or pre-recorded. To figure out what your video or audio needs, see <a href="#standards">Managing Accessible Media &amp; Standards</a>. &lt;-@@</p>

## Additional Benefits

<p>Accessible video and audio is essential for people with disabilities, and is <strong>useful for everyone</strong> in a variety of situations. For example, accessible video and audio content can be:</p>
<ul>
  <li>Used in loud environments where users cannot hear the audio.</li>
  <li>Used in quiet environments where users cannot turn on sound.</li>
  <li>Skimmed or read rather than watched or listened to, which is easier and quicker for many users.</li>
  <li>Used without needing to download video files; for example, to save data on mobile.</li>
  <li>Used by people who cannot understand the spoken language well and can understand the written language better.</li>
  <li>Better understood when users can  hear the information in audio and  see it in text at the same time. [reference]</li>
  <li>Better indexed by search engines.</li>
</ul>
<p>Some benefits of captions are illustrated in this 1-minute <a href="https://www.w3.org/WAI/perspective-videos/captions/">Video on  Captions</a>.<br>
  <em>[optional image: screen capture for visual interest]</em> </p>

## Automatic Captions are Not Sufficient

<p>Automatically-generated captions do not meet user needs or accessibility requirements, unless they are confirmed to be fully accurate.</p>
<p>There are tools that use speech recognition technology to turn a soundtrack into a timed caption file. For example, many videos uploaded to YouTube have automatic captions. [<a href="https://support.google.com/youtube/answer/3038280">YouTube info</a>] However, automatic captions are often inaccurate. Often the text does not match the spoken audio &mdash; and in ways that  change the meaning (or are embarrassing). For example, missing just one word such as &quot;not&quot; can make the captions contradict the actual audio content.
<p>[<em>optionally as an illustration for visual interest (with text as true text):</em><br>
  &quot;Spoken text: 
  Broil on high for 4 to 5 minutes. You should not preheat the oven.&quot;<br>
  &quot;Automatic caption: Broil on high for 45 minutes. You should know to preheat the oven.&quot;<br>
  <em>optional illustration/picture:  fire coming from oven, or totally burned food on a broiler pan ;-)</em>]
<p>Automatic captions can be used as a starting point for developing accurate captions and transcripts, as described in <a href="#captions">Creating Captions</a> and <a href="#transcripts">Creating Transcripts</a>.&lt;-@@</p>
