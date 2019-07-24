---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.

title: "Accessible Media Players"   # Do not translate "title:". Do translate the text after "title:".
title_html: '<img src="/content-images/wai-media-guide/player.png" alt="" class="" style="float: right; height: 2em;">Accessible Media Players'
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
   path: 'player.md'   # Add the language shortcode to the middle of the filename, for example index.fr.md

resource:
  ref: /design-develop/media/
navigation:
  previous:     /design-develop/media/sign-languages/
 
  
footer: >   # Translate all the words below, including "Date:" and "Editor:". 

---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page provides information about accessible media players.

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

## Introduction

Modern browsers provide a default media player. Most have limited functionality to support accessibility.

Rather than coding all the things needed to make a player support accessibility, most organizations choose to use an existing player with good accessibility support.

There are players developed specifically for accessibility. Some are free, open source and some are commercial.

## Skills Needed {#skills}

Using an existing media player developed for accessibility requires moderate HTML skills.

Developing your own accessible media player requires advanced HTML and JavaScript skills.

## Player Accessibility Functionality

Accessible media players provide a user interface that works without a mouse, through speech interface, when the page is zoomed larger, and by screen reader users. For example, media players need to:
* Support captions
* Provide access to audio description of visual information and to sign language
* Provide keyboard support ([in Understanding WCAG: Keyboard Accessible](https://www.w3.org/WAI/WCAG21/Understanding/keyboard-accessiblel))
* Provide clear labels ([in Understanding WCAG: Labels or Instructions](https://www.w3.org/WAI/WCAG21/Understanding/labels-or-instructions), [in Understanding WCAG: Info and Relationships](https://www.w3.org/WAI/WCAG21/Understanding/info-and-relationships))
* Make the keyboard focus indicator visible ([in Understanding WCAG: Focus Visible](https://www.w3.org/WAI/WCAG21/Understanding/focus-visible))

Media players can provide additional accessibility functionality such as:
* Changing the speed of the video
* Setting how captions are displayed (e.g., text size and colors)
* Interactive transcripts

Interactive transcripts use the captions file. Interactive transcripts highlight text phrases as they are spoken. Users can select text in the transcript and go to that point in the video.

<img src="{{ "/content-images/wai-media-guide/interactive-transcript.png" | relative_url }}" alt="">

More details on player accessibility functionalty are in a separate document: [Media Accessibility User Requirements](https://www.w3.org/TR/media-accessibility-reqs/).

## Existing Players

There is information online indicating the accessibility of media players. For example, [Web-Based Media Player Accessibility Comparison Table {% include_cached icon.html name="external" %}](http://kensgists.github.io/apt/).

Each media player provides documentation of the steps to set it up in a web page. For example, [AblePlayer Setup Steps {% include_cached icon.html name="external" %}](https://ableplayer.github.io/ableplayer/#setup-step-1-use-html5-doctype).
