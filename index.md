---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
title: "How to Make Video and Audio Accessible - Introduction"   # Do not translate "title:". Do translate the text after "title:".
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

This multi-page resource helps you make video and audio (such as podcasts) accessible to people with disabilities.

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

## Elements of Accessible Video and Audio

<p>To make your video and audio accessible to people with disabilities, provide captions, transcripts,  audio description, and optionally sign language &mdash; based on the content.</p>

### Captions
<p>Captions provide content to people who are Deaf and others who cannot hear the audio. They are also used by people who process written information better than audio.</p>
<p>Captions are a text version of the speech and non-speech audio information needed to understand the content. They are displayed within the media player and  are synchronized with the audio.</p>
<p>Most are "closed captions" that can be hidden or shown by people watching the video. They can  be "open captions" that are always displayed and cannot be turned off.</p>
<p><strong><em>Subtitles</em></strong> are the spoken audio translated into another language. They are implemented like captions. Subtitles can be only the spoken audio (for people who can hear the audio) or can be a translation of the caption content including non-speech audio information.</p>
<p style="text-align:center"><em>[image: example static image from Perspectives Video on Captions showing captions.]</em></p>

### Transcripts
<p>Basic transcripts are a text version of the speech and non-speech audio information needed to understand the content.</p>
<p><strong><em>Descriptive transcripts</em></strong> also include visual information needed to understand the content.</p>
<img src="{{ "/content-images/braille.jpg" | relative_url }}" alt="" style="float: right; margin-left: 2rem; clear:right; width: 30%; max-width: 220px">
<p>Descriptive transcripts are required to provide content to people who are both Deaf and blind. They are also used by people who process text information better than audio and video.</p>
<p>Interactive transcripts highlight text phrases as they are spoken. Users can select text in the transcript and go to that point in the video. (This is a feature of the media player. It uses the captions file.)</p>
<img src="{{ "/content-images/captions.png" | relative_url }}" alt="" style="float: right; margin-left: 2rem; clear:right; width: 30%; max-width: 220px">

### Audio Description
<p>Audio description provides content to people who are blind and others who cannot see the video adequately.</p>
<p>Audio description describes visual information needed to understand the content. It is usually narration added to the soundtrack.</p>
<p>For some types of video (such as some training videos), description of the visual information can be seamlessly integrated by the speakers as the video is planned and created, and you don't need separate audio description.</p>
<p style="text-align:center"><em>[optional image: blind person listening to video]</em></p>

### Sign Language
<p>Sign languages use hand and arm movements, facial expressions, and body positions to convey meaning. For most people who are Deaf, sign language is their native language, and some do not read written language well. Note that there are different sign languages in different regions and countries; for example, American Sign Language (ASL), British Sign Language (BSL), and Auslan (Australian Sign Language) are all different.</p>
<p>Sign language is not required to meet most minimum accessibility standards.</p>
<p style="text-align:center"><em>[optional image: person signing]</em></p>

### Video and Audio Content
<p>There are also accessibility requirements for the video or audio content itself. For example, in videos,  avoid flashing that can cause seizures.</p>

## Managing Media Accessibility & Standards

### Accessibility Requirements

<p>Providing a descriptive transcript for  videos (or basic transcript for audio-only) meets a wide range of accesibility needs.</p>
<p>To meet Web Content Accessibility Guidelines (WCAG) Level AA, <em>most</em> videos need to include:</p>
<ul>
  <li>Captions (<a href="https://www.w3.org/WAI/WCAG21/Understanding/captions-prerecorded">WCAG Success Criteria 1.2.2</a>)</li>
  <li>Audio Description (<a href="https://www.w3.org/WAI/WCAG21/Understanding/audio-description-prerecorded">WCAG Success Criteria 1.2.5</a>)</li>
</ul>
<p>Requirements are different based on the content and whether they are live or pre-recorded. To figure out what your video or audio needs, see <a href="@@">Managing Development of Media Alternatives and Meeting Standards</a></p>

### Develop In-House or Outsource

<p>One approach to developing media alternatives is:</p>
<ol>
  <li>An audio described version is developed by the same people, at the same time as the main video.</li>
  <li>Captions are outsourced, including for the main video, for the audio described version, and of the audio description itself. Often whoever produces the video also provides captions.</li>
  <li>Descriptive transcripts are developed in-house using the text from the caption files.</li>
</ol>
<p>Some organizations do it all in-house, and some outsource it all. For help figuring out how to get your media alternatives developed, see the section on <a href="@@">Managing Development of Media Alternatives</a>.</p>

### Automatic Captions are Not Sufficient

<p>Automatically-generated captions do not meet user needs or accessibility requirements, unless they are confirmed to be fully accurate.</p>
<p>There are tools that use speech recognition technology to turn a soundtrack into a timed caption file. For example, many videos uploaded to YouTube have automatic captions. [<a href="https://support.google.com/youtube/answer/3038280">YouTube info</a>] However, often the automatic caption text does not match the spoken audio &mdash; and in ways that change the meaning (or are embarrassing). For example, missing just one word such as &quot;not&quot; can make the captions contradict the actual audio content.</p>
<p style="text-align:center; text-size:85%">[<em>optionally as an illustration for visual interest (with text as true text):</em><br>
  &quot;Spoken text: 
  Broil on high for 4 to 5 minutes. You should not preheat the oven.&quot;<br>
  &quot;Automatic caption: Broil on high for 45 minutes. You should know to preheat the oven.&quot;<br>
  <em>optional illustration/picture:  fire coming from oven, or totally burned food on a broiler pan ;-)</em>]</p>
<p>Automatic captions can be used as a starting point for developing accurate captions and transcripts, as described in <a href="#captions">Creating Captions</a> and <a href="#transcripts">Creating Transcripts</a>.</p>

### Creating Media Alternatives

Other pages in this resource provide specific guidance on:
* [Creating Captions](@@)
* [Creating Transcripts](@@)
* [Creating Audio Description of Visual Information](@@)
* [Creating Video and Audio Content](@@)

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
<p>Some benefits of captions are illustrated in this 1-minute <a href="https://www.w3.org/WAI/perspective-videos/captions/">Video on  Captions</a>.</p>
<img src="{{ "/content-images/caption-video-still.png" | relative_url }}" alt="" style="float: right; margin-left: 2rem; clear:right; width: 30%; max-width: 220px">

<p style="text-align:center"><strong>[ Next > ]</strong></p>


