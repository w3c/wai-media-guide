---
title: "Planning"
title_html: '<img src="/content-images/wai-media-guide/planning.svg" alt="" class="" style="float: right; height: 2em;">Planning  Audio and Video Media'
nav_title: "Planning"

lang: en   # change "en" to lang code, here and 2 @@s below
last_updated: 2019-09-10   # Change to date of translation YYYY-MM-DD (month in middle)
# translator: "..."
# contributors: "..."

permalink: /media/av/planning/   # Add lang to end /link/to/page/@@
ref: /media/av/planning/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'planning.md'   # Add lang to the middle of the filename, e.g., index.@@.md

resource:
  ref: /media/av/
navigation:
  previous: /media/av/
  next:     /media/av/av-content/
  
description: Helps you plan how to make audio and video media accessible, whether you are outsourcing it or creating it in-house.
image: /content-images/wai-media-guide/social.png

footer: >   # Translate words below, including "Date:" and "Editor:". (Do not update the date.)
   <p><strong>Date:</strong> Updated 10 September 2019.</p>
   <p><strong>Editor:</strong> <a href="http://www.w3.org/People/Shawn">Shawn Lawton Henry</a>. <a href="/media/av/acknowledgements/">Acknowledgements</a> lists contributors and credits.</p>
   <p>Developed by the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Originally drafted as part of the <a href="https://www.w3.org/WAI/WCAGTA/">WCAG TA Project</a> funded by the <abbr title="United States">U.S.</abbr> Access Board. Revised as part of the <a href="https://www.w3.org/WAI/expand-access/">WAI Expanding Access project</a> funded by the Ford Foundation.</p>

---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page helps you:
* **figure out which accessibility aspects your specific audio or video needs** (captions, description, a transcript, etc.)
* manage projects and plan what to develop in-house and what to outsource
* understand the **standards** for audio and video media in Web Content Accessibility Guidelines (WCAG)

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
{:.no_toc}

For background, see the introduction page of this resource _[Making Video and Audio Accessible](index)_, for:
* brief explanations of captions, transcripts, description, sign language, and media player accessibility
* user experiences to help you understand the "why" behind the requirements

What accessibility features you provide with your media will likely be influenced by:
* user needs
* governmental regulations and other policy requirements
* budget and time constraints

This resource endeavors to help you know the requirements and encourages you to meet all user needs.

## Checklists for Audio and Video {#checklist}

