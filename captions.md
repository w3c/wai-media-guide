---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
title: "Captions/Subtitles"   # Do not translate "title:". Do translate the text after "title:".
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
   path: 'index.md'   # Add the language shortcode to the middle of the filename, for example index.fr.md
footer: >   # Translate all the words below, including "Date:" and "Editor:". 
navigation:
  previous: /design-develop/media/description/
  next:     /design-develop/media/transcripts/
---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page provides guidance on understanding and creating captions and subtitles.

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

_Captions are only one aspect of making audio and video accessible. For more, see [Making Video and Audio Accessible - Introduction](http://@@)._

## Introduction

_Who:_ Captions (also called "intralingual subtitles") provide content to people who are Deaf and others who cannot hear the audio. They are also used by people who process written information better than audio.

<img src="{{ "/content-images/captions.png" | relative_url }}" alt="" style="float: right; margin-left: 2rem; clear:right; width: 30%; max-width: 220px">

_What:_ Captions are a text version of the speech and non-speech audio information needed to understand the content. They are displayed within the media player and are synchronized with the audio.

Most are "closed captions" that can be hidden or shown by people watching the video. They can be "open captions" that are always displayed and cannot be turned off.

### Captions and Subtitles

Captions are called "intralingual subtitles" in some areas. This resource uses the term "captions" throughout.

Spoken audio **translated into another language** is called:
* _subtitles_ in areas that use "caption" terminology
* _interlingual subtitles_ in areas that use "intralingual subtitles" terminology

_Subtitles_ are implemented like captions. Subtitles/intralingual subtitles are usually only the spoken audio (for people who can hear the audio but do not know the spoken language). They can be a translation of the caption content, including non-speech audio information.

### Live Captions

Live captions are usually done by professional real-time captioners (also called Communication Access Realtime Translation (CART) providers). Live captions can be done in-person or remotely. That is, the person doing the captioning/CART does not have to be at the same location as the live action; they can be doing the live captions by listening to the audio over a phone or Internet connection.

If you have live captions and you post a recording, you will probably need to do minor editing for accuracy.

This rest of this page addresses developing captions for pre-recorded media.

### Interactive Transcripts from Captions
{:.no_toc}

Caption files are used by media players to provide _interactive transcripts_. Interactive transcripts highlight text phrases as they are spoken. Users can select text in the transcript and go to that point in the video. Some players provide interactive transcript functionality, and some do not.)

<img src="{{ "/content-images/interactive-transcript.png" | relative_url }}" alt="">

### Notes
{:.no_toc}

For optimum accessibility, provide a separate caption file of the audio description.

**Captions and transcripts include the same text, so one can be used to develop the other.**

## Does My Media Need Captions?

<div id="tree-ao" style="border: solid 1px #DDD; padding-bottom: 0;">
  <p style="background:#FFF; padding: 5px 5px 5px 11px; font-weight:bold; margin: 0;">Audio-only (e.g., podcast):</p>
  <div style="background:#D9EDF7; padding: 5px 0 0 11px; margin-top:0;">
    <ul style="padding-bottom: 11px; padding-top: 0; margin-top: 0; margin-bottom: 0;">
      <li>For pre-recorded:
        <ul>
          <li>Captions are <strong><em>not</em></strong> required. (Your audio content is provided in a <a href="/design-develop/media/transcripts/">transcript</a>.)</li>
          <li>Captions are useful for who are hard of hearing to get the richness of listening to the audio and fill in what they don’t hear well by reading the captions.</li>
        </ul>
      </li>
      <li>For live:
        <ul>
          <li>Captions are <strong><em>required</em></strong> to provide the audio content to people who are Deaf or hard of hearing.</li>
        </ul>
      </li>
    </ul>
  </div>
