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

resource:
  ref: /design-develop/media/
navigation:
  previous: /design-develop/media/
  next:     /design-develop/media/av-content/

footer: >   # Translate all the words below, including "Date:" and "Editor:". 

---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page helps you plan accessible media. It:
* helps you **figure out what your specific audio or video needs** (captions, audio description, a transcript, etc.)
* helps with project management and planning what to develop in-house and what to outsource
* shows the Web Content Accessibility Guidelines ([WCAG](/standards-guidelines/wcag/)) standards for audio and video media

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include toc.html type="start" title="Page Contents" %}
{:/}

- This will be replaced by an automatically generated TOC when using Markdown formatting.
{::options toc_levels="2,3" /}
{:toc}

{::nomarkdown}
{% include toc.html type="end" %}
{:/}

## Introduction

For background, see _[Making Video and Audio Accessible - Introduction](index)_ that provides:
* brief descriptions of captions, transcripts, audio description, sign language, and media player accessibility
* examples of user experiences to help you understand why who needs what

What accessibility features you provide with your media will likely be influenced by:
* governmental regulations and other policy requirements
* budget and time constraints
* user needs

This resource endeavors to help you know the minimum requirements and encourages you to meet all user needs.

## Checklists

The checklists below:
* include all that is needed to meet user needs (including what goes beyond minimum accessibility standards and policies)
* indicate what is required in Web Content Accessibility Guidelines (WCAG) at Level A, AA, and AAA. _(For an explanation of all that, jump down to the [Standards section of this page](#standards).)_

The links go to a page with details on understanding and implementing each thing.

### Audio-only Checklist

This section covers things like podcasts that don't have video.

{::nomarkdown}
{% include box.html type="start" title="Pre-recorded audio:" class="highlighted" id="tree-ap" %}
{:/}

-   **[Audio content](/design-develop/media/av-content/#audio-only-and-videos) (A)** that is accessible; for example, what is said and how it's recorded
-   **[Transcript](/design-develop/media/transcripts/) (A)** separate from the audio
-   [Captions](/design-develop/media/captions/) synched with the audio
-   [Sign language(s)](/design-develop/media/sign-languages/) (AAA)
{:.checkbox}

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include box.html type="start" title="Live audio:" class="highlighted" id="tree-la" %}
{:/}

-   **[Audio content](/design-develop/media/av-content/#audio-only-and-videos) (A)** that is accessible; for example, what is said and how it's recorded
-   **[Captions](/design-develop/media/captions/) (AA)**
-   [Transcript](/design-develop/media/transcripts/) (AAA)
-   [Sign language(s)](/design-develop/media/sign-languages/)
{:.checkbox}

{::nomarkdown}
{% include box.html type="end" %}
{:/}

### Video Checklist

{::nomarkdown}
{% include box.html type="start" title="Pre-recorded video:" class="highlighted" id="tree-vp" %}
{:/}

**Does the video have speech or other audio** that is needed to understand the
content?

-   If yes,
    -   **[Audio content](/design-develop/media/av-content/#audio-only-and-videos) (A)** that is accessible; for example, what is said and how it's recorded
    -   **[Captions](/design-develop/media/captions/)** **(AA)**
    -   [Transcript of audio information](/design-develop/media/transcripts/) (AAA) *(The same text from the captions file, in a different format.)*
    -   [Sign language(s)](/design-develop/media/sign-languages/) (AAA)
    {:.checkbox}
-   If no, [inform users](#none).

**Does the video have visual information** that is needed to understand the
content?

-   If yes,
    -   **[Video content](/design-develop/media/av-content) (A)** that is accessible; for example, doesn't cause seizures
    -   **[Audio description of the visual information](/design-develop/media/description) (A/AA)**
    -   **[Descriptive transcript](/design-develop/media/transcripts) (AAA)** *(If you have a descriptive transcript, you do not need an additional transcript of only audio information from the previous question.)*
    {:.checkbox}
-   If no, [inform users](#none).

![]({{ "/assets/images/checkbox.svg" | relative_url }}) **[Media player](/design-develop/media/player) (A)** that
supports accessibility.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include box.html type="start" title="Live video:" class="highlighted" id="tree-lv" %}
{:/}

**Is there speech or other audio** that is needed to understand the
content?

-   If yes,
    -   **[Audio content](/design-develop/media/av-content/#audio-only-and-videos) (A)** that is accessible; for example, what is said and how it's captured
    -   **[Captions](/design-develop/media/captions/) (AA)**
    -   @@ need to say in format available to Braille?
    -   [Sign language(s)](/design-develop/media/sign-languages/)
    {:.checkbox}
-   If no, [inform users](#none).

**Is there visual information** that is needed to understand the
content?

-   If yes,
    -   **[Video content](/design-develop/media/av-content/) (A)** that is accessible; for example, doesn't cause seizures
    -   @@ Description of the visual information - also provided as a text stream available to Braille ?
    {:.checkbox}
-   If no, [inform users](#none).

![]({{ "/assets/images/checkbox.svg" | relative_url }}) **[Media player](/design-develop/media/player) (A)** that
supports accessibility.


{::nomarkdown}
{% include box.html type="end" %}
{:/}

### Inform Users When Not Needed {#none}
{:.no_toc}

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

### Provide Both Captions and a Transcript {#captions-and-transcript}

It is best to provide captions and a separate transcript.

For videos, captions enable people who are Deaf or hard of hearing to see the visual content and read the captions at the same time. 

For audio-only, captions enable people who are hard of hearing to get the richness of listening to the audio and fill in what they don't hear well by reading the captions.

Transcripts are needed to provide access to people who are Deaf-blind and use braille. Also, transcripts have several [additional benefits](/design-develop/media/#additional-benefits) to all users.

**Captions and transcripts use the same text. Once you have one, it's fairly easy to develop the other.**

## Project Management

<img src="{{ "/content-images/wai-media-guide/in-or-out.png" | relative_url }}" alt="" style="float: right; margin-left: 2rem; clear:right; width: 30%; max-width: 220px">

Include specific accessibility requirements in your:
* Project requirements - internal and external
* Requests for Proposal (RFP) or Requests for Tender (RFT)
* Contracts

Here is an example workflow for developing an accessible video, with notes on who develops the material:

{::nomarkdown}
{% include box.html type="start" title="Workflow and Responsibilities" class="" %}
{:/}

1. Address accessibility in **[video content](/design-develop/media/av-content/)** as the video is planned and produced.<br>_By:_ Script writers, videographers, producers, and others.

2. Develop an **[described version](/design-develop/media/description/)** of the video at the same time as the main video, if needed.<br>_By:_ Usually the same people who produce the main video also produce the described version."

3. Develop **[captions](/design-develop/media/captions/)** for the main video, for the audio described version, and of the audio description itself.<br>_By:_ Usually if the video is professionally produced, the producers provide captions. Sometimes when informal videos are developed in-house, captions are outsourced.

4. Develop a **[descriptive transcript](/design-develop/media/transcripts/)** using the text from the caption files.<br>_By:_ Often transcripts are developed in-house from caption files.

5. Implement it in an **[accesible media player](/design-develop/media/player/)** (usually an existing player with good accessibility support).<br>_By:_ Usually in-house web developers.

_@@ sign languages ? ([survey results](https://www.w3.org/2002/09/wbs/35532/AVmedia-21-jun/results#xsign))_

{::nomarkdown}
{% include box.html type="end" %}
{:/}

To help you plan in-house and outsourced work, the sub-pages of this resource include **considerations, skills, and tools needed** for creating accessible media:
* [Audio Description Considerations](/design-develop/media/description/#audio-description-considerations)
* [Captions, Skills and Tools](/design-develop/media/captions/#skills-and-tools) and [Automatic Captions are Not Sufficient](/design-develop/media/captions/#automatic-captions-are-not-sufficient)
* [Transcripts, Process - Skills and Tools](/design-develop/media/transcripts/#process---skills-and-tools)
* [Media Palyers, Skills and Tools](/design-develop/media/player/#skills-and-tools)

When planning for accessible media, it maybe helpful to communicate the **[additional benefits](/design-develop/media/#additional-benefits) to all users** and to your organization, such as search engine optimization (SEO).

## Standards

Web Content Accessibility Guidelines (WCAG) is introduced in the [WCAG Overview](https://www.w3.org/WAI/standards-guidelines/wcag/).

{::nomarkdown}
{% include box.html type="start" class="" %}
{:/}

This resource uses most WCAG terminology, with a few differences:
* "time-based media" in WCAG = "audio and video media" in this resource
* "[alternative for time based media](https://www.w3.org/TR/WCAG#alt-time-based-mediadef)" in WCAG = "transcript" for audio-only and "descriptive transcript" for video in this resource

{::nomarkdown}
{% include box.html type="end" %}
{:/}

WCAG includes requirements for audio and video media at [Level](https://www.w3.org/WAI/WCAG21/Understanding/conformance.html#uc-levels-head) A, AA, and AAA. Most media is required by governing policies to meet Level AA &mdash; which includes both A and AA listed in the tables below.

Accessibility requirements for video and audio are different based on if they are:
* pre-recorded or live
* video with audio, video without audio (video only), or audio only

### Pre-Recorded
{:.no_toc}

<table class="quiet">
<tr>
<th scope="col">&nbsp;</th>
<th scope="col">Transcript <span class="normal-weight">(including auditory and visual content)</span></th>
<th scope="col">Captions</th>
<th scope="col">Audio Description <span class="normal-weight">(if visual content not in audio)</span></th>
<th scope="col">Sign Language</th>
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
<tr>
  <th scope="row">Video with Audio</th>
  <td><a href="https://www.w3.org/TR/UNDERSTANDING-WCAG20/media-equiv-text-doc">AAA 1.2.8</a></td>
  <td><strong><a href="https://www.w3.org/WAI/WCAG21/Understanding/captions-prerecorded">A 1.2.2</a></strong></td>
  <td><strong><a href="https://www.w3.org/WAI/WCAG21/Understanding/audio-description-or-media-alternative-prerecorded">A 1.2.3</a></strong>&nbsp;(audio description <em><strong>or</strong></em> transcript)<br>
    <strong><a href="https://www.w3.org/WAI/WCAG21/Understanding/audio-description-prerecorded">AA 1.2.5</a></strong><br>
    <a href="https://www.w3.org/WAI/WCAG21/Understanding/extended-audio-description-prerecorded">AAA 1.2.7</a></td>
  <td><a href="https://www.w3.org/WAI/WCAG21/Understanding/sign-language-prerecorded">AAA 1.2.6</a></td>
</tr>
</table>

### Live
{:.no_toc}

<table class="quiet">
<tr>
<th scope="col">&nbsp;</th>
<th scope="col">Transcript</th>
<th scope="col">Captions</th>
<th scope="col">Audio Description</th>
<th scope="col">Sign Language</th>
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
<tr>
  <th scope="row">Video with Audio</th>
  <td>&nbsp;</td>
  <td><strong><a href="https://www.w3.org/WAI/WCAG21/Understanding/captions-live">AA 1.2.4</a></strong></td>
  <td>&nbsp;</td>
  <td>&nbsp;</td>
</tr>
</table>

### More about Standards
{:.no_toc}

To learn more about WCAG standards for media, see [Understanding Guideline 1.2: Time-based Media](https://www.w3.org/WAI/WCAG21/Understanding/time-based-media).

Other WCAG requirements related to audio and video include:
* Requirements for content covered in this resource: [Accessible Audio and Video Content](/design-develop/media/av-content/)
* [2.2.2 Pause, Stop, Hide](https://www.w3.org/TR/UNDERSTANDING-WCAG20/time-limits-pause.html) (Level A) For moving, blinking, scrolling, or auto-updating information, all of the following are true:...
* [1.4.2 Audio Control](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-dis-audio.html) (Level A) If any audio on a Web page plays automatically for more than 3 seconds, either a mechanism is available to pause or stop the audio, or a mechanism is available to control audio volume...

Your audio and video may be subject to additional requirements, for example under governmental regulations. Some of these are listed in [Web Accessibility Laws & Policies](https://www.w3.org/WAI/policies/). 

### Descriptive Transcripts

<p>Although WCAG Level AA does not require descriptive transcripts for videos, we recommend them because they:</p>
<ul>
  <li>are needed for most videos to be accessible to people who are &quot;Deaf-blind&quot;</li>
  <li>meet a wide range of accessibility needs, including for people who have difficulty processing auditory information and people who cannot focus and comprehend auditory or visual information when there is changing visuals</li>
  <li>provide <a href="/design-develop/media/#additional-benefits">additional benefits</a> for users <em>without</em> disabilities, and for your organization (for example, <abbr title="search engine optimization"> SEO</abbr>)</li>
  <li><strong>are easy and inexpensive to develop</strong> using captions and audio description that you already have to meet Level AA</li>
</ul>
