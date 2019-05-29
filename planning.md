---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
title: "Planning Accessible Audio and Video Media"   # Do not translate "title:". Do translate the text after "title:".
nav_title: "Planning" # A short title that is used in the navigation
lang: en   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2019-04-10   # Put the date of this translation YYYY-MM-DD (with month in the middle)
# translator: "@@"   # Replace @@ with name or names separated with a comma
# contributors: "@@"   # Replace @@ with name(s) or delete this line
permalink: /design-develop/media/planning/   # Add the language shortcode to the end; for example /fundamentals/accessibility-intro/fr
ref: /design-develop/media/planning   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'index.md'   # Add the language shortcode to the middle of the filename, for example index.fr.md
footer: >   # Translate all the words below, including "Date:" and "Editor:". 
---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page helps you plan accessible media. It:
* helps you figure out if your specific audio or video needs captions, audio description, a basic transcript, or a descriptive transcript
* shows the Web Content Accessibility Guidelines (<a href="https://www.w3.org/WAI/standards-guidelines/wcag/">WCAG</a>) standards for video and audio (&quot;media&quot;)

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

_For brief descriptions of captions, transcripts, audio description, and sign language, see the previous page: [Making Video and Audio Accessible - Introduction](https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/)._


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

## Planning Accessible Audio and Video

<img src="{{ "/content-images/in-or-out.png" | relative_url }}" alt="" style="float: right; margin-left: 2rem; clear:right; width: 30%; max-width: 220px">

Include specific accessibility requirements in your:
* Project requirements - internal and external
* Requests for Proposal (RFP) or Requests for Tender (RFT)
* Contracts

Here is one example of a workflow for developing an accessible video, with notes on who develops the material.

{::nomarkdown}
{% include box.html type="start" title="Example Video Workflow" class="" %}
{:/}

1. **[Video content](@@)** accessibility is addressed when the video is planned and produced.<br>_By:_ Script writers, videographers, producers, and others.
2. **[An audio described version](@@)** of the video is developed at the same time as the main video, if needed.<br>_By:_ The same people doing the main video also do the describe version.
3. **[Captions](@@)** are developed for the main video, for the audio described version, and of the audio description itself.<br>_By:_ Usually if the video is professionally produced, the producers provide captions. Sometimes when informal videos are developed in-house, captions are outsourced.
4. **[A descriptive transcript](@@)** is developed using the text from the caption files.<br>_By:_ Often transcripts are developed in-house from caption files.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

The sub-pages of this resource include considerations, skills, and tools needed for creating audio description, captions, and transcripts.

It is important to note that <a href="@@">Automatic Captions are Not Sufficient</a>.

### Standards

Standards for accessible audio and video are defined in the Web Content Accessibility Guidelines (WCAG). They are described in the Bringing Together the Aspects of Accessible Audio and Video page, [Standards section](@@).


<p style="text-align:center"><strong>[ < Previous &nbsp;&nbsp;&nbsp; Next > ]</strong></p>
