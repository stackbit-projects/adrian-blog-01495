---
title: Contact
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: Nume
        options: []
        is_required: false
        label: Nume
        default_value: Scrie numele
      - input_type: email
        name: email
        label: Email
        default_value: Adresa de email
        is_required: true
        options:
          - lorem-ipsum
      - input_type: select
        name: Subiect
        label: Subiect
        default_value: Select
        options:
          - Error on the site
          - Sponsorship
          - Other
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
