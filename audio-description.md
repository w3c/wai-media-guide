---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
title: "Creating Audio Description of Visual Information"   # Do not translate "title:". Do translate the text after "title:".
nav_title: "Audio Description" # A short title that is used in the navigation
lang: en   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2019-04-10   # Put the date of this translation YYYY-MM-DD (with month in the middle)
# translator: "@@"   # Replace @@ with name or names separated with a comma
# contributors: "@@"   # Replace @@ with name(s) or delete this line
permalink: /design-develop/media-guide/audio-description/   # Add the language shortcode to the end; for example /fundamentals/accessibility-intro/fr
ref: /design-develop/media-guide/audio-description/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'index.md'   # Add the language shortcode to the middle of the filename, for example index.fr.md
footer: >   # Translate all the words below, including "Date:" and "Editor:". 
---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page provides guidance on creating audioe description for new and existing videos.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include toc.html type="start" title="Page Contents" %}
{:/}

- This will be replaced by an automatically generated TOC when using Markdown formatting.
{:toc}

{::nomarkdown}
{% include toc.html type="end" %}
{:/}

{::nomarkdown}
{% include box.html type="start" title="From the Introduction" class="" %}
{:/}

Audio description provides content to people who are blind and others who cannot see the video adequately.

Audio description describes visual information needed to understand the content. It is usually narration added to the soundtrack.

For some types of video (such as some training videos), description of the visual information can be seamlessly integrated by the speakers as the video is planned and created, and you don't need separate audio description.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include box.html type="start" title="From Managing Development" class="" %}
{:/}

When accessibility is considered before videos are produced, it significantly cuts down on cost and effort to develop audio description.

For some videos, description of the visual information can be seamlessly integrated into the main video without any additional cost. 

For example, instead of the speaker saying: <q>As you can see on this chart, sales increased significantly from the first quarter to the second quarter.</q> The speaker can say: <q>This chart shows that sales increased from 1 million in the first quarter to 1.3 million in the second quarter.</q>

If you have an existing video and you want to add audio description, you'll need:
... skills to write it, speak it, integrate it in new audio and video files...

{::nomarkdown}
{% include box.html type="end" %}
{:/}

## Terminology

Audio description is called "described video" in some areas, such as Canada.

This page uses "described video" in some places as a shortened form of "a video that includes audio description of the visual information".

## Scope

This page addresses common types of videos designed for the web such as instructional videos, training videos, recordings of presentations, and such.

It does **not** address all the issues around full-feature movies, television shows, and such.

## What Description to Provide for My Video?

### Content and Timing Considerations
First, figure out these issues about your video content and timing:
* **Integrated** &mdash; Can the speakers describe the relevant visual information as the video is recorded? This works for well for some videos, such as presentations and instructional videos. For example:

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

* **Space in audio** &mdash; Is there enough space in the main audio for the description? That is, are there sufficient pauses throughout the narration or speaking where the relevant description will fit? For example, if the only description is needed is at the beginning of the video where these is a title and background music, then: Yes, there is enough space. Or if the speaker talks continually without pausing, then: No, there is not enough space for description.

* **Media player support** &mdash; Does the media player you are using provide functionality for a separate audio file? Or, will you use a plug-in or other method to provide it? Player and platforms that support separate audio description files: Brightcove, Kaltura, Oz Player, ?Vidyard. (Able Player facilitates showing a separate video with audio description.) Plug-ins: 3Play Plugin, JW Player, with plug-in (works in IE11 & Safari, other browsers require Flash), VideoJS with Plug-in (works in IE11 & Safari, other browsers require Flash).

Use this information to answer the following questions in order to determine how to provide audio description for your video.

### For New Videos
* Can the speakers describe the visual information in the main audio?
	* If yes, provide integrated description. No separate audio description is needed.
	* If no, can you smoothly provide enough space in the main audio for the description? And will you use a media player that supports a separate audio track for the description?
		* If yes, provide description in a separate audio file, _**or**_ provide a separate described video.
		* If no, provide a separate described video.

### For Existing Videos
* Is there enough space in the main audio for the description? And will you use a media player that supports a separate audio track for the description?
	* If yes, provide description in a separate audio file, _**or**_ provide a separate described video.
	* If no, provide a separate described video.

## Planning New Videos

