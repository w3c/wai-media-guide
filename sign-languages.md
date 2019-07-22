---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.

title: "Sign Languages"   # Do not translate "title:". Do translate the text after "title:".
nav_title: "Sign Languages" # A short title that is used in the navigation
doc-note-type: draft

lang: en   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2019-04-10   # Put the date of this translation YYYY-MM-DD (with month in the middle)
# translator: "@@"   # Replace @@ with name or names separated with a comma
# contributors: "@@"   # Replace @@ with name(s) or delete this line

permalink: /design-develop/media/sign-languages/   # Add the language shortcode to the end; for example /fundamentals/accessibility-intro/fr
ref: /design-develop/media/sign-languages/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'index.md'   # Add the language shortcode to the middle of the filename, for example index.fr.md

resource:
  ref: /design-develop/media/
navigation:
  previous: /design-develop/media/transcribing/
  next:     /design-develop/media/player/

footer: >   # Translate all the words below, including "Date:" and "Editor:". 

---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page provides guidance on understanding and creating sign language interpretation for audio and video media.

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

Sign languages use hand and arm movements, facial expressions, and body positions to convey meaning.

Sign language is the native language of many people are Deaf. Some do not read or understand written language well &mdash; especially at the speed of most captions.

Not everyone who is Deaf knows sign languages, especially if they became Deaf later in life.

Sign languages are different across regions and countries. For example, American Sign Language (ASL), British Sign Language (BSL), and Auslan (Australian Sign Language) are all different.

There are some efforts to provide automatic sign language from text; however, avatars that simulate sign language interpretation are not robust enough to be adequate.

## Standards Requirements

Sign language is not required by most policies.

Sign language is in the WCAG standard at Level AAA. _(The Planning page of this resource introduces the [WCAG Standard](https://wai-media-guide.netlify.com/design-develop/media/planning/#wcag-standard).)_

## Skills and Tools

To include sign language alternatives, you will need people, skills, and tools to:
* do the sign language interpretation
* record it
* edit it in/with the audio or video file

## Example

Example sign language in video: [NHS 111 British Sign Language (BSL) Advert (YouTube)[offsite icon]](https://www.youtube.com/watch?v=TCq3ru9HQSc){% include video-link.html class="default" href="https://www.youtube.com/watch?v=TCq3ru9HQSc" src="/content-images/wai-media-guide/sign-example.jpg" %}

## Creating Sign Language Alternatives

Use colors that are easy to distinguish - _planning, recording_
: Usually it is best if the background and the signer’s clothing are solid colors that contrast with their skin tone. That way their hands and face are easier to see.

Use good lighting - _planning, recording_
: Ensure good lighting to help make the signer clearly visible.

Capture the full signing space - _recording_
: For most sign languages the signing space extends from well below the waist to above the head and at least an elbow width to each side.

Ensure the signer is large enough - _post-production_
: Viewers need to be able to clearly see all movements and facial expressions.

Avoid obscuring important content - _post-production_
: Position the signer to avoid obscuring important information in the video. The signer is usually at the bottom right. If your video has information such as a news ticker at the bottom, position the signer above that.
: Ideally when the video was made, the position of the signer was planned for, as noted in another page of this resource: [Plan for sign language – storyboarding, recording](/design-develop/media/av-content/#plan-for-sign-language--storyboarding-recording).
{:.paragraph-like}

There are resources on the web that provide additional guidance on creating sign language alternatives. For example:
* [Sign Language Interpretation in HBBTV (PDF)[offsite icon]](http://pagines.uab.cat/hbb4all/sites/pagines.uab.cat.hbb4all/files/sign_language_interpreting_in_hbbtv.pdf) includes specific guidance on aspects such as working with sign language interpreters and types of onscreen presentation
* Guidelines for the Production of Signing Books includes [Sign language presentation [offsite icon]](http://www.sign-lang.uni-hamburg.de/signingbooks/deliver/d31/deliv_31_part3-2.html#3.2.2.6) and [Editing [offsite icon]](http://www.sign-lang.uni-hamburg.de/signingbooks/sbrc/grid/d71/guide13.htm)