The checklists below cover audio-only content and video content, and pre-recorded and live. They include:
* What is required in the Web Content Accessibility Guidelines (WCAG) standard at Level A, AA, and AAA. _([WCAG](#wcag-standard) is explained below.)_
* What is needed to meet user needs, beyond WCAG. (If it doesn't have any 'A', then it is not required in WCAG.)

The links below go to a web page in this resource with details on understanding and implementing each thing.

{::nomarkdown}
{% include box.html type="start" title="All Audio and Video Media" class="highlighted" id="checklist-all" %}
{:/}

- **[Audio content](/design-develop/media/av-content/#audio-only-and-videos) (A)** is accessible (for example, what is said and how it's recorded)
- **[Video content](/design-develop/media/av-content) (A)** is accessible (for example, doesn't cause seizures)
- **[Media player](/design-develop/media/player) (A)** supports accessibility
{:.alt}

{::nomarkdown}
{% include box.html type="end" %}
{:/}

### <img src="{{ "/content-images/wai-media-guide/audio.svg" | relative_url }}" alt="" style="height:1.3em"> Audio-only Checklists

This section covers audio-only media, like podcasts that don't have video.

{% capture boxhead %}
<img src="{{ "/content-images/wai-media-guide/recorded.svg" | relative_url }}" alt="" style="height:1em"> Pre-Recorded Audio-only
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="checklist-ap" %}
{:/}

-   **[Transcript](/design-develop/media/transcripts/) (A)** separate from the audio
-   **[Sign language(s)](/design-develop/media/sign-languages/) (AAA)**
-   **[Captions](/design-develop/media/captions/)** synchronised with the audio
{:.alt}

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{% capture boxhead %}
<img src="{{ "/content-images/wai-media-guide/live.svg" | relative_url }}" alt="" style="height:1em"> Live Audio-only
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="checklist-la" %}
{:/}

-   **[Captions](/design-develop/media/captions/) (AA)**
-   **[Transcript](/design-develop/media/transcripts/) (AAA)**
-   **[Sign language(s)](/design-develop/media/sign-languages/)**
{:.alt}

{::nomarkdown}
{% include box.html type="end" %}
{:/}

### <img src="{{ "/content-images/wai-media-guide/video.svg" | relative_url }}" alt="" style="height:1.3em">  Video Checklists

{% capture boxhead %}
<img src="{{ "/content-images/wai-media-guide/recorded.svg" | relative_url }}" alt="" style="height:1em"> Pre-Recorded Video
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="checklist-vp" %}
{:/}

**Does the video have speech or other audio** that is needed to understand the content?

-   If yes,
    -   **[Captions](/design-develop/media/captions/)** **(AA)**
    -   **[Transcript of audio information](/design-develop/media/transcripts/) (AAA)** *(The same text from the captions file, in a different format.)*
    -   **[Sign language(s)](/design-develop/media/sign-languages/) (AAA)**
    {:.alt}
-   If no, [inform users](#none).

**Does the video have visual information** that is needed to understand the content?

-   If yes,
    -   **[Audio description of the visual information](/design-develop/media/description) (A/AA)**
    -   **[Descriptive transcript](/design-develop/media/transcripts) (AAA)** *(If you have a descriptive transcript, you do not need an additional transcript of only audio information from the previous question.)*
    {:.alt}
-   If no, [inform users](#none).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{% capture boxhead %}
<img src="{{ "/content-images/wai-media-guide/live.svg" | relative_url }}" alt="" style="height:1em"> Live Video
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="checklist-lv" %}
{:/}

**Is there speech or other audio** that is needed to understand the content?

-   If yes,
    -   **[Captions](/design-develop/media/captions/) (AA)**
    -   **[Sign language(s)](/design-develop/media/sign-languages/)**
    -   Text stream available to screen readers (and braille devices)
    {:.alt}
-   If no, [inform users](#none).

**Is there visual information** that is needed to understand the content?

-   If yes,
    -   Description of important visual information in a text stream available to screen readers (and braille devices)
    {:.alt}
-   If no, [inform users](#none).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

### Inform Users When Not Needed {#none}

If your video does not need captions (because there is no substantive audio content) or does not need description (because there is no substantive visual content), it's good to let users know that. Otherwise, they might think that you accidentally forgot to provide it.

Users who need captions will look there, so you can provide a captions file with only the appropriate indication, such as "[background music]". Or you can provide the information in text with the video, such as:

{::nomarkdown}
{% include box.html type="start" class="" %}
{:/}

Captions not needed: The only sound in this video is background music.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include box.html type="start" class="" %}
{:/}

Description not needed: The visuals in this video only support what is spoken; the visuals do not provide additional information.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

### Provide Both Captions and a Transcript {#captions-and-transcript}

It is best to provide captions and a separate transcript.

For videos, captions enable people who are Deaf or hard of hearing to see the visual content and read the captions at the same time. 

For audio-only, captions enable people who are hard of hearing to get the richness of listening to the audio and fill in what they don't hear well by reading the captions.

Transcripts are needed to provide access to people who are Deaf-blind and use braille. Also, transcripts are used by people without disabilities, as listed in the intro page of this resource under [Benefits to Organizations and Individuals](/#benefits).

### Descriptive Transcripts

Descriptive transcripts for videos:

* are needed for most videos to be accessible to people who are "Deaf-blind"
* meet a wide range of accessibility needs, including for people who have difficulty processing auditory information and people who cannot focus and comprehend auditory or visual information when there is changing visuals
* are used by people _without_ disabilities, and benefit your organization (examples are in the intro page under [Benefits to Organizations and Individuals](/#benefits))
* **are easy and inexpensive to develop** using captions and description that you already have to meet Level AA

**Captions and transcripts use the same text. Once you have one, it's fairly easy to develop the other.**

### Other Languages

Translation of the audio into other languages can be provided:
* as text, using captions format (called subtitles or intralingual subtitles)
* as spoken audio, usually as a separate audio stream (for people who cannot read captions)
* as sign language

## Project Management

<!-- maybe better image in future iteration: <img src="{{ "/content-images/wai-media-guide/in-or-out.png" | relative_url }}" alt="" style="float: right; margin-left: 2rem; clear:right; width: 30%; max-width: 220px"> -->

Include specific accessibility requirements in your:
* Project requirements - internal and external
* Requests for Proposal (RFP) or Requests for Tender (RFT)
* Contracts

Here is an example workflow for developing an accessible video, with notes on who develops the material. Links go to other pages in this resource.

{::nomarkdown}
{% include box.html type="start" title="Example Workflow and Responsibilities" class="" %}
{:/}

1. Address accessibility in **[video content](/design-develop/media/av-content/)** as the video is planned and produced.<br>_By:_ Script writers, videographers, producers, and others.

2. Develop a **[described version of the video](/design-develop/media/description/)** at the same time as the main video, if needed.<br>_By:_ Usually the same people who produce the main video also produce the described version.

3. Develop **[captions](/design-develop/media/captions/)** for the main video, for the described version, and of the description itself.<br>_By:_ Usually if the video is professionally produced, the producers provide captions. Sometimes when informal videos are developed in-house, captions are outsourced.

4. Develop a **[descriptive transcript](/design-develop/media/transcripts/)** using the text from the caption files.<br>_By:_ Often transcripts are developed in-house from caption files.

5. Implement it in an **[accesible media player](/design-develop/media/player/)** (usually an existing player with good accessibility support).<br>_By:_ Usually in-house web developers.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

### Resourcing Accessibility {#in-or-out}

To help you **plan in-house and outsourced work**, the pages of this resource include considerations, skills, and tools needed for creating accessible media in these sections:
* [Description Considerations, Skills, and Tools](/design-develop/media/description/#audio-description-considerations-skills-and-tools)
* [Captions, Skills and Tools](/design-develop/media/captions/#skills-and-tools) and [Automatic Captions are Not Sufficient](/design-develop/media/captions/#automatic-captions-are-not-sufficient)
* [Transcripts, Process - Skills and Tools](/design-develop/media/transcripts/#process---skills-and-tools)
* [Media Players, Skills and Tools](/design-develop/media/player/#skills-and-tools)
* [Sign Languages, Skills and Tools](/design-develop/media/sign-languages/#skills-and-tools)

When planning and budgeting for accessible media, it is often helpful to communicate the **benefits to organizations**, such as search engine optimization (SEO), better user experience for all, improved customer satisfaction, and more listed in the intro page under [Benefits to Organizations and Individuals](/#benefits).

## WCAG Standard

Web Content Accessibility Guidelines (WCAG) is introduced in a separate resource: [WCAG Overview](https://www.w3.org/WAI/standards-guidelines/wcag/).

{::nomarkdown}
{% include box.html type="start" class="" %}
{:/}

This resource uses most WCAG terminology, with a few differences:
* "time-based media" in WCAG = "audio and video media" in this resource
* "[alternative for time based media in WCAG](https://www.w3.org/TR/WCAG#alt-time-based-mediadef)" = "transcript" for audio-only and "descriptive transcript" for video in this resource

{::nomarkdown}
{% include box.html type="end" %}
{:/}

WCAG includes requirements for audio and video media at Level A, AA, and AAA. (More info in a separate resource: [Understanding Levels of Conformance](https://www.w3.org/WAI/WCAG21/Understanding/conformance.html#levels).) Most media is required by governing policies to meet Level AA &mdash; which includes both A and AA listed in the tables below.

Accessibility requirements for video and audio are different based on if they are:
* pre-recorded or live
* video with audio, video without audio (video only), or audio only

The links in the tables below go to a page in a separate resource: Understanding WCAG 2.1.

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
  <td><a href="https://www.w3.org/WAI/WCAG21/Understanding/media-alternative-prerecorded">AAA 1.2.8</a></td>
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

To learn more about WCAG requirements for media, see [Understanding Guideline 1.2: Time-based Media](https://www.w3.org/WAI/WCAG21/Understanding/time-based-media).

Other WCAG requirements related to audio and video include:
* In this resource:
  * [Accessible Audio and Video Content](/design-develop/media/av-content/)
  * [Media Player Functionality](/design-develop/media/player/#player-accessibility-functionality)
* In Understanding WCAG:
   * [2.2.2 Pause, Stop, Hide](https://www.w3.org/WAI/WCAG21/Understanding/pause-stop-hide) (Level A) For moving, blinking, scrolling, or auto-updating information, all of the following are true:...
   * [1.4.2 Audio Control](https://www.w3.org/WAI/WCAG21/Understanding/audio-control) (Level A) If any audio on a Web page plays automatically for more than 3 seconds, either a mechanism is available to pause or stop the audio, or a mechanism is available to control audio volume...

Your audio and video may be subject to additional requirements, for example under governmental regulations. Some of these are listed in [Web Accessibility Laws & Policies](https://www.w3.org/WAI/policies/).
