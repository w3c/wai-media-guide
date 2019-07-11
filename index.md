---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.

title: "Making Audio and Video Media Accessible"   # Do not translate "title:". Do translate the text after "title:".
nav_title: "Audio & Video Media" # A short title that is used in the navigation
doc-note-type: draft

lang: en   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2019-04-10   # Put the date of this translation YYYY-MM-DD (with month in the middle)
# translator: "@@"   # Replace @@ with name or names separated with a comma
# contributors: "@@"   # Replace @@ with name(s) or delete this line

permalink: /design-develop/media/   # Add the language shortcode to the end; for example /fundamentals/accessibility-intro/fr
ref: /design-develop/media/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'index.md'   # Add the language shortcode to the middle of the filename, for example index.fr.md

resource:
  title: "Making Audio and Video Media Accessible"
  ref: /design-develop/media/
navigation:
  next: /design-develop/media/planning/
 
footer: >   # Translate all the words below, including "Date:" and "Editor:". 

---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This Web Accessibility Initiative (WAI) resource helps you make your audio and video media:
* accessible to people with disabilities
* meet international standards

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

## Understanding User Experiences

It's easy to understand that a person who is Deaf can't hear the audio, so you need to provide important audio information in another form. Here are some other considerations to help you understand the user experience behind making audio and video accessible. _(Descriptions of each aspect is below on this page.)_
* Many people who are **Deaf** can read text well, and use _transcripts_ or _captions_. Some cannot, and prefer _sign language_.
* Many people who are **hard of hearing** like to listen to the audio to hear what they can, and have _captions_ to fill in what they can't hear adequately.
* Some people who have **difficulty processing auditory information** also use _captions_. Many need _transcripts_ so they can read at their own pace.
* People who are **blind** need to know the relevant visual information in a video.  _Audio description of visual information_ can be provided separate from the main video.
* People who are **Deaf-blind** need the audio information and the visual information in text so they can read it with Braille. They need _descriptive transcripts_.
* Some people **cannot focus and comprehend auditory or visual information** when there is changing visuals. For most videos, they also need _descriptive transcripts_.

## How to Make Audio and Video Accessible

<img src="{{ "/content-images/wai-media-guide/planning.png" | relative_url }}" alt="" style="float: left; margin-right: 2rem; width: 11%; max-width: 77px">

This resource walks through understanding accessible media, whether you are outsourcing it or creating it in-house. To **figure out what your specific audio or video needs** and to learn about **standards** for audio and video media, see **[Planning Accessible Audio and Video Media](/design-develop/media/planning/)**.

<img src="{{ "/content-images/wai-media-guide/av-content.png" | relative_url }}" alt="" style="float: left; margin-right: 2rem; width: 11%; max-width: 77px">

When you are creating **new** audio or video, there are several things to consider such as background noise and avoiding flashing that can cause seizures. These are explained in **[Audio and Video Content](/design-develop/media/av-content/)**.

Specific guidance for other aspects of making your media accessible is in the pages linked below. Some media needs all of these, and others need only a transcript.

<img src="{{ "/content-images/wai-media-guide/AD.png" | relative_url }}" alt="" style="float: left; margin-right: 2rem; width: 11%; max-width: 77px">

**[Audio Description of Visual Information](/design-develop/media/description/)** &mdash; Audio description provides content to people who are blind and others who cannot see the video adequately. It describes visual information needed to understand the content.

<img src="{{ "/content-images/wai-media-guide/CC.png" | relative_url }}" alt="" style="float: left; margin-right: 2rem; width: 11%; max-width: 77px">

**[Captions/Subtitles](/design-develop/media/captions/)** &mdash; Captions (also called "intralingual subtitles") provide content to people who are Deaf and others who cannot hear the audio. Captions are a text version of the speech and non-speech audio information needed to understand the content. _Subtitles_ are the spoken audio translated into another language. Captions and subtitles are synchronized with the audio and usually shown in a media player.

<img src="{{ "/content-images/wai-media-guide/transcript.png" | relative_url }}" alt="" style="float: left; margin-right: 2rem; width: 11%; max-width: 77px">

**[Transcripts](/design-develop/media/transcripts/)** &mdash; Basic transcripts are a text version of the speech and non-speech audio information needed to understand the content. _Descriptive transcripts_ also include description of the visual information needed to understand the content. Descriptive transcripts are required to provide content to people who are both Deaf and blind. Transcripts are separate from a media player.

<img src="{{ "/content-images/wai-media-guide/sign.png" | relative_url }}" alt="" style="float: left; margin-right: 2rem; width: 11%; max-width: 77px">

**[Sign Languages](/design-develop/media/sign-languages/)** &mdash; Sign languages use hand and arm movements, facial expressions, and body positions to convey meaning. For most people who are Deaf, sign language is their native language, and some do not understand written language well. (Sign language is not required to meet most minimum accessibility standards.)

<img src="{{ "/content-images/wai-media-guide/player.png" | relative_url }}" alt="" style="float: left; margin-right: 2rem; width: 11%; max-width: 77px">

**[Media Player](/design-develop/media/player/)** &mdash; Media players have different levels of accessibility support. For example, some provide a separate audio track for description and some use the caption file to provide an _interactive transcript_.

## Example

An example accessible video is [Video Captions](/perspective-videos/captions/). That page provides:
* video and audio content with accessibility considerations, such as low background audio
* an audio described version of the video
* captions
* a descriptive transcript
* a media player with accessibility support, including an interactive transcript

## Additional Benefits

Accessible video and audio is **essential for people with disabilities**, and is **useful for everyone** in a variety of situations.

For example, transcripts can be:
* Skimmed or read rather than watched or listened to. This is significantly easier and quicker for many users. Sometimes people want to skim the transcript first before deciding whether or not to play the media.
* Used without needing to download video files. For example, to save data on mobile.
* Used offline, printed, or converted to Braille.
* Better indexed by search engines.

And captions can be:
* Used in loud environments where users cannot hear the audio. For example, a bar, an airport, and [@@ another good example].
* Used in quiet environments where users cannot turn on sound. For example, a library, when others are sleeping, and and [@@ another good example].
* Used by people who cannot understand the spoken language well and can understand the written language better. For example, people who are not native speakers of the language.
* Used by people to help them learn to read. For example, children, adults, and people learning a new language.
* Used to better understand content since users can hear the information in audio and see it in text at the same time. For example, {@@some data like [this](https://www.3playmedia.com/2019/02/21/8-benefits-of-transcribing-captioning-videos/)}.

Some benefits of captions are illustrated in this 1-minute <a href="https://www.w3.org/WAI/perspective-videos/captions/">Video on  Captions <img src="{{ "/content-images/wai-media-guide/captions-video-still.jpg" | relative_url }}" alt="" style="align: center; margin-left: 2rem; clear:right; width: 30%; max-width: 220px"></a>
