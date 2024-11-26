---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/pexels-anniroenkae-2693212.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 55
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: Pedro Teixeira
    subtitle: >-
      Sou estudante do curso técnico de Gestão e Programação de Sistemas
      Informáticos. Frequento agora o meu último ano de curso onde adquiri
      diversas características para o mercado de trabalho
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
  - type: DividerSection
    title: Divider
    elementId: ''
    styles:
      self:
        width: wide
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
  - type: LabelsSection
    title: Skills
    subtitle: Linguagens
    items:
      - type: Label
        label: SQLServer
        url: ''
      - type: Label
        label: C#
        url: ''
      - type: Label
        label: HTML5
        url: ''
      - type: Label
        label: Vue.js
        url: ''
      - type: Label
        label: Node.js
        url: ''
      - type: Label
        label: Java
        url: ''
      - type: Label
        label: C++
        url: ''
      - type: Label
        label: PHP
        url: ''
      - type: Label
        label: Python
        url: ''
      - type: Label
        label: MySQL
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
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
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
---
