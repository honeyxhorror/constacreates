---
type: PageLayout
title: Contact
sections:
  - type: ContactSection
    title: Contact Me
    text: >+
      Feel free to contact me about any ideas or questions you may have, I'd
      love to work with you. Fill out this form and I'll get back to you within
      the next 24 hours. Thank you for reaching out and showing interest, we'll
      speak soon!

    form:
      type: FormBlock
      title: Contact
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: First and Last Name
          width: full
          isRequired: 'true'
        - type: EmailFormControl
          name: email
          label: ''
          hideLabel: true
          placeholder: Email
          width: full
          isRequired: 'true'
        - type: TextFormControl
          name: phone
          label: ''
          hideLabel: true
          placeholder: Phone Number
          width: full
          isRequired: false
        - type: TextareaFormControl
          name: message
          label: ''
          hideLabel: true
          placeholder: Interested in my work? Let's discuss ideas!
          width: full
          isRequired: true
      submitLabel: Submit
      elementId: contact-form
      styles:
        submitLabel:
          textAlign: left
    colors: colors-b
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: center
      text:
        textAlign: center
  - type: LabelsSection
    title: Skills
    subtitle: The section subtitle
    items:
      - type: Label
        label: 'WEB 1, 2, 3'
        url: ''
      - type: Label
        label: React
        url: ''
      - type: Label
        label: Microsoft Office
        url: ''
      - type: Label
        label: Next.js
        url: ''
      - type: Label
        label: Netlify
        url: ''
      - type: Label
        label: Pancakes
        url: ''
      - type: Label
        label: C++
        url: ''
      - type: Label
        label: Swift
        url: ''
    colors: colors-f
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-0
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
addTitleSuffix: true
colors: colors-b
---
