---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
title: "Audio Description of Visual Information"   # Do not translate "title:". Do translate the text after "title:".
nav_title: "Audio Description" # A short title that is used in the navigation
doc-note-type: draft
lang: en   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2019-04-10   # Put the date of this translation YYYY-MM-DD (with month in the middle)
# translator: "@@"   # Replace @@ with name or names separated with a comma
# contributors: "@@"   # Replace @@ with name(s) or delete this line
permalink: /design-develop/media/description/   # Add the language shortcode to the end; for example /fundamentals/accessibility-intro/fr
ref: /design-develop/media/description/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'index.md'   # Add the language shortcode to the middle of the filename, for example index.fr.md
footer: >   # Translate all the words below, including "Date:" and "Editor:".
   <p> ... Tips References: <a href="https://dcmp.org/learn/227">Description Tip Sheet [offsite icon]</a> and <a href="http://www.descriptionkey.org/how_to_describe.html">How to Describe [offsite icon]</a>. ...</p>
navigation:
  previous: /design-develop/media/av-content/
  next:     /design-develop/media/captions/
---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page provides guidance on understanding and creating audio description of visual information for new and existing videos. (It does not apply to audio-only, such as podcasts.)

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

_Who:_ Audio description provides content to people who are blind and others who cannot see the video adequately.

_What:_ Audio description describes visual information needed to understand the content. It is usually narration added to the soundtrack.

