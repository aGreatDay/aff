---
date: '2025-05-16T13:50:01+02:00'
draft: true
title: ''
layout: hextra-home
---

{{< hextra/hero-badge >}}
  <div class="hx:w-2 hx:h-2 hx:rounded-full hx:bg-primary-400"></div>
  <span>Free, open source</span>
  {{< icon name="arrow-circle-right" attributes="height=14" >}}
{{< /hextra/hero-badge >}}

<div class="hx:mt-6 hx:mb-6">
{{< hextra/hero-headline >}}
  Build modern websites&nbsp;<br class="hx:sm:block hx:hidden" />with Markdown and Hugo
{{< /hextra/hero-headline >}}
</div>

<div class="hx:mb-12">
{{< hextra/hero-subtitle >}}
  Fast, batteries-included Hugo theme&nbsp;<br class="hx:sm:block hx:hidden" />for creating beautiful static websites
{{< /hextra/hero-subtitle >}}
</div>

<div class="hx:mb-6">
{{< hextra/hero-button text="Get Started" link="docs" >}}
</div>

<div class="hx:mt-6"></div>


{{< cards >}}
  {{< card link="../callout" title="Callout" icon="warning" >}}
  {{< card link="../callout" title="Card with tag" icon="tag" tag= "A custom tag" >}}
  {{< card link="/" title="No Icon" >}}
{{< /cards >}}

{{< cards >}}
  {{< card link="/" title="Image Card" image="image1.jpg" subtitle="Unsplash Landscape" >}}
  {{< card link="/" title="Local Image" image="image2.jpg" subtitle="Raw image under static directory." >}}
  {{< card link="/" title="Local Image" image="image3.webp" subtitle="Image under assets directory, processed by Hugo." method="Resize" options="600x q80 webp" >}}
{{< /cards >}}