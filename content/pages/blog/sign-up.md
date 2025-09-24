---
type: PostLayout
title: ''
date: ''
excerpt: ''
featuredImage:
  type: ImageBlock
  url: /images/abstract-feature1.svg
  altText: Thumbnail
  elementId: ''
  styles:
    self:
      padding:
        - pt-0
        - pl-0
        - pb-0
        - pr-0
bottomSections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Sign up now to make an account!
      color: text-dark
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
          placeholder: password
          isRequired: true
          width: full
        - type: CheckboxFormControl
          name: terms
          label: I have read and accept the legal terms.
          isRequired: false
          width: full
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
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
    colors: bg-light-fg-dark
slug: sign-up
isFeatured: false
isDraft: false
seo:
  type: Seo
  metaTitle: lorem-ipsum
  metaDescription: lorem-ipsum
  addTitleSuffix: false
  metaTags: []
colors: bg-light-fg-dark
styles:
  self:
    flexDirection: row
---
