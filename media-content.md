---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
title: "Creating Audio and Video Content"   # Do not translate "title:". Do translate the text after "title:".
nav_title: "Audio & Video Content" # A short title that is used in the navigation
lang: en   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2019-04-10   # Put the date of this translation YYYY-MM-DD (with month in the middle)
# translator: "@@"   # Replace @@ with name or names separated with a comma
# contributors: "@@"   # Replace @@ with name(s) or delete this line
permalink: /design-develop/media-guide/media-content/   # Add the language shortcode to the end; for example /fundamentals/accessibility-intro/fr
ref: /design-develop/media-guide/media-content/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'index.md'   # Add the language shortcode to the middle of the filename, for example index.fr.md
footer: >   # Translate all the words below, including "Date:" and "Editor:". 
---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page addresses accessibility considerations for planning and producing video and audio content.

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

_This page covers only some aspects of making audio and video accessible. For more, see [Making Video and Audio Accessible - Introduction](http://@@)._

## Introduction

This page introduces things to consider when planning, scripting, storyboarding, recording, and producing audio and video.

## Audio-Only and Videos

### Low Background Audio

When the main audio is a person speaking and you have background music, set the levels so people with hearing or cognitive disabilities can easily distinguish the speaking from the background.

Specifically, make the background sounds at least 20 decibels lower than the foreground speech content (with the exception of occasional sounds that last for only one or two seconds).

<span style="color:#585858; font-style:italic;">More information is in [Understanding Success Criterion 1.4.7: Low or No Background Audio](https://www.w3.org/WAI/WCAG21/Understanding/low-or-no-background-audio.html).</span>

### Provide redundancy for sensory charachteristics

Make your information work for people who cannot see and/or cannot hear.

For example, instead of saying:
<blockquote>Attach this to the green end.</blockquote>
Say:
<blockquote>Attach the small ring to the green end, which is the larger end.</blockquote>

<span style="color:#585858; font-style:italic;">More information that primarily addresses web pages, yet is relevant to audio and video, is in [Understanding Success Criterion 1.3.3: Sensory Characteristics](https://www.w3.org/WAI/WCAG21/Understanding/sensory-characteristics.html).</span>

## Videos

### Avoid Causing Seizures

Avoid anything that flashes more than three times in any one second period. 

<span style="color:#585858; font-style:italic;">More information is in [Understanding Success Criterion 2.3.2: Three Flashes](https://www.w3.org/WAI/WCAG21/Understanding/three-flashes.html) and [Understanding Success Criterion 2.3.1: Three Flashes or Below Threshold](https://www.w3.org/WAI/WCAG21/Understanding/three-flashes-or-below-threshold.html)</span>

### Make overlay text readable

For any text, consider the font family, size, and contrast between the text and background.

<span style="color:#585858; font-style:italic;">More information is in [Understanding Success Criterion 1.4.3: Contrast (Minimum)](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum.html) and [Understanding Success Criterion 1.4.6: Contrast (Enhanced)](https://www.w3.org/WAI/WCAG21/Understanding/contrast-enhanced).</span>

### Plan for Audio Description of Visual Information

_Audio description_ provides content to people who are blind and others who cannot see the video adequately. It describes the visual information needed to understand the content.

Plan to either:
* Integrate description of the visual information that users need to understand into the main audio content, _**or**_
* Record extra time for scenes that need description of the visual information.

#### Integrate Description

For many videos, the best way to handle audio description is not to need it at all &mdash; that is, all the visual information that users need to understand the content is integrated in the main audio. When planned in advance, this is fairly simple for many types of videos on the web, such as presentations and instructional videos. For example:

<table>
  <tr>
    <th scope="col"><svg aria-label="Wrong" class="icon-ex-circle "><use xlink:href="/WAI/assets/images/icons.svg#icon-ex-circle"></use></svg> Instead of the speaker saying:</th>
    <th scope="col"><svg aria-label="OK" class="icon-check-circle "><use xlink:href="/WAI/assets/images/icons.svg#icon-check-circle"></use></svg> The speaker can say:</th>
  </tr>
  <tr>
    <td>As you can see on this chart, sales increased significantly from the first quarter to the second quarter.</td>
    <td>This chart shows that sales increased significantly, from 1 million in the first  quarter to 1.3 million in the second quarter.</td>
  </tr>
  <tr>
    <td>Whip the mixture until it looks like this.</td>
    <td>Whip the mixture until the oil, vinegar, and spices are well combined.</td>
  </tr>
  <tr>
    <td>Attach this to the green end.</td>
    <td>Attach the small ring to the green end, which is the larger end.</td>
  </tr>
</table>

Guidance on what to include is in the "Creating Audio Description of Visual Information" page,  [Tips for Writing Description section]https://deploy-preview-6--wai-media-guide.netlify.com/design-develop/media-guide/description/#tips-for-writing-description).

#### Time for Description

For some types of videos, the description of the visual information cannot be smoothly handled by the speakers and narrator in the main video, because it would make the default video too much longer or more cumbersome. In that case, you will have the description separate. You can make the described version smoother by planning for the description.

Where the description is fairly short, plan space in the audio for the description.

Where the description is longer that you want to leave space in the main audio, you can record extra time in the scene to accommodate the description without having to pause the scene. That is, the same scene is shown with a little longer at the beginning or the end of it. For example:

<table>
  <tr>
    <th scope="col">Narration</th>
    <th scope="col">Main Video Scene Duration</th>
    <th scope="col">Described Video Scene Duration</th>
    <th scope="col">Description</th>
  </tr>
  <tr>
    <td><q>Captions are also handy for people who want to watch video in loud environments.</q></td>
    <td>3&nbsp;seconds</td>
    <td>7&nbsp;seconds</td>
    <td>A man is watching the captioned video with a group of people chatting away next to him.</td>
  </tr>
  <tr>
    <td><q>Or where you need to be very, very quiet.</q></td>
    <td>2&nbsp;seconds</td>
    <td>5&nbsp;seconds</td>
    <td>Turns out that they are in a library. The group is shushed by the librarian.</td>
  </tr>
</table>

An example of this is the [Web Accessibility Perspectives: Video Captions](https://www.w3.org/WAI/perspective-videos/captions/) video. The main video is 48 seconds long. The described version is 1 minute and 18 seconds long, yet there are no pauses in the visual aspect of the video.

<p style="text-align:center"><strong>[ < Previous &nbsp;&nbsp;&nbsp; Next > ]</strong></p>
