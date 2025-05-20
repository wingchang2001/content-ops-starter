---
title: Pricing
slug: pricing
sections:
  - title:
      text: Flexible Pricing
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: This is the subtitle for the pricing section
    plans:
      - title: SPROUT
        price: '$2,500'
        details: per project
        description: |
          For Idea validation (MVP Only)
        features:
          - 1 functional prototype (3D-printed or no-code digital)
          - Basic user testing with 5 target customers
          - 2 rounds of minor revisions
        image:
          url: /images/abstract-feature1.svg
          altText: Pricing plan 1
          type: ImageBlock
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
        type: PricingPlan
      - title: BLOOM
        price: '$6,900'
        details: per project
        description: |
          For Ready-to-test products (MVP + UI/UX)
        features:
          - Everything in SPROUT
          - Custom UI/UX design (Figma/Adobe XD)
          - Mobile/desktop responsiveness
          - 1 animated prototype demo (Lottie)
        image:
          url: /images/abstract-feature2.svg
          altText: Pricing plan 2
          type: ImageBlock
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
        type: PricingPlan
      - title: BLAST OFF
        price: Custom
        details: per month
        description: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam.
        features:
          - Feature one
          - Feature two
          - Feature three
          - Feature four
          - Feature five
        image:
          url: /images/abstract-feature3.svg
          altText: Pricing plan 3
          type: ImageBlock
        actions:
          - label: Contact us
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
            type: Button
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
        type: PricingPlan
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: PricingSection
seo:
  metaTitle: Pricing - Demo site
  metaDescription: This is the pricing page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
