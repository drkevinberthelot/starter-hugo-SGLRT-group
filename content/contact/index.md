---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        Expliquez le motif de votre message (prise ou changement de RDV), Information par rapport à votre traitement ou à votre pathologie. Message informatif. Retour d'expérience...
      email: radiotherapie.sgl@gmail.com
      phone: 01 39 27 58 03
      address:
        street: 20 rue Armagis
        city: Saint-Germain-En-Laye
        region: Yvelines
        postcode: '78100'
        country: France
        country_code: FR
      coordinates:
        latitude: '48.89713'
        longitude: '2.08490'
      directions: Entrée avec accueil au RDC et secrétariat au 1er étage
      office_hours:
        - 'Lundi de 08:00 à 19:00'
        - 'Mardi de 08:00 à 19:00'
        - 'Mercredi de 08:00 à 19:00'
        - 'Jeudi de 08:00 à 19:00'
        - 'Vendredi de 08:00 à 19:00'
        - 'Fermé le weekend'
      appointment_url: 'https://calendly.com/kev-berthelot'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
