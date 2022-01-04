---
title: Contact
sections:
  - type: hero_section
    title: Contact
    subtitle: >-
      Remplissez le formulaire et vous serez recontacter très rapidement.
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content: >-
      ## Artisan Solution

      Lundi - Vendredi : 8h - 19h

      ### [06 85 40 75 81](tel://0685407581)

    content_align: left
    form_position: left
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nom
        default_value: Votre nom
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Votre adresse email
        is_required: true
      - input_type: textarea
        name: message
        label: Message
        default_value: Votre message
    submit_label: Envoi
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
seo:
  title: Contact
  description: Ceci est la page de contact
  extra:
    - name: og:type
      value: website
      keyName: property
    - name: og:title
      value: Contact
      keyName: property
    - name: og:description
      value: Ceci est la page de contact
      keyName: property
    - name: twitter:card
      value: summary
    - name: twitter:title
      value: Contact
    - name: twitter:description
      value: Ceci est la page de contact
layout: advanced
---
