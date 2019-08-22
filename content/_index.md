---
title: Home
sections:
  - type: heroblock
    template: heroblock
    section_id: hero
    title: This Is A Big Hero Headline
    component: hero_block.html
    content: >-
      Azimuth is the perfect theme for developers, designers and entrepreneurs
      who need a sleek, modern SaaS site. 
    image: images/hero.png
    actions:
      - label: Learn More
        url: /features
  - type: featuresblock
    template: featuresblock
    section_id: features
    title: Features
    component: features_block.html
    subtitle: >-
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam a metus
      quis lorem malesuada luctus.
    bg: gray
    featureslist:
      - title: The Best Feature of Your Services
        content: >-
          Nam pulvinar ante eu ultricies volutpat. Aenean hendrerit, eros sed
          aliquet luctus, lorem risus volutpat dolor, nec dignissim diam neque
          consequat ex.
        image: images/feature1.png
        actions:
          - label: Learn More
            url: /features
      - title: Awesome Feature of Your Services
        content: >-
          Etiam vel urna sed massa egestas vulputate eu a velit. Sed ut nisl nec
          sapien interdum luctus. Cras rhoncus condimentum metus sit amet
          auctor.
        image: images/feature2.png
        actions:
          - label: Learn More
            url: /features
      - title: Cool Feature of Your Services
        content: >-
          In ante enim, lobortis quis congue vel, finibus sit amet mi. Aenean
          quis venenatis sem. Proin eget massa id metus eleifend maximus sit
          amet nec urna.
        image: images/feature3.png
        actions:
          - label: Learn More
            url: /features
  - type: reviewsblock
    template: reviewsblock
    section_id: reviews
    title: Testimonials
    component: reviews_block.html
    subtitle: >-
      Aliquam malesuada ligula eget est fringilla blandit. Integer finibus
      semper libero id sodales. 
    bg: white
    reviews:
      - author: John Doe
        avatar: images/review1.jpg
        content: >-
          Vestibulum a nunc ut eros condimentum posuere. Nullam dapibus quis
          nunc non interdum. Pellentesque tortor ligula, gravida ac commodo eu.
      - author: Jane Roe
        avatar: images/review2.jpg
        content: >-
          Sed laoreet magna commodo libero euismod sodales. Nunc ac libero
          convallis, interdum ligula vel, pretium diam. Integer commodo sem at
          dui sollicitudin, vel posuere justo laoreet.
      - author: Richard Roe
        avatar: images/review3.jpg
        content: >-
          Integer consectetur purus neque, ac porttitor enim convallis vitae.
          Interdum et malesuada fames ac ante ipsum primis in faucibus.
  - type: ctablock
    template: ctablock
    section_id: call-to-action
    title: This Is Call To Action Block!
    component: cta_block.html
    subtitle: This is an optional description for the call to action block.
    actions:
      - label: Get Started
        url: /signup
  - type: postsblock
    template: postsblock
    section_id: recent-posts
    title: Latest Posts
    component: posts_block.html
    bg: gray
menu:
  main:
    name: Home
    weight: 1
layout: home
---