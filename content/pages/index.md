---
title: Home
sections:
  - type: hero_section
    subtitle: >-
      Solutions digitales pour artisans, professions libérales et TPE/PMEs.
    actions:
      - label: Nous contacter
        url: /contact
        style: primary
    image: /images/site-attrayant.svg
    image_alt: Un site moderne
    media_position: right
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
    title: Solutions digitales
  - type: features_section
    title: Nos services
    subtitle: Ce que nous proposons pour répondre aux problématiques des artisans et TPE/PMEs. 
    features:
      - title: Site internet
        subtitle: 'Site clé en main'
        content: >-
          Pour vendre ou simplement pour présenter votre activité, nous créons un site adapté à votre activité, votre public et vos besoins spécifiques, et optimisé pour votre référencement.
        image: images/website-design.png
        image_alt: Site web moderne
        media_position: right
        media_width: sixty
      - title: Boutique en ligne
        subtitle: 'Solutions ecommerce'
        content: >-
          Pour que la gestion d'une boutique en ligne soit la plus facile possible,
          nos solutions sont simples et automatisées, avec par exemple le calcul 
          des frais d'expédition, la gestion des stocks, ou l'envoi automatique d'email et de SMS.
          Des solutions adaptées à chaque situation.
        image: images/feature-2.svg
        image_alt: Boutique en ligne
        media_position: right
        media_width: sixty
      - title: Transformation Digitale
        subtitle: 'Des solutions qui facilitent la vie pour votre activité.'
        content: >-
          Solutions téléphoniques avec Serveur 
          Virtuel Interactif (aucun matériel n'est nécessaire); Gestion
          des bases de données prospects et clients, des devis et factures;
          Automatisation des tâches bureautiques répétitives.
        actions:
          - label: Voir les questions
            url: /faq
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/feature-3.svg
        image_alt: Solutions numériques
        media_position: right
        media_width: sixty
      - title: Marchés Publics
        subtitle: 'Accédez aux marchés publics.'
        content: >-
          Assistance pour trouver et répondre à un appel d'offre de marché public.
        actions:
          - label: En savoir plus
            url: /marches-publics
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/feature-1.svg
        image_alt: Appels d'offres de marché public
        media_position: right
        media_width: sixty
    feature_padding_vert: large
    align: center
    background_color: none
  - type: grid_section
    title: Ils nous font confiance
    subtitle: Nos références
    align: center
    grid_items:
      - image: images/logo-BeautyIndustrie.jpeg
        image_alt: Beauty Industrie
        image_align: center
      - image: images/logo-FabienneAumont.png
        image_alt: Cabinet Fabienne Aumont
        image_align: center
      - image: images/logo-SoftPeople.png
        image_alt: Soft People
        image_align: center
      - image: images/logo-DN95.svg
        image_alt: Destruction Nuisibles
        image_align: center
    grid_cols: four
    grid_gap_horiz: medium
    grid_gap_vert: medium
  - type: form_section
    content: >-
      ## Discutons


      Contactez-nous pour avoir plus d'informations sur nos services, 
      ou pour demander un devis.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: stacked
    enable_card: false
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: Nom
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
  title: Artisan Solution
  description: La présentation d'Artisan Solution
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Artisan Solution
      keyName: property
    - name: 'og:description'
      value: Des solutions digitales pour artisans et TPE/PME
      keyName: property
    - name: 'og:image'
      value: images/personal-preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit Personal Theme
    - name: 'twitter:description'
      value: The preview of the Personal theme
    - name: 'twitter:image'
      value: images/personal-preview.png
      relativeUrl: true
layout: advanced
---
