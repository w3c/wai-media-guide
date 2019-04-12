---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
title: "Managing Development of Media Alternatives"   # Do not translate "title:". Do translate the text after "title:".
nav_title: "Managing Development" # A short title that is used in the navigation
lang: en   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2019-04-10   # Put the date of this translation YYYY-MM-DD (with month in the middle)
# translator: "@@"   # Replace @@ with name or names separated with a comma
# contributors: "@@"   # Replace @@ with name(s) or delete this line
permalink: /design-develop/media-guide/managing/   # Add the language shortcode to the end; for example /fundamentals/accessibility-intro/fr
ref: /design-develop/media-guide/managing/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'index.md'   # Add the language shortcode to the middle of the filename, for example index.fr.md
footer: >   # Translate all the words below, including "Date:" and "Editor:". 
---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page helps you manage accessible media development. It includes guidance to help you decide what to develop in-house and what to outsource.

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

<p><em>For descriptions of captions, transcripts, audio description, sign language and other introductory information, see the <a href="#intro">Introduction</a>.</em></p>

{::nomarkdown}
{% include box.html type="start" title="From the Introduction:" class="" %}
{:/}

<p>A common approach to developing media alternatives is:</p>
<ol>
  <li>An audio described version is developed by the same people, at the same time as the main video.</li>
  <li>Captions are outsourced, including for the main video, for the audio described version, and of the audio description itself.</li>
  <li>Descriptive transcripts are developed in-house using the text from the caption files.</li>
</ol>
<p>Some organizations do it all in-house, and some outsource it all.</p>

{::nomarkdown}
{% include box.html type="end" %}
{:/}

## The Basics 
<p>What you need for most videos is:</p>
<ol>
  <li><strong>Text version of the audio</strong> (including speech and non-speech) information that users need to understand the content.
    <ul>
      <li>Text with time codes in a file format for closed captions. (This is also be used for interactive transcripts.)</li>
      <li>The same text can be used for the descriptive transcript.</li>
    </ul>
  </li>
  <li><strong>Description of the visual information</strong> that users need  to understand the content.
    <ul>
      <li>An audio version for audio description within the video. (@@ or file for screen readers)</li>
      <li>A  text version for media players that support it and for the descriptive transcript.</li>
    </ul>
  </li>
</ol>

<p><s>Whether  you develop captions, transcripts, and audio description in-house or  outsource them depends on several factors, including: ...</s></p>

<p>The sections below provide additional information to help you decide how to get your captions, transcripts, and audio description developed.</p>

## Captions Considerations

<p>Live captions are usually done by professional Communication Access Realtime Translation (CART) providers. The rest of this section addresses captions for pre-recorded media.</p>

<p>Creating captions requires typing up audio (&quot;transcribing&quot;) and formatting it in a file with timestamps. It is surprisingly difficult to transcribe an audio file, and takes quite a bit of time for people who don't have the software and skill for it. The file formast for captions are  simple, yet it's tedious to add timestamps, especially without software or service for developing caption files. Good captioning requires knowledge of which non-speech audio information should be included in the captions.</p>
<p>Even correcting an automatice caption files takes quite a bit of time for people who don't do it regularly.</p>
<p>However, for people who have the software, skills, and experience in developing captions, they are much easier and faster to develop.</p>
<p>For these reasons, many organizations choose to outsource their captions.</p>
<p>More information is in <a href="@@">Creating Captions</a>.</p>


## Audio Description Considerations
<p>When accessibility is considered before videos are produced, it significantly cuts down on cost and effort to develop audio description.</p>
<p>For some videos, description of the visual information can be seamlessly integrated into the main video <em>without <strong>any</strong> additional cost</em>. For example, instead of the speaker saying:</p>
<blockquote>As you can see on this chart, sales increased significantly from the first quarter to the second quarter.</blockquote>
The speaker can say:
<blockquote>This chart shows that sales increased from 1 million in the first quarter to 1.3 million in the second quarter.</blockquote>
<p><strong>If you have an existing video</strong> and you want to add audio description, you'll need:</p>
<ul>
  <li>... skills to write it, speak it, intergrate it in the video...</li>
</ul>
<p>More information is in <a href="@@">Creating Audio Description of Visual Information</a>.</p>

## Transcript Considerations
<p>Transcripts are easy to develop once you have captions for the main video and of the  audio description. In-house staff who know how to create basic web content can develop the descriptive transcript.</p>
<p>More information is in <a href="@@">Creating Transcripts</a>.</p>

## Media Player Considerations
<p>[A little here just to let managers know that a decision will have to be made which player to use and some developer teim &amp; skills needed to make it all work. How for developers  would be in a potential future Implementing Media Tutorial.]</p>

## Content Considerations
<p>Make sure accessibility is considered when storyboarding and producing your vidoes and audio.</p>
<p>More information is in <a href="@@">Creating Video and Audtion Content</a>.</p>


<p style="text-align:center"><strong>[ < Previous &nbsp;&nbsp;&nbsp; Next > ]</strong></p>
