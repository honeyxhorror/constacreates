---
type: PageLayout
title: Home
colors: colors-b
sections:
  - elementId: ''
    colors: colors-b
    backgroundSize: full
    title: 'I''m Connie, a Digital Multimedia Designer based in TX!'
    subtitle: >-
      I'm a creative individual who loves to create content and collaborate with
      others. Constantly eager to learn something new and enhance my skillset.
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions:
      - type: Button
        label: More About Me
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
    media:
      type: ImageBlock
      url: /images/me.png
      altText: ''
      caption: ''
      elementId: ''
  - type: DividerSection
    title: Divider
    elementId: ''
    styles:
      self:
        width: full
        padding:
          - pt-0
          - pb-0
        justifyContent: center
        borderWidth: 1
  - colors: colors-b
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Button
        label: See All Projects
        altText: ''
        url: /projects
        showIcon: true
        icon: arrowUpRight
        iconPosition: right
        style: secondary
        elementId: ''
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: ''
    title: Latest Projects
  - type: DividerSection
    title: Divider
    elementId: ''
    styles:
      self:
        width: full
        padding:
          - pt-0
          - pb-0
          - pl-0
          - pr-0
        justifyContent: center
        borderWidth: 1
  - type: ContactSection
    colors: colors-b
    backgroundSize: full
    title: Contact
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: Full Name
          label: ''
          hideLabel: false
          placeholder: First and Last Name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - type: TextFormControl
          name: Phone Number
          label: ''
          hideLabel: false
          placeholder: Phone Number
          width: full
          isRequired: true
        - type: TextareaFormControl
          name: Message
          label: Message
          hideLabel: true
          placeholder: Interested in my work? Let's discuss ideas!
          width: full
          isRequired: true
      submitLabel: 'Submit '
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
    text: >
      Feel free to contact me about any ideas or questions you may have, I'd
      love to work with you. Fill out this form and I'll get back to you within
      the next 24 hours. Thank you for reaching out and showing interest, we'll
      speak soon!
---
