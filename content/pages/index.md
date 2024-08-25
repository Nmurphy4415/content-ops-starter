---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: 'Strength, Fitness & Nutrition Coaching'
      color: text-dark
      type: TitleBlock
    subtitle: Customized plans tailored to your goals
    text: |+
      *   Initial assessment and goal-setting session

      *   Customized workout and nutrition plans available

      *   Regular check-ins and adjustments

      *   Lifting form analysis and technique corrections

      *   Nutritional guidance tailored to your goals

    actions: []
    media:
      url: /images/IMG_2773.jpeg
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: online coach
      color: text-primary
      type: Badge
      styles:
        self:
          fontWeight: 400
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
      subtitle:
        textAlign: left
  - type: FeaturedItemsSection
    title:
      text: What's your goal?
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Weight loss or gain and nutrition guidance
        subtitle: Custom meal plans
        text: >
          Drop the fad diets and learn proper macronutrient management to lose
          weight and keep it off.
        actions: []
        elementId: null
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          elementId: ''
          url: /images/Untitled design (14).png
          styles:
            self:
              borderRadius: x-large
      - title: Strength and fitness
        subtitle: Custom workout plans
        text: >
          Let's achieve your dream strength and fitness goals. Muscle-ups at 40?
          Deadlifting 400 pounds at 50? Dream big!
        image:
          url: /images/Untitled design (15).png
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
      - title: Mindset
        subtitle: Growth and success
        text: >
          Build confidence through improving your mindset. Continual, small
          improvements lead to a lifetime of change.
        image:
          url: /images/Untitled design (13).png
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
    actions:
      - label: DM to start
        altText: ''
        url: '/https://www.instagram.com/nmurphyfitness/'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
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
      text: EASY WORKOUT AND NUTRITION TRACKING
      color: text-dark
      type: TitleBlock
    subtitle: Communicate with Nate and share progress
    text: >
      Everfit App included with coaching makes training, nutrition, progress
      tracking, habit coaching and messaging a breeze at no extra cost to you.
    actions: []
    media:
      url: /images/Screenshot 2024-08-24 at 9.16.54 AM.jpeg
      altText: Fun feature preview
      type: ImageBlock
    badge:
      label: included with coaching
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
    type: GenericSection
  - type: FeaturedPostsSection
    title:
      type: TitleBlock
      text: How it works
      color: text-dark
      styles:
        self:
          textAlign: center
    posts:
      - >-
        content/pages/blog/how-to-write-a-blog-post-that-will-get-you-more-traffic.md
      - content/pages/blog/five-tips-for-starting-a-startup.md
      - content/pages/blog/what-is-a-design-system.md
    showThumbnail: true
    showExcerpt: true
    showDate: false
    showAuthor: false
    actions: []
    elementId: ''
    variant: small-list
    colors: bg-light-fg-dark
    hoverEffect: thin-underline
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
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
  - type: GenericSection
    title:
      type: TitleBlock
      text: About Coach Nate
      color: text-dark
      styles:
        self:
          textAlign: left
    subtitle: 10+ years experience with a passion for helping others
    text: >
      My journey into strength training and nutrition started seriously in 2013
      after my uncle passed away. I witnessed first-hand the importance of
      regular movement and quality nutrition. Since then, I've committed to
      being the best version of myself through strength training and proper
      nutrition. Over the years I've mastered the manipulation of macronutrients
      to suit the intended goal and how to create effective training programs.
    actions: []
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: row
        justifyContent: center
      subtitle:
        textAlign: left
  - title:
      text: Sign up for your chance to win cash!
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: >
      You'll receive invitations to workout and nutrition challenges, free
      resources and lots more with an opportunity to win cash prizes.
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
      label: cash prize transformation challenges
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
