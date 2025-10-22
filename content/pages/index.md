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
  - type: HeroSection
    title: Harsh Dwivedi
    subtitle: >-
      Focused on Full-Stack Development, Data Analytics, and Intelligent
      Software Solutions.
    actions: []
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
    text: >+
      *   *   Graduated with a Bachelor of Computer Science (Data Science major)
      from Deakin University, Melbourne.*   Passionate about developing
      data-driven software solutions that integrate analytics, automation, and
      design.*   Skilled in Python, React, Flask, Node.js, Power BI, and cloud
      technologies including AWS and Azure.*   Experience as Project Intern at
      Deakin FreelanceHub and Data Analyst Intern at Infinitude Logistics.*  
      Proficient in building dashboards, optimizing workflows, and transforming
      raw data into measurable outcomes.*   Continuously exploring new
      technologies and mentoring students in STEM through the In2Science
      Program.

    media:
      type: ImageBlock
      url: /images/IMG_6613.JPG
      altText: altText of the image
      caption: Caption of the image
      elementId: ''
  - type: FeaturedProjectsSection
    subtitle: 'Projects:'
    actions:
      - type: Button
        label: Project Link
        altText: ''
        url: 'https://infinitudelogistics.in/'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
      - type: Button
        label: Project Link
        altText: ''
        url: 'https://surveyforge.online/'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
    projects:
      - content/pages/projects/project-one.md
      - content/pages/projects/project-two.md
    colors: colors-f
    variant: variant-a
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
        textAlign: left
  - type: FeaturedItemsSection
    items:
      - type: FeaturedItem
        subtitle: A fresh perspective with the determination to innovate and excel
        text: >+
          ### Project Intern


          **Deakin FreelanceHub, Melbourne**

          *February 2025 - Present*


          *   Creating data visualization dashboards for community insights


          ### Data Analyst Intern


          **Infinitude Logistics**

          *October 2023 - February 2024*


          *   Optimized workflows using Power BI and Python, cutting operational
          costs by 15%


          *   Automated data extraction processes, improving reporting
          efficiency by 30%

        actions: []
        styles:
          self:
            textAlign: left
        title: 'Experience:'
      - type: FeaturedItem
        subtitle: My Academic Journey
        text: |+
          ### Bachelor of Computer Science, Major in Data Science

          **Deakin University, Melbourne**
          *July 2023 - June 2025*

          *   Awarded Deakin International Scholarship for academic excellence

          ### High School

          **DCM Presidency, India**
          *April 2020 - August 2022*

          *   High School Captain

        actions: []
        styles:
          self:
            textAlign: left
        title: 'Education:'
    actions: []
    colors: colors-f
    columns: 2
    spacingX: 60
    spacingY: 60
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
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
        label: 'React '
        url: ''
      - type: Label
        label: 'Node.js '
        url: ''
      - type: Label
        label: 'Tableau '
        url: ''
      - type: Label
        label: Power BI
        url: ''
    colors: colors-b
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
        textAlign: center
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Got an interesting project? or want to reach out for an opportunity Tell me more...\U0001F4AC"
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
addTitleSuffix: false
---
