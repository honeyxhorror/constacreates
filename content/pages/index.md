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
    actions: []
    media:
      type: ImageBlock
      url: 'https://assets.stackbit.com/components/images/default/default-image.png'
      altText: ''
      caption: ''
      elementId: ''
  - colors: colors-b
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
        icon: arrowRight
        iconPosition: right
        showIcon: true
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
    subtitle: Projects
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
          placeholder: Insterested in my work? Let's discuss ideas!
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
  - type: FeaturedItemsSection
    title: Value propositions
    items:
      - type: FeaturedItem
        title: ''
        subtitle: ''
        text: ''
        actions:
          - type: Button
            label: ''
            altText: ''
            url: /
            showIcon: true
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
        elementId: ''
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        title: ''
        subtitle: ''
        text: ''
        actions:
          - type: Button
            label: ''
            altText: ''
            url: /
            showIcon: true
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
        elementId: ''
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        title: ''
        subtitle: ''
        text: ''
        actions:
          - type: Button
            label: ''
            altText: ''
            url: /
            showIcon: true
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
        elementId: ''
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        title: Item Title
        subtitle: ''
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        featuredImage:
          type: ImageBlock
          url: >-
            https://assets.stackbit.com/components/images/default/default-image.png
          altText: Item image
          caption: Caption of the image
          elementId: ''
        elementId: ''
        styles:
          self:
            textAlign: left
    actions: []
    colors: colors-f
    columns: 4
    spacingX: 16
    spacingY: 16
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
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-start
---
