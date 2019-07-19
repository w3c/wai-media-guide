---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.

title: "Accessible Audio and Video Content"   # Do not translate "title:". Do translate the text after "title:".
nav_title: "Audio & Video Content" # A short title that is used in the navigation
doc-note-type: draft

lang: en   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2019-04-10   # Put the date of this translation YYYY-MM-DD (with month in the middle)
# translator: "@@"   # Replace @@ with name or names separated with a comma
# contributors: "@@"   # Replace @@ with name(s) or delete this line

permalink: /design-develop/media/av-content/   # Add the language shortcode to the end; for example /fundamentals/accessibility-intro/fr
ref: /design-develop/media/av-content/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'index.md'   # Add the language shortcode to the middle of the filename, for example index.fr.md

resource:
  ref: /design-develop/media/
navigation:
  previous: /design-develop/media/planning/
  next:     /design-develop/media/description/

footer: >   # Translate all the words below, including "Date:" and "Editor:". 

---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page addresses accessibility considerations for planning and producing video and audio content.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::options toc_levels="2,3" /}
{::nomarkdown}
{% include toc.html type="start" title="Page Contents" %}
{:/}

- This will be replaced by an automatically generated TOC when using Markdown formatting.
{:toc}

{::nomarkdown}
{% include toc.html type="end" %}
{:/}

## Introduction
{:.no_toc}

This page introduces things to consider when planning, scripting, storyboarding, recording, and producing audio and video.

Some are indicated as Web Content Accessibility Guidelines ([WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/)) requirements. Others are good practice.

## Audio

### Create high-quality audio – _recording setup_

* Use high-quality microphone(s) and recording software.
* When feasible, record in a room that is isolated from all external sounds.
* Avoid rooms with hard surfaces, such as tile or wood floors.

### Use low background audio – _recording, post-production_ (WCAG AAA)

When the main audio is a person speaking and you have background music, set the levels so people with hearing or cognitive disabilities can easily distinguish the speaking from the background.

Specifically, make the background sounds at least 20 decibels lower than the foreground speech content (with the exception of occasional sounds that last for only one or two seconds).

