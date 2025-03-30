---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - type: RecentProjectsSection
    subtitle: Projects
    actions:
      - type: Link
        label: See all projects
        altText: See all projects
        url: /projects
        showIcon: false
        icon: arrowRight
        iconPosition: right
        elementId: ''
      - type: Button
        label: Learn more
        altText: ''
        url: /wdwewefwewq
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    colors: colors-f
    variant: variant-c
    elementId: ''
    recentCount: 6
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
        textAlign: left
  - type: HeroSection
    title: >-
      I am a Software Engineer with expertise in Full-Stack Development and Data
      Analytics.
    subtitle: ''
    actions:
      - type: Button
        label: Connect with Me !
        altText: ''
        url: '/https://www.linkedin.com/in/harshdwivedi050/'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    colors: colors-f
    backgroundSize: inset
    elementId: ''
    styles:
      self:
        height: auto
        width: full
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        flexDirection: row-reverse
        textAlign: left
    text: "*    \U0001F393 Currently completing my Bachelor of Computer Science (Major in Data Science) at Deakin University, Melbourne.\n\n*   ⚡ Passionate about building scalable, efficient, and user-friendly full-stack applications.\n\n*   \U0001F50D Experienced in data analytics, machine learning, and automation—leveraging Python, React, Flask, and cloud technologies.\n\n*   \U0001F680 Project Intern at Deakin FreelanceHub, Senior Leader in the Data Science Team at Chameleon, and former Data Analyst Intern at Infinitude Logistics.\n\n*   \U0001F4CA Skilled in data visualization, predictive modeling, and cloud platforms like AWS & Azure.\n\n*   \U0001F3C6 Awarded the Deakin International Scholarship for academic excellence.\n\n*   \U0001F4A1 Current Project: Developing a Personal Finance Assistant with ML-based forecasting to help users optimize their budgeting.\n\n*   \U0001F3AD Beyond Code: I enjoy mentoring students in STEM, volunteering, cycling, and exploring new tech innovations.\n\n*   \U0001F331 Take a look around my digital space, and let’s build something awesome together!\n\n"
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: >-
      I’m a developer, digital artist, consultant and a bunch of other
      impressive titles and buzz words.
    subtitle: "\U0001F393 Currently completing my Bachelor of Computer Science (Major in Data Science) at Deakin University, Melbourne.⚡ Passionate about building scalable, efficient, and user-friendly full-stack applications.\U0001F50D Experienced in data analytics, machine learning, and automation—leveraging Python, React, Flask, and cloud technologies.\U0001F680 Project Intern at Deakin FreelanceHub, Senior Leader in the Data Science Team at Chameleon, and former Data Analyst Intern at Infinitude Logistics.\U0001F4CA Skilled in data visualization, predictive modeling, and cloud platforms like AWS & Azure.\U0001F3C6 Awarded the Deakin International Scholarship for academic excellence.\U0001F4A1 Current Project: Developing a Personal Finance Assistant with ML-based forecasting to help users optimize their budgeting.\U0001F3AD Beyond Code: I enjoy mentoring students in STEM, volunteering, cycling, and exploring new tech innovations.\U0001F331 Take a look around my digital space, and let’s build something awesome together!"
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
        flexDirection: row-reverse
        textAlign: left
    type: HeroSection
    actions: []
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
      - type: Button
        label: Learn more
        altText: ''
        url: /dwssffs
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
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
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        textAlign: left
    subtitle: Projects
  - type: TextSection
    title: The Section Title
    text: >-
      Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium
      doloremque laudantium, totam rem aperiam. Eaque ipsa quae ab illo
      inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.
      Sed ut perspiciatis undeomnis iste natus error sit voluptatem accusantium
      doloremque laudantium, totam rem aperiam. Eaque ipsa quae ab illo
      inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.
    colors: colors-f
    variant: variant-a
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        textAlign: left
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: Featured Posts
    showFeaturedImage: false
    actions:
      - type: Link
        label: See all posts
        url: /blog
    posts:
      - content/pages/blog/post-six.md
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        textAlign: left
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Got an interesting project? Tell me more...\U0001F4AC"
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
          width: 1/2
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        self:
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
        flexDirection: row
        textAlign: left
  - type: LabelsSection
    title: Skills
    subtitle: The section subtitle
    items:
      - type: Label
        label: Python
        url: ''
      - type: Label
        label: ' C/C++'
        url: ''
      - type: Label
        label: SQL
        url: ''
      - type: Label
        label: 'NumPy/Pandas '
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
    colors: colors-d
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
        textAlign: left
---
