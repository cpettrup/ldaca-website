---
layout: home
title: "Process & analyse"
---

<SimpleHero breadcrumb="Working with data > Process & analyse" title="Process & analyse data" description="Hands-on tutorials and tools for processing and analysing large collections of language data."/>

<SimpleNavigation
title="Analysing language data at scale"
description="Being able to analyse large amounts of language data opens up vast possibilities for researchers across disciplines. Language data may also need to be cleaned and processed in other ways to suit your research purposes. We are making tools for text analysis available, alongside our collaborators including Language Technology and Data Analysis Laboratory (LADAL), Sydney Corpus Lab, Sydney Informatics Hub (SIH), QUT Digital Observatory and the Melbourne Data Analytics Platform.\n\nTest out tools for processing and analysing data and access analysis and reuse training and tutorials for a diverse range of skill levels."
:contents="[
    { label: 'Analytical tools & notebooks', href: '#tools-notebooks' },
    { label: 'Guides', href: '#guides' },
    { label: 'On the blog', href: '#on-the-blog' },
    { label: 'Additional resources', href: '#additional-resources' },
    { label: 'Collaborators', href: '#collaborators' }
  ]"
/>

<ToolsGrid 
  id="tools-notebooks"
  heading="ANALYTICAL TOOLS & NOTEBOOKS"
  description="Explore available tools for language research and work."
  crate="https://raw.githubusercontent.com/Language-Research-Technology/ldaca-analytical-tools/refs/heads/main/ro-crate/ro-crate-metadata.json"
  />

<GuideCarousel 
  id="guides"
  heading="GUIDES"
  :items="[
      {
        title: 'Introduction to Text Analysis',
        description: 'An introduction to working with text as data. Covers key text analysis concepts and the workflow from preparing and analysing text through to documenting and packaging research outputs for reuse.',
        link: 'https://www.atap.edu.au/text-analysis/overview/',
        level: 'Beginner',
        audience: 'Researchers and students',
        image:'/images/PlainBackgrounds/Blackplain.png',
        category: 'FIELD GUIDE'
      },
      {
        title: 'Text Analytics',
        description: 'A LADAL tutorial introducing text analysis in R and a range of text analytics methods. Some familiarity with R and RStudio is required, so we recommend being comfortable with the material covered in the R Basics section before getting started.',
        level: 'Beginner-Intermediate',
        audience: 'Researchers and students interested in learning R',
        category: 'TECHNOLOGIES GUIDE',
        buttonColor: '#393939',
        image:'/images/PlainBackgrounds/Greenplain.png',
        link: 'https://ladal.edu.au/tutorials.html#text-analytics'
      },
    ]"/>

<Carousel 
  id="on-the-blog"
  shade="light"
  backgroundColor="#EAE4D68C"
  :opacity="100"
  heading="ON THE BLOG"
  :items="[
      {
        title: 'Analyse image collections with the Image Dataset Explorer',
        link: '/resources/posts/image-dataset-explorer'
      },
      {
        title: 'Team member tip: There\'s no substitute for looking closely at the data',
        link: '/resources/posts/team-member-tip-sam-hames'
      },
      {
        title: 'Putting data to work — 2',
        link: '/resources/posts/putting-data-to-work-2'
      }
    ]"/>

<ThreeTiles 
  id="additional-resources"
  backgroundColor="#EAE4D68C"
  :opacity="100"
  heading="ADDITIONAL RESOURCES"
  :items="[
      {
        title: 'FIB DigiTalk 2025 ke-7, \'Using Large Data Sets for Qualitative Research\'',
        image: '/working-with-data/process-analyse/FIBDigiTalk2025.png',
        link: 'https://www.youtube.com/live/twCAdPazV2M',
        category: 'RECORDING'
      },
      {
        title: 'The ParlaMint corpora of European parliamentary proceedings',
        link: '/training-events/events/2025/parlamint-corpora',
      },
       {
        title: 'Vulgarity in English: Language, Creativity & Social Meaning',
        image: '/working-with-data/process-analyse/ISLE.png',
        link: 'https://www.youtube.com/watch?v=l3K4v4LtDTQ',
        category: 'RECORDING'
      },
    ]"/>

<Collaborators 
  id="collaborators"
  heading="COLLABORATORS"
  :items="[
      {
        title: 'Sydney Corpus Lab',
        image: '/images/partner-logos/cropped-SydneyCorpusLab_Black_Small.png',
        link: 'https://sydneycorpuslab.com/'
      },
      {
        title: 'Sydney Informatics Hub',
        image: '/images/partner-logos/sydney_informatics_hub_logo.png',
        link: 'https://www.sydney.edu.au/research/facilities/sydney-informatics-hub.html'
      },
      {
        title: 'LADAL',
        image: '/images/partner-logos/ladal_logo.png',
        link: 'https://ladal.edu.au/'
      },
      {
        title: 'ADO',
        image: '',
        link: 'https://www.digitalobservatory.net.au/'
      },
      {
        title: 'MDAP',
        image: 'https://dataservices.research.unimelb.edu.au/static/img/logos/logo-2023.svg',
        link: 'https://www.unimelb.edu.au/mdap'
      },
    ]"/>

<ContactBox 
  heading="Interested in contributing to LDaCA?"
  description="Do you have data, expertise or resources you'd like to share? We'd love to hear from you."
  buttonText="Get in touch"
  buttonLink="/contact/"
/>