---
title: Contact
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: To get in touch please fill the form below.
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - type: tel
        name: Mobile Number
        label: Mobile Number
        default_value: Your mobile number
        options: []
        is_required: true
      - type: textarea
        name: message
        label: Message
        default_value: Your message
        is_required: true
      - type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
template: advanced
---
