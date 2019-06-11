---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
title: "Planning Accessible Audio and Video Media"   # Do not translate "title:". Do translate the text after "title:".
nav_title: "Planning" # A short title that is used in the navigation
doc-note-type: draft
lang: en   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2019-04-10   # Put the date of this translation YYYY-MM-DD (with month in the middle)
# translator: "@@"   # Replace @@ with name or names separated with a comma
# contributors: "@@"   # Replace @@ with name(s) or delete this line
permalink: /design-develop/media/planning/   # Add the language shortcode to the end; for example /fundamentals/accessibility-intro/fr
ref: /design-develop/media/planning/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'index.md'   # Add the language shortcode to the middle of the filename, for example index.fr.md
footer: >   # Translate all the words below, including "Date:" and "Editor:". 
navigation:
  previous: /design-develop/media/
  next:     /design-develop/media/media-content/
---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page helps you plan accessible media. It:
* helps you **figure out what your specific audio or video needs** (captions, audio description, a basic transcript, or a descriptive transcript)
* helps you plan what to develop in-house and what to outsource
* shows the Web Content Accessibility Guidelines (<a href="https://www.w3.org/WAI/standards-guidelines/wcag/">WCAG</a>) standards for media accessibility media

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
  <li><strong>[_] <a href="https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/media-content/#audio-only-and-videos">Content</a> </strong>that ...</li>   
  <li><strong>[_] <a href="https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/transcripts/">Transcript</a> </strong>that provides the audio information as text to people who are Deaf or hard of hearing.</li>
  <li>[_] <em>Optionally,</em> <a href="https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/captions/">Captions</a> that provides text synchronized with the audio for people who are hard of hearing and want to listen the audio.</li>
</ul>
</div>

## What does my video need to be accessible?

<div id="tree-b" style="background:#D9EDF7; border: solid 1px #999; padding-left: 11px; padding-right: 5px;">
<p><strong>Is there speech or other audio</strong> that is needed to understand the content?</p>
    <ul>
      <li>If yes,
        <ul>
          <li><strong>[_] <a href="https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/media-content/#audio-only-and-videos">Audio content</a> </strong>that ...</li>  
          <li><strong>[_] <a href="https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/captions/">Captions</a> </strong>that provide the information as text synchronized with the audio for people who are Deaf or hard of hearing.</li>
          <li>[_] <em>Optionally,</em> <a href="https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/transcripts/">Transcript of audio information</a> that provides the text separate from the video.<br><em>(This transcript is the same text from the captions file, in a different format.)</em></li>
        </ul>
      </li>
      <li>If no, <a href="#none">inform users</a>.</li>
    </ul>

<p><strong>Is there visual information</strong> that is needed to understand the content?</p>
    <ul>
      <li>If yes,
        <ul>
          <li><strong>[_] <a href="https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/media-content/">Video content</a> </strong>that ...</li>  
          <li><strong>[_] <a href="https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/description/">Audio description of the visual information</a> </strong>that provides the information to people who are blind and want to listen to the video.</li>
          <li><strong>[_] <a href="https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/transcripts/">Descriptive transcript</a> </strong>that provides the audio and video information to people who are Deaf-blind.<br><em>(If you have a descriptive transcript, you do not need an additional transcript of only audio information from the previous question.)</em></li>
          <li>[_] <em>Optionally,</em> <a href="https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/sign-language/">Sign language(s)</a> that ...</li>  
        </ul>
      </li>
      <li>If no, <a href="#none">inform users</a>.</li>
    </ul>

<p><strong>[_] <a href="https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/player/">Media player</a> </strong>that ...</p>
</div>

### Informing Users When None Needed {#none}

<p>If your video does not need captions (because there is no substantive audio content) or does not need audio description (because there is no substantive visual content), it's good to let users know that. Otherwise, they might think that you accidentally forgot to provide it. For example:</p>

{::nomarkdown}
{% include box.html type="start" class="" %}
{:/}

Captions not needed: The only sound with this video is background music. There is no speaking.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include box.html type="start" class="" %}
{:/}

