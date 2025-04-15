---
title: Blog
slug: /blog
numOfPostsPerPage: 8
enableSearch: false
topSections:
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: FAQ'S
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: Can't find your question? Feel free to send us an email!
    items:
      - type: FeaturedItem
        title: What Should I Expect?
        subtitle: Honesty above all.
        text: >
          Once you schedule your consultation, we will arrive at your business
          in person or create a zoom call. From there, our team will create a
          picture of what your current process performs while taking notes along
          the way. We will interview key players in various departments and work
          to understand the lifecycle of your product or service from the bottom
          up.


          Once the interview stage completes, we will meet with your leadership
          team and discuss immediate pinch points and initial findings. We will
          then depart your facility or call and spend the next 24-48 hours
          developing a road map for your business to optimize the areas we've
          consulted and present our findings, suggestions, and SOP write ups to
          your leadership team for implementation.
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
        subtitle: 1 to 2 hours.
        text: >
          From start to finish, our method of consulting will take about 1-2
          hours of your time.


          We will work quickly to establish an overview of your processes,
          interview key personnel, and let you know the timeframe we will need
          to complete our handoff packet.


          24-48 hours after our meeting, you will receive a packet of
          information outlining our findings, suggestions, and all SOP write ups
          for implementation.


          If you require less time than 1 hour, we are happy to accommodate your
          needs and only request that you gather your personnel in preparation
          to expedite the consult.


          If you require more time than 2 hours, we are happy to accommodate
          your request. However, after 2 hours, we do charge an hourly rate of
          $85. 


          We are more than happy to negotiate consultations in excess of 1 full
          day, but ask you send us an email in advance. 
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
        subtitle: We are here for any business need.
        text: >
          All of our services are tailored to your individual needs. Many
          factors come into play for each client and no two consultations are
          the same.


          However, if referring to services outside the tiered levels, yes, we
          can offer a la carte services to create a plan tailored for your
          needs.


          Each additional service has a flat rate charge to add to your invoice
          and is based on the complexity of the task and/or resources required.




          Please send us an email prior to committing to a tier if you require a
          custom solution!
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
    actions: []
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
styles:
  title:
    textAlign: center
seo:
  metaTitle: Blog - Demo site
  metaDescription: >-
    This is the blog of the demo site where we post about technology, product,
    and design.
  socialImage: /images/img-placeholder.svg
  type: Seo
type: PostFeedLayout
bottomSections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Need more help?
      color: text-dark
    subtitle: Drop us a line!
    text: >
      We are happy to respond to all inquiries to give you peace of mind before
      committing to our services.
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
---
