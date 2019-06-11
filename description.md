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
navigation:
  previous: /design-develop/media/media-content/
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

#### Terminology

Audio description is called "described video" in some areas, such as Canada.

This page uses "described video" in some places as a shortened form of "a video that includes audio description of the visual information".

#### Scope

This page addresses common types of videos designed for the web such as instructional videos, training videos, recordings of presentations, and such. It does **not** address all the issues around full-feature movies, television shows, and such.

#### Audio Description Considerations

When accessibility is considered before videos are produced, it significantly cuts down on cost and effort to develop audio description. For some types of video (such as some training videos), description of the visual information can be seamlessly integrated by the speakers as the video is planned and created, and you don't need separate audio description, thus there is no additional cost.

To add audio description to an existing video, you'll likely **need skills and tools** to:
* write it
* narrate it
* record it
* integrate it in new audio and/or video files
&mdash; as described on this page.

## What Description to Provide for My Video?

#### Content and Timing Considerations
First, figure out these issues about your video content and timing:
* **Integrated** &mdash; For new videos, can the speakers describe the relevant visual information as the video is recorded? This works for well for some videos, such as presentations and instructional videos. For examples, see the "Creating Audio and Video Content" page, [Integrated Description section](@@).

* **Space in audio** &mdash; Is there enough space in the main audio for the description? That is, are there sufficient pauses throughout the narration or speaking where the relevant description will fit? For example,
   * If the only description needed is at the beginning of the video where these is a text title and background music, then: Yes, there is enough space.
   * I the speaker talks continually without pausing, then: No, there is not enough space for description.

* **Media player support** &mdash; Does the media player, platform, or plug-in that you are using provide functionality for a separate audio file? The Accessible Media Player pages lists [Support for Separate Audio Files](@@#support-for-separate-audio-files).

<div id="tree" style="background:#D9EDF7; border: solid 1px #999; padding: 5px;" markdown="1">

Use the information from above to answer the following questions in order to determine how to provide audio description for your video.

<h3 style="font-weight:bold; color:#000;">For New Videos:</h3>

* Can the speakers describe the visual information in the main audio?
	* **If yes**, provide integrated description. No separate audio description is needed.
	* **If no**, can you smoothly provide enough space in the main audio for the description? And will you use a media player that supports a separate audio track for the description?
		* **If yes**, provide description in a separate audio file, _**or**_ provide a separate described video.
		* **If no**, provide a separate described video.
		
<h3 style="font-weight:bold; color:#000;">For Existing Videos:</h3>

* Is there enough space in the main audio for the description? And will you use a media player that supports a separate audio track for the description?
	* **If yes**, provide description in a separate audio file, _**or**_ provide a separate described video.
	* **If no**, provide a separate described video.
	
</div>

#### Planning New Videos

Information for addressing audio description in new videos is in the "Creating Audio and Video Content" page, [Plan for Audio Description of Visual Information section](@@).

## Options

Depending on your video situation, do one of the options below &mdash; as determined from the "What Description to Provide for My Video?" section above.

### Creating Integrated Description

The process to develop a video with integrated description is basically:
1. When writing the script, make sure all relevant visual information is included. See [Tips for Describing – Writing below](http://@@).

Before finalizing the video, check to confirm that all relevant visual information is covered in the audio.

### Creating a Separate Described Video - If Descriptions Fit in Spaces

If the descriptions fit in the spaces _(as described in @@ above)_, you need to develop a separate audio file. This requires skills and software for audio recording and video editing. Depending on the player that you are using, you might need video software to regenerate the video.

The process to develop a separate audio file is basically:
1. Write out the descriptions. See [Tips for Describing - Writing below](http://@@).
2. Record the descriptions. See [Tips for Describing - Recording below](http://@@).
3. Create a new audio file by combining the original audio and the new description audio. See [Tips for Describing – Combining Audio Files below](http://@@).
4. Provide the file(s):
* _**If**_ your player uses separate video and audio tracks,<br>you're done.
* _**If**_ your player uses a single video file that includes the audio,<br>generate the new described video with the audio file that you just created.

(Make sure on the web page where the video is available, the Audio Described version uses the correct version that you just created.)

### Creating a Separate Described Video - If Descriptions Do Not Fit in Spaces

If all the descriptions do **not** fit in the spaces _(as described in @@ above)_, you'll need to develop a separate audio file and also edit the visual track. This requires skills and software for audio recording, audio editing, and video editing.

The process to develop a separate audio file and edit the visual track is basically:
1. Write out the descriptions. See [Tips for Describing - Writing below](http://@@).
2. Record the descriptions. See [Tips for Describing - Recording below](http://@@).
3. Create a new audio file by combining the original audio and the new description audio. See [Tips for Describing – Combining Audio Files below](http://@@).
4. Create a new video:
	* _**If**_ you have source video with longer scenes _(as described in @@ above)_, recut the scenes longer to fill in the visual space where you need to accommodate the time for the description.
	* _**If  not or you're adding to an existing video**_, you will need to leave a static image in the video while the description is playing in the audio. (For example, this video pauses at 00:00 for the audio description.)

(Make sure on the web page where the video is available, the Audio Described version uses the correct version that you just created.)

### Creating Description in a Separate Audio File Only

This requires skills and software for audio recording and audio editing.

_(Per above, this approach only works when there enough space in the main audio for the description, and the media player supports a separate audio track for the description.)_

The process to develop description in a separate audio file is basically:
1. Write out the descriptions. See [Tips for Describing – Writing below](http://@@).
2. Record the descriptions. See [Tips for Describing - Recording below](http://@@).
3. Provide synching data for the audio file … @@...
4. Provide a caption file of the description. [Example VTT file of audio description](http://@@)
5. Ensure the files are integrated with the player on the web page.

#### Other Options
_{include or not based on decisions in [Open Issues, Coverage of Options](https://www.w3.org/WAI/EO/wiki/Accessible_Media_Guide#Coverage_of_Options).}_

… description in text file…

… Another option is to provide functionality for the video to pause for the description. This is not suggested in most cases because it requires extra coding and provides a less-than-optimum user experience.

## Tips

#### Tips For Writing Descriptions

...

#### Tips for Recording Descriptions

...

#### Tips for Combining Audio Files
...
