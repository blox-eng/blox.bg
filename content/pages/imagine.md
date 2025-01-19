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
      text: Imagine
      color: text-dark
    subtitle: Shape your dream
    text: >
      Shape your dreams by engaging in active conversation. Imagine will guide
      your mind and spark ideas that you will fall in love with.
    actions:
      - type: Button
        label: Dream on
        url: /imagine
        icon: arrowRight
        iconPosition: right
        style: secondary
        altText: Get started
      - type: Link
        label: See Tutorials
        url: /imagine
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        altText: See Tutorials
    media:
      type: ImageBlock
      url: /images/hero2.svg
      altText: Fun feature preview
    badge:
      type: Badge
      label: unleash your mind
      color: text-primary
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: How it works
      color: text-primary
      styles:
        self:
          textAlign: center
    subtitle: Make up your mind
    items:
      - type: FeaturedItem
        title: Engaging
        tagline: Active
        subtitle: ''
        text: >
          All dreams start from a simple spark. With Imagine you are going to
          actively engage in shaping your dream into full clarity.
        image:
          type: ImageBlock
          url: /images/abstract-feature3.svg
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
        title: Adaptive
        tagline: Individual
        subtitle: ''
        text: >
          Your individual desires and always reflected in your dreams. Imagine
          adapts to your imagination and needs, on the fly.
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
        title: Endless
        tagline: Knowledge
        subtitle: ''
        text: >
          Go beyond the limits of the human imagination. Leverage our endless
          knowledge Base to level up your imagination.
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
slug: /imagine
isDraft: false
seo:
  type: Seo
  metaTitle: Imagine Platform
  metaDescription: Shape your dream and details. Our minds have no limits. Ready to imagine?
  addTitleSuffix: true
  socialImage: /images/main-hero.jpg
  metaTags: []
---
