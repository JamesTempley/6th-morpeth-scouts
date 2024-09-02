---
type: PageLayout
title: Blank sub page
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Tuesday/Wednesday/Thursday Beavers/Cubs/Scouts
      color: text-dark
    subtitle: 'For young people aged '
    text: |
      Section description:

      Info from old website

      Meeting times

      Section size

      Leaders
    actions: []
    media:
      type: ImageBlock
      url: /images/hero2.svg
      altText: Fun feature preview
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
  - type: GenericSection
    title:
      type: TitleBlock
      text: Our Programme
      color: text-dark
    subtitle: What we are up to this term
    text: |
      An outline of the programme plan for this term
    actions: []
    media:
      type: ImageBlock
      url: /images/hero3.svg
      altText: Dope design preview
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
  - type: GenericSection
    title:
      type: TitleBlock
      text: Join us
      color: text-dark
    subtitle: Please use the boxes to get in touch
    text: >
      We currently have spaces in Beavers, Cubs and Scouts. If you would like to
      join us please get in touch.


      Without our volunteers, Scouts would not exist. Volunteering with the
      Scouts helps us continue to give our young people new skills and
      experiences. The more leaders we have, the more young people can be
      provided with these opportunities.


      And it helps you too. Share your skills and gain some new ones. Volunteers
      come from all walks of life and give as little or as much time as they can
      spare.


      We offer ongoing training, awards and recognition.


      Please contact us to find out more. 
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
          placeholder: Your message
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
    badge:
      type: Badge
      label: Contact Us
      color: text-primary
    elementId: Contact-Us
    colors: bg-light-fg-dark
slug: Blank
isDraft: false
seo:
  type: Seo
  metaTitle: Landing Page
  metaDescription: Write here your new page's description including most relevant keywords.
  addTitleSuffix: true
  socialImage: /images/main-hero.jpg
  metaTags: []
---