</div>
<br>
<div id="tree-vo" style="border: solid 1px #DDD; padding-bottom: 0;">
  <p style="background:#FFF; padding: 5px 5px 5px 11px; font-weight:bold; margin: 0;">Video-only (no audio content):</p>
  <div style="background:#D9EDF7; padding: 5px 0 0 11px; margin-top:0;">
    <ul style="padding-bottom: 11px; padding-top: 0; margin-top: 0; margin-bottom: 0;">
      <li>For pre-recorded and live:
        <ul>
          <li>Captions are <strong><em>not</em></strong> required (because there is no audio information).</li>
        </ul>
      </li>
    </ul>
  </div>
</div>
<br>
<div id="tree-va" style="border: solid 1px #DDD; padding-bottom: 0;">
  <p style="background:#FFF; padding: 5px 5px 5px 11px; font-weight:bold; margin: 0;">Video with audio content:</p>
  <div style="background:#D9EDF7; padding: 5px 0 0 11px; margin-top:0;">
    <ul style="padding-bottom: 11px; padding-top: 0; margin-top: 0; margin-bottom: 0;">
      <li>For pre-recorded and live:
        <ul>
          <li>Captions are <strong><em>required</em></strong> to provide the audio content to people who are Deaf or hard of hearing. </li>
        </ul>
      </li>
    </ul>
  </div>
</div>

## Skills and Tools

Creating captions requires typing up audio (&quot;transcribing&quot;) and formatting it in a file with timestamps. It is fairly difficult to transcribe an audio file, and takes quite a bit of time for people who don't have the software and skill for it. The file format for captions are simple, yet it's tedious to add timestamps, especially without software or service for developing caption files.

**Good captioning requires knowledge of which non-speech audio information should be included in the captions, and (@@Chris).**

Even correcting an automatic caption files takes quite a bit of time for people who don't do it regularly.

However, people who have the software, skills, and experience in developing captions, can develop them much faster.

For these reasons, many organizations choose to outsource their captions.

## Automatic Captions are Not Sufficient

Automatically-generated captions do not meet user needs or accessibility requirements, unless they are confirmed to be fully accurate. Usually they need significant editing. 

