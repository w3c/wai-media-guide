---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.

title: "Captions/Subtitles"   # Do not translate "title:". Do translate the text after "title:".
title_html: '<img src="/content-images/wai-media-guide/CC.png" alt="" class="" style="float: right; height: 2em;">Captions/Subtitles'
nav_title: "Captions/Subtitles" # A short title that is used in the navigation
doc-note-type: draft

lang: en   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2019-04-10   # Put the date of this translation YYYY-MM-DD (with month in the middle)
# translator: "@@"   # Replace @@ with name or names separated with a comma
# contributors: "@@"   # Replace @@ with name(s) or delete this line

permalink: /design-develop/media/captions/   # Add the language shortcode to the end; for example /fundamentals/accessibility-intro/fr
ref: /design-develop/media/captions/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'captions.md'   # Add the language shortcode to the middle of the filename, for example index.fr.md

resource:
  ref: /design-develop/media/
navigation:
  previous: /design-develop/media/description/
  next:     /design-develop/media/transcripts/

footer: >   # Translate all the words below, including "Date:" and "Editor:".
   <p><strong>Date:</strong> <strong>Draft </strong>Updated @@ August 2019.</p>
   <p><strong>Editor:</strong> <a href="http://www.w3.org/People/Shawn">Shawn Lawton Henry</a>. <a href="/design-develop/media/acknowledgements/">Acknowledgements</a> lists contributors and credits.</p>
   <p>Developed by the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Originally drafted as part of the <a href="https://www.w3.org/WAI/WCAGTA/">WCAG TA Project</a> funded by the <abbr title="United States">U.S.</abbr> Access Board. Revised as part of the <a href="https://www.w3.org/WAI/expand-access/">WAI Expanding Access project</a> funded by the Ford Foundation.</p>

---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page helps you understand and create captions (also called "subtitles").

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

_Who:_ Captions (also called "intralingual subtitles") provide content to people who are Deaf and others who cannot hear the audio. They are also used by people who process written information better than audio.

{% include image.html src="captions.png" alt="" class="large right" %}

_What:_ Captions are a text version of the speech and non-speech audio information needed to understand the content. They are displayed within the media player and are synchronized with the audio.

Most are "closed captions" that can be hidden or shown by people watching the video. They can be "open captions" that are always displayed and cannot be turned off.

### Captions and Subtitles

The terms "captions" and "subtitles" are used for the same thing in different regions of the world. This resource uses:
* _Captions_ for the same language.
* _Subtitles_ for spoken audio translated into another language.

Some regions use _subtitles_ for both the same language as the audio and for the translation. Sometimes they are distinguished as _intralingual subtitles_ (same language) and _interlingual subtitles_ (different language).

Subtitles are implemented the same way as captions. Subtitles/intralingual subtitles are usually only the spoken audio (for people who can hear the audio but do not know the spoken language). They can be a translation of the caption content, including non-speech audio information.

### Live Captions

Live captions are usually done by professional real-time captioners (also called Communication Access Realtime Translation (CART) providers). Live captions can be done in-person or remotely. That is, the person doing the captioning/CART does not have to be at the same location as the live action; they can be doing the live captions by listening to the audio over a phone or Internet connection.

If you have live captions and you post a recording, you will probably need to do minor editing for accuracy.

This rest of this page addresses developing captions for pre-recorded media.

### Interactive Transcripts from Captions
{:.no_toc}

Caption files are used by some media players to provide _interactive transcripts_. Interactive transcripts highlight text phrases as they are spoken. Users can select text in the transcript and go to that point in the video. Some players provide interactive transcript functionality.

<img src="{{ "/content-images/wai-media-guide/interactive-transcript.png" | relative_url }}" alt="">

### Notes
{:.no_toc}

For optimum accessibility, provide a separate caption file of the audio description.

**Captions and transcripts include the same text, so one can be used to develop the other.**

## Does My Media Need Captions? {#checklist}