<span style="color:#585858; font-style:italic;">More information is in [Understanding Success Criterion 1.4.7: Low or No Background Audio (AAA)](https://www.w3.org/WAI/WCAG21/Understanding/low-or-no-background-audio.html).</span>

### Speak clearly – _speakers_

Speak clearly. Speak as slowly as appropriate. This will enable listeners to understand better, and make the timing better for captions and sign language.

### Give people time to process information – _speakers, post-production_

Pause between topics.

### Use clear language – _script_

Avoid or explain jargon, acronyms, and idioms. For example, expressions such as “raising the bar” can be interpreted literally by some people with cognitive disabilities and can be confusing.

### Provide redundancy for sensory characteristics – _script_ (WCAG A)

Make your information work for people who cannot see and/or cannot hear.

For example, instead of saying:
<blockquote>Attach this to the green end.</blockquote>
Say:
<blockquote>Attach the small ring to the green end, which is the larger end.</blockquote>

<span style="color:#585858; font-style:italic;">More information that primarily addresses web pages, yet is relevant to audio and video, is in [Understanding Success Criterion 1.3.3: Sensory Characteristics (A)](https://www.w3.org/WAI/WCAG21/Understanding/sensory-characteristics.html).</span>

## Video

### Avoid causing seizures – _storyboarding, post-production_ (WCAG A)

Avoid anything that flashes more than three times in any one second period. 

<span style="color:#585858; font-style:italic;">More information is in [Understanding Success Criterion 2.3.2: Three Flashes (AAA)](https://www.w3.org/WAI/WCAG21/Understanding/three-flashes.html) and [Understanding Success Criterion 2.3.1: Three Flashes or Below Threshold (A)](https://www.w3.org/WAI/WCAG21/Understanding/three-flashes-or-below-threshold.html)</span>

### Consider speaker visibility – _storyboarding, recording, post-production_

Some people use mouth movement to help understand spoken language. When feasible, ensure that the speaker's face is visible and in good light.

### Make overlay text readable – _storyboarding, post-production_ (WCAG AA, AAA)

For any text, consider the font family, size, and contrast between the text and background.

<span style="color:#585858; font-style:italic;">More information is in [Understanding Success Criterion 1.4.3: Contrast (Minimum) (AA)](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum.html) and [Understanding Success Criterion 1.4.6: Contrast (Enhanced) (AAA)](https://www.w3.org/WAI/WCAG21/Understanding/contrast-enhanced).</span>

### Plan for audio description of visual information – _storyboarding, recording_

_Audio description_ provides content to people who are blind and others who cannot see the video adequately. It describes the visual information needed to understand the content.

Plan to either:
* Integrate description of the visual information that users need to understand into the main audio content,<br>_**or**_
* Record extra time for scenes that need description of the visual information.

#### Integrate description

For many videos, the best way to handle audio description is not to need it at all &mdash; that is, all the visual information that users need to understand the content is integrated in the main audio. When planned in advance, this is fairly simple for many types of videos on the web, such as presentations and instructional videos. For example:

<table>
  <tr>
    <th scope="col"><svg aria-label="Wrong" class="icon-ex-circle "><use xlink:href="/WAI/assets/images/icons.svg#icon-ex-circle"></use></svg> Instead of the speaker saying:</th>
    <th scope="col"><svg aria-label="OK" class="icon-check-circle "><use xlink:href="/WAI/assets/images/icons.svg#icon-check-circle"></use></svg> The speaker can say:</th>
  </tr>
  <tr>
    <td>As you can see on this chart, sales increased significantly from the first quarter to the second quarter.</td>
    <td>This chart shows that sales increased significantly, from 1 million in the first  quarter to 1.3 million in the second quarter.</td>
  </tr>
  <tr>
    <td>Whip the mixture until it looks like this.</td>
    <td>Whip the mixture until the oil, vinegar, and spices are well combined.</td>
  </tr>
  <tr>
    <td>Attach this to the green end.</td>
    <td>Attach the small ring to the green end, which is the larger end.</td>
  </tr>
</table>

Guidance on what to include is in the "Creating Audio Description of Visual Information" page, [Tips for Writing Description section](/design-develop/media/description/#tips-for-writing-description).

#### Time for description

For some types of videos, the description of the visual information cannot be smoothly handled by the speakers in the main video, because it would make the default video much longer or more cumbersome. For those videos, the description will be separate.

Where the description is fairly short, plan space in the audio to add the description.

Where the description is longer that you want to leave space in the main audio, you can record extra time in the scene to accommodate the description without having to pause the scene. That is, the same scene is shorter in the main video. In the described version, that same scene is a little longer at the beginning or the end of it. For example:

<table>
  <tr>
    <th scope="col">Narration</th>
    <th scope="col">Main Video Scene Duration</th>
    <th scope="col">Described Video Scene Duration</th>
    <th scope="col">Description</th>
  </tr>
  <tr>
    <td><q>Captions are also handy for people who want to watch video in loud environments.</q></td>
    <td>3&nbsp;seconds</td>
    <td>7&nbsp;seconds</td>
    <td>A man is watching the captioned video with a group of people chatting away next to him.</td>
  </tr>
  <tr>
    <td><q>Or where you need to be very, very quiet.</q></td>
    <td>2&nbsp;seconds</td>
    <td>5&nbsp;seconds</td>
    <td>Turns out that they are in a library. The group is shushed by the librarian.</td>
  </tr>
</table>

An example of this is the [Web Accessibility Perspectives: Video Captions](https://www.w3.org/WAI/perspective-videos/captions/) video. The main video is 48 seconds long. The described version is 1 minute and 18 seconds long, yet there are no pauses in the visual aspect of the video.

#### More about audio description

More information is in the next page of this resource: [Audio Description of Visual Information](/design-develop/media/description/).
