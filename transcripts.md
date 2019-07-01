---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
title: "Transcripts"   # Do not translate "title:". Do translate the text after "title:".
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

_Transcripts are only one aspect of making audio and video accessible. For more, see [Making Video and Audio Accessible - Introduction]( /design-develop/media/)._


## Introduction

Basic transcripts are a text version of the speech and non-speech audio information needed to understand the content.

_Who:_ Basic transcripts are used by people who are Deaf, are hard of hearing, have difficulty processing auditory information, and others.

<img src="{{ "/content-images/wai-media-guide/braille.jpg" | relative_url }}" alt="" style="float: right; margin-left: 2rem; clear:right; width: 30%; max-width: 220px">

**_Descriptive transcripts_** for videos also include visual information needed to understand the content.

_Who:_ Descriptive transcripts are needed to provide audio and video content to people who are both Deaf and blind. They are also used by people who process text information better than audio and visual/pictorial information.

If you provide a descriptive transcript, you do not need a separate basic transcript.

_Interactive transcripts_ highlight text phrases as they are spoken. Users can select text in the transcript and go to that point in the video. This is a feature of the media player. It uses the captions file.

<img src="{{ "/content-images/wai-media-guide/interactive-transcript.png" | relative_url }}" alt="">

## Does My Media Need a Transcript?

