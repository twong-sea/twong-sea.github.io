---
# Display name
title: Trevor Wong

# Name pronunciation (optional)
#name_pronunciation: Chien Shiung Wu

# Full name (for SEO)
first_name: Trevor
last_name: Wong

# Status emoji
#status:
#  icon: 🍜

# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role: Data & Analytics Professional

# Organizations/Affiliations to display in Biography blox
#organizations:
  #- name: GenCoin
  #  url: https://www.example.com/

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  #- icon: email-svgrepo-com
  - icon: hero/envelope
    url: 'mailto:trevor@trevorwong.com'
    label: E-mail Me
  #- icon: brands/x
  #  url: https://twitter.com/GetResearchDev
  - icon: brands/github
    url: https://github.com/twong-sea
    label: Github
  - icon: brands/linkedin
    url: https://www.linkedin.com/in/trevor-wong-sea/
    label: LinkedIn
  #- icon: brands/instagram
  #  url: https://www.instagram.com/

education:
  - area: Certificate in Geographic Information Systems (GIS)
    institution: University of Washington
    date_start: 2010-09-01
    date_end: 2011-06-01
    summary: |
      - Professional and Continuing Education program teaching GIS skills using ArcGIS.
      - Course content covered site selection, IDW/Spline/Krieg interpretation methods, and cartography.
      - Won 2nd place in the Richard ‘Dick’ Thomas Student Presentation Competition at the 2011 Washington GIS Conference with a presentation on modeling forestry land sale prices.
# maybe use this for Projects
#    button:
#      text: 'Read Thesis'
#      url: 'https://example.com'
  - area: Bachelor of Arts - Political Science, Minor in Chemistry
    institution: University of Washington
    date_start: 2003-09-01
    date_end: 2008-06-01
    #summary: |
#      GPA: 3.8/4.0
#
#      Courses included:
#      - lorem ipsum dolor sit amet, consectetur adipiscing elit
#      - lorem ipsum dolor sit amet, consectetur adipiscing elit
#      - lorem ipsum dolor sit amet, consectetur adipiscing elit

work:
  - position: Senior Analytics Consultant
    company_name: Amperity
    company_url: 'https://www.amperity.com'
    company_logo: 'amperity_favicon_inkscape'
    date_start: 2022-05-01
    date_end: 2024-01-31
    summary: |2-
      - Served eight client companies in retail, travel, and transportation industries ranging from $10 million to $10 billion in revenue
      - Produced and presented email campaign reporting to demonstrate effectiveness of multi-flight campaigns
      - Used Regex parsing on 32,000 unformatted data fields to analyze customer spending and lead-to-sale timing
      - Developed method for appending demographic information to 135 million limited PII records
      - Created statistical model assigning gender probabilities from 157 nationalities and ethnic groups to limited PII customer records, improving prediction rates by 25% over existing model
      - Drove adoption of in-platform client-accessible reporting
  - position: Project Manager, Campaigns & Ripple
    company_name: BlueLabs
    company_url: ''
    company_logo: ''
    date_start: 2020-03-01
    date_end: 2022-04-30
    summary: |
      - Analyzed demographic data, historic election results, and past violations of voting rights to geographically target areas in need of Voter Protection support during the 2020 election
      - Validated person-level religiosity models and generated insights and use- cases for client
      - Created analysis and reports of client-facing influencers database to demonstrate value to customers and reference for relationship expansion
      - Produced network graph expansions using Python and Gremlin Querying Language
      - Generated and delivered survey samples from occupation and donation data
  - position: Tools Support Engineer
    company_name: Catalist
    company_url: ''
    company_logo: ''
    date_start: 2017-11-01
    date_end: 2020-02-20
    summary: |
      - Transitioned user creation workflow to incorporate third party SSO vendor
      - Created Tableau reporting of user behavior for product optimization
      - Designed user permissioning structures for next generation identity resolution platform
  - position: Battleground States Analytics Lead / GIS Administrator
    company_name: Hillary for America
    company_url: ''
    company_logo: ''
    date_start: 2016-06-01
    date_end: 2016-11-20
    summary: |
      - Led Strategic planning and goals creation for national field program with over 2,600 organizers and 1.8 million volunteers
      - Deployed PostgreSQL/PostGIS geodatabase and other GIS tools to 70 state analytics staff
      - Developed geographic reporting
      - Established metrics, analytics frameworks, and data reporting tools to assess voter contact performance in Ohio, Pennsylvania, and Virginia
      - Optimized Iowa early vote locations using spatial analysis to maximize turnout    
# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  #- name: Technical Skills
  - name:
    items:
      - name: SQL
        description: 'PostgreSQL, Vertica, Redshift, Presto, Spark'
        percent: 100
        icon: hero/circle-stack
      - name: Spatial Analysis
        description: 'PostGIS, ArcGIS, QGIS'
        percent: 100
        #icon: chart-bar
        #icon: analysis-svgrepo-com
        icon: map
      - name: Business Intelligence
        description: 'Tableau, Looker, Google Data Studio, Power BI'
        percent: 100
        #icon: code-bracket
        #icon: business-information-reporting-svgrepo-com
        icon: chart-bar
      - name: Retail Analytics
        description: 'Discounting, Marketing Measurement, Customer Segmentation, Site Selection'
        percent: 80
        #icon: business-information-reporting-svgrepo-com
        #icon: building-storefront
        icon: shopping-bag
  #- name: Soft Skills
  - name: 
    color: '#eeac02'
    color_border: '#f0bf23'
    items:
      - name: Training
        description: 'SQL, QGIS, Excel'
        percent: 80
        #icon: person-simple-walk
        #icon: training-class-svgrepo-com
        icon: academic-cap
      - name: Presentations
        description: 'Powerpoint, Slides, Keynote'
        percent: 80
        #icon: camera
        icon: presentation-6-svgrepo-com
        #icon: presentation-chart-line
      - name: Project Management
        description: 'Jira, Asana, Confluence'
        percent: 60
        #icon: cat
        icon: jira-svgrepo-com_mod
        #icon: briefcase
      - name: Product Development
        description: 'UI Design, UI Testing'
        percent: 40
        #icon: cat
        #icon: jira-svgrepo-com
        icon: light-bulb
#these are represented by 
#languages:
#  - name: English
#    percent: 100
#  - name: Chinese
#    percent: 75
#  - name: Portuguese
#    percent: 25

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
awards: #actually projects
# icons for this are placed in the "brands" folder
  - title: Limited PII Gender Model
    #url: https://www.coursera.org/learn/neural-networks-deep-learning
    date: '2023-12-25'
    awarder: Amperity
    icon: amperity_favicon_inkscape
    summary: |
      Created statistical model assigning gender probabilities from 157 nationalities and ethnic groups to customer records with limited PII (Personally identifiable information), improving prediction rates by 25% over existing model.

  - title: 'Recount 2020 - Arizona Data Director'
    date: '2020-11-01'
    awarder: Recount 2020
    icon: vote_icon
    summary: |
      Recount 2020 was a project to provide data and analytics support to legal efforts around the 2020 election. I led Recount 2020's data operations for Arizona. Duties included projecting likelihood of a recount, preparing for ballot curing, and creating data pipelines of election result data.

  - title: Chefs for the Polls - Site Selection
    url: https://wck.org/news/chefsforthepolls
    date: '2020-10-01'
    #date_end: '2021-01-01'
    awarder: World Central Kitchen
    icon: wck_favico_inkscape_mod
    #icon: xworld-central-kitchen-logo-vector
    summary: |
      World Central Kitchen (WCK) planned to place food trucks outside polling locations for the 2020 General and 2020 Georgia Runoff elections. 

      - Created a model to forecast voting irregularities in FL, GA, and NC
      - Scraped polling location precinct assignments using the Google Civic API
      - Used Spatial Analysis to determine food truck locations that could serve multiple priority voting sites


  - title: 'Understanding Policy Influencers’ Priorities in a Post-COVID World'
    url: https://www.slideshare.net/GloverParkGroup/navigating-covid19-may-26
    #url: https://fgsglobal.com/insights/report-understanding-policy-influencers-priorities-in-a-post-covid-world
    #presentation_url: https://www.slideshare.net/GloverParkGroup/navigating-covid19-may-26
    date: '2020-05-01'
    awarder: Glover Park Group
    icon: Glover_Park_Group_inkscape
    summary: |
      Survey of Policy Influencers (Elected Officials, Staffers, Business Leaders, Major Donors) attitudes toward COVID response. Findings include heavy political polarization with a small group of persuadable Republicans.

  - title: 'Data BootCamp Coach'
    #url: https://www.slideshare.net/GloverParkGroup/navigating-covid19-may-26
    #url: https://fgsglobal.com/insights/report-understanding-policy-influencers-priorities-in-a-post-covid-world
    #presentation_url: https://www.slideshare.net/GloverParkGroup/navigating-covid19-may-26
    date: '2016-02-01'
    awarder: Wellstone Action
    icon: wellstone_action
    summary: |
      Coached students through an intensive six day bootcamp designed to prepare the next generation of political data professionals. Students went on to work in multiple states and organizations in the 2016 campaign.

---

Seasoned Data Analyst with 12 years of expertise in various SQL dialects and spatial analysis. Proficient in BI Tools such as Tableau, Looker Studio, and Power BI. Known for discovering actionable insights and delivering compelling presentations to stakeholders. Conducts training sessions on GIS and other data-related skills.
Loves spatial analysis, data visualization, and ramen.
