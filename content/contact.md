---
title: Kontakt
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: Da bi ste stupili u kontakt sa nama molimo vas da popunite polja
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Vaše ime
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Vaša imejl adresa
        is_required: true
      - input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Error on the site
          - Sponsorship
          - Other
      - input_type: textarea
        name: message
        label: Message
        default_value: Vaša poruka
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Pošalji poruku
layout: advanced
---
