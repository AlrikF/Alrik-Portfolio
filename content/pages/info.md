---
type: PageLayout
title: About
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/pxfuel (1).jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: "### Hey I’m Alrik. \U0001F44B\n\nI’m a passionate developer fueled by curiosity and a love for technology. I hold a Master’s degree in Computer Science from the University of Southern California and am deeply immersed in the world of Computer Science. My expertise lies at the intersection of Software Development, Machine Learning, Data Engineering, and Analytics, where I thrive on building impactful, practical solutions to complex problems.\n\n\n\n"
    media:
      type: ImageBlock
      url: /images/WhatsApp Image 2024-12-15 at 10.41.15 PM.jpeg
      altText: Hero image
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
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: MediaGallerySection
    colors: colors-f
    subtitle: 'I worked with these folks:'
    images:
      - type: ImageBlock
        url: /images/Screenshot 2024-12-16 000255.png
        altText: Logo one
        caption: Logo one
      - type: ImageBlock
        url: /images/Screenshot 2024-12-16 000446.png
        altText: Logo two
        caption: Logo two
      - type: ImageBlock
        url: /images/Intangles-UK_latest.webp
        altText: Logo three
        caption: Logo three
      - type: ImageBlock
        url: /images/HRT.png
        altText: Logo four
        caption: Logo four
    spacing: 10
    columns: 4
    aspectRatio: auto
    showCaption: false
    enableHover: true
    styles:
      self:
        width: wide
        height: auto
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: x-small
        borderWidth: 0
        borderStyle: solid
        borderColor: border-secondary
        margin:
          - mt-1
          - mr-1
          - ml-1
          - mb-1
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: LabelsSection
    title: Skills
    subtitle: Languages
    items:
      - type: Label
        label: Python
        url: ''
      - type: Label
        label: Java
        url: ''
      - type: Label
        label: C++
        url: ''
      - type: Label
        label: SQL
        url: ''
      - type: Label
        label: C#
        url: ''
    colors: colors-f
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-0
          - pb-0
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: LabelsSection
    title: ''
    subtitle: Cloud Platforms
    items:
      - type: Label
        label: Microsoft Azure
        url: ''
      - type: Label
        label: AWS
        url: ''
    colors: colors-f
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-0
          - pb-0
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: LabelsSection
    colors: colors-f
    subtitle: 'Frameworks '
    items:
      - type: Label
        label: PySpark
      - type: Label
        label: REST
        url: ''
      - type: Label
        label: Airflow
      - type: Label
        label: React
      - type: Label
        label: Pytorch
      - type: Label
        label: Pandas
        url: ''
      - type: Label
        label: Tensorflow
      - type: Label
        label: Kafka
      - type: Label
        label: Tensorflow
        url: ''
      - type: Label
        label: Spring
        url: ''
      - type: Label
        label: Flask
        url: ''
      - type: Label
        label: Apache Spark
        url: ''
      - type: Label
        label: Numpy
        url: ''
  - type: LabelsSection
    title: ''
    subtitle: Tools
    items:
      - type: Label
        label: PostgreSQL
        url: ''
      - type: Label
        label: AWS Redshift
        url: ''
      - type: Label
        label: Git
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
          - pb-0
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        actions:
          - type: Link
            label: GitHub
            url: 'https://github.com/AlrikF'
        styles:
          self:
            textAlign: left
    columns: 3
    spacingX: 120
    spacingY: 0
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
    subtitle: 'You can find me here:'
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: TextSection
    variant: variant-a
    subtitle: 'Contact:'
    colors: colors-f
    text: |
      [thisismyemail.@myemail.me](mailto:thisismyemail.@myemail.me)
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        subtitle: 'Experience:'
        text: |-
          **Current**

          * freelance @freelance.me

          **2018-2021**

          * fullstack at this startup

          **2015**

          * senior front-end at this place

          **2013**

          * intern developer at a big company

          **2011**

          * flipping burgers
        styles:
          self:
            textAlign: left
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
      - type: FeaturedItem
        subtitle: 'Education:'
        text: |-
          **2015-2018**

          * ba computer sciense at a semi fancy school

          **2014**

          * react certificate somewhere

          **2011**

          * my highschool
        styles:
          self:
            textAlign: left
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
    columns: 2
    spacingX: 60
    spacingY: 60
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
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: ContactSection
    backgroundSize: full
    title: "Let’s talk... \U0001F4AC"
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Tell me about your project
          isRequired: true
          width: full
          type: TextareaFormControl
      submitLabel: "Submit \U0001F680"
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
          - ml-4
          - mr-4
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
