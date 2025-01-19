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
      text: Build
      color: text-dark
    subtitle: Your dream
    text: |
      Blueprint and track the completion of your dream, be part of the journey.
    actions:
      - type: Button
        label: Build now
        url: /build
        icon: arrowRight
        iconPosition: right
        style: secondary
        altText: Build now
      - type: Link
        label: See Tutorials
        url: /build
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
      label: simply
      color: text-primary
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: How it works
      color: text-primary
      styles:
        self:
          textAlign: center
    subtitle: The plan to make your dream come true
    items:
      - type: FeaturedItem
        title: Plan
        tagline: Step-by-step
        subtitle: ''
        text: >
          We'll lay out the plan to success for you, from blueprint on paper, to
          concrete on land.
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
        title: Adapt
        tagline: Actively
        subtitle: ''
        text: >
          Don't worry if things do not go according to plan. Adapt your plan
          quickly and efficiently.
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
        title: Execute
        tagline: Sucessfully
        subtitle: ''
        text: |
          Helping you stick to plan, stick to your dream, guarantee success.
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
slug: build
isDraft: false
seo:
  type: Seo
  metaTitle: Build Platform
  metaDescription: >-
    Blueprint and track your dreams building. Plan, adapt and execute
    effortlessly, at your own pace.
  addTitleSuffix: true
  socialImage: /images/main-hero.jpg
  metaTags: []
---