Audio description not needed: This video does not include audio description because the visuals only support what is spoken; the visuals do not provide additional information.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

## Both Captions and a Transcript

Ideally you provide captions and a separate transcript.

For audio-only, captions enable people who are hard of hearing to get the richness of listening to the audio and fill in what they don't hear well by reading the captions.

For videos, captions enable people who are Deaf or hard of hearing to see the visual content and read the captions at the same time. 

Separate transcripts are required to provide access to people who are Deaf-blind and use braille. (Also, some people without disabilities prefer to skim or read transcripts at their own pace, rather than listening to audio or watching video.)

## Planning Accessible Audio and Video

<img src="{{ "/content-images/in-or-out.png" | relative_url }}" alt="" style="float: right; margin-left: 2rem; clear:right; width: 30%; max-width: 220px">

Include specific accessibility requirements in your:
* Project requirements - internal and external
* Requests for Proposal (RFP) or Requests for Tender (RFT)
* Contracts

Here is an example workflow for developing an accessible video, with notes on who develops the material:

{::nomarkdown}
{% include box.html type="start" title="Workflow and Responsibilities" class="" %}
{:/}

1. Address accessibility in **[video content](https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/media-content/)** as the video is planned and produced.<br>_By:_ Script writers, videographers, producers, and others.

2. Develop an **[audio described version](https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/description/)** of the video at the same time as the main video, if needed.<br>_By:_ The same people doing the main video also do the describe version.

3. Develop **[captions](https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/captions/)** for the main video, for the audio described version, and of the audio description itself.<br>_By:_ Usually if the video is professionally produced, the producers provide captions. Sometimes when informal videos are developed in-house, captions are outsourced.

4. Develop a **[descriptive transcript](https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/transcripts/)** using the text from the caption files.<br>_By:_ Often transcripts are developed in-house from caption files.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

