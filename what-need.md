---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
title: "What Does My Video/Audio Need?"   # Do not translate "title:". Do translate the text after "title:".
nav_title: "What Does My Video/Audio Need?" # A short title that is used in the navigation
lang: en   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2019-04-10   # Put the date of this translation YYYY-MM-DD (with month in the middle)
# translator: "@@"   # Replace @@ with name or names separated with a comma
# contributors: "@@"   # Replace @@ with name(s) or delete this line
permalink: /design-develop/media-guide/what-need/   # Add the language shortcode to the end; for example /fundamentals/accessibility-intro/fr
ref: /design-develop/media-guide/what-need/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'index.md'   # Add the language shortcode to the middle of the filename, for example index.fr.md
footer: >   # Translate all the words below, including "Date:" and "Editor:". 
---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page helps you figure out if your specific video or audio needs captions, audio description, a basic transcript, or a descriptive transcript.

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

<p><em>For descriptions of captions, transcripts, audio description, sign language and other introductory information, please see: <a href="#intro">Making Video and Audio Accessible - Introduction</a>.</em></p>

{::nomarkdown}
{% include box.html type="start" title="From the Introduction:" class="" %}
{:/}

<p>Providing a descriptive transcript for videos (or basic transcript for audio-only) meets a wide range of accesibility needs.</p>
<p>To meet Web Content Accessibility Guidelines (WCAG) Level AA, <em>most</em> videos need to include:</p>
<ul>
  <li>Captions (<a href="https://www.w3.org/WAI/WCAG21/Understanding/captions-prerecorded">WCAG Success Criteria 1.2.2</a>)</li>
  <li>Audio Description (<a href="https://www.w3.org/WAI/WCAG21/Understanding/audio-description-prerecorded">WCAG Success Criteria 1.2.5</a>)</li>
</ul>
<p>Requirements are different based on the content and whether they are live or pre-recorded.</p>

{::nomarkdown}
{% include box.html type="end" %}
{:/}

<p>Web Content Accessibility Guidelines (<a href="https://www.w3.org/WAI/standards-guidelines/wcag/">WCAG</a>) guidelines are explained in <a href="@@">WCAG Media Standards</a>.<br>This page describes the optimum for pre-recorded media to meet users' needs.</p>

## Providing a Descriptive Transcript for Your Videos
<p>Descriptive transcripts are not required to meet WCAG Level AA. However, they:</p>
<ul>
  <li>meet a wide range of accessibility needs, and are needed in order for videos to be accessible to people who are &quot;Deaf-blind&quot;</li>
  <li>provide <a href="@@#benefits">additional benefits</a> for users <em>without</em> disabilities, and for your organization (for example, <abbr title="search engine optimization"> SEO</abbr>)</li>
  <li><strong>are easy and inexpensive to develop</strong> using captions and audio description that you already have to meet Level AA</li>
</ul>

## Deciding How to Meet User Needs
<p>The wording below helps you think about what users need in order to understand the information that you are presenting in the video or audio, including users who cannot hear it or see it. We've included &quot;who are Deaf&quot; and &quot;who are blind&quot; to help you understand what to provide. However, keep in mind that many people who <em>can</em> see and hear will also benefit from these, as described in <a href="@@#@@">Additional Benefits</a>.</p>

### What does my video need to be accessible?
<ul>
  <li><strong>Is there speech or other audio</strong> that is needed to understand the content?
    <ul>
      <li> If yes,
        <ul>
          <li><strong>[_] Captions</strong> that provide the information to people who are Deaf or hard of hearing and want to watch the video. (<a href="https://www.w3.org/WAI/WCAG21/Understanding/captions-prerecorded">A 1.2.2</a>)</li>
          <li><strong>[_] Transcript of audio information </strong> that provides the information to people who don't want to watch the video. (<a href="https://www.w3.org/TR/UNDERSTANDING-WCAG20/media-equiv-text-doc">AAA 1.2.8</a>) <em>(This transcript is the same text from the captions file, in a different format.)</em></li>
        </ul>
      </li>
      <li>If no, inform users.</li>
    </ul>
  </li>
  <li><strong>Is there visual information</strong> that is needed to understand the content?
    <ul>
      <li> If yes,
        <ul>
          <li><strong>[_] Audio description</strong> that provides the information to people who are blind and want to listen to the video. (<a href="https://www.w3.org/WAI/WCAG21/Understanding/audio-description-prerecorded">AA 1.2.5</a>)</li>
          <li><strong>[_] Descriptive transcript</strong> that provides the information to people who are blind and Deaf (&quot;Deaf-blind&quot;). (<a href="https://www.w3.org/TR/UNDERSTANDING-WCAG20/media-equiv-text-doc">AAA 1.2.8</a>) <em>(If you have a descriptive transcript, you do not need an additional transcript from the previous question.)</em></li>
        </ul>
      </li>
      <li>If no, inform users.</li>
    </ul>
  </li>
</ul>

### What does my audio-only (e.g., podcast) need to be accessible?
<ul>
  <li><strong>[_] Captions</strong> that provide the information to people who are hard of hearing and want to listen the audio. (<a href="https://www.w3.org/WAI/WCAG21/Understanding/captions-prerecorded">A 1.2.2</a>)</li>
  <li><strong>[_] Transcript of audio information </strong> that provides the information to people who don't want to listen to the audio or want an interactive transcript. (<a href="https://www.w3.org/TR/UNDERSTANDING-WCAG20/media-equiv-text-doc">AAA 1.2.8</a>)</li>
</ul>

## Informing Users When None Needed
<p> If your media does not need captions (because there is no substantive audio content) or does not need audio description (because there is no substantive visual content), it's good to let users know that. Otherwise, they might think that you accidentally forgot to provide it. For example:</p>
<ul>
  <li>Captions not needed: The only sound with this video is background music. There is no speaking.</li>
  <li>Audio description not needed: This video does not include audio description because the visuals only support what is spoken; the visuals do not provide additional information.</li>
</ul>

<p style="text-align:center"><strong>[ < Previous &nbsp;&nbsp;&nbsp; Next > ]</strong></p>
