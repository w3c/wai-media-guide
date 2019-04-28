---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
title: "How to Make Audio and Video Accessible - Introduction"   # Do not translate "title:". Do translate the text after "title:".
nav_title: "Make Audio & Video Accessible" # A short title that is used in the navigation
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

This multi-page resource helps you make audio and video accessible to people with disabilities.

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

## Introduction

...

... below is general, could be exceptions...

## What does my audio-only (e.g., podcast) need to be accessible?

<div id="tree-a" style="background:#D9EDF7; border: solid 1px #999; padding-left: 11px; padding-right: 5px;">
<ul>
  <li><strong>[_] <a href="@@">Content</a> </strong>that ...</li>   
  <li><strong>[_] <a href="@@">Transcript</a> </strong>that provides the audio information as text to people who are Deaf or hard of hearing.</li>
  <li>[_] <em>Optionally,</em> <a href="@@">Captions</a> that provides text synchronized with the audio for people who are hard of hearing and want to listen the audio.</li>
</ul>
</div>

## What does my video need to be accessible?

<div id="tree-b" style="background:#D9EDF7; border: solid 1px #999; padding-left: 11px; padding-right: 5px;">
<ul>
  <li><strong>Is there speech or other audio</strong> that is needed to understand the content?
    <ul>
      <li>If yes,
        <ul>
          <li><strong>[_] <a href="@@">Audio content</a> </strong>that ...</li>  
          <li><strong>[_] <a href="@@">Captions</a> </strong>that provide the information as text synchronized with the audio for people who are Deaf or hard of hearing.</li>
          <li>[_] <em>Optionally,</em> <a href="@@">Transcript of audio information</a> that provides the text separate from the video.<br><em>(This transcript is the same text from the captions file, in a different format.)</em></li>
        </ul>
      </li>
      <li>If no, <a href="@@">inform users</a>.</li>
    </ul>
  </li>
  <li><strong>Is there visual information</strong> that is needed to understand the content?
    <ul>
      <li>If yes,
        <ul>
          <li><strong>[_] <a href="@@">Video content</a> </strong>that ...</li>  
          <li><strong>[_] <a href="@@">Audio description of the visual information</a> </strong>that provides the information to people who are blind and want to listen to the video.</li>
          <li><strong>[_] <a href="@@">Descriptive transcript</a> </strong>that provides the audio and video information to people who are Deaf-blind.<br><em>(If you have a descriptive transcript, you do not need an additional transcript of only audio information from the previous question.)</em></li>
          <li>[_] <em>Optionally,</em> <a href="@@">Sign language(s)</a> that ...</li>  
        </ul>
      </li>
      <li>If no, <a href="@@">inform users</a>.</li>
    </ul>
  </li>
   <li><strong>[_] <a href="@@">Media player</a> </strong>that ...</li>
</ul>
</div>

## Managing Development of Media Alternatives

Here is one example of a workflow for developing an accessible video, with notes on using in-house and outsourced resources.

<img src="{{ "/content-images/in-or-out.png" | relative_url }}" alt="" style="float: right; margin-left: 2rem; clear:right; width: 30%; max-width: 220px">

{::nomarkdown}
{% include box.html type="start" title="Example Video Workflow" class="" %}
{:/}

1. **[Video content](@@)** accessibility is addressed when the video is planned and produced.<br>_By:_ Script writers, videographers, producers, and others.
2. **[An audio described version](@@)** of the video is developed at the same time as the main video, if needed.<br>_By:_ The same people doing the main video also do the describe version.
3. **[Captions](@@)** are developed for the main video, for the audio described version, and of the audio description itself.<br>_By:_ Often whoever produces the video also provides captions.
4. **[A descriptive transcript](@@)** is developed using the text from the caption files.<br>_By:_ Often transcripts are developed in-house from caption files.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

The sub-pages of this resource include considerations, skills, and tools needed for creating captions, audio description, and transcripts.

It is important to note that <a href="@@">Automatic Captions are Not Sufficient</a>.

## Additional Benefits

<p>Accessible video and audio is essential for people with disabilities, and is <strong>useful for everyone</strong> in a variety of situations. For example, accessible video and audio content can be:</p>
<ul>
  <li>Used in loud environments where users cannot hear the audio. For example, a bar, an airport, and another. [captions]</li>
  <li>Used in quiet environments where users cannot turn on sound. For example, a library, when others are sleeping, and another. [captions]</li>
  <li>Skimmed or read rather than watched or listened to. This is significantly easier and quicker for many users. Some want to skim the trasncript first before deciding whether or not to play the media. [transcripts]</li>
  <li>Used without needing to download video files. For example, to save data on mobile. [transcripts]</li>
  <li>Used by people who cannot understand the spoken language well and can understand the written language better. For example, people who are not native speakers of the language. [captions]</li>
  <li>Used by people to help them learn to read. For example, children, adults, and people learning a new language. [captions]</li>
  <li>Used offline, printed, or converted to Braille. [transcripts]</li>
  <li>Better understood when users can hear the information in audio and see it in text at the same time. For example, {some data like <a href="https://www.3playmedia.com/2019/02/21/8-benefits-of-transcribing-captioning-videos/">this</a>}. [captions]</li>
  <li>Better indexed by search engines. [captions and transcripts]</li>
</ul>
<p>Some benefits of captions are illustrated in this 1-minute <a href="https://www.w3.org/WAI/perspective-videos/captions/">Video on  Captions <img src="{{ "/content-images/captions-video-still.jpg" | relative_url }}" alt="" style="float: right; margin-left: 2rem; clear:right; width: 30%; max-width: 220px">
</a>.</p>

## Standards

?? here or not ??

<p style="text-align:center"><strong>[ Next > ]</strong></p>