There are tools that use speech recognition technology to turn a soundtrack into a timed caption file. For example, many videos uploaded to YouTube have automatic captions. [[YouTube info](https://support.google.com/youtube/answer/3038280)] However, often the automatic caption text does not match the spoken audio — and in ways that change the meaning (or are embarrassing). For example, missing just one word such as "not" can make the captions contradict the actual audio content.

<p style="text-align:center; text-size:85%">[<em>optionally as an illustration for visual interest (with text as true text):</em><br>
  &quot;Spoken text: 
  Broil on high for 4 to 5 minutes. You should not preheat the oven.&quot;<br>
  &quot;Automatic caption: Broil on high for 45 minutes. You should know to preheat the oven.&quot;<br>
  <em>optional illustration/picture:  fire coming from oven, or totally burned food on a broiler pan ;-)</em>]</p>

Automatic captions can be used as a starting point for developing accurate captions and transcripts.

## Creating Captions

### Example Workflow

More information on these steps are in this web page.

{::nomarkdown}
{% include box.html type="start" class="" %}
{:/}

1. Pick a caption tool.
2. Understand what to include in captions, including the Tips.
3. Write up the captions and timing in the tool.
4. Review your captions as the video plays, and edit as needed.
5. Export the caption file.
6. If your tool provides it, export a file to create the transcript.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

### Caption Tools

Most people use software or services to help develop captions. There are several free captioning software programs and online services available.

<p style="text-align:center">[image of captioning software or service, probably YouTube since that's one many novies will use]</p>

Some tools create automatic captions that you can use as a starting point. You will need to edit automatic captions for accuracy.

For example, YouTube provides automatic captions and tools for you to edit the captions, as described in [Edit or remove captions – YouTube Help](https://support.google.com/youtube/answer/2734705?hl=en).

### What to Included in Caption Files

Include in the captions file:
* All speech and other relevant non-speech sound, such as this-good-example.
* The time each phrase should be displayed.
* Speaker identification, for example, in interviews.

{% include excol.html type="start" id="" %}

#### Tips for Caption Content

{% include excol.html type="middle" %}

Keep in mind that the main purpose of the captions is to provide information to people who cannot hear the audio. That will help you know what to sounds to transcribe, and what are not needed. The following are common practices, not requirements.

##### Specific for captions

* Captions are one or two rows. ?? character length

* Put a new sentence on a new line.

* If you need to break a sentence into multiple segments, break it at a logical phrase.

##### For captions and transcripts

* Identify the speakers as relevant. Often it is best to use the full name the first time and single name throughout &mdash; either first/given or last/family depending on the formality.

* You can include relevant information about the speech. For example:<br>
	<em>( shouting ):</em><br>
	I hate this computer!

* Put important non-speech sounds in parentheses, lowercase, italics, with a space before and after. For example:<br>
	 <em>( computer crashing into bits and parts sliding across the floor )</em>

* When a speaker is off-screen, you can put their speech in italics. For example:<br>
	<em>Jose: What was that awful noise?</em><br>
	Zoe: You don't want to know.<br>
	<em>Jose: Well, I'm coming to find out.</em>

* Only include background music if it's important to understand the content of the video. Use objective descriptions that indicate the mood; avoid subjective words, such as "beautiful." If the words in the music are important, add a musical note to the beginning and end of each caption. Put music information in italics. For example:<br>
	<em>♪ scary music, JAWS theme ♪</em>

* Do not emphasize a word using all capital letters except to indicate screaming.

###### Be True to the Audio Content

* **Do not change or adapt or add to the text**. Transcribe what is said accurately.
   * For example, it is usually not appropriate to correct grammar or other mistakes.
   * Do not censor. For example, if objectionable words are said, include those in the captions. If the audio is edited to obscure a phrase (e.g., "bleeped" audio), reflect that in the captions, e.g., <em> --bleep-- </em>
   * Do not provide additional clarifying information in the captions. (You can provide some in the transcript as appropriate.)

* Level of detail:
   * For some content, such as legal depositions, transcribe everything verbatim, including things like "um", "ah", and repeated phrases.
   * For most web content, it is acceptable to leave out non-substantive text to make the captions easier to process &mdash; while adhering to the tips above. For example, if the speaker says:<br><em><strong>I just got so frustrated</strong> (cough, cough) sorry – uhhh what was I saying?..., oh yea - <strong>I got so frustrated with my computer.</strong></em><br>
You can caption:<br>
<em><strong>I just got so frustrated with my computer.</strong></em>
   * If there is speech that is not at all relevant, indicate that it has been excluded from the captions. For example:<br>
	<em>[participants discuss the weather while the presenter reboots his computer]</em>

* If you cannot understand what is said, transcribe:<br>
[unintelligible]

* [@@ Do not caption the same, or nearly the same, information that is already shown onscreen. https://dcmp.org/learn/225 ]

{% include excol.html type="end" %}

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

{::nomarkdown}
{% include box.html type="start" title="Example VTT file of audio description" class="" %}
{:/}

```
WEBVTT

00:00:04.000 --> 00:00:07.980
<v Audio Descriptions>A man sitting at a desk starts watching a video on his computer. 

00:00:17.260 --> 00:00:20.780
<v Audio Descriptions>The video on his computer shows a person speaking to the camera.

00:00:20.780 --> 00:00:23.140
<v Audio Descriptions>It is playing with no audio.

00:00:26.880 --> 00:00:29.620
<v Audio Descriptions>The man watching the video has a hearing aid.
```

{::nomarkdown}

.
{% include box.html type="end" %}
{:/}

Other caption formats are: Timed Text Markup Language ([TTML](https://www.w3.org/TR/ttml2/)) and [SRT](https://matroska.org/technical/specs/subtitles/srt.html).
