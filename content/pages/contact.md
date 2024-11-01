---
type: PageLayout
title: Contact
sections:
  - type: ContactSection
    title: Contact Me
    text: I'm look forward to hearing from you.
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
          label: Name
          hideLabel: false
          placeholder: Your name
          width: full
          isRequired: false
        - type: TextareaFormControl
          name: message
          label: Tell me about your project
          hideLabel: true
          placeholder: Tell me about your project
          width: full
          isRequired: true
      submitLabel: Send Message
      elementId: contact-form
      styles:
        submitLabel:
          textAlign: left
    colors: colors-f
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
addTitleSuffix: true
colors: colors-b
---
