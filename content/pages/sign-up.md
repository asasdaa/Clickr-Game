---
type: PageLayout
title: Sign up
sections:
  - type: GenericSection
    subtitle: ''
    text: ''
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
        - type: TextFormControl
          name: password
          label: password
          hideLabel: true
          placeholder: Password
          isRequired: true
          width: full
        - type: CheckboxFormControl
          name: Terms
          label: I have read and accept the legal terms.
          isRequired: false
          width: full
      elementId: account-creation
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
      submitButton:
        type: SubmitButtonFormControl
        label: Create Account
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
    badge:
      type: Badge
      label: Contact Us
      color: text-primary
    colors: bg-light-fg-dark
slug: sign-up
seo:
  type: Seo
  metaTitle: Pricing - Demo site
  metaDescription: This is the pricing page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  metaTags: []
---
