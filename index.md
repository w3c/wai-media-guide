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

This multi-page resource helps you make audio and video media accessible to people with disabilities.

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

Before we launch into details and descriptions, it's useful to understand the user experiences of people with disabilities. Then you'll know the "why" behind the media accessibility requirements in this resource. For example, a person who is Deaf can't hear the audio, so you need to provide important audio information in another form.

* Many people who are **Deaf** can read text well. They get the audio information from **transcripts** or **captions**. Some cannot, and prefer **sign language**.
* Many people who are **hard of hearing** like to listen to the audio to hear what they can, and have **captions** to fill in what they can't hear adequately.
* Some people who have **difficulty processing auditory information** also use **captions**. Many use **transcripts** so they can read at their own pace.
* People who are **blind** can't see videos. They use **audio description of visual information** to understand what's going on visually.
* People who are **Deaf-blind** use a screen reader and Braille to read **descriptive transcripts** that include the audio and visual information as text.
* Some people **cannot focus and comprehend auditory or visual information** when there are changing visuals. For most videos, they also need **descriptive transcripts**.

## How to Make Audio and Video Accessible

<img src="{{ "/content-images/wai-media-guide/planning.png" | relative_url }}" alt="" style="float: right; margin-left: 1rem; width: 11%; max-width: 77px">

This resource walks through understanding what is needed to make media accessible, whether you are outsourcing it or creating it in-house. To **figure out what your specific audio or video needs**, for project management guidance, and to learn about **standards**, see **[Planning Accessible Audio and Video Media](/design-develop/media/planning/)**.

<img src="{{ "/content-images/wai-media-guide/av-content.png" | relative_url }}" alt="" style="float: right; margin-left: 1rem; width: 11%; max-width: 77px">

When you are creating **new** audio or video, there are several things to consider such as background noise and avoiding flashing that can cause seizures. These are explained in **[Audio and Video Content](/design-develop/media/av-content/)**.

<img src="{{ "/content-images/wai-media-guide/player.png" | relative_url }}" alt="" style="float: right; margin-left: 1rem; width: 11%; max-width: 77px">

Most default browser media players have limited functionality to support accessibility. Some third-party players are designed specifically for accessibility. Learn more from **[Media Players](/design-develop/media/player/)**.

Specific guidance for other aspects of making your media accessible are in the following pages:

<img src="{{ "/content-images/wai-media-guide/AD.png" | relative_url }}" alt="" style="float: left; margin-right: 2rem; width: 11%; max-width: 77px">

<p style="margin-left:123px"><strong><a href="/design-develop/media/description/">Audio Description of Visual Information</a></strong> &mdash; Audio description provides content to people who are blind and others who cannot see the video adequately. It describes visual information needed to understand the content.</p>

<img src="{{ "/content-images/wai-media-guide/CC.png" | relative_url }}" alt="" style="float: left; margin-right: 2rem; width: 11%; max-width: 77px">

<p style="margin-left:123px"><strong><a href="/design-develop/media/captions/">Captions/Subtitles</a></strong> &mdash; Captions (also called "subtitles") provide content to people who are Deaf and others who cannot hear the audio. Captions are a text version of the speech and non-speech audio information needed to understand the content. They are synchronized with the audio and usually shown in a media player.</p>

<img src="{{ "/content-images/wai-media-guide/transcript.png" | relative_url }}" alt="" style="float: left; margin-right: 2rem; width: 11%; max-width: 77px">

<p style="margin-left:123px"><strong><a href="/design-develop/media/transcripts/">Transcripts</a></strong> &mdash; Basic transcripts are a text version of the speech and non-speech audio information needed to understand the content. <em>Descriptive transcripts</em> also include description of the visual information needed to understand the content. Descriptive transcripts are required to provide video content to people who are both Deaf and blind.</p>

<img src="{{ "/content-images/wai-media-guide/sign.png" | relative_url }}" alt="" style="float: left; margin-right: 2rem; width: 11%; max-width: 77px">

<p style="margin-left:123px"><strong><a href="/design-develop/media/sign-languages/">Sign Languages</a></strong> &mdash; Sign languages use hand and arm movements, facial expressions, and body positions to convey meaning. For many people who are Deaf, sign language is their native language, and some do not understand written language well. (Sign language is not required by most policies.)</p>

## Example

An example accessible video is on the <a href="https://www.w3.org/WAI/perspective-videos/contrast/">Colors with Good Contrast page<br><img src="{{ "/content-images/wai-media-guide/contrast-still2.png" | relative_url }}" alt="" style="width: 30%; max-width: 220px"></a>

That page provides:
* video and audio content with accessibility considerations, such as low background audio
* an audio described version of the video
* captions
* a descriptive transcript
* a media player with accessibility support, including an interactive transcript

## Additional Benefits

Organizations that make their audio and video accessible can realize benefits such as:
* Better indexing by search engines.
* Better user experience for all and improved customer satisfaction.
* Increased use in the situations described below.

Benefits to organizations are illustrated in separate pages:
* The business case resource includes **case study data from adding transcripts**, and more on how accessibility can [increase your market reach](https://www.w3.org/WAI/business-case/#increase-market-reach).
* Benefits of transcripts and captions to a university are mentioned in a **[user story/persona of an online student who is hard of hearing](https://www.w3.org/WAI/people-use-web/user-stories/#onlinestudent)**.
* Some benefits of captions are illustrated in a 1-minute<br>{% include video-link.html class="small" title="Video on Captions" href="https://www.w3.org/WAI/perspective-videos/captions/" src="/content-images/wai-media-guide/captions-video-still.jpg" %}

### Use by People With and Without Disabilities

Accessible video and audio is **essential for people with disabilities**, and is **useful for everyone** in a variety of situations.

For example, transcripts can be:
* Skimmed or read rather than watched or listened to. This is significantly easier and quicker for many users. Sometimes people want to skim the transcript first before deciding whether or not to play the media.
* Used without needing to download video files. For example, to save data on mobile.
* Used offline, printed, or converted to Braille.

And captions can be:
* Used in loud environments where users cannot hear the audio. For example, a bar, an airport, or a concert.
* Used in quiet environments where users cannot turn on sound. For example, in a library, on public transporation, or when others are sleeping.
* Used by people who cannot understand the spoken language well and can understand the written language better. For example, people who are not native speakers of the language.
* Used by people to help them learn to read. For example, children, adults, and people learning a new language.
* Used to better understand content since users can hear the information in audio and see it in text at the same time. For example, {@@some data like [this](https://www.3playmedia.com/2019/02/21/8-benefits-of-transcribing-captioning-videos/)}.
