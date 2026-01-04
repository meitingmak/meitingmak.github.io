---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      #button:
      #  text: Download CV
      #  url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        My main interest lies in understanding how photochemical hazes can impact the atmospheric structure among different types of planets, and how these effects, in turn, shape their habitability and observability. Currently, I am investigating how atmospheric transport processes lead to asymmetrical haze distributions across a planet’s atmosphere, and how these variations can be detected with state-of-the-art telescopes such as the James Webb Space Telescope. 

        Please reach out to collaborate 😃
    design:
      columns: '1'
  #- block: collection
  #  id: papers
  #  content:
  #    title: Featured Publications
  #      folders:
  #    filters:
  #        - publications
  #      featured_only: true
  #  design:
  #    view: article-grid
  #    columns: 2
  #- block: collection
  #  id: papers
  #  content:
  #    title: Recent Publications
  #    text: ''
  #    filters:
  #      folders:
  #        - publications
  #      exclude_featured: false
  #  design:
  #    view: citation
  - block: markdown
    id: papers
    content:
      title: First-author Publications
      text: |-
        - **Mak, M. T.**, Komacek, T., Mayne, N.
        *Predicting The Distribution of Photochemical Hazes Across The Two Limbs of hot-Jupiters*  
        [in prep.]

        - **Mak, M. T.**, Sergeev, D., Mayne, N., Manners, J., Zamyatina, M., Steinrueck, M., et al.
        *3D simulations of TRAPPIST-1e with varying CO2, CH4, and haze profiles*  
        [Monthly Notices of the Royal Astronomical Society, Volume 542, Issue 3, pp.1873–1900 (2025)](https://academic.oup.com/mnras/article/542/3/1873/8217259?login=true)

        - **Mak, M. T.**, Sergeev, D., Mayne, N., Banks, N., Eager-Nash, J., Manners, J., Arney, G., et al.
        *3D simulations of TRAPPIST-1e with varying CO2, CH4, and haze profiles*  
        [Monthly Notices of the Royal Astronomical Society, Volume 530, Issue 3, pp.2933-2933 (2024)](https://academic.oup.com/mnras/article/529/4/3971/7633970?login=true)
    
        - **Mak, M. T.**, Mayne, N., Sergeev, D., Eager-Nash, J., Manners, J., Hebrard E., Kohary, K. 
        *3D Simulations of the Archean Earth Including Photochemical Haze Profiles*  
        [Journal of Geophysical Research: Atmospheres, Volume 128, Issue 20 (2023)](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2023JD039343)
    design:
      columns: '1'
  - block: markdown
    content:
      title: Co-author Publications
      text: |-
        - Adams, S., Manners, J., Mayne, N., et al., **incl. Mak, M. T.**<br>    
        *Benchmarking Photolysis Rates: Species for Earth and Exoplanets*    
        [EGUsphere in review]

        - Mukherjee, S., Sings, D., Fu, G., et al., **incl. Mak, M. T.**<br>    
        *Cloudy mornings and clear evenings on a giant extrasolar world*    
        [accepted in Science]

        - Li, H., Wang, X., Dong, C., et al., **incl. Mak, M. T.**<br>        
        *Modeling Atmospheric Ion Escape from Kepler-1649 b and c over Time*          
        [The Astrophysical Journal Letters, Volume 994, Number 2, L50 (2025)](https://iopscience.iop.org/article/10.3847/2041-8213/ae1a65)

        - Eager-Nash, J., Daines, S., McDermott, J., et al., **incl. Mak, M. T.**<br>
        *Simulating biosignatures from pre-oxygen photosynthesizing life on TRAPPIST-1e*  
        [Monthly Notices of the Royal Astronomical Society, Volume 531, Issue 1, pp.468-494 (2024)](https://academic.oup.com/mnras/article/531/1/468/7659831?login=true)
    
        - Villanueva, G., Fauchez, T., Kofman, V., et al., **incl. Mak, M. T.**<br>
        *Modeling Atmospheric Lines by the Exoplanet Community (MALBEC) Version 1.0: A CUISINES Radiative Transfer Intercomparison Project*  
        [The Planetary Science Journal, Volume 5, Issue 3, id.64, 15 pp (2024)](https://iopscience.iop.org/article/10.3847/PSJ/ad2681)
    design:
      columns: '1'
  #- block: collection
  #  id: talks
  #  content:
  #    title: Recent & Upcoming Talks
  #    filters:
  #      folders:
  #        - events
  #  design:
  #    view: card
  #- block: markdown
  #  id: news
  #  content:
  #    title: Recent News
  #    subtitle: ''
  #    text: |-
  #        📣 <strong>Recent News:</strong>  
  #      <p style="font-size:1.2rem;">
  #        <a href="https://croucher.org.hk/en/fellows-and-scholars/martha-mak" target="_blank" style="border-bottom:2px solid currentColor;">
  #        I have been awarded a Croucher Fellowship at Oxford →
  #        </a>
  #      </p>
 
  #  design:
  #    columns: '1'

  - block: cta-card
    id: news
    content:
      title: "Croucher Fellowship"
      text: |
        I am delighted to share that I have been appointed a Croucher Fellow by the Croucher Foundation to conduct postdoctoral research at the University of Oxford.
    
        <div style="margin-top:1rem;">
          <a class="btn btn-primary"
             style="display:block; margin-bottom:0.75rem; text-decoration: underline;"
             href="https://croucher.org.hk/en/news/welcome-croucher-class-of-2025"
             target="_blank">
             Click here to read the announcement!
           </a>

           <a class="btn btn-primary"
              style="display:block; text-decoration: underline;"
              href="https://croucher.org.hk/en/fellows-and-scholars/martha-mak"
              target="_blank">
              Clich here to read my Croucher Fellow profile!
           </a>
        </div>
    design:
      card:
        css_class: "bg-primary-200 dark:bg-primary-800"
  - block: cta-card
    content:
      title: "Bell Burnell Graduate Scholarship Fund"
      text: |
        I am honoured to have been awarded the Bell Burnell Graduate Scholarship Fund by the Institute of Physics, supporting my research and academic development.

        <div style="margin-top:1rem;">
          <a class="btn btn-primary"
             style="display:block; margin-bottom:0.75rem; text-decoration: underline;"
             href="https://news-archive.exeter.ac.uk/homepage/title_860428_en.html"
             target="_blank">
             Click here to read the announcement!
           </a>

           <a class="btn btn-primary"
              style="display:block; text-decoration: underline;"
              href="https://www.iop.org/about/support-grants/bell-burnell-fund/2021-awardees/mei-ting-mak"
              target="_blank">
              Clich here to read my interview!
           </a>
    
           <a class="btn btn-primary"
              style="display:block; text-decoration: underline;"
              href="https://www.youtube.com/watch?v=N0bJpAnBX4k"
              target="_blank">
              Clich here to watch the awardees, including me, and Dame Jocelyn Bell Burnell share the impact the scholarship fund is making!
           </a>
        </div>
    design:
      card:
        css_class: "bg-primary-200 dark:bg-primary-800"



  #- block: collection
  #  id: news
  #  content:
  #   title: Recent News
  #    subtitle: ''
  #    text: ''
  #    # Page type to display. E.g. post, talk, publication...
  #    page_type: blog
  #    # Choose how many pages you would like to display (0 = all pages)
  #    count: 10
  #    # Filter on criteria
  #    filters:
  #      author: ''
  #      category: ''
  #      tag: ''
  #      exclude_featured: false
  #      exclude_future: false
  #      exclude_past: false
  #      publication_type: ''
  #    # Choose how many pages you would like to offset by
  #    offset: 0
  #    # Page order: descending (desc) or ascending (asc) date.
  #    order: desc
  #  design:
  #    # Choose a layout view
  #    view: card
  #    # Reduce spacing
  #    spacing:
  #      padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-primary-300 dark:bg-primary-700'
        css_style: ''
---
