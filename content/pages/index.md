---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Welcome to 6th Morpeth Scouts
      color: text-dark
    subtitle: >-
      We offer challenge and adventure to young people in Morpeth,
      Northumberland. We have over 100 members in Beavers, Cubs and Scouts.
    text: >
      Our programmes are based around three main themes; outdoor & adventure,
      world and skills. this programme of activities is planned by the
      leadership team in partnership with our young people, incorporating
      elements from each theme to offer young people the most interesting and
      diverse experience.
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
    colors: bg-light-fg-dark
    elementId: Contact-Us
seo:
  metaTitle: 'Home '
  metaDescription: >-
    6th Morpeth scouts is a local scout group in Morpeth with Beavers, Cubs and
    Scouts taking part in weekly meetings
  socialImage: /images/6th Morpeth scouts logo.png
  type: Seo
type: PageLayout
---
