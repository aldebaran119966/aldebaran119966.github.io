---
title: 'ERC50'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: LAZY OLD MAN
      text: $LAZE is an ERC50 blah blah blah
      primary_action:
        text: Dexscreener
        url: https://dexscreener.com/
        icon: gitlab
      #secondary_action:
        #text: Read the docs
        #url: https://docs.hugoblox.com
      announcement:
        text: "CoRkC3r6MqYuTeMRc7D8JJF7UiUyFWurXGpYy1xQATNq"
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
        - statistic: "60M"
          description: |
            (70%)  
            Public Sale
        - statistic: "10M"
          description: |
            (10%)  
            Utility
        - statistic: "5M"
          description: |
            (20%)  
            Early Developers
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: howitworks
    content:
      title: HOW IT WORKS
      items:
        - name: 10,000,000 $ERC50
          icon: magnifying-glass
          description: Can be swapped for a Common NFT.
        - name: 15,000,000 $ERC50
          icon: bolt
          description: Can be swapped for a Rare NFT.
        - name: 20,000,000 $ERC50
          icon: sparkles
          description: Can be swapped for a Mythic NFT.
        - name: 50,000,000 $ERC50
          icon: code-bracket
          description: Can be swapped for a 1/1 NFT.
        - name: Royalty fee
          icon: star
          description: A 3.33% Royalty fee  for NFT Marketplaces.
        - name: Trade
          icon: rectangle-group
          description: Trade on any marketplace that enforces royalties on token extension NFTs.
  - block: cta-image-paragraph
    id: about
    content:
      items:
        - title: <project_name> Partners
          text: 'We partnered with SolSniper to bring you the #1 SPL404 on Solana. More partnership announcements soon.'
          feature_icon: check
          features:
            - blah blah blah
            - blah blah blah
            - blah blah blah
          # Upload image to `assets/media/` and reference the filename here
          image: bald.jpeg
          button:
            text: Learn More
            url: 
        - title: Cex Listings
          text: Join our large community and buy at your favorite Cex.
          feature_icon: bolt
          features:
            - Bybit
            - Gate.io
            - Binance
          # Upload image to `assets/media/` and reference the filename here
          image: Topplayers.png
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: cta-card
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        text: Read my latest paper on LLMs
        icon: academicons/arxiv
        url: https://arxiv.org/abs/2304.01852
        #- text: Watch my new YouTube video to achieve 20x productivity
          #icon: brands/youtube
          #url: https://youtube.com
        #- text: Connect with me on LinkedIn
          #icon: brands/linkedin
          #url: https://linkedin.com
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
