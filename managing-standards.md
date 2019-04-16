---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
title: "Managing Development of Media Alternatives and Meeting Standards"   # Do not translate "title:". Do translate the text after "title:".
nav_title: "Managing Media & Standards" # A short title that is used in the navigation
lang: en   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2019-04-10   # Put the date of this translation YYYY-MM-DD (with month in the middle)
# translator: "@@"   # Replace @@ with name or names separated with a comma
# contributors: "@@"   # Replace @@ with name(s) or delete this line
permalink: /design-develop/media-guide/managing-standards/   # Add the language shortcode to the end; for example /fundamentals/accessibility-intro/fr
ref: /design-develop/media-guide/managing-standards/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'index.md'   # Add the language shortcode to the middle of the filename, for example index.fr.md
footer: >   # Translate all the words below, including "Date:" and "Editor:". 
---



{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page helps you manage accessible media development. It:
* shows the Web Content Accessibility Guidelines (<a href="https://www.w3.org/WAI/standards-guidelines/wcag/">WCAG</a>) standards for video and audio (&quot;media&quot;)
* helps you figure out if your specific video or audio needs captions, audio description, a basic transcript, or a descriptive transcript
* includes guidance to help you decide what to develop in-house and what to outsource

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

_For descriptions of captions, transcripts, audio description, sign language and other introductory information, please see the previous page: [Making Video and Audio Accessible - Introduction](http://@@)._

## WCAG Media Standards

{::nomarkdown}
{% include box.html type="start" title="From the Introduction:" class="" %}
{:/}

Providing a descriptive transcript for videos (or basic transcript for audio-only) meets a wide range of accessibility needs.

To meet Web Content Accessibility Guidelines (WCAG) Level AA, <em>most</em> videos need to include:
* Captions ([WCAG Success Criteria 1.2.2](https://www.w3.org/WAI/WCAG21/Understanding/captions-prerecorded))
* Audio Description ([WCAG Success Criteria 1.2.5](https://www.w3.org/WAI/WCAG21/Understanding/audio-description-prerecorded))

Requirements are different based on the content and whether they are live or pre-recorded.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

### WCAG

Web Content Accessibility Guidelines (WCAG) is introduced in the [WCAG Overview](https://www.w3.org/WAI/standards-guidelines/wcag/).

WCAG includes requirements for video and audio (&quot;media&quot;), at [Level](https://www.w3.org/WAI/WCAG21/Understanding/conformance.html#uc-levels-head) A, AA, and AAA. Most media is required by governing policies to meet Level AA &mdash; which includes both A and AA listed in the tables below.

Accessibility requirements for video and audio are different based on if they are:
* pre-recorded or live
* video with audio, video without audio (video only), or audio only

#### Pre-Recorded

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
<td><strong><a href="https://www.w3.org/WAI/WCAG21/Understanding/captions-prerecorded">A 1.2.2</a></strong></td>
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

#### Live

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

### Learn More About Standards

To learn more about WCAG standards for media, see [Understanding Guideline 1.2: Time-based Media  {% include_cached different.html %}](https://www.w3.org/WAI/WCAG21/Understanding/time-based-media).

## What Does My Video/Audio Need?

<p>This section describes the optimum for pre-recorded media to meet users' needs.</p>

### Providing a Descriptive Transcript for Your Videos
<p>Descriptive transcripts are not required to meet WCAG Level AA. However, they:</p>
<ul>
  <li>meet a wide range of accessibility needs, and are needed in order for videos to be accessible to people who are &quot;Deaf-blind&quot;</li>
  <li>provide <a href="@@#benefits">additional benefits</a> for users <em>without</em> disabilities, and for your organization (for example, <abbr title="search engine optimization"> SEO</abbr>)</li>
  <li><strong>are easy and inexpensive to develop</strong> using captions and audio description that you already have to meet Level AA</li>
</ul>

### Deciding How to Meet User Needs
<p>The wording below helps you think about what users need in order to understand the information that you are presenting in the video or audio, including users who cannot hear it or see it. We've included &quot;who are Deaf&quot; and &quot;who are blind&quot; to help you understand what to provide. However, keep in mind that many people who <em>can</em> see and hear will also benefit from these, as described in <a href="@@#@@">Additional Benefits</a>.</p>

#### What does my video need to be accessible?
<ul>
  <li><strong>Is there speech or other audio</strong> that is needed to understand the content?
    <ul>
      <li> If yes,
        <ul>
          <li><strong>[_] Captions</strong> that provide the information to people who are Deaf or hard of hearing and want to watch the video. (<a href="https://www.w3.org/WAI/WCAG21/Understanding/captions-prerecorded">A 1.2.2</a>)</li>
          <li><strong>[_] Transcript of audio information </strong> that provides the information to people who don't want to watch the video. (<a href="https://www.w3.org/TR/UNDERSTANDING-WCAG20/media-equiv-text-doc">AAA 1.2.8</a>)<br><em>(This transcript is the same text from the captions file, in a different format.)</em></li>
        </ul>
      </li>
      <li>If no, inform users.</li>
    </ul>
  </li>
  <li><strong>Is there visual information</strong> that is needed to understand the content?
    <ul>
      <li>If yes,
        <ul>
          <li><strong>[_] Audio description</strong> that provides the information to people who are blind and want to listen to the video. (<a href="https://www.w3.org/WAI/WCAG21/Understanding/audio-description-prerecorded">AA 1.2.5</a>)</li>
          <li><strong>[_] Descriptive transcript</strong> that provides the information to people who are blind and Deaf (&quot;Deaf-blind&quot;). (<a href="https://www.w3.org/TR/UNDERSTANDING-WCAG20/media-equiv-text-doc">AAA 1.2.8</a>)<br><em>(If you have a descriptive transcript, you do not need an additional transcript of only audio information from the previous question.)</em></li>
        </ul>
      </li>
      <li>If no, inform users.</li>
    </ul>
  </li>
</ul>

#### What does my audio-only (e.g., podcast) need to be accessible?
<ul>
  <li><strong>[_] Captions</strong> that provide the information to people who are hard of hearing and want to listen the audio. (<a href="https://www.w3.org/WAI/WCAG21/Understanding/captions-prerecorded">A 1.2.2</a>)</li>
  <li><strong>[_] Transcript of audio information </strong> that provides the information to people who don't want to listen to the audio or want an interactive transcript. (<a href="https://www.w3.org/TR/UNDERSTANDING-WCAG20/media-equiv-text-doc">AAA 1.2.8</a>)<br><em>(This transcript is the same text from the captions file, in a different format.)</em></li>
</ul>

### Informing Users When None Needed
<p> If your media does not need captions (because there is no substantive audio content) or does not need audio description (because there is no substantive visual content), it's good to let users know that. Otherwise, they might think that you accidentally forgot to provide it. For example:</p>
<ul>
  <li>Captions not needed: The only sound with this video is background music. There is no speaking.</li>
  <li>Audio description not needed: This video does not include audio description because the visuals only support what is spoken; the visuals do not provide additional information.</li>
</ul>

##  Managing Development of Media Alternatives
This section provides guidance to help you decide what to develop in-house and what to outsource.

{::nomarkdown}
{% include box.html type="start" title="From the Introduction:" class="" %}
{:/}

<p>One approach to developing media alternatives is:</p>
<ol>
  <li>An audio described version is developed by the same people, at the same time as the main video.</li>
  <li>Captions are outsourced, including for the main video, for the audio described version, and of the audio description itself. Often whoever produces the video also provides captions.</li>
  <li>Descriptive transcripts are developed in-house using the text from the caption files.</li>
</ol>
<p>Some organizations do it all in-house, and some outsource it all.</p>

{::nomarkdown}
{% include box.html type="end" %}
{:/}

### The Basics 
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

### Captions Considerations

<p>Live captions are usually done by professional Communication Access Realtime Translation (CART) providers. The rest of this section addresses captions for pre-recorded media.</p>

<p>Creating captions requires typing up audio (&quot;transcribing&quot;) and formatting it in a file with timestamps. It is surprisingly difficult to transcribe an audio file, and takes quite a bit of time for people who don't have the software and skill for it. The file formast for captions are  simple, yet it's tedious to add timestamps, especially without software or service for developing caption files. Good captioning requires knowledge of which non-speech audio information should be included in the captions.</p>
<p>Even correcting an automatice caption files takes quite a bit of time for people who don't do it regularly.</p>
<p>However, for people who have the software, skills, and experience in developing captions, they are much easier and faster to develop.</p>
<p>For these reasons, many organizations choose to outsource their captions.</p>
<p>More information is in <a href="@@">Creating Captions</a>.</p>


### Audio Description Considerations
<p>When accessibility is considered before videos are produced, it significantly cuts down on cost and effort to develop audio description.</p>
<p>For some videos, description of the visual information can be seamlessly integrated into the main video <em>without <strong>any</strong> additional cost</em>. For example, instead of the speaker saying:</p>
<blockquote>As you can see on this chart, sales increased significantly from the first quarter to the second quarter.</blockquote>
The speaker can say:
<blockquote>This chart shows that sales increased from 1 million in the first quarter to 1.3 million in the second quarter.</blockquote>
<p><strong>If you have an existing video</strong> and you want to add audio description, you'll need:</p>
<ul>
  <li>... skills to write it, speak it, integrate it in new audio and video files...</li>
</ul>
<p>More information is in <a href="@@">Creating Audio Description of Visual Information</a>.</p>

### Transcript Considerations
<p>Transcripts are easy to develop once you have captions for the main video and of the  audio description. In-house staff who know how to create basic web content can develop the descriptive transcript.</p>
<p>More information is in <a href="@@">Creating Transcripts</a>.</p>

### Media Player Considerations
<p>[A little here just to let managers know that a decision will have to be made which player to use and some developer teim &amp; skills needed to make it all work. How for developers  would be in a potential future Implementing Media Tutorial.]</p>

### Content Considerations
<p>Make sure accessibility is considered when storyboarding and producing your vidoes and audio.</p>
<p>More information is in <a href="@@">Creating Video and Audtion Content</a>.</p>

<p style="text-align:center"><strong>[ < Previous &nbsp;&nbsp;&nbsp; Next > ]</strong></p>
