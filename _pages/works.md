---
permalink: /works/
defaults:
   # _pages
  - scope:
      path: ""
      type: pages
    values:
      layout: single
      author_profile: true

feature_row:
  - image_path: /assets/images/eoegalleryicon.jpg
    alt: "Edge of Eternity"
    title: "Edge of Eternity Japan Edition"
    excerpt: "Edge of Eternity ([© 2021 Plug In Digital](https://plugindigital.com/ )) game localization & release planning, including full Japanese voiceover work."
feature_row2:
  - image_path: /assets/images/evolandgalleryicon.jpg
    alt: "Evoland Legendary Collection"
    title: "Evoland Legendary Collection Japan Digital Edition"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/plaguetale1galleryicon.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/shantae7sirensgalleryicon.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row5:
  - image_path: /assets/images/snowrunnergalleryicon.jpg
    alt: "placeholder"
    title: "placeholder"
    excerpt: "placeholder"
feature_row6:
  - image_path: /assets/images/tfcgalleryicon.jpg
    alt: "placeholder"
    title: "placeholder"
    excerpt: "placeholder"
---

{% include feature_row id="feature_row" type="right"%}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="left" %}

{% include feature_row id="feature_row5" type="right" %}

{% include feature_row id="feature_row6" type="left" %}
