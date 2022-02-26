- Curso React Avançado

  Essa landing page é um módulo extra do curso React Avançado, ministrado pelo Prof. Willian Justen para introduzir o Strapi como CMS que será usado como ferramenta para a construção do Projeto Won Games.

  ## Estrutura do Projeto

  Tipo: Single Page

  Nome da página: LandingPage

  ### Campos que compõem a página

  ### Header

  - Estrutura: media

  - Nome do campo: logo

  - Tipo do campo: single media

  - Required field: true

  - Type of media: image

  ------

  - Estrutura: component

  - Nome do campo: header

  - Category: page

  - Tipo do campo: single component

  - Required field: false

  - Icon: H

  ------

  - 
    - Estrutura: text
    - Nome do campo: title
    - Tipo do campo: short text
    - Required field: true

  ------

  - 
    - Estrutura: text
    - Nome do campo: description
    - Tipo do campo: long text
    - Required field: true

  ------

  - 
    - Estrutura: button
    - Nome do campo: button
    - Category: page
    - Tipo do campo: single component
    - Required field: false
    - Icon: url

  
  ------
  
  - 
    - 
      - Estrutura: text
      - Nome do campo: label
      - Tipo do campo: short text
      - Required field: true
      - Maximum length: 20
  

  ------

  - 
    - 
      - Estrutura: text
      - Nome do campo: url
      - Tipo do campo: short text

    - Required field: true

  
  ------
  
  - 
    - Estrutura: image
    - Nome do campo: image
    - Tipo do campo: single media
    - Required field: true
    - Type of media: Images

  
  ------
  
  ### About Project
  
  - Estrutura: component
  
  - Nome do campo: sectionAboutProject
  
  - Category: page
  
  - Tipo do campo: single component
  
  - Required field: false
  
  - Icon: Information
  
  ------
  
  - Estrutura: text
  
  - Nome do campo: title
  
  - Tipo do campo: short text
  
  - Required field: true
  
  ------
  
  - Estrutura: rich text
  
  - Nome do campo: description
  
  - Required field: true
  
  ------
  
  - Estrutura: media
  
  - Nome do campo: image
  
  - Tipo do campo: single media
  
  - Required field: true
  
  - Type of media: images
  
  ------
  
  ### Section Tech
  
  - Estrutura: component
  
  - Nome do campo: sectionTech
  - Category: page

  - Tipo do campo: single component

  - Icon: tool

  ------
  
  - Estrutura: text
  
  - Nome do campo: title
  
  - Tipo do campo: short text
  
  - Required field: true
  
  ------
  
  - 
    - Estrutura: component
    - Nome do campo: techicons
    - Category: page
    - Tipo do campo: repeatable component
    - Maximum value: 10 
    - Minimum value: 5
    - Icon: tool

  
  ------

  - 
    - 
      - Estrutura: media
      - Nome do campo: icon
      - Tipo do campo: multiple media
      - type of media: images
      - Required field: true

  
  ------
  
  - Estrutura: text
  
  - Nome do campo: title

  - Tipo do campo: short text

  - Required field: true

  ------

  ### Section Concepts

  - Estrutura: component

  - Nome do campo: sectionConcepts
  - Category: page
  
  - Tipo do campo: single component
  
  - Icon: página
  
  ------
  
  - Estrutura: text

  - Nome do campo: title

  - Tipo do campo: short text

  - Required field: true

  ------

  - 
    - Estrutura: component
    - Nome do campo: concepts
    - Category: page
    - Tipo do campo: repeatable component
    - Icon: outra página
  

  ------

  - 
    - 
      - Estrutura: text
      - Nome do campo: title
      - Tipo do campo: short text
      - Required field: true

  
  ------
  
  ### Section Modules
  
  - Estrutura: component
  
  - Nome do campo: sectionModules
  - Category: page

  - Tipo do campo: single component

  - Icon: livro

  ------

  - Estrutura: text
  
  - Nome do campo: title
  
  - Tipo do campo: short text
  
  - Required field: true
  
  ------
  
  - Estrutura: component
  
  - Nome do campo: modules
  - Category: page

  - Tipo do campo: repeateble component
  - Requered: true
  - minimum: 2

  - Icon: paper

  ------
  
  - Estrutura: text
  
  - Nome do campo: title
  
  - Tipo do campo: short text
  
  - Required field: true
  
  ------
  
  - Estrutura: text
  
  - Nome do campo: subTitle
  
  - Tipo do campo: short text
  
  - Required field: true
  
  ------
  
  - Estrutura: rich text
  
  - Nome do campo: description
  
  - Required field: true
  
  ------
  
  ### Section Agenda
  
  - Estrutura: component
  
  - Nome do campo: sectionAgenda
  - Category: page

  - Tipo do campo: single component
  - Requered: true
  
  - Icon: calendar
  
  ------
  
  - Estrutura: text

  - Nome do campo: title
  
  - Tipo do campo: short text
  
  - Required field: true
  
  ------
  
  - Estrutura: rich text
  
  - Nome do campo: description
  
  - Required field: true
  
  ------
  
  ### Pricing Box
  
  - Estrutura: component
  - Nome do campo: pricingBox
  - Category: page
  - Tipo do campo: single component
  - Required: true
  - Icon: $

  ------

  - Estrutura: number
  
  - Nome do campo: totalPrice
  
  - Tipo do campo: integer
  
  - Required field: true
  - Default value: 415

  ------

  - Estrutura: number

  - Nome do campo: numberInstallments

  - Tipo do campo: integer
  
  - Required field: true
  
  ------
  
  - Estrutura: number
  
  - Nome do campo: priceInstallments
  
  - Tipo do campo: integer
  
  - Required field: true
  
  ------
  
  - Estrutura: rich text
  
  - Nome do campo: benefits
  
  - Default value: Create items as bullet list
  
  - Required field: true
  
  ------
  
  - Estrutura: component
  
  - Nome do campo: button
  - Category: page

  - Tipo do campo: Use an existing component
  - Name: button
  
  - Type: single component
  - Select component: button

  ------
  
  ### Collection Authors
  
  - Estrutura: collection type

  - Nome do campo: author
  
  ------
  
  - Estrutura: media
  
  - Nome do campo: photo
  - Category: page

  - Tipo do campo: single media
  - Requered: true
  
  - Type of media: images
  
  ------
  
  - Estrutura: text

  - Nome do campo: name
  
  - Tipo do campo: short text
  
  - Required field: true
  
  ------
  
  - Estrutura: text
  
  - Nome do campo: role
  
  - Tipo do campo: short text
  
  - Required field: true
  
  ------
  
  - Estrutura: component
  
  - Nome do campo: socialLinks
  - Category: page

  - Tipo do campo: repeatable component
  - Required: true
  
  - Icon: network
  
  ------
  
  - Estrutura: enumeration

  - Nome do campo: title
  
  - Values
    - Github
    - Twitter
    - Dribble
    - LinkedIn
    - Facebook
  - Default value: Twitter
  - Required: true

  ------
  
  - Estrutura: text
  
  - Nome do campo: url
  - Tipo do campo: short text
  
  - Required: true

  ------

  - Estrutura:  text

  - Nome do campo: description
  - Tipo do campo: long text

  - Required: true

  ------

  ### Section About Us

  - Estrutura: component
  
  - Nome do campo: sectionAboutUs
  - Category: page

  - Tipo do campo: single component
  - Required: true
  
  - Icon: author
  
  ------
  
  - Estrutura:  text

  - Nome do campo: title
  - Tipo do campo: short text

  - Required: true

  ------

  - Estrutura:  relation

  - Relação: 1 para muitos
  
  ------
  
  ### Section Reviews
  
  - Estrutura: component
  
  - Nome do campo: sectionReviews
  - Category: page

  - Tipo do campo: single component
  - Required: true
  
  - Icon: star
  
  ------
  
  - Estrutura:  text

  - Nome do campo: title
  - Tipo do campo: long text

  - Required: true

  ------

  - Estrutura: component
  - Nome do campo: reviews
  - Category: page
  - Tipo do campo: repeatable component
  - Required: true
  - Minimum value: 4
  - Icon: star
  
  ------
  
  - Estrutura:  text
  
  - Nome do campo: name
  - Tipo do campo: short text
  
  - Required: true

  ------

  - Estrutura:  text

  - Nome do campo: text
  - Tipo do campo: long text

  - Required: true

  ------

  - Estrutura:  media

  - Nome do campo: photo
  - Tipo do campo: single media
  - type of media: imagens
  
  - Required: false
  
  ------
  
  ### Section FAQ
  
  - Estrutura: component
  - Nome do campo: sectionFaq
  - Category: page
  - Tipo do campo: single component
  - Required: true
  - Icon: question

  ------

  - Estrutura:  text
  
  - Nome do campo: title
  - Tipo do campo: long text
  
  - Required: true

  ------

  - Estrutura: component
  - Nome do campo: questions
  - Category: page
  - Tipo do campo: repeatable component
  - Required: true
  - Minimum value: 2
  - Icon: question
  
  ------
  
  - Estrutura:  text
  
  - Nome do campo: question
  - Tipo do campo: long text
  
  - Required: true

  ------

  - Estrutura: rich text

  - Nome do campo: answer
  - Tipo do campo: long text

  - Required: true