### Integrated Description
For many videos, the best way to handle audio description is not to need it at all &mdash; that is, all the visual information that users need to understand the content is integrated in the main audio. When planned in advance, this is fairly simple for many types of videos on the web, such as presentations and instructional videos. (Example above under [Content and Timing Considerations](#@@).)
 
**If you develop your video with integrated description, you don't need to bother with any of the other timing or developing options on this page! You're done.**

### Timing for Description

For some types of videos, the description of the visual information cannot be smoothly handled by the speakers and narrator in the main video, because it would make the default video too much longer or more cumbersome. In that case, you will have the description separate. You can make the described version smoother by planning for the description.

Where the description is fairly short, plan space in the audio for the description.

Where the description is longer that you want to leave space in the main audio, you can record extra time in the scene to accommodate the description without having to pause the scene. That is, the same scene is shown with a little longer at the beginning or the end of it. For example:

<table>
  <tr>
    <th scope="col">Narration</th>
    <th scope="col">Main Video Scene Duration</th>
    <th scope="col">Described Video Scene Duration</th>
    <th scope="col">Description</th>
  </tr>
  <tr>
    <td><q>Captions are also handy for people who  want to watch video in loud environments.</q></td>
    <td>3&nbsp;seconds</td>
    <td>7&nbsp;seconds</td>
    <td>A man is watching the captioned video with a  group of people chatting away next to him.</td>
  </tr>
  <tr>
    <td><q>Or where you need to be very, very quiet.</q></td>
    <td>2&nbsp;seconds</td>
    <td>5&nbsp;seconds</td>
    <td>Turns out that they are in a library. The group  is shushed by the librarian.</td>
  </tr>
</table>


An example of this is the [Web Accessibility Perspectives: Video Captions](https://www.w3.org/WAI/perspective-videos/captions/) video. The main video is 48 seconds long. The described version is 1 minute and 18 seconds long, yet there are no pauses in the visual aspect of the video.

## Developing Integrated Description

The process to develop a video with integrated description is basically:
1. When writing the script, make sure all relevant visual information is included. See [Tips for Describing – Writing below](http://@@).

Before finalizing the video, check to confirm that all relevant visual information is covered in the audio.

**That's it! You don't need to bother with any of the developing options below.**

## Developing Description in a Separate Audio File Only

This requires skills and software for audio recording and audio editing.

_(Per above, this approach only works when there enough space in the main audio for the description, and the media player supports a separate audio track for the description.)_

The process to develop description in a separate audio file is basically:
1. Write out the descriptions. See [Tips for Describing – Writing below](http://@@).
2. Record the descriptions. See [Tips for Describing - Recording below](http://@@).
3. Provide synching data for the audio file … @@...
4. Provide a caption file of the description. [Example VTT file of audio description](http://@@)
5. Ensure the files are integrated with the player on the web page.

## Developing a Separate Described Video

### If Descriptions Fit in Spaces

If the descriptions fit in the spaces _(as described in @@ above)_, you need to develop a separate audio file. This requires skills and software for audio recording and video editing. Depending on the player that you are using, you might need video software to regenerate the video.

The process to develop a separate audio file is basically:
1. Write out the descriptions. See [Tips for Describing - Writing below](http://@@).
2. Record the descriptions. See [Tips for Describing - Recording below](http://@@).
3. Create a new audio file by combining the original audio and the new description audio. See [Tips for Describing – Combining Audio Files below](http://@@).
4. Provide the file(s):
* _**If**_ your player uses separate video and audio tracks,<br>you're done.
* _**If**_ your player uses a single video file that includes the audio,<br>generate the new described video with the audio file that you just created.

(Make sure on the web page where the video is available, the Audio Described version uses the correct version that you just created.)

### If Descriptions Do Not Fit in Spaces

If all the descriptions do **not** fit in the spaces _(as described in @@ above)_, you'll need to develop a separate audio file and also edit the visual track. This requires skills and software for audio recording, audio editing, and video editing.

The process to develop a separate audio file and edit the visual track is basically:
1. Write out the descriptions. See [Tips for Describing - Writing below](http://@@).
2. Record the descriptions. See [Tips for Describing - Recording below](http://@@).
3. Create a new audio file by combining the original audio and the new description audio. See [Tips for Describing – Combining Audio Files below](http://@@).
4. Create a new video:
	* _**If**_ you have source video with longer scenes _(as described in @@ above)_, recut the scenes longer to fill in the visual space where you need to accommodate the time for the description.
	* _**If  not or you're adding to an existing video**_, you will need to leave a static image in the video while the description is playing in the audio. (For example, this video pauses at 00:00 for the audio description.)

(Make sure on the web page where the video is available, the Audio Described version uses the correct version that you just created.)

## Other Options
_{include or not based on decisions in [Open Issues, Coverage of Options](https://www.w3.org/WAI/EO/wiki/Accessible_Media_Guide#Coverage_of_Options).}_

… description in text file…

… Another option is to provide functionality for the video to pause for the description. This is not suggested in most cases because it requires extra coding and provides a less-than-optimum user experience.  

<p style="text-align:center"><strong>[ < Previous &nbsp;&nbsp;&nbsp; Next > ]</strong></p>

