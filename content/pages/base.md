---
type: PageLayout
title: Base
sections:
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: ''
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: ''
    items: []
    actions: []
    badge:
      type: Badge
      label: Coming soon
      color: text-dark
      styles:
        self:
          textAlign: center
    elementId: ''
    variant: two-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - type: GenericSection
    title:
      type: TitleBlock
      text: Base
      color: text-dark
    subtitle: Build anything on top of it
    text: >
      Single platform with all the tools you need to make your dream a reality.
      The whats, whos and hows behind the scenes of your show.
    actions:
      - type: Button
        label: Explore
        url: /base
        icon: arrowRight
        iconPosition: right
        style: secondary
        altText: Explore
      - type: Link
        label: See Tutorials
        url: /base
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
    media:
      type: ImageBlock
      url: /images/hero3.svg
      altText: Dope design preview
    badge:
      type: Badge
      label: Strurdy and strong
      color: text-primary
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Building Base
      color: text-primary
      styles:
        self:
          textAlign: center
    subtitle: The foundation you need
    items:
      - type: FeaturedItem
        title: Materials
        tagline: Earth
        subtitle: ''
        text: >
          From natural to artificial, we proactively enrich our knowledge on
          modern and established materials, so any dream is possible.
        image:
          type: ImageBlock
          url: /images/abstract-feature2.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
      - type: FeaturedItem
        title: Equipment
        tagline: Efficient
        subtitle: ''
        text: >
          Proactively collecting and scanning equipment in order to make
          building your dream more efficient.
        image:
          type: ImageBlock
          url: /images/abstract-feature1.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
      - type: FeaturedItem
        title: Recipes
        tagline: Proven
        subtitle: ''
        text: >
          Don't reinvent the wheel. Leverage our experience and knowledge on
          building that is constantly being extended.
        image:
          type: ImageBlock
          url: /images/abstract-feature1.svg
          altText: Placeholder text
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
      - type: FeaturedItem
        title: Vendors
        tagline: Explore
        subtitle: ''
        text: >
          We know where you can buy at the price that fits your budget. Explore
          our partners and find a deal!
        image:
          type: ImageBlock
          url: /images/abstract-feature2.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
      - type: FeaturedItem
        title: Contractors
        tagline: Find
        subtitle: ''
        text: >
          We know the right folks for the right job. Find a partner to build
          your dream that aligns with you.
        image:
          type: ImageBlock
          url: /images/abstract-feature2.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
      - type: FeaturedItem
        title: Knowhow
        tagline: Do it yourself
        subtitle: ''
        text: >
          Build your dream yourself following our playbooks for success. Nothing
          is too complex!
        image:
          type: ImageBlock
          url: /images/abstract-feature2.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
    actions: []
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
  - type: GenericSection
    title:
      type: TitleBlock
      text: Ready to meet your dream in person?
      color: text-dark
    subtitle: We sure are
    text: >
      Yesterday was the best day to start. Today is the second best. No more
      procrastinating. Build your dream now! Our team will help you get started!
    actions: []
    media:
      type: FormBlock
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: true
          placeholder: Your dream
          isRequired: true
          width: full
      submitButton:
        type: SubmitButtonFormControl
        label: Go
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    badge:
      type: Badge
      label: Contact us
      color: text-primary
    colors: bg-light-fg-dark
slug: base
isDraft: false
seo:
  type: Seo
  metaTitle: Base Platform
  metaDescription: >-
    Single platform for managing your builds. The whats, whos and hows to help
    you succeed.
  addTitleSuffix: true
  socialImage: /images/main-hero.jpg
  metaTags: []
---
