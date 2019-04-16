---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
title: "Creating Captions"   # Do not translate "title:". Do translate the text after "title:".
nav_title: "Captions" # A short title that is used in the navigation
lang: en   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2019-04-10   # Put the date of this translation YYYY-MM-DD (with month in the middle)
# translator: "@@"   # Replace @@ with name or names separated with a comma
# contributors: "@@"   # Replace @@ with name(s) or delete this line
permalink: /design-develop/media-guide/captions/   # Add the language shortcode to the end; for example /fundamentals/accessibility-intro/fr
ref: /design-develop/media-guide/captions/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'index.md'   # Add the language shortcode to the middle of the filename, for example index.fr.md
footer: >   # Translate all the words below, including "Date:" and "Editor:". 
---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page provides guidance on creating captions.

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

{::nomarkdown}
{% include box.html type="start" title="From the Introduction:" class="" %}
{:/}

<p>Captions provide content to people who are Deaf and others who cannot hear the audio. They are also used by people who process written information better than audio.</p>
<p>Captions are a text version of the speech and non-speech audio information needed to understand the content. They are displayed within the media player and  are synchronized with the audio.</p>
<p>Most are "closed captions" that can be hidden or shown by people watching the video. They can  be "open captions" that are always displayed and cannot be turned off.</p>
<p><strong><em>Subtitles</em></strong> are the spoken audio translated into another language. They are implemented like captions. Subtitles can be only the spoken audio (for people who can hear the audio) or can be a translation of the caption content including non-speech audio information.</p>
<p style="text-align:center"><em>[image: example static image from Perspectives Video on Captions showing captions.]</em></p>

{::nomarkdown}
{% include box.html type="end" %}
{:/}

## Scope

This page addresses developing captions for pre-recorded media. Live captions are usually done by professional Communication Access Realtime Translation (CART) providers. Live captions are not addressed on this page.

## What to Included in Caption Files

Captions include all speech and other relevant non-speech sound, such as this-good-example.

Caption files include the time each phrase should be displayed. They also identify the speaker, for example, in interviews.

For optimum accessibility, the audio description is also provided as a separate caption file.

Specific guidance is in the [Tips below](#tips-for-captions).

## Caption File Format

The most common format for captions on the web is [WebVTT: The Web Video Text Tracks Format]( https://www.w3.org/TR/webvtt/).

{::nomarkdown}
{% include box.html type="start" title="Example VTT file with speakers identified" class="" %}
{:/}

…

{::nomarkdown}
{% include box.html type="end" %}
{:/}


{::nomarkdown}
{% include box.html type="start" title="Example VTT file of audio description" class="" %}
{:/}

…

{::nomarkdown}
{% include box.html type="end" %}
{:/}

Other caption formats are: [Timed Text Markup Language (TTML)](https://www.w3.org/TR/ttml2/) and [SRT](https://matroska.org/technical/specs/subtitles/srt.html).

## Developing Captions

Most people who develop captions use software to help. There are several free captioning software programs and online services available. Some will create automatic captions that you can use as a starting point. Note that you will need to be edit automatic captions for accuracy.

<p style="text-align:center">[image of captioning software or service, probably YouTube since that's one many novies will use]</p>

For example, YouTube provides automatic captions and tools for you to edit the captions, as described in [Edit or remove captions – YouTube Help](https://support.google.com/youtube/answer/2734705?hl=en).

**Captions and transcripts include the same text, so one can be used to develop the other.**

{% include excol.html type="start" id="" %}

## Tips for Caption Content

{% include excol.html type="middle" %}

Keep in mind that the main purpose of the captions is to provide information to people who cannot hear the audio. That will help you know what to sounds to transcribe, and what are not needed. The following are common practices, not requirements.

### Specific for captions

* Captions are one or two rows. ?? character length

* Put a new sentence on a new line.

* If you need to break a sentence into multiple segments, break it at a logical phrase.

### For captions and transcripts

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

#### Editing Content

* Do not change or adapt or add to the text. For example, it is usually not appropriate to correct grammar or other mistakes.

* Do not censor. ...captions should reflect the words that are spoken in the audio track. If objectionable words are used in the audio, the captions should show those words. If the audio is edited to obscure a specific word or phrase (e.g., "bleeped" audio), the captions should reflect the fact that a word or phrase has been obscured....

* For some content, such as legal depositions, transcribe everything verbatim, including things like "um" and repeated phrases.

* For most web content, it is acceptable to do light editing to make the captions easier to process. For example, if the speaker says:<br><em>I just got so frustrated (cough, cough) sorry – uhhh, oh yea - I got so frustrated with my computer.</em><br>
You can caption:<br>
<em>I just got so frustrated with my computer.</em>

* If there is speech that is not relevant, it is usually best to indicate that it has been excluded from the captions. For example:<br>
	<em>[participants discuss the weather while the presenter reboots his computer].</em>

* [@@ Do not caption the same, or nearly the same, information that is already shown onscreen. https://dcmp.org/learn/225 ]

{% include excol.html type="end" %}


<p style="text-align:center"><strong>[ < Previous &nbsp;&nbsp;&nbsp; Next > ]</strong></p>
