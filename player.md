---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
title: "Accessible Media Players"   # Do not translate "title:". Do translate the text after "title:".
nav_title: "Media Player" # A short title that is used in the navigation
doc-note-type: draft
lang: en   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2019-04-10   # Put the date of this translation YYYY-MM-DD (with month in the middle)
# translator: "@@"   # Replace @@ with name or names separated with a comma
# contributors: "@@"   # Replace @@ with name(s) or delete this line
permalink: /design-develop/media/player/   # Add the language shortcode to the end; for example /fundamentals/accessibility-intro/fr
ref: /design-develop/media/player/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'index.md'   # Add the language shortcode to the middle of the filename, for example index.fr.md
footer: >   # Translate all the words below, including "Date:" and "Editor:". 
navigation:
  previous:     /design-develop/media/sign-languages/
---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page provides information about media players and accessibility.

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

_The media player is only one aspect of making audio and video accessible. For more, see [Making Video and Audio Accessible - Introduction](http://@@)._

## Skills and Tools

Setting up an accessible media player requires HTML 5 skills.

## HTML 5

HTML 5 lets you embed audio and video with the ```<audio>```, ```<video>```, and ```<track>``` elements. There are JavaScript APIs for controlling them. Several resources on the web provide guidance on embedding audio and video in HTML5. For example, [Video and audio content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content) and [```<video>```: The Video Embed element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video).

Modern browsers will provide a default player &mdash; usually within the web page, or with the QuickTime player on iPhones. These default players have different user interfaces, and most have **limited functionality** to support accessibility.

**Rather than coding all the things needed to make a player support accessibility, most organizations choose to use an existing player with good accessibility support.**

## Media Player Support for Accessibility

Accessible media players provide a user interface that works without a keyboard, through speech interface, and by screen reader users. They audio description, captions, and transcripts. _{@@ how much to say here???...functionality for users to change volume, speed, navigate through the media, modify captions font size, spacing, font...}_
 More details are in the [Media Accessibility User Requirements document](https://www.w3.org/TR/media-accessibility-reqs/) _{@@ include that link or not because that's much more info than most people really need here}_.

There are players developed specifically for accessibility. Some are free, open source and some are commercial.

The following resource lists accessibility support in several players: **...[old Google Doc version](https://docs.google.com/spreadsheets/d/1QJVcXx5hTWYBcJbHJD3DrL3hSFVbfy1VQFyADMtrDFY/edit?pli=1#gid=0), [GitHub version though also out-of-date](http://kensgists.github.io/apt/)...** _{@@ does someone want to step up to see if they can help get this information active and updated?}_

Each media player provides documentation of the steps to set it up in a web page. For example [AblePlayer Setup Steps](setup-step-1-use-html5-doctype).


