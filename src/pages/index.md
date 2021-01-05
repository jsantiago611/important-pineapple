---
title: Home
meta_title: Stackbit Azimuth Theme
meta_description: The preview of the Azimuth theme
sections:
  - type: section_hero
    template: section_hero
    title: 'Hello, I''m Jon'
    section_id: hero
    content: >+
      From car, house, life, and business insurance, we make insurance for
      families and businesses easy again. Choose your option below to get
      started in a matter of seconds:

    image: images/hero.png
    image_alt: App preview
    actions:
      - type: action
        template: action
        label: Home Insurance
        url: /features
        primary: true
      - label: Auto Insurance
        url: lorem-ipsum
        primary: false
        new_window: false
        no_follow: false
        type: action
      - label: Life Insurance
        url: lorem-ipsum
        primary: false
        new_window: false
        no_follow: false
        type: action
  - type: section_reviews
    template: section_reviews
    title: Testimonials
    section_id: reviews
    subtitle: >-
      Aliquam malesuada ligula eget est fringilla blandit. Integer finibus
      semper libero id sodales. 
    background: white
    reviews:
      - type: review_item
        template: review_item
        author: John Doe
        avatar: images/review1.jpg
        content: >-
          Vestibulum a nunc ut eros condimentum posuere. Nullam dapibus quis
          nunc non interdum. Pellentesque tortor ligula, gravida ac commodo eu.
      - type: review_item
        template: review_item
        author: Jane Roe
        avatar: images/review2.jpg
        content: >-
          Sed laoreet magna commodo libero euismod sodales. Nunc ac libero
          convallis, interdum ligula vel, pretium diam. Integer commodo sem at
          dui sollicitudin, vel posuere justo laoreet.
      - type: review_item
        template: review_item
        author: Richard Roe
        avatar: images/review3.jpg
        content: >-
          Integer consectetur purus neque, ac porttitor enim convallis vitae.
          Interdum et malesuada fames ac ante ipsum primis in faucibus.
  - type: section_cta
    template: section_cta
    title: This Is Call To Action Block!
    section_id: call-to-action
    subtitle: This is an optional description for the call to action block.
    actions:
      - type: action
        template: action
        label: Get Started
        url: /signup
        primary: true
template: landing
---
