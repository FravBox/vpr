# Vidding Photosensitivity Relay
<img title="Enby, a pink octopus with sunglasses, by artist James Eden" src="img/enby_octopus_by_jameseden.png" height="500px">

 Vidding is the name for the hobby of editing fan-videos. Photosensitive individuals are often overlooked when creating and sharing content, making it hard for them to find videos that are safe to view. The VPR system seeks to change this by offering information on how to relay content advisories for common photosensitive risks.

If you'd like to read more about what can cause seizures to further help rate your video, please see [WCAG](https://www.w3.org/TR/UNDERSTANDING-WCAG20/seizure-does-not-violate.html) (Web content accessibility guidelines) and/or [Prodicle's Photosensitivity Prevention Best Practice Guideline - Production](https://web.archive.org/web/20211130113204/https://help.prodicle.com/hc/en-us/articles/360044218174-Photosensitivity-Prevention-Best-Practice-Guideline-Production) (TODO: find a more reliable url or copy the content elsewhere as it's no longer public.)

This page is designed as a community-based collaboration. You can submit issues and pull requests to [the GitHub repository here]({{ site.github.repository_url }}).

<div class="notice">TL;DR: It's like a CW, but for photosensitivities</div>

<a class ="title" href="{{ site.github.baseurl }}/risks.html">Risk Factors</a>
Collloquially considered "triggers," these are the types of items associated with physical health risks:
  <ul>
{% for risk in site.risks %}
    <li><a href="{{site.github.baseurl}}/risks.html#{{ risk.shortcode }}">{{ risk.name }}</a></li>
{% endfor %}
  </ul>

<a href="{{ site.github.baseurl }}/writing.html" class="title">How to write VPR</a>
TL;DR: Briefly describe what visually happens in the video. Use timestamps if risk factors are isolated to one section.
Make this visible somewhere before the video starts playing.
  <ul>
{% for writing in site.writing %}
    <li><a href="{{site.github.baseurl}}/writing.html#{{ writing.shortcode }}">{{ writing.name }}</a></li>
{% endfor %}
  </ul>

  <a href="{{ site.github.baseurl }}/access.html" class="title">Increasing accessibility for photosensitive individuals</a>
More solutions to allow people with photosensitivities access to more content.
  <ul>
{% for access in site.access %}
    <li><a href="{{site.github.baseurl}}/access.html#{{ access.shortcode }}">{{ access.name }}</a></li>
{% endfor %}
  </ul>

    <a href="{{ site.github.baseurl }}/faq.html" class="title">Frequently Asked Questions (FAQ)</a>
  <ul>
{% for faq in site.faq %}
    <li><a href="{{site.github.baseurl}}/faq.html#{{ faq.shortcode }}">{{ faq.name }}</a></li>
{% endfor %}
  </ul>