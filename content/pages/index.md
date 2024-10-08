---
type: PageLayout
title: Home
colors: colors-d
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - type: HeroSection
    title: Gabriel ponte
    subtitle: >-
      Sou estudante do curso técnico de Gestão e Programação de Sistemas
      Informáticos. Frequento agora o meu último ano de curso onde adquiri
      diversas características para o mercado de trabalho
    actions: []
    colors: colors-d
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    media:
      type: ImageBlock
      url: /images/VIT_2993.JPG
      altText: altText of the image
      caption: Caption of the image
      elementId: ''
  - type: LabelsSection
    title: Skills
    subtitle: As linguagens de programação que domino
    items:
      - type: Label
        label: Python
        url: ''
      - type: Label
        label: C++
        url: ''
      - type: Label
        label: JavaScript
        url: ''
      - type: Label
        label: PHP
        url: ''
      - type: Label
        label: CSS
        url: ''
      - type: Label
        label: Java
        url: ''
      - type: Label
        label: mySQL
        url: ''
      - type: Label
        label: SQLServer
        url: ''
      - type: Label
        label: C#
        url: ''
      - type: Label
        label: NodeJS
        url: ''
      - type: Label
        label: ViewJS
        url: ''
    colors: colors-f
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: FeaturedProjectsSection
    subtitle: 'Projects:'
    actions:
      - type: Link
        label: See all projects
        altText: See all projects
        url: /projects
        showIcon: false
        icon: arrowRight
        iconPosition: right
        elementId: ''
    projects:
      - content/pages/projects/project-one.md
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
    colors: colors-d
    variant: variant-b
    elementId: ''
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: wide
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
        justifyContent: center
---
