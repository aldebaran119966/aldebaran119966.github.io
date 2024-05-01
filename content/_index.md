---
title: 'LAZe'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: LAZY OLD MAN
      text: Just an old man $LAZe and chill..... nothing special Launch with ERC50 No rug, No team, just $LAZe
      primary_action:
        text: Twitter
        url: https://twitter.com/LazeonBase
        icon: custom/square-x-twitter
      secondary_action:
        text: Telegram
        url: https://t.me/LazeonBase
        icon: custom/telegram
      announcement:
        text: "XXXXXXXXXXXXXXXXXXXXX"
        #link:
          #text: "Read more"
          #url: "/blog/"
    design:
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "orange"
        image:
          # Add your image background to `assets/media/`.
          filename: backgrounderc.svg
          filters:
            brightness: 0.5
          #size: contain
      spacing:
        padding: [0, 0, "1rem", 0]
  - block: stats
    content:
      title: TOKENOMICS
      items:
        - statistic: "50%"
          description: |  
            Presale
        - statistic: "50%"
          description: |
            Liquidity Pool
        - statistic: "3B"
          description: |
            Max. Supply
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: markdown
    id: section-1
    content:
      title: HOW IT WORKS
      #subtitle: A subtitle
      text: <img src="https://i.imghippo.com/files/GcYO11714580288.jpg" alt="" border="0" width="1200" height="720">
    design:
      background:
        image:
          # Name of image in `assets/media/`.
          filename: howdoesitwork.svg
          # Apply image filters?
          filters:
            # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
            brightness: 0
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: cover
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true
  #- block: features
    #id: howitworks
    #content:
      #title: HOW IT WORKS
      #items:
        #- name: 10,000,000 $ERC50
          #icon: magnifying-glass
          #description: Can be swapped for a Common NFT.
        #- name: 15,000,000 $ERC50
          #icon: bolt
          #description: Can be swapped for a Rare NFT.
        #- name: 20,000,000 $ERC50
          #icon: sparkles
          #description: Can be swapped for a Mythic NFT.
        #- name: 50,000,000 $ERC50
          #icon: code-bracket
          #description: Can be swapped for a 1/1 NFT.
        #- name: Royalty fee
          #icon: star
          #description: A 3.33% Royalty fee  for NFT Marketplaces.
        #- name: Trade
          #icon: rectangle-group
          #description: Trade on any marketplace that enforces royalties on token extension NFTs.
  - block: cta-image-paragraph
    id: about
    content:
      items:
        - title: By being $LAZe, we are rich 🤑
          #text: 'We partnered with SolSniper to bring you the #1 SPL404 on Solana. More partnership announcements soon.'
          feature_icon: check
          features:
            - Presale
            - Launch Dexscreen
            - Be Rich!
          # Upload image to `assets/media/` and reference the filename here
          image: bald.jpeg
          button:
            text: Learn More
            url: 
        #- title: Cex Listings
          #text: Join our large community and buy at your favorite Cex.
          #feature_icon: bolt
          #features:
            #- Bybit
            #- Gate.io
            #- Binance
          # Upload image to `assets/media/` and reference the filename here
          #image: howdoesitwork.jpeg
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  #- block: testimonials
    #content:
      #title: ""
      #text: ""
      #items:
        #- name: "Hugo Smith"
          #role: "Marketing Executive at X"
          ## Upload image to `assets/media/` and reference the filename here
          #image: "testimonial-1.jpg"
          #text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!"
    #design:
      #spacing:
        ## Reduce bottom spacing so the testimonial appears vertically centered between sections
        #padding: ["6rem", 0, 0, 0]
  #- block: cta-card
    #content:
      #title: Build your future-proof website
      #text: As easy as 1, 2, 3!
      #button:
        #text: Get Started
        #url: https://hugoblox.com/templates/
    #design:
      #card:
        ## Card background color (CSS class)
        #css_class: "bg-primary-700"
        #css_style: ""
---
