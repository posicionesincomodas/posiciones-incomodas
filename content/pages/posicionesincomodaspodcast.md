---
type: PageLayout
title: Podcast
sections:
  - type: PricingSection
    title:
      type: TitleBlock
      text: Podcast
      color: text-light
      styles:
        self:
          textAlign: center
    subtitle: This is the subtitle for the pricing section
    plans:
      - type: PricingPlan
        title: '001'
        price: El puente está quebrado
        details: Con Ana Luisa González
        description: >
          Conversación sobre la crítica de arte y su divulgación con Ana Luisa
          González, periodista cultural y creadora de El Rayón Podcast.
        features: []
        image:
          type: ImageBlock
          url: /images/1.jpg
          altText: '1'
        actions:
          - type: Button
            label: Escuchar aquí
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-6
              - pl-6
              - pr-6
            borderRadius: large
            borderColor: border-light
      - type: PricingPlan
        title: 002-007
        price: Arte joven
        details: >-
          con Doreiby Perafán, Santiago Lemus, Carolina Borrero, Daniel R.
          Blanco, Camila Vargas, Jorge Esteban y Steven Moreno
        description: >
          Encuesta: ¿Qué piensan los "artistas jóvenes" de la crítica y los
          críticos?
        features: []
        image:
          type: ImageBlock
          url: /images/1.jpg
          altText: Pricing plan 2
        actions:
          - type: Button
            label: Try for free
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
      - type: PricingPlan
        title: 008
        price: Crítica y Validez
        details: con Lucas Ospina
        description: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam.
        features:
          - Feature one
          - Feature two
          - Feature three
          - Feature four
          - Feature five
        image:
          type: ImageBlock
          url: /images/1.jpg
          altText: Pricing plan 3
        actions:
          - type: Button
            label: Contact us
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
    colors: bg-dark-fg-light
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
slug: posicionesincomodaspodcast
seo:
  type: Seo
  metaTitle: Pricing - Demo site
  metaDescription: This is the pricing page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  metaTags: []
---
