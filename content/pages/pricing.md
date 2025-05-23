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
        price: '$1,500'
        details: 3-5 days
        description: |
          For Idea validation (Minimum Viable Product)
        features:
          - 1 functional prototype
          - Basic user testing with 3 target customers
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
        price: '$3,000'
        details: 14 days
        description: |
          For Ready-to-test products (MVP +User Experience)
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
        price: '$6,000'
        details: 30 days
        description: |
          For Launch-ready products (Full Suite: MVP + UI/UX + Social Media)
        features:
          - Everything in BLOOM
          - 30-day social media campaign (3 platforms)
          - 3 viral-worthy videos (TikTok/Reels/Shorts)
          - Hashtag strategy + influencer outreach list
        image:
          altText: Pricing plan 3
          type: ImageBlock
          url: /images/pricing_blastv2.png
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