To help you plan in-house and outsourced work, the sub-pages of this resource include **considerations, skills, and tools needed** for creating accessible media:
* [Audio Description Considerations](https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/description/#audio-description-considerations)
* [Captions, Skills and Tools](https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/captions/#skills-and-tools) and <a href="https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/captions/#automatic-captions-are-not-sufficient">Automatic Captions are Not Sufficient</a>
* [Transcripts, Skills and Tools](https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/transcripts/#skills-and-tools)

When planning for accessible media, it maybe helpful to communicate the **[additional benefits](https://deploy-preview-7--wai-media-guide.netlify.com/design-develop/media/#additional-benefits) to all users** and to your organization, such as search engine optimization (SEO).

## Standards

Web Content Accessibility Guidelines (WCAG) is introduced in the [WCAG Overview](https://www.w3.org/WAI/standards-guidelines/wcag/).

WCAG includes requirements for video and audio (&quot;media&quot;), at [Level](https://www.w3.org/WAI/WCAG21/Understanding/conformance.html#uc-levels-head) A, AA, and AAA. Most media is required by governing policies to meet Level AA &mdash; which includes both A and AA listed in the tables below.

Accessibility requirements for video and audio are different based on if they are:
* pre-recorded or live
* video with audio, video without audio (video only), or audio only

### Pre-Recorded

<table>
<tr>
<th scope="col">&nbsp;</th>
<th scope="col">Transcript <span class="normal-weight">(including auditory and visual content)</span></th>
<th scope="col">Captions</th>
<th scope="col">Audio Description <span class="normal-weight">(if visual content not in audio)</span></th>
<th scope="col">Sign Language</th>
</tr>
<tr>
<th scope="row">Video with Audio</th>
<td><a href="https://www.w3.org/TR/UNDERSTANDING-WCAG20/media-equiv-text-doc">AAA 1.2.8</a></td>
<td><strong><a href="https://www.w3.org/WAI/WCAG21/Understanding/captions-prerecorded">A 1.2.2</a></strong></td>
<td><strong><a href="https://www.w3.org/WAI/WCAG21/Understanding/audio-description-or-media-alternative-prerecorded">A 1.2.3</a></strong>&nbsp;(audio description <em><strong>or</strong></em> transcript)<br>
<strong><a href="https://www.w3.org/WAI/WCAG21/Understanding/audio-description-prerecorded">AA 1.2.5</a></strong><br>
<a href="https://www.w3.org/WAI/WCAG21/Understanding/extended-audio-description-prerecorded">AAA 1.2.7</a></td>
<td><a href="https://www.w3.org/WAI/WCAG21/Understanding/sign-language-prerecorded">AAA 1.2.6</a></td>
</tr>
<tr>
<th scope="row">Audio only</th>
<td><strong><a href="https://www.w3.org/WAI/WCAG21/Understanding/audio-only-and-video-only-prerecorded">A 1.2.1</a></strong><br>
<a href="https://www.w3.org/WAI/WCAG21/Understanding/media-alternative-prerecorded">AAA 1.2.8</a></td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td><a href="https://www.w3.org/WAI/WCAG21/Understanding/sign-language-prerecorded">AAA 1.2.6</a></td>
</tr>
<tr>
<th scope="row">Video only</th>
<td><strong><a href="https://www.w3.org/WAI/WCAG21/Understanding/audio-only-and-video-only-prerecorded">A 1.2.1</a></strong> (transcript <em><strong>or</strong></em> audio description)<br>
<a href="https://www.w3.org/WAI/WCAG21/Understanding/media-alternative-prerecorded">AAA 1.2.8</a></td>
<td>&nbsp;</td>
<td><strong><a href="https://www.w3.org/WAI/WCAG21/Understanding/audio-description-or-media-alternative-prerecorded">A 1.2.3</a></strong>&nbsp;(audio description <em><strong>or</strong></em> transcript)<br>
<strong><a href="https://www.w3.org/WAI/WCAG21/Understanding/audio-description-prerecorded">AA 1.2.5</a></strong></td>
<td>&nbsp;</td>
</tr>
</table>

### Live

<table>
<tr>
<th scope="col">&nbsp;</th>
<th scope="col">Transcript</th>
<th scope="col">Captions</th>
<th scope="col">Audio Description</th>
<th scope="col">Sign Language</th>
</tr>
<tr>
<th scope="row">Video with Audio</th>
<td>&nbsp;</td>
<td><strong><a href="https://www.w3.org/WAI/WCAG21/Understanding/captions-live">AA 1.2.4</a></strong></td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<th scope="row">Audio only</th>
<td><a href="https://www.w3.org/WAI/WCAG21/Understanding/audio-only-live">AAA 1.2.9</a></td>
<td><strong><a href="https://www.w3.org/WAI/WCAG21/Understanding/captions-live">AA 1.2.4</a></strong></td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<th scope="row">Video only</th>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
</table>

### More

...Providing a descriptive transcript for videos (or basic transcript for audio-only) meets a wide range of accesibility needs.]...<br>
@@
<p>Descriptive transcripts are not required to meet WCAG Level AA. However, they:</p>
<ul>
  <li>meet a wide range of accessibility needs, and are needed in order for videos to be accessible to people who are &quot;Deaf-blind&quot;</li>
  <li>provide <a href="@@#benefits">additional benefits</a> for users <em>without</em> disabilities, and for your organization (for example, <abbr title="search engine optimization"> SEO</abbr>)</li>
  <li><strong>are easy and inexpensive to develop</strong> using captions and audio description that you already have to meet Level AA</li>
</ul>
@@
Although descriptive transcripts are not required at WCAG Level AA, they are:
* Needed for most videos to be accessible to people who are Deaf-blind
* Easy and inexpensive to develop using captions and audio description that you already have to meet Level AA

To learn more about WCAG standards for media, see [Understanding Guideline 1.2: Time-based Media  {% include_cached different.html %}](https://www.w3.org/WAI/WCAG21/Understanding/time-based-media).

... terminology...
* "time-based media" in WCAG = "audio and video" and "media"
* "[https://www.w3.org/TR/WCAG/#alt-time-based-mediadef alternative for time based media]" in WCAG" = "transcript" in this resource




