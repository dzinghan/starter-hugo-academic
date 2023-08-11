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
    design:
      columns: 2
  - block: markdown
    content:
      title: Announcements
      text: |-
              * [06/23] I will present a poster on common sense reasoning and human-in-the-loop at the ACL 2023 Student Research Workshop in Toronto, Canada.
              * [05/23] I received the [FRQNT](https://frq.gouv.qc.ca/) Master's research scholarship!
              * [02/23] I will join [Nuance](https://www.nuance.com/index.html) this summer as a Research Developer Intern.
              * [02/23] I will join [Prof. Bang Liu](http://www-labs.iro.umontreal.ca/~liubang/index.html)'s group at [Université de Montréal](https://diro.umontreal.ca/english/home/) and [Mila](https://mila.quebec/en/) as a MSc student this September! 
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
          company_logo: nuance
          location: Montreal, Quebec
          date_start: '2023-05-15'
          date_end: '2023-08-01'
        - title: Undergraduate Research Assistant
          company: McGill University
          company_url: https://www.mcgill.ca/
          company_logo: mcgill
          location: Montreal, Quebec
          date_start: '2021-09-01'
          date_end: '2023-05-01'
        - title: Data Scientist Intern
          company: Raymond Chabot Grant Thornton
          company_url: https://www.rcgt.com/fr/
          company_logo: rcgt
          location: Montreal, Quebec
          date_start: '2021-05-03'
          date_end: '2021-08-27'
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
  - block: markdown
    id: publications
    content:
      title: Selected Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
        Coming soon...
    design:
      columns: 2
  # - block: collection
  #   id: publications
  #   content:
  #     title: Selected Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #       Coming soon...
  #     filters:
  #       folders:
  #         - publication
  #       # exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation
  
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Note: My pronouns are she/her.

        I speak fluently English, français, and 中文, so feel free to use the language of your choice!
      # Contact (add or remove contact options as necessary)
      email: 'jing.han.sun [at] umontreal.ca'
      contact_links:
        - icon: github
          icon_pack: fab
          name: My GitHub
          link: https://github.com/dzinghan
        - icon: linkedin
          icon_pack: fab
          name: My LinkedIn
          link: https://www.linkedin.com/in/sunjinghan
        - icon: wechat
          icon_pack: fab
          name: "WeChat ID: jhhhsun (两只熊)"
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
