---
type: PageLayout
title: Contact
sections:
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
slug: /contact
seo:
  type: Seo
  metaTitle: Home - Blox
  metaDescription: 'Empower your dreams, bring them to life using Blox.'
  socialImage: /images/main-hero.jpg
  metaTags: []
isDraft: true
---
