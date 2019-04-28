---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
title: "Bringing Together the Aspects of Accessible Audio and Video"   # Do not translate "title:". Do translate the text after "title:".
nav_title: "All Together Now" # A short title that is used in the navigation
lang: en   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2019-04-10   # Put the date of this translation YYYY-MM-DD (with month in the middle)
# translator: "@@"   # Replace @@ with name or names separated with a comma
# contributors: "@@"   # Replace @@ with name(s) or delete this line
permalink: /design-develop/media-guide/together/   # Add the language shortcode to the end; for example /fundamentals/accessibility-intro/fr
ref: /design-develop/media-guide/together/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'index.md'   # Add the language shortcode to the middle of the filename, for example index.fr.md
footer: >   # Translate all the words below, including "Date:" and "Editor:". 
---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

...

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

_...: [Making Video and Audio Accessible - Introduction](http://@@)._

<span style="background:yellow"><strong>This is an unpolished page with rough ideas of what might or might not go here. Some is also in other places to compare where it might fit better.</strong></span>

## Introduction

... An example page is [Video Captions] (https://www.w3.org/WAI/perspective-videos/captions/). It has:
* player...
* descriptive transcript...

## ... other sub-topics ...

## Informing Users When None Needed
<p>If your media does not need captions (because there is no substantive audio content) or does not need audio description (because there is no substantive visual content), it's good to let users know that. Otherwise, they might think that you accidentally forgot to provide it. For example:</p>

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

## Where to Put Transcripts

Transcripts can be:
* Included on the same web page with the media. ([example decriptive transcript at the bottom of same page with video](https://www.w3.org/WAI/perspective-videos/captions/#transcript))
* Provided on a separate web page. ([example podcast transcript on separate page](https://www.w3.org/WAI/highlights/200606wcag2interview.html))

Make sure it is easy for users to know that a transcript is available and to get to the transcript.

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

Although descriptive transcripts are not required at WCAG Level AA, they are:
* Needed for most videos to be accessible to people who are Deaf-blind
* Easy and inexpensive to develop using captions and audio description that you already have to meet Level AA

To learn more about WCAG standards for media, see [Understanding Guideline 1.2: Time-based Media  {% include_cached different.html %}](https://www.w3.org/WAI/WCAG21/Understanding/time-based-media).

... terminology...
* "time-based media" in WCAG = "audio and video" and "media"
* "[https://www.w3.org/TR/WCAG/#alt-time-based-mediadef alternative for time based media]" in WCAG" = "transcript" in this resource


<p style="text-align:center"><strong>[ < Previous ]</strong></p>
