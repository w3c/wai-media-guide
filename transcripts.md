---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
title: "Transcripts"   # Do not translate "title:". Do translate the text after "title:".
title_html: "Transcripts<br><span style='background:yellow; font-size:65%'>Note: This page is not ready for detailed review yet.</span>"
nav_title: "Transcripts" # A short title that is used in the navigation
doc-note-type: draft
lang: en   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2019-04-10   # Put the date of this translation YYYY-MM-DD (with month in the middle)
# translator: "@@"   # Replace @@ with name or names separated with a comma
# contributors: "@@"   # Replace @@ with name(s) or delete this line
permalink: /design-develop/media/transcripts/   # Add the language shortcode to the end; for example /fundamentals/accessibility-intro/fr
ref: /design-develop/media/transcripts/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'index.md'   # Add the language shortcode to the middle of the filename, for example index.fr.md
footer: >   # Translate all the words below, including "Date:" and "Editor:". 
navigation:
  previous: /design-develop/media/captions/
  next:     /design-develop/media/transcribing/

---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page provides guidance on understanding and creating transcripts.

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

_Transcripts are only one aspect of making audio and video accessible. For more, see [Making Video and Audio Accessible - Introduction](http://@@)._

... [below currently mostly addresses video. edit for simple transcript-only info e.g. for podcasters] ...

## Introduction

Basic transcripts are a text version of the speech and non-speech audio information needed to understand the content.

<img src="{{ "/content-images/wai-media-guide/braille.jpg" | relative_url }}" alt="" style="float: right; margin-left: 2rem; clear:right; width: 30%; max-width: 220px">

**_Descriptive transcripts_** also include visual information needed to understand the content.

_Who:_ Descriptive transcripts are required to provide content to people who are both Deaf and blind. They are also used by people who process text information better than audio and video.

If you provide a descriptive transcript, you do not need a separate basic transcript.

Interactive transcripts highlight text phrases as they are spoken. Users can select text in the transcript and go to that point in the video. (This is a feature of the media player. It uses the captions file.)

<img src="{{ "/content-images/wai-media-guide/interactive-transcript.png" | relative_url }}" alt="">

### Skills and Tools

[... if don't have captions...]

... Transcripts are easy to develop once you have captions for the main video and of the audio description. In-house staff who know how to create basic web content can develop the descriptive transcript.

## Does my Audio or Video Need a Transcript?

<div id="tree-a" style="background:#D9EDF7; border: solid 1px #999; padding-left: 11px; padding-right: 5px;">
<ul>
  <li>< ...</li>
</ul>
</div>

### Providing a Descriptive Transcript for Your Videos
{:.no_toc}

<p>Descriptive transcripts are not required to meet WCAG Level AA. However, they:</p>
<ul>
  <li>meet a wide range of accessibility needs, and are needed in order for videos to be accessible to people who are &quot;Deaf-blind&quot;</li>
  <li>provide <a href="@@#benefits">additional benefits</a> for users <em>without</em> disabilities, and for your organization (for example, <abbr title="search engine optimization"> SEO</abbr>)</li>
  <li><strong>are easy and inexpensive to develop</strong> using captions and audio description that you already have to meet Level AA</li>
</ul>

## Creating Transcripts

**Transcripts and captions include the same text, so one can be used to develop the other.**

Often captions are developed first, and then transcripts are created from that text. Most caption-editing tools provide an option to export a plain text transcript.

Whatever tool you use to develop web content, you can use to develop your transcript.

### Example Workflow

This example is for developing a descriptive transcript from:
* a caption file for the main audio
* a caption file of the audio description of visual information

{::nomarkdown}
{% include box.html type="start" class="" %}
{:/}

1. Open your web editing tool.
2. If you are putting the descriptive transcript in a table, create the table.
3. Open the caption file of the main audio and the caption file of the audio description of visual information.
4. Copy and paste the information from the caption files into the table. Combine lines from the caption file into single table cells. @@say-more-or-link-to-tip. An [example descriptive transcript is below](#descriptive).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

### What to Include in Transcripts

In basic transcripts, include all speech and other relevant non-speech sound, such as this-good-example.

In descriptive transcripts, also include description of the visual information.

Add information to make the transcript more useful. For example, add headings, links, a summary, and maybe time stamps, as described in the Tips below.

{% include excol.html type="start" id="" %}

#### Tips

{% include excol.html type="middle" %}

Keep in mind that the main purpose of a descriptive transcript is to provide the information to people who cannot get it from the video. That will help you know what to include and how to format it. The following are optional, not requirements.

Transcripts generally include all of the audio information from the captions, and additional information. See the guidance under [For captions and transcripts[]@@). _{can we programmatically put one source here & there so users don't have to go elsewhere to get it, and we only have to update it in one places?}_

* **If you're starting with a captions file, edit the line breaks.** Put the information in logical paragraphs, lists, and sections. For example, in the example excerpts above, 6 lines of captions are grouped into 2 paragraphs of text (in table cells).

* **Add navigation and clarifications:**
   * Add headings and links where it will make the transcript more usable. This also helps with SEO. For example:
      * [Example with added links in short podcast transcript](http://www.w3.org/WAI/highlights/200606wcag2interview.html)
   * It is generally acceptable to add clarifying information, as long as it is clear that it is not part of the actual audio, e.g., words added to a paragraph put in [brackets], or separate sections with headings "Introduction", "Transcript", "Resources".
      * [Example with added headings in long presentation transcript](http://www.w3.org/WAI/highlights/200706wcag2pres)

* **Indicate the speakers for optimum usability** For example:
   * When there are multiple speakers, use hanging indents to make it easy to skim for a particular speaker.
   * When the focus should be on the interviewee's answers and not the interviewer, you could format the interviewer's questions in smaller, lighter text so the interviewee's answers stand out more clearly.

* **Include timestamps only when useful.** In many cases, including timestamps would be unnecessary clutter. If you do include them, they usually don't need to be as granular as the captions, and do not need to include end times.

{::nomarkdown}
{% include box.html type="start" title="Example caption file with timestamps (excerpt)" class="" %}
{:/}

…

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include box.html type="start" title="Example transcript of the same information (excerpt)" class="" %}
{:/}

… grouped more with single start time…

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{% include excol.html type="end" %}

### How to Format Transcripts

Most transcripts on the web are provided in HTML. There is not a set format for transcripts. You can choose how to present them based on your content.

A transcript of a podcast can be simple text paragraphs with the speakers identified.

{::nomarkdown}
{% include box.html type="start" title="Example transcript of a podcast interview with two speakers (excerpt)" class="" %}
{:/}

…

{::nomarkdown}
{% include box.html type="end" %}
{:/}

A descriptive transcript can be in a table so that readers can easily read only the audio information down a column if they choose. A [descriptive transcript example is below](#descriptive).

### Where to Put Transcripts

Transcripts can be:
* Included on the same web page with the media. ([example descriptive transcript at the bottom of same page with video](https://www.w3.org/WAI/perspective-videos/captions/#transcript))
* Provided on a separate web page. ([example podcast transcript on separate page](https://www.w3.org/WAI/highlights/200606wcag2interview.html))

Make sure it is easy for users to know that a transcript is available and to get to the transcript.

{% include excol.html type="start" id="example-descriptive" %}

## Example Descriptive Transcript from Caption Files

{% include excol.html type="middle" %}

Below is an example of caption files used to create a descriptive transcript.

{::nomarkdown}
{% include box.html type="start" title="Example caption file of audio information (excerpt)" class="" %}
{:/}

```
00:00:08.120 --> 00:00:10.240
Video isn't just about pictures,

00:00:10.241 --> 00:00:12.040
it's also about sound.

00:00:12.160 --> 00:00:16.280
Without the audio, you would have to guess what this film is about.

00:00:23.140 --> 00:00:24.730
Frustrating isn't it?

00:00:24.731 --> 00:00:26.880
Not knowing what's going on.

00:00:29.620 --> 00:00:32.840
That's the situation for everyone who can't hear.
```

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include box.html type="start" title="Example caption file of audio description of visual information (excerpt)" class="" %}
{:/}

```
00:00:04.000 --> 00:00:07.980
<v Audio Descriptions> A man sitting at a desk starts watching a video on his computer. 

00:00:17.260 --> 00:00:20.780
<v Audio Descriptions> The video on his computer shows a person speaking to the camera.

00:00:20.780 --> 00:00:23.140
<v Audio Descriptions> It is playing with no audio.

00:00:26.880 --> 00:00:29.620
<v Audio Descriptions> The man watching the video has a hearing aid.
```

{::nomarkdown}
{% include box.html type="end" %}
{:/}

<div id="descriptive"></div>

{::nomarkdown}
{% include box.html type="start" title="Example descriptive transcript from the caption files above (excerpt)" class="" %}
{:/}

<table>
  <thead>
    <tr>
      <th width="65%">Audio</th>
      <th>Visual</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Video isn't just about pictures, it's also about sound. Without the audio, you would have to guess what this film is about.</td>
      <td>A man sitting at a desk starts watching a video on his computer.<br></td>
    </tr>
    <tr>
      <td>[no sound]</td>
      <td>The video on his computer shows a person speaking to the camera. It is playing with no audio.</td>
    </tr>
    <tr>
      <td>Frustrating isn't it? Not knowing what's going on. That's the situation for everyone who can't hear.</td>
      <td>The man watching the video has a hearing aid.</td>
    </tr>
  </tbody>
</table>

{::nomarkdown}
{% include box.html type="end" %}
{:/}

**Notice that the single lines in the caption files have been grouped together in table cells.**

<p style="text-align:center"><em>[? detailed instructions &/or video showing slh's process for quickly developing descriptive transcript from the 2 VTT files]</em></p>

{% include excol.html type="end" %}
