---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: THE ICE STUPA
      color: text-dark
      type: TitleBlock
    subtitle: PROJECT
    text: >
      Ladakh, a trans-Himalayan mountain desert in northern India, is home to
      villages nestled at altitudes ranging from 2,700m to 4,000m. Known for its
      harsh climate, this cold desert experiences winter temperatures plummeting
      to -30°C and receives an annual precipitation of just 100 mm. Despite
      these challenging conditions, human settlements thrive by harnessing
      glacial streams that flow into the Indus River and its tributaries. The
      survival and prosperity of these communities hinge on the ancient art of
      water diversion, where carefully constructed canals channel precious
      glacial meltwater to the arid land, making it possible to cultivate crops
      like barley, wheat, and vegetables, and nurture trees such as apricots,
      apples, willow, and poplar.
    actions: []
    media:
      altText: IceStupaLogo
      elementId: ''
      type: ImageBlock
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - type: GenericSection
    title:
      type: TitleBlock
      text: The Problem?
      color: text-dark
    subtitle: ''
    text: >+
      Many villages in Ladakh experience severe water shortages, particularly
      during the critical months of April and May, when glacial streams run low
      and villagers compete for water to irrigate their newly planted crops. By
      mid-June, however, the situation reverses as rapid snow and glacier melt
      leads to an excess of water, often causing flash floods. By mid-September,
      farming activities conclude, but a steady stream continues to flow
      throughout the winter, wastefully draining into the Indus River without
      serving any purpose.


      This problem is intensifying over time as Himalayan glaciers shrink due to
      global warming and local pollution, threatening the water security of
      these fragile communities.



    actions: []
    media:
      type: ImageBlock
      url: /images/Rehabilitation2.webp
      altText: Dope design preview
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
  - type: GenericSection
    title:
      type: TitleBlock
      text: Our Solution!
      color: text-dark
    subtitle: ''
    text: >+

      After years of experimentation at the [SECMOL](https://secmol.org) &
      [HIAL](https://hial.edu.in), we witness the creation of Ice Stupa. These
      artificial glaciers are designed to capture the unused winter water by
      storing it as ice mountains, which gradually melt in the warmer months,
      providing much-needed water to farmers during the critical growing season.
      This innovative solution was initiated by His Holiness Drikung Skyabgon
      Chetsang Rinpochey.

    actions: []
    media:
      type: ImageBlock
      url: /images/ice.webp
      altText: Fun feature preview
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
  - title:
      text: ''
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: ''
    text: ''
    media:
      title: Title of the video
      url: 'https://www.youtube.com/watch?v=FdVijr10DZ0'
      controls: true
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: VideoBlock
      autoplay: true
      loop: false
      muted: false
    badge:
      label: Key Benefits
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: col
        justifyContent: center
      subtitle:
        textAlign: center
    type: GenericSection
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: Got Interesting Ideas?
      color: text-dark
      type: TitleBlock
    subtitle: Tell us more
    text: ''
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
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
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contact Us
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
