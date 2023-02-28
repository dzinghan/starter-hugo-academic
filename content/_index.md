---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: markdown
    content:
      title: Announcements
      text: |-
              * [21/02/23] I will join [Nuance](https://www.nuance.com/index.html) this summer as a Research Developer Intern.
              * [01/02/23] I will join [Prof. Bang Liu](http://www-labs.iro.umontreal.ca/~liubang/index.html)'s group at [MILA](https://mila.quebec/en/) and [Université de Montréal](https://diro.umontreal.ca/english/home/) as a MSc student this September! 
    design:
      columns: '2'
      view: list
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research Developer Intern
          company: Nuance
          company_url: https://www.nuance.com/index.html
          company_logo: org-gc
          location: Montreal, Quebec
          date_start: '2023-05'
          date_end: '2023-08'
        - title: Undergraduate Research Assistant
          company: McGill University
          company_url: ''
          company_logo: org-gc
          location: Montreal, Quebec
          date_start: '2021-09'
          date_end: '2023-05'
        - title: Data Scientist Intern
          company: Raymond Chabot Grant Thornton
          company_url: https://www.rcgt.com/fr/
          company_logo: rcgt
          location: Montreal, Quebec
          date_start: '2021-05'
          date_end: '2021-08'
    design:
      columns: '2'
  
  
  # - block: collection
  #   id: publications
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  - block: collection
    id: publications
    content:
      title: Selected Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
        Coming soon...
      # filters:
      #   folders:
      #     - publication
      #   exclude_featured: true
    design:
      columns: '2'
      view: citation
  
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Note: My first name is Jing Han (Jinghan works too) and my pronouns are she/her. Please address me by my first name.

        I speak English, français, and 中文, so feel free to use the language your feel the most comfortable!
      # Contact (add or remove contact options as necessary)
      email: 'jing [dot] h [dot] sun [at] mail [dot] mcgill [dot] ca'
      contact_links:
        - icon: github
          icon_pack: fab
          name: My GitHub
          link: https://github.com/dzinghan
        - icon: linkedin
          icon_pack: fab
          name: My LinkedIn
          link: https://www.linkedin.com/in/sunjinghan
      # Automatically link email and phone or display as text?
      autolink: false
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
