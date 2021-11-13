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
        default_value: Selecteaza
        options:
          - Eroare pe site
          - Sponsorizare
          - Altele
      - input_type: textarea
        name: Mesaj
        label: Mesaj
        default_value: Mesajul tau
      - input_type: checkbox
        name: consent
        label: >-
          Inteleg că acest formular stochează informațiile trimise de mine,
          astfel încat să pot fi contactat.
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