_Example:_ [Video that includes audio description of the visual information (YouTube) {off-site icon}](https://www.youtube.com/watch?v=4qIordU8vT8)

<p style="text-align:center"><em>[optional image: blind person listening to video]</em></p>

### Terminology
{:.no_toc}

Web Content Accessibility Guidelinnes (WCAG) uses the term "audio description". It is called "described video" in some regions, such as Canada.

This page uses "described video" in some places as a shortened form of "a video that includes audio description of the visual information".

## Does My Media Need Description?

<div id="tree-ano" style="border: solid 1px #DDD; padding-bottom: 0; margin-bottom: 1em;">
  <p style="background:#FFF; padding: 5px 5px 5px 11px; font-weight:bold; margin: 0;">Audio-only (e.g., podcast):</p>
  <div style="background:#D9EDF7; padding: 5px 0 0 11px; margin-top:0;">
    <ul style="padding-bottom: 11px; padding-top: 0; margin-top: 0; margin-bottom: 0;">
      <li>For pre-recorded and live:
        <ul>
          <li>Description is <strong><em>not needed</em></strong> because there is no visual information.</li>
        </ul>
      </li>
    </ul>
  </div>
</div>

<div id="tree-video" style="border: solid 1px #DDD; padding-bottom: 0; margin-bottom: 1em;">
  <p style="background:#FFF; padding: 5px 5px 5px 11px; font-weight:bold; margin: 0;">Video:</p>
  <div style="background:#D9EDF7; padding: 5px 0 0 11px; margin-top:0;">
    <ul style="padding-bottom: 11px; padding-top: 0; margin-top: 0; margin-bottom: 0;">
      <li>For pre-recorded:
        <ul>
          <li>Description of important visual information is <em><strong>required</strong></em> to provide the information to people who are blind and listen to the video. It is in Web Content Accessibility Guidelines (<a href="/design-develop/media/planning/#standards">WCAG</a>) at Level A or AA.</li>
        </ul>
      </li>
      <li>For live:
        <ul>
          <li>Description of important visual information would be <strong><em>useful</em></strong> for people who are blind. It is not required to meet most minimum accessibility standards.</li>
        </ul>
      </li>
    </ul>
  </div>
</div>

## Audio Description Considerations

When accessibility is considered before videos are produced, it significantly cuts down on cost and effort to develop audio description. For some types of video (such as some training videos), description of the visual information can be seamlessly integrated by the speakers as the video is planned and created, and you don't need separate audio description, thus there is no additional cost.

To add audio description to _an existing video_, you'll likely **need skills and tools** to:
* write it
* narrate it
* record it
* integrate it in new audio and/or video files

Information for addressing audio description in _new videos_ is in the "Creating Audio and Video Content" page, [Plan for Audio Description of Visual Information section](/design-develop/media/av-content/#plan-for-audio-description-of-visual-information).

## What Description to Provide for My Video?

First, figure out these issues about your video content and timing:

* **Integrated** &mdash; For new videos, can the speakers describe the relevant visual information as the video is recorded? This works for well for some videos, such as presentations and instructional videos. For examples, see the "Creating Audio and Video Content" page, [Integrated Description section](/design-develop/media/av-content/#integrate-description).

<a id="space"> </a>
* **Space in audio** &mdash; Is there enough space in the main audio for the description? That is, are there sufficient pauses throughout the narration or speaking where the relevant description will fit? For example,
   * If the only description needed is at the beginning of the video where these is a text title and background music, then: Yes, there is enough space.
   * If the speaker talks continually without pausing, then: No, there is not enough space for description.

* **Media player support** &mdash; Does the media player, platform, or plug-in that you are using provide functionality for a separate audio track for description? Information about player functionality is in [Accessible Media Players](/design-develop/media/av-content/#integrate-description).

***Use the information from above to answer the following questions*** in order to determine how to provide audio description for your video.

<div id="tree-new" style="border: solid 1px #DDD; padding-bottom: 0; margin-bottom: 1em;">
  <p style="background:#FFF; padding: 5px 5px 5px 11px; font-weight:bold; margin: 0;">New videos:</p>
  <div style="background:#D9EDF7; padding: 5px 0 0 11px; margin-top:0;">
    <p>Can the speakers describe the visual information in the main audio?</p>
    <ul style="padding-bottom: 11px; padding-top: 0; margin-top:0; margin-bottom: 0;">
      <li>If yes, provide <strong>integrated description</strong>. No separate audio description is needed. </li>
      <li>If no, can you smoothly provide enough space in the main audio for the description? <em>And</em> will you use a media player that supports a separate audio track for the description?
        <ul>
          <li>If yes, provide  description in a <strong>separate audio file</strong>,<br>
            <em><strong>or</strong></em> provide a <strong>separate described  video</strong>. </li>
          <li>If no, provide a <strong>separate described  video</strong>. </li>
        </ul>
      </li>
    </ul>
  </div>
</div>

<div id="tree-existing" style="border: solid 1px #DDD; padding-bottom: 0;">
  <p style="background:#FFF; padding: 5px 5px 5px 11px; font-weight:bold; margin: 0;">Existing videos:</p>
  <div style="background:#D9EDF7; padding: 5px 0 0 11px; margin-top:0;">
    <p>Is there enough space in the main audio for the description? <em>And</em> will you use a media player that supports a separate audio track for the description?</p>
    <ul style="padding-bottom: 11px; padding-top: 0; margin-top:0; margin-bottom: 0;">
      <li>If yes, provide  description in a <strong>separate audio file</strong>,<br>
        <em><strong>or</strong></em> provide a <strong>separate described  video</strong>. </li>
      <li>If no, provide a <strong>separate described  video</strong>.</li>
    </ul>
  </div>
</div>

## Options for Creating Description

Depending on your video situation, do one of the options below &mdash; as determined from the "What Description to Provide for My Video?" section above.

### Creating Integrated Description

The process to develop a video with integrated description is basically:
1. When writing the script, make sure all relevant visual information is included. See [Tips for Writing Descriptions below](#writing) and examples in Accessible Audio and Video Content, [Integrate descriptionsection](/design-develop/media/av-content/#integrate-description))

Before finalizing the video, check to confirm that all relevant visual information is covered in the audio.

### Creating a Separate Described Video - If Descriptions Fit in Spaces

This applies if the descriptions do fit in the spaces, as described in _[Space in audio above](#space)_. It requires skills and software for audio recording and video editing. Depending on the player that you are using, you might need video software to regenerate the video.

The process to develop a separate audio file is basically:
1. Write out the descriptions. See [Tips for Writing Descriptions below](#writing).
2. Record the descriptions. See [Tips for Recording Descriptions below](#recording).
3. Create a new audio file by combining the original audio and the new description audio. See [Tips for Combining Audio Files below](#combining).
4. Provide the file(s):
* _**If**_ your player uses separate video and audio tracks,<br>you're done.
* _**If**_ your player uses a single video file that includes the audio,<br>generate the new described video with the audio file that you just created.

(Make sure on the web page where the video is available, the Audio Described version uses the correct version that you just created.)

### Creating a Separate Described Video - If Descriptions Do Not Fit in Spaces

If all the descriptions do **not** fit in the spaces _(as described in [Space in audio above](#space)_, you'll need to develop a separate audio file and also edit the visual track. This requires skills and software for audio recording, audio editing, and video editing.

The process to develop a separate audio file and edit the visual track is basically:
1. Write out the descriptions. See [Tips for Writing Descriptions below](#writing).
2. Record the descriptions. See [Tips for Recording Descriptions below](#recording).
3. Create a new audio file by combining the original audio and the new description audio. See [Tips for Combining Audio Files below](#combining).
4. Create a new video:
	* _**If**_ you have source video with longer scenes _(as described in Accessible Audio and Video Content, [Time for description section](/design-develop/media/av-content/#time-for-description))_, recut the scenes longer to fill in the visual space where you need to accommodate the time for the description.
	* _**If not or if you're adding to an existing video**_, you will need to leave a static image in the video while the description is playing in the audio. (For example, this video [need example] pauses at 00:00 for the audio description.)

(Make sure on the web page where the video is available, the Audio Described version uses the correct version that you just created.)

### Creating Description in a Separate Audio File Only

This requires skills and software for audio recording and audio editing.

_(Per above, this approach only works when there enough space in the main audio for the description, and the media player supports a separate audio track for the description.)_

The process to develop description in a separate audio file is basically:
1. Write out the descriptions. See [Tips for Writing Descriptions below](#writing).
2. Record the descriptions. See [Tips for Recording Descriptions below](#recording).
3. Provide synching data for the audio file … @@...
4. Provide a caption file of the description. [Example VTT file of audio description](#vtt)
5. Ensure the files are integrated with the player on the web page.

### Other Options
{:.no_toc}

* Audio Description via text track &mdash; "As of February 2019 when this Advisory technique was last reviewed by the Working Group, there is no native support in user agents for this technique. However, support is available via JavaScript polyfills." — [WCAG Technique H96](https://www.w3.org/TR/WCAG20-TECHS/H96.html) 
* Extended Audio Description with SMIL &mdash; The only markup-based method for providing extended audio descriptions is to use SMIL 3.0. Support for SMIL is very limited. Implementations would most likely require plug-ins and/or heavily customized approaches.
* Provide functionality for the video to pause for the description &mdash; This is not suggested in most cases because it requires extra coding and provides a less-than-optimum user experience.

{% include_cached excol.html type="start" id="tips" %}

## Tips

{% include_cached excol.html type="middle" %}

### Tips for Writing Descriptions {#writing}
{:.no_toc}

* Describe the visual elements that are important to understand what the video is communicating.
* Describe objectively, without interpretation, censorship, or comment.
* Write description in present tense, active voice, and in third-person narrative style.

More guidance on writing descriptions: [Description Tip Sheet [icon]](https://dcmp.org/learn/227) and [How to Describe [icon]](http://www.descriptionkey.org/how_to_describe.html).

### Tips for Recording Descriptions {#recording}
{:.no_toc}

* Use a voice, style, and delivery that is distinguishable from other voices used in the video.
* When recording a single file with timed descriptions, voice the descriptions at the same time as the visual content, or right before the visual content. Don't put the description after the visual content.
* See [guidance on audio content](/design-develop/media/av-content/#audio).

### Tips for Combining Audio Files {#combining}
{:.no_toc}

* Put descriptions at the same time as the visual content, or right before the visual content. Don't put the description after the visual content.

* When mixing the descriptions with the main audio, lower the main audio level when the description plays and raise the description audio level. When the description is finished playing, lower the description audio level and raise the main audio level to its normal setting. Repeat this process (known as "ducking") for every description instance.

{% include_cached excol.html type="end" %}


{::nomarkdown}
{% include box.html type="start" title="Example VTT file of audio description" class="" id="vtt" %}
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
{% include box.html type="end" %}
{:/}

