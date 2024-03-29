---
title: Three printmakers at Artweeks 2022
permalink: /three-printmakers/
display_title: true
display_image: true
thumb_crop: true
display_thumb_title: true
frontpage: true
archive: false
gallery_date: 2022-02-27 00:00:00
copy_html: >-
  <p>Three printmakers: Lucy Tennyson, Nic Hamilton and Biddy Hudson exhibiting
  at the easyHotel in Summertown. <a
  href="https://www.artweeks.org/v/nicholas-hamilton-biddy-hudson-opc-lucy-tennyson-opc">Visit
  the Artweeks website for more
  information.</a></p><div><div><div><p><strong>Nic Hamilton</strong> : My work
  takes inspiration from the city of Oxford. Walking the lanes and alleys
  between the colleges has for many years provided me with sites of potential
  narrative content; finding resonance the 1940's films such as "The Third
  Man".</p></div></div></div><div><div>Sites explored through drawing and
  photography include the lanes and alleys of Oxford at twilight, the
  interweaving of plant forms with structure at Oxford Botanic Gardens and
  abstract work exploring the idea movement and
  equilibrium.</div><div>&nbsp;</div><div><strong>Lucy Tennyson</strong>: My
  theme is the bridges and waterways of Oxford. I discovered another side and
  viewpoint of the city &nbsp;when I started kayaking along its&nbsp; many
  waterways</div><div>My Artweeks exhibition is based on a walk (or paddle)
  upstream starting at Folly Bridge.</div></div>
homepage_description_markdown: >-
  Three printmakers: Lucy Tennyson, Nic Hamilton and Biddy Hudson exhibiting at
  the easyHotel in Summertown
main_image_path: /uploads/bridge1-1.JPG
main_image_caption: >-
  Three printmakers Lucy Tennyson, Nic Hamilton and Biddy Hudson exhibiting at
  the easyHotel in Summertown
images:
  - image_path: /uploads/bridge1.JPG
    image_title: 'Lucy Tennyson: Folly Bridge1'
    image_description:
  - image_path: /uploads/5--bridge.JPG
    image_title: 'Lucy Tennyson: Bridge'
    image_description:
  - image_path: /uploads/bridge2.JPG
    image_title: Oxford bridge
    image_description:
  - image_path: /uploads/nic-hamilton-pic.jpg
    image_title: 'Nic Hamilton: Oxford lane'
    image_description:
  - image_path: /uploads/nichamilton2.jpg
    image_title: 'Nic Hamilton: Oxford lane '
    image_description:
_inputs:
  title:
    label: Gallery title
  permalink:
    label: URL
    comment: The folder address of your gallery e.g. */gallery-name/*
  main_image_path:
    type: image
    label: Featured image
    comment: Main full width image for the page
    options:
      uploads_dir: assets/images/:year
      width: 1200
      height: 1200
      resize_style: contain
      mime_type: image/jpeg
  main_image_caption:
    type: text
    label: Featured image description
    comment: Essential hidden text that describes your image
  frontpage:
    label: Show gallery on home page
    type: switch
  gallery_date:
    label: Gallery date
    comment: May be used to order your galleries on the gallery and home pages
  display_title:
    type: switch
    label: Show gallery title at top of gallery
  display_image:
    type: switch
    label: Show main image at top of gallery
  thumb_crop:
    type: switch
    label: Crop thumbnail images
  archive:
    type: switch
    label: Archive this gallery
    comment: Archiving will keep your page, but hide it from the public
  display_thumb_title:
    type: switch
    label: Display titles with thumbnails
  homepage_description_markdown:
    label: Home page description
    comment: This text is displayed on the home page
    options:
      bold: true
      format: p h2 h3 h4 h5 pre address div
      italic: true
      numberedlist: true
      bulletedlist: true
      image: true
      link: true
      styles: /css/editor.scss
      center: center-this-text
      left: align-left
      right: align-right
  copy_html:
    type: html
    label: Gallery page text
    comment: This text appears at the top of your gallery
    options:
      bold: true
      format: p h2 h3 h4 h5 pre address div
      italic: true
      numberedlist: true
      bulletedlist: true
      image: true
      link: true
      styles: /css/editor.scss
      center: center-this-text
      left: align-left
      right: align-right
---

<a href="cloudcannon:collections/{{ page.relative_path }}" class="editor-link">Edit</a>
