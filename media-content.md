---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
title: "Creating Audio and Video Content"   # Do not translate "title:". Do translate the text after "title:".
nav_title: "Audio and Video Content" # A short title that is used in the navigation
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

## Video

### Avoid Causing Seizures

Avoid anything that flashes more than three times in any one second period. 

<span style="color:#585858; font-style:italic;">More information is in [Understanding Success Criterion 2.3.2: Three Flashes](https://www.w3.org/WAI/WCAG21/Understanding/three-flashes.html) and [Understanding Success Criterion 2.3.1: Three Flashes or Below Threshold](https://www.w3.org/WAI/WCAG21/Understanding/three-flashes-or-below-threshold.html)</span>

### Make overlay text readable

For any text, consider the font family, size, and contrast between the text and background.

<span style="color:#585858; font-style:italic;">More information is in [Understanding Success Criterion 1.4.3: Contrast (Minimum)](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum.html) and [Understanding Success Criterion 1.4.6: Contrast (Enhanced)](https://www.w3.org/WAI/WCAG21/Understanding/contrast-enhanced).</span>

### Plan for Audio Description of Visual Information

Plan to either:
* Integrate into the main audio all of the visual information that users need to understand the content.
* For scenes that need description of the visual information, record extra time.

See more specific information in [Creating Audio Description of Visual Information](@@).

## Video and Audio-Only

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

<hr>
@@ others ?

<p style="text-align:center"><strong>[ < Previous ]</strong></p>