This section tells you:
* What is required in the WCAG standard at Level A, AA, and AAA. _([WCAG](https://wai-media-guide.netlify.com/design-develop/media/planning/#wcag-standard) is introduced in the Planning page of this resource.)_
* What is needed to meet user needs, beyond WCAG. If there are no "A"s, then it is not required in WCAG.

<div id="checklist-ao" style="border: solid 1px #DDD; padding-bottom: 0; margin-bottom: 1em;">
  <p style="background:#FFF; padding: 5px 5px 5px 11px; font-weight:bold; margin: 0;">Audio-only (e.g., podcast):</p>
  <div style="background:#D9EDF7; padding: 5px 0 0 11px; margin-top:0;">
    <ul style="padding-bottom: 11px; padding-top: 0; margin-top: 0; margin-bottom: 0;">
      <li>For pre-recorded:
        <ul>
          <li>Captions are useful for people who are hard of hearing to get the richness of listening to the audio and fill in what they don’t hear well by reading the captions.<br>Captions are not required to meet WCAG. (Transcripts are at Level A.)</li>
        </ul>
      </li>
      <li>For live:
        <ul>
          <li>Captions are needed to provide the audio content to people who are Deaf or hard of hearing.<br>Captions are <strong><em>required</em></strong> in WCAG at Level AA.</li>
        </ul>
      </li>
    </ul>
  </div>
</div>

<div id="checklist-vo" style="border: solid 1px #DDD; padding-bottom: 0; margin-bottom: 1em;">
  <p style="background:#FFF; padding: 5px 5px 5px 11px; font-weight:bold; margin: 0;">Video-only (no audio content):</p>
  <div style="background:#D9EDF7; padding: 5px 0 0 11px; margin-top:0;">
    <ul style="padding-bottom: 11px; padding-top: 0; margin-top: 0; margin-bottom: 0;">
      <li>For pre-recorded and live:
        <ul>
          <li>Captions are not needed because there is no audio information.</li>
        </ul>
      </li>
    </ul>
  </div>
</div>

<div id="checklist-video" style="border: solid 1px #DDD; padding-bottom: 0; margin-bottom: 1em;">
  <p style="background:#FFF; padding: 5px 5px 5px 11px; font-weight:bold; margin: 0;">Video:</p>
  <div style="background:#D9EDF7; padding: 5px 0 0 11px; margin-top:0;">
    <p><strong>Does the video have audio information</strong> that is needed to understand what the video is communicating?</p>
    <ul style="padding-bottom: 11px; padding-top: 0; margin-top: 0; margin-bottom: 0;">
      <li>If no (for example, it is just background music):
        <ul>
          <li>Captions are not needed because there is no important audio content. Consider <a href="https://wai-media-guide.netlify.com/design-develop/media/planning/#none">informing users</a>.</li>
        </ul>
      </li>
      <li>If yes:
        <ul>
          <li>For pre-recorded:
            <ul>
              <li>Captions are needed to provide the audio content to people who are Deaf or hard of hearing.<br>
                Captions are <em><strong>required</strong></em> in WCAG at Level A.</li>
            </ul>
          </li>
          <li>For live:
            <ul>
              <li>Captions are needed to provide the audio content to people who are Deaf or hard of hearing.<br>
                Captions are <em><strong>required</strong></em> in WCAG at Level AA.</li>
            </ul>
          </li>
        </ul>
      </li>
    </ul>
  </div>
</div>

## Skills and Tools

Creating captions requires typing up the audio (&quot;transcribing&quot;) and formatting it in a file with timestamps. Transcribing an audio file is fairly difficult and takes quite a bit of time for people who don't have the software and skill for it. The file format for captions are simple, yet it's tedious to add timestamps, especially without software or service for developing caption files.

Creating high-quality captions requires knowledge of which non-speech audio information should be included in the captions. It's more art than science --- for example, it's not always clear which non-speech audio information to include and how to communicate it in text.

Even correcting an automatic caption files takes quite a bit of time for people who don't do it regularly.

However, people who have the software, skills, and experience in developing captions, can develop them much faster.

For these reasons, many organizations choose to outsource their captions.

## Automatic Captions are Not Sufficient

Automatically-generated captions do not meet user needs or accessibility requirements, unless they are confirmed to be fully accurate. Usually they need significant editing. 

There are tools that use speech recognition technology to turn a soundtrack into a timed caption file. For example, some common video websites provide automatic captions. However, often the automatic caption text is wrong and does not match the spoken audio — sometimes in ways that change the meaning (or are embarrassing). For example, missing just one word such as "not" can make the captions contradict the actual audio content.

{::nomarkdown}
{% include box.html type="start" title="Example of bad automatic captions (that cause a fire)" class="simple aside"  %}
{:/}

{% include image.html src="food-fire.jpg" alt="" class="normal right" %}
  _Spoken text:_<br>&quot;Broil on high for <strong>4 to 5 minutes</strong>. You should <strong>not</strong> preheat the oven.&quot;<br>
  _Automatic caption:_<br>&quot;Broil on high for <strong>45 minutes</strong>. You should <strong>know to</strong> preheat the oven.&quot;

{::nomarkdown}
{% include box.html type="end" %}
{:/}

Automatic captions can be used as a starting point for developing accurate captions and transcripts.

## Creating Captions

### Caption File Format

The most common format for captions on the web is [WebVTT](https://www.w3.org/TR/webvtt/): The Web Video Text Tracks Format.

{::nomarkdown}
{% include box.html type="start" title="Example VTT file with speakers identified" class="" %}
{:/}

```
WEBVTT

00:11.000 --> 00:13.000
<v Rajwinder Kaur>Welcome to the podcast.

00:13.000 --> 00:17.000
<v Shawn Henry>Thank you for this opportunity to share information about accessibility.

00:17.000 --> 00:20.000
<v Rajwinder>Would you start by telling us a little about your role at W3C?

00:20.000 --> 00:24.000
<v Shawn>I work within the Web Accessibility Initiative, W-A-I, pronounced "way".
```

{::nomarkdown}
{% include box.html type="end" %}
{:/}
	
Other caption formats are: Timed Text Markup Language ([TTML](https://www.w3.org/TR/ttml2/)) and [SRT](https://matroska.org/technical/specs/subtitles/srt.html).

### Caption Tools

Most people use software or services to help develop captions. There are several free captioning software programs and online services available.

Several free and fee-based tools create automatic captions that you can use as a starting point. For example, a common video website includes automatic captions and tools for you to edit the captions. **You will need to edit automatic captions for accuracy.**

If you already have transcription of the audio into text, there are free tools that will generate a captions file with timestamps. You will need to edit it for line breaks as described in another page of this resource, Transcribing Audio to Text: [More on Captions](/design-develop/media/transcribing/#more-on-captions).

Most caption-editing tools can export a plain text transcript.

<img src="{{ "/content-images/wai-media-guide/caption-editing.png" | relative_url }}" alt="" style="width: 50%; max-width: 500px"><br>_The screen capture shows one tool for editing captions, in the area underneath the video._

### Transcribing Audio to Text

For specific guidance on what to type up, see another page in this resource: [Transcribing Audio to Text]( /design-develop/media/transcribing/).

## Positioning and Styling Captions

There are options for authors to position and style captions. Support in browsers and other media players is inconsistent and sometimes unreliable. Most web videos just use the player's default presentation style, which is usually white characters in a black box.

Some media players enable users to set preferences for how and where captions are displayed, including text style, text size, colors, and position of the captions.
