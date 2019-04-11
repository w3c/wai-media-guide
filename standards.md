---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
title: "WCAG Media Standards"   # Do not translate "title:". Do translate the text after "title:".
nav_title: "Standards" # A short title that is used in the navigation
lang: en   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2019-04-10   # Put the date of this translation YYYY-MM-DD (with month in the middle)
# translator: "@@"   # Replace @@ with name or names separated with a comma
# contributors: "@@"   # Replace @@ with name(s) or delete this line
permalink: /design-develop/media-guide/standards/   # Add the language shortcode to the end; for example /fundamentals/accessibility-intro/fr
ref: /design-develop/media-guide/standards/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'index.md'   # Add the language shortcode to the middle of the filename, for example index.fr.md
footer: >   # Translate all the words below, including "Date:" and "Editor:". 
---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This pages shows the Web Content Accessibility Guidelines (<a href="https://www.w3.org/WAI/standards-guidelines/wcag/">WCAG</a>) standards for video and audio (&quot;media&quot;).

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

<p><em>For descriptions of captions, transcripts, audio description, sign language and other introductory information, please see the previous page: <a href="#intro">Making Video and Audio Accessible - Introduction</a>.</em></p>

{::nomarkdown}
{% include box.html type="start" title="From the Introduction:" class="" %}
{:/}

<p>Providing a descriptive transcript for videos (or basic transcript for audio-only) meets a wide range of accesibility needs.</p>
<p>To meet Web Content Accessibility Guidelines (WCAG) Level AA, <em>most</em> videos need to include:</p>
<ul>
  <li>Captions (<a href="https://www.w3.org/WAI/WCAG21/Understanding/captions-prerecorded">WCAG Success Criteria 1.2.2</a>)</li>
  <li>Audio Description (<a href="https://www.w3.org/WAI/WCAG21/Understanding/audio-description-prerecorded">WCAG Success Criteria 1.2.5</a>)</li>
</ul>
<p>Requirements are different based on the content and whether they are live or pre-recorded.</p>

{::nomarkdown}
{% include box.html type="end" %}
{:/}

<p>Web Content Accessibility Guidelines (<a href="https://www.w3.org/WAI/standards-guidelines/wcag/">WCAG</a>) includes requirements for video and audio (&quot;media&quot;), at <a href="https://www.w3.org/WAI/WCAG21/Understanding/conformance.html#uc-levels-head">Level</a> A, AA, and AAA. Most media is required by governing policies to meet Level AA &mdash; which includes both A and AA listed in the tables below.</p>
<p>Accessibility requirements for video and audio are different based on if they are:</p>
<ul>
  <li> pre-recorded or live</li>
  <li> video with audio, video without audio, or audio only</li>
</ul>

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
<strong><a href="https://www.w3.org/WAI/WCAG21/Understanding/audio-description-prerecorded">AA 1.2.5</a><a href="https://www.w3.org/WAI/WCAG21/Understanding/media-equiv-audio-desc-only"></a></strong><br>
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
<td><strong><a href="https://www.w3.org/WAI/WCAG21/Understanding/audio-only-and-video-only-prerecorded">A 1.2.1</a><a href="https://www.w3.org/WAI/WCAG21/Understanding/media-equiv-av-only-alt"></a></strong> (transcript <em><strong>or</strong></em> audio description)<br>
<a href="https://www.w3.org/WAI/WCAG21/Understanding/media-alternative-prerecorded">AAA 1.2.8</a>
<td>&nbsp;</td>
<td><strong><a href="https://www.w3.org/WAI/WCAG21/Understanding/audio-description-or-media-alternative-prerecorded">A 1.2.3</a></strong>&nbsp;(audio description <em><strong>or</strong></em> transcript)<br>
<strong><a href="https://www.w3.org/WAI/WCAG21/Understanding/audio-description-prerecorded">AA 1.2.5</a></strong></td>
<td>&nbsp;</td>
</tr>
</table>

## Live
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
<td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
</table>

## Learn More

<p>To learn more about WCAG standards, see <a href="https://www.w3.org/WAI/WCAG21/Understanding/time-based-media">Understanding Guideline 1.2: Time-based Media</a>.

<p>To figure out what your specific video or audio needs, see <a href="@@">What Does My Video/Audio Need?</a></p>

<p style="text-align:center"><strong>[ < Previous &nbsp;&nbsp;&nbsp; Next > ]</strong></p>

