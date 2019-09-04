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
   <p><strong>Date:</strong> <strong>Draft </strong>Updated @@ August 2019.</p>
   <p><strong>Editor:</strong> <a href="http://www.w3.org/People/Shawn">Shawn Lawton Henry</a>. <a href="/design-develop/media/acknowledgements/">Acknowledgements</a> lists contributors and credits.</p>
   <p>Developed by the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Originally drafted as part of the <a href="https://www.w3.org/WAI/WCAGTA/">WCAG TA Project</a> funded by the <abbr title="United States">U.S.</abbr> Access Board. Revised as part of the <a href="https://www.w3.org/WAI/expand-access/">WAI Expanding Access project</a> funded by the Ford Foundation.</p>

---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

Accessible audio and video is essential for people with disabilities, and benefits organizations. Depending on the content of your media, it might need **captions/subtitles** (a text version of the audio that is shown synchronized in the media player), a **transcript** (a separate text version of the audio), **audio description of visual information** (usually an additional audio stream that describes important visual content), **or other** accessibility functionality/features.

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

## First, Understand User Needs

Before we get into details and descriptions, it's useful to understand the user experiences of people with disabilities. Then you'll know the "why" behind the media accessibility requirements in this resource. For example, a person who is Deaf can't hear the audio, so you need to provide important audio information in another form.

* Many people who are **Deaf** can read text well. They get the audio information from **transcripts** or **captions**. Some people prefer **sign language**.
* Some people who are **hard of hearing** like to listen to the audio to hear what they can, and have **captions** to fill in what they can't hear adequately.
* Some people who have **difficulty processing auditory information** also use **captions**. Many use **transcripts** so they can read at their own pace.
* Some people who are **blind** or have low vision can't see videos well or at all. They use **audio description of visual information** to understand what's going on visually.
* Some people who are **Deaf-blind** use a screen reader and braille to read **descriptive transcripts** that include the audio and visual information as text.
* Some people **cannot focus and comprehend auditory or visual information** when there are changing visuals. For most videos, they also need **descriptive transcripts**.
* Some people cannot use their hands and **use voice recognition software** to operate their computer, including the **media player**.  And people who are **blind** need the media player to work without a mouse.
* Some people use multiple accessibility features simultaneously. For example, someone might want captions, description of visual information as text, and description in audio.

_(More information is in separate pages: [How People with Disabilities Use the Web](/people-use-web/) and [Media Accessibility User Requirements](https://www.w3.org/TR/media-accessibility-reqs/).)_

## How to Make Audio and Video Accessible

[{% include image.html src="planning.svg" alt="Planning Audio and Video Media" class="mini right" %}](/design-develop/media/planning/)

This resource helps you understand how to make media accessible, whether you are outsourcing it or creating it in-house. To **figure out which accessibility aspects your specific audio or video needs** to be accessible, for project management guidance, and to learn about Web Content Accessibility Guidelines (WCAG) standards, see [Planning Audio and Video Media](/design-develop/media/planning/).

[{% include image.html src="av-content.svg" alt="Audio Content and Video Content" class="mini right" %}](/design-develop/media/av-content/)

When you are creating **new** audio or video, there are several accessibility barriers to avoid such as flashing that can cause seizures and distracting background noise. These are explained in [Audio Content and Video Content](/design-develop/media/av-content/).

[{% include image.html src="player.svg" alt="Media Players" class="mini right" %}](/design-develop/media/player/)

Most default browser media players have limited functionality to support accessibility. Some third-party players are designed specifically for accessibility. Learn more from [Media Players](/design-develop/media/player/).

Specific guidance for other aspects of making your media accessible are in the following pages:

* {:.left} [{% include image.html src="ad.svg" alt="" %} Audio Description of Visual Information](/design-develop/media/description/) &mdash; Description provides content to people who are blind and others who cannot see the video adequately. It describes visual information needed to understand the content.

* {:.left} [{% include image.html src="cc.svg" alt="" %} Captions/Subtitles](/design-develop/media/captions/) &mdash; Captions (also called "subtitles") provide content to people who are Deaf and hard-of-hearing. Captions are a text version of the speech and non-speech audio information needed to understand the content. They are synchronized with the audio and usually shown in a media player when users turn them on.

* {:.left} [{% include image.html src="transcript.svg" alt="" %} Transcripts](/design-develop/media/transcripts/) &mdash; Basic transcripts are a text version of the speech and non-speech audio information needed to understand the content. <em>Descriptive transcripts</em> also include text description of the visual information needed to understand the content. Descriptive transcripts are required to provide video content to people who are both Deaf and blind.

* {:.left} [{% include image.html src="sign.svg" alt="" %} Sign Languages](/design-develop/media/sign-languages/) &mdash; Sign languages use hand and arm movements, facial expressions, and body positions to convey meaning. For many people who are Deaf, sign language is their native language, and some do not understand written language well. (Sign language is not required by most policies.)
{:.nolist.withicons.mini}

## Example Video

An example accessible video is on the [Colors with Good Contrast page.<br>
{% include image.html src="contrast-still.png" alt="" class="normal video" %}](https://www.w3.org/WAI/perspective-videos/contrast/)

That page provides:
* audio and video content with accessibility considerations, such as low background audio
* a version of the video with description of visual information integrated in the main audio, and description available as text
* captions
* a descriptive transcript
* a media player with accessibility support, including an interactive transcript

## Benefits to Organizations and Individuals {#benefits}

Organizations that make their audio and video accessible can realize benefits such as:
* Increased traffic and website use by people with and without disabilities, for example, in the [situations described below](#situations).
* Better user experience for all and improved customer satisfaction.
* Better indexing by search engines.

Benefits to organizations are illustrated in these other resources:
* The business case includes **case study data** from adding transcripts, and more on how accessibility can [increase your market reach](https://www.w3.org/WAI/business-case/#increase-market-reach).
* Benefits of transcripts and captions to a university are mentioned in a [**user story/persona** of an online student who is hard of hearing](https://www.w3.org/WAI/people-use-web/user-stories/#onlinestudent).
* Some benefits of captions are illustrated in a 1-minute [**Video** on Captions.<br>
{% include image.html src="captions-video-still.jpg" alt="" class="normal video" %}](https://www.w3.org/WAI/perspective-videos/captions/)

### Used by People With and Without Disabilities {#situations}

Accessible audio and video is **essential for people with disabilities**, and is **useful for everyone** in a variety of situations.

For example, transcripts can be:
* Skimmed or read rather than watched or listened to. This is significantly easier and quicker for many users. Sometimes people want to skim the transcript first before deciding whether or not to play the media.
* Used without needing to download video files. For example, to save data on mobile.
* Used offline, printed, or converted to braille.

And captions can be used:
* In loud environments where users cannot hear the audio. For example, a bar, an airport, or a concert.
* In quiet environments where users cannot turn on sound. For example, in a library, on public transportation, or when others are sleeping.
* By people who cannot understand the spoken language well and can understand the written language better. For example, people who are not native speakers of the language.
* By people learning to read, including people learning a new language.
* To better understand content because users can hear the information in audio and see it in text at the same time. For example, a [Research Study of Closed Captions & Transcripts {% include_cached external.html %}](https://www.3playmedia.com/2019/02/21/8-benefits-of-transcribing-captioning-videos/) found that 71% of students _without_ hearing difficulties use captions, primarily to help them focus and retain information.

This resource helps make your media usable in all those situations, by people with and without disabilities. The next page gets you started **[Planning Accessible Audio and Video Media](/design-develop/media/planning/)**.
