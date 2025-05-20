---
title: Pricing
slug: pricing
sections:
  - title:
      text: Our Pricing
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Pick your propulsion package—let’s blast off before lunch.
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
          url: /images/pricing_sprout.png
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
          url: /images/pricing_bloom.png
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
        price: '$12,500'
        details: per project
        description: |
          For Launch-ready products (Full Suite: MVP + UI/UX + Social)
        features:
          - Everything in BLOOM
          - 30-day social media campaign (3 platforms)
          - 3 viral-worthy videos (TikTok/Reels/Shorts)
          - Hashtag strategy + influencer outreach list
        image:
          url: /images/pricing_blast.png
          altText: Pricing plan 3
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