**Short answer: Yes, transcripts are needed to meet the wide range of user needs**. In a some cases, they are not required to meet minimum standards. The Web Content Accessibility Guidelines (WCAG) standard is addressed in another page of this resource: Planning Accessible Audio and Video Media, ([Standards section](/design-develop/media/planning/#standards).

<div id="tree-ao" style="border: solid 1px #DDD; padding-bottom: 0; margin-bottom: 1em;">
  <p style="background:#FFF; padding: 5px 5px 5px 11px; font-weight:bold; margin: 0;">Audio-only (e.g., podcast):</p>
  <div style="background:#D9EDF7; padding: 5px 0 0 11px; margin-top:0;">
    <ul style="padding-bottom: 11px; padding-top: 0; margin-top: 0; margin-bottom: 0;">
      <li>For pre-recorded:
        <ul>
           <li>Transcripts are <strong><em>required</em></strong> at WCAG Level A.</li>
        </ul>
      </li>
      <li>For live:
        <ul>
          <li>Transcripts are at WCAG Level AAA. (Captions are AA.)</li>
        </ul>
      </li>
    </ul>
  </div>
</div>
<div id="tree-vo" style="border: solid 1px #DDD; padding-bottom: 0; margin-bottom: 1em;">
  <p style="background:#FFF; padding: 5px 5px 5px 11px; font-weight:bold; margin: 0;">Video-only (no audio content):</p>
  <div style="background:#D9EDF7; padding: 5px 0 0 11px; margin-top:0;">
    <ul style="padding-bottom: 11px; padding-top: 0; margin-top: 0; margin-bottom: 0;">
      <li>For pre-recorded and live:
        <ul>
          <li>Transcripts are not needed because there is no audio information.</li>
        </ul>
      </li>
    </ul>
  </div>
</div>
<div id="tree-va" style="border: solid 1px #DDD; padding-bottom: 0;">
  <p style="background:#FFF; padding: 5px 5px 5px 11px; font-weight:bold; margin: 0;">Video with audio content:</p>
  <div style="background:#D9EDF7; padding: 5px 0 0 11px; margin-top:0;">
    <ul style="padding-bottom: 11px; padding-top: 0; margin-top: 0; margin-bottom: 0;">
      <li>For pre-recorded:
        <ul>
          <li>Transcripts are at WCAG Level AAA. (Captions are AA.)</li>
        </ul>
      </li>
      <li>For live:
        <ul>
          <li>A live steam separate from the media player is needed for people who cannot access the captions. (Captions are AA.)</li>
        </ul>
      </li>
    </ul>
  </div>
</div>

### Provide a Descriptive Transcript for Your Videos
{:.no_toc}

We strongly recommend that you provide descriptive transcripts, even though they are not required to meet most minimum accessibility standards. Descriptive transcripts are needed by people who are Deaf-blind and others. (A bit more justification is in the Planning page: [Descriptive Transcripts](/design-develop/media/planning/#descriptive-transcripts).) And **descriptive transcripts are easy and inexpensive to make** using captions and audio description that you already have to meet Level AA, as explained on this page.

## Process - Skills and Tools

The process for providing transcripts is basically:
1.	Get a text version of the audio, called "transcribing".
2.	Format the transcript.
3.	Put the transcript online, and make it easy for users to find the transcript from the audio or video file.

### If You Start with Captions

For videos, often transcribing the audio to text is done to create captions, as described in the [captions page](/design-develop/media/captions/). Then the captions file is used to create the transcript.

Creating transcripts from caption files is easy with basic web skills and tools.

### If You Start with Transcribing

Transcribing an audio file takes quite a bit of time for people who don't have the software and skill for it. Many organizations choose to outsource the transcribing. Guidance for doing it yourself (DIY) is in another page of this resource: [Transcribing Audio to Text](/design-develop/media/transcribing/).

Once you have the transcription, creating the transcript is easy with basic web skills and tools.

## Creating Transcripts

If you already have captions, you can use that file to create the transcript. Most caption-editing tools provide an option to export a plain text transcript. Otherwise, you will need to delete the timestamps, or edit them per below.

If you don't have captions, you'll need transcription of the audio information. That's addressed in another page of this resource: [Transcribing Audio to Text](/design-develop/media/transcribing/).

### Transcript File Format

Most transcripts on the web are provided in HTML. There is not a set design for transcripts. Different options and examples are described throughout the guidance below.

A transcript of a podcast can be simple text paragraphs with the speakers identified.

{::nomarkdown}
{% include box.html type="start" title="Example transcript of a podcast interview with two speakers (excerpt)" class="" %}
{:/}

<p>Rajwinder Kaur: Welcome to the podcast.</p>
<p><strong>Shawn Henry:</strong> Thank you for this opportunity to share information about accessibility.</p>
<p>Rajwinder: Would you start by telling us a little about your role at W3C?</p>
<p><strong>Shawn:</strong> I work within the Web Accessibility Initiative, W-A-I, pronounced "way". </p>

{::nomarkdown}
{% include box.html type="end" %}
{:/}

A descriptive transcript can be in a table so that readers can easily read only the audio information down a column if they choose. A [descriptive transcript example is below](#descriptive).

{% include excol.html type="start" id="" open="true" %}

### Making Transcripts More Useful

{% include excol.html type="middle" %}

Keep in mind that the main purpose of a transcript is to provide the information to people who cannot get it from the audio and/or video. That will help you know what to include and how to design it. Add information to make the transcript more useful. For example, add headings, links, a summary, and maybe time stamps, as described below. The following are optional, not requirements.

* **Put the information in logical paragraphs, lists, and sections**. If you're starting with a captions file, you will probably combine several lines into paragraphs. For example, in the [example excerpts below](#example-descriptive-transcript-from-caption-files), 6 lines of captions are grouped into 2 paragraphs of text (in table cells).

* **Add navigation and clarifications:**
   * Add headings and links where it will make the transcript more usable. (This also helps with SEO.) Here's an [example with added links in short podcast transcript](http://www.w3.org/WAI/highlights/200606wcag2interview.html).
   * It is generally acceptable to add clarifying information, _as long as it is clear that it is not part of the actual audio_ &mdash; for example, words added to a paragraph put in [brackets], or separate sections with headings "Introduction", "Transcript", "Resources". Here's an [example with added headings in long presentation transcript](http://www.w3.org/WAI/highlights/200706wcag2pres).

* **Indicate the speakers based on the type of content.** For example:
   * When there are multiple speakers, you could use hanging indents to make it easy to skim for a particular speaker.
   * When you want the focus on the interviewee's answers and not the interviewer, you could bold the interviewee's name so it stands out more clearly.

* **Include timestamps only when useful.** In many cases, including timestamps would be unnecessary clutter. If you do include them, they usually don't need to be as granular as the captions, and do not need to include end times.

* **If starting with captions for video:** The video might have text information that was not included in the captions, for example, the title of the video or the name and title of people speaking. If you also have the captions for the description of visual information, it should already be in there. If not, you'll need to review the video and see if there is text visually that wasn't repeated in the captions, and add that to your transcript.

## Where to Put Transcripts

Make it is easy for users to know that a transcript is available and to get to the transcript.

For media on your website, often it's best to include the transcript on the same page. Here's an [example descriptive transcript at the bottom of same page with a video](https://www.w3.org/WAI/perspective-videos/captions/#transcript).

When your media is hosted elsewhere, you might have the transcript on a separate web page. Here's an [example podcast transcript on separate page](https://www.w3.org/WAI/highlights/200606wcag2interview.html).

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
