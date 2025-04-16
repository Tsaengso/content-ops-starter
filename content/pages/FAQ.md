---
type: PageLayout
title: Frequently Asked Questions
sections:
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Frequently Asked Questions
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: Find answers to commonly asked questions about our services.
    items:
      - type: FeaturedItem
        title: What Should I Expect?
        subtitle: Honesty above all.
        text: >
          Your consultation is a fairly straightforward process.


          First, we will coordinate a time for us to meet you on site or via
          zoom and begin a 1-2 hour investigation that consists of an overview
          of how your current workflow is, interviews with key members of your
          staff, and finally a start to finish lifecycle of your product or
          service. Throughout this, we will take detailed notes which we will
          disclose at the end of our session.


          From there, we will take 24-48 hours to analyze opportunities for
          improvement and create a gameplan for your needs which we will present
          back to you for implementation.




          Our goal is to provide you with sustainable practices that you will be
          able to implement immediately for long term success!
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: How Long Will it Take?
        subtitle: 1-2 Hours.
        text: >+
          A typical consultation session will only take about 1-2 hours, though
          it depends on the scope of your consult needs.


          By default, we allocated the full 2 hours to your consultations and we
          do not double book. That allows us to fully dedicate our services to
          your business without the pressure of overrunning the clock.


          There are instances when you may require more or less time, and we are
          happy to accommodate these requests through the following policies:


          *   If you require more than 2 hours, we charge an hourly rate of $85.
          For consults requiring more than 6 hours, or multiple days, we ask to
          please email us your request ahead of your booking.



          *   If you require less than 1 hour, please understand that we cannot
          adjust our flat booking rate but are happy to offer one of our
          optional services free of charge. 

        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: Do You Offer Custom Consultations?
        subtitle: Engineering
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
    actions:
      - type: Button
        label: Apply now
        url: /
        icon: arrowRight
        iconPosition: right
        style: primary
    variant: toggle-list
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pb-40
          - pt-16
          - pl-3
          - pr-3
        justifyContent: center
      subtitle:
        textAlign: center
  - type: GenericSection
    title:
      type: TitleBlock
      text: Generic Section With A Form
      color: text-dark
    subtitle: Section with a form subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
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
slug: FAQ
isDraft: false
seo:
  type: Seo
  metaTitle: Landing Page
  metaDescription: Write here your new page's description including most relevant keywords.
  addTitleSuffix: true
  socialImage: /images/main-hero.jpg
  metaTags: []
---
