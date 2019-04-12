---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
title: "Creating Transcripts"   # Do not translate "title:". Do translate the text after "title:".
nav_title: "Create Transcripts" # A short title that is used in the navigation
lang: en   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2019-04-10   # Put the date of this translation YYYY-MM-DD (with month in the middle)
# translator: "@@"   # Replace @@ with name or names separated with a comma
# contributors: "@@"   # Replace @@ with name(s) or delete this line
permalink: /design-develop/media-guide/transcripts/   # Add the language shortcode to the end; for example /fundamentals/accessibility-intro/fr
ref: /design-develop/media-guide/transcripts/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'index.md'   # Add the language shortcode to the middle of the filename, for example index.fr.md
footer: >   # Translate all the words below, including "Date:" and "Editor:". 
---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

@@ Summary

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

{::nomarkdown}
{% include box.html type="start" title="From the Introduction:" class="" %}
{:/}

<p>Basic transcripts are a text version of the speech and non-speech audio information needed to understand the content.</p>
<p><strong><em>Descriptive transcripts</em></strong> also include visual information needed to understand the content.</p>
<p>Descriptive transcripts are required to provide content to people who are both Deaf and blind. They are also used by people who process text information better than audio and video.</p>
<p style="text-align:center"><em>[optional image: person interacting with dynamic Braille display, not looking at video in background]</em></p>
<p>Interactive transcripts highlight text phrases as they are spoken. Users can select text in the transcript and go to that point in the video. (This is a feature of the media player. It uses the captions file.)</p>
<p style="text-align:center"><em>[image like <a href="https://w3c.github.io/wai-media-intro/img/xcr_perspectives-d998a967.png">https://w3c.github.io/wai-media-intro/img/xcr_perspectives-d998a967.png</a>]</em> </p>

{::nomarkdown}
{% include box.html type="end" %}
{:/}

## What is Included in Transcripts

Basic transcripts include all speech and other relevant non-speech sound, such as this-good-example.

Descriptive transcripts also include audio description.

Optionally, transcripts can include: time stamps, headings, links, and other information to make the transcripts more useful.

## How Transcripts are Formatted

There is not a set format for transcripts. You can choose how to present them based on your content. Most transcripts on the web are provided in HTML.

For example, a transcript of a podcast can be simple text paragraphs with the speakers identified.


{::nomarkdown}
{% include box.html type="start" title="Example transcript of a podcast interview with two speakers" class="" %}
{:/}
…
{::nomarkdown}
{% include box.html type="end" %}
{:/}

A descriptive transcript can be in a table to that readers can easily read only the audio information down a column if they choose.

{::nomarkdown}
{% include box.html type="start" title="Example descriptive transcript" class="" %}
{:/}
…
{::nomarkdown}
{% include box.html type="end" %}
{:/}


## Developing Transcripts

[callout] Transcripts and captions include the same text, so one can be used to develop the other. Most caption-editing tools provide an option to export a plain text transcript.

Often captions (including of the audio description) are developed first, and then transcripts are created from that text.

Whatever tool you use to develop web content, you can use to develop your transcript.

Below is an example of using caption file to create a describtive transcript.

{::nomarkdown}
{% include box.html type="start" title="Example caption file of audio information" class="" %}
{:/}
…
{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include box.html type="start" title="Example caption file of audio description if visual information" class="" %}
{:/}
…
{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include box.html type="start" title="Example descriptive transcript" class="" %}
{:/}
…
{::nomarkdown}
{% include box.html type="end" %}
{:/}

<p style="text-align:center"><em>[optional video showing slh process for quickly developing descriptive transcript from the 2 VTT files]</em></p>

## Tips for Developing Transcripts

Keep in mind that the main purpose of a descriptive transcript is to provide the information to people who cannot get it from the video. That will help you know what to include and how to format it. The following are optional, not requirements.

Transcripts generally include all of the audio information from the captions, and additional information. See the guidance under "For captions and transcripts". _{can we programmatically put one source here & there so users don't have to go elsewhere to get it, and we only have to update it in one places?}_

* If you're starting with a captions file, edit the line breaks. Put the information in logical paragraphs, lists, and sections.

* Add navigation and clarifications:
   * Add headings and links where it will make the transcript more usable. This also helps with SEO. For example:
   * Example with added links in short podcast transcript.
   * It is generally acceptable to add clarifying information, as long as it is clear that it is not part of the actual audio, e.g., words added to a paragraph put in [brackets], or separate sections with headings "Introduction", "Transcript", "Resources".
      * [Example with added headings in long presentation transcript](http://www.w3.org/WAI/highlights/200706wcag2pres)

* Indicate the speakers for optimum usability. For example:
   * When there are multiple speakers, use hanging indents to make it easy to skim for a particular speaker.
   * When the focus should be on the interviewee's answers and not the interviewer, you could format the interviewer's questions in smaller, lighter text so the interviewee's answers stand out more clearly.

* Include timestamps only when useful. In many cases, including timestamps would be unnecessary clutter. If you do include them, they usually don't need to be as granular as the captions, and do not need to include end times.

{::nomarkdown}
{% include box.html type="start" title="Example caption file" class="" %}
{:/}
…
{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include box.html type="start" title="Example transcript of same information" class="" %}
{:/}
… grouped more with single start time…
{::nomarkdown}
{% include box.html type="end" %}
{:/}


<p style="text-align:center"><strong>[ < Previous &nbsp;&nbsp;&nbsp; Next > ]</strong></p>
