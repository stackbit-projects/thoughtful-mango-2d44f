---
title: Blog
sections:
  - type: hero_section
    title: Blog
    subtitle: The optional subtitle
    align: center
    padding_top: medium
    padding_bottom: none
    background_color: none
  - type: form_section
    title: Inline Form
    title_align: center
    content: Subscribe to our newsletter to make sure you don't miss anything.
    content_align: center
    form_position: bottom
    form_layout: inline
    form_id: subscribeForm
    form_action: /thank-you
    form_fields:
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
    submit_label: Subscribe
    padding_top: medium
    padding_bottom: medium
    has_border: true
    background_color: secondary
  - section_id: lorem-ipsum
    title: lorem-ipsum
    content: >-
      ## Lorem ipsum


      Lorem ipsum dolor sit amet, **consectetur adipiscing elit**, sed do
      eiusmod tempor incididunt ut labore et dolore magna aliqua.


      - Lorem ipsum

      - dolor sit amet
    actions: []
    actions_position: bottom
    actions_width: fourty
    align: left
    padding_top: medium
    padding_bottom: medium
    has_border: false
    background_color: none
    background_image_opacity: 0
    background_image_size: cover
    background_image_position: center center
    background_image_repeat: no-repeat
    type: cta_section
seo:
  title: Blog
  description: This is the blog page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Blog
      keyName: property
    - name: 'og:description'
      value: This is the blog page
      keyName: property
    - name: 'og:image'
      value: images/classic/post-5.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Blog
    - name: 'twitter:description'
      value: This is the blog page
    - name: 'twitter:image'
      value: images/classic/post-5.png
      relativeUrl: true
layout: advanced
---
