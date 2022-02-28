---
title: Mythical landscapes
permalink: /mythical-landscape/
display_title: true
display_image: true
thumb_crop: true
display_thumb_title: true
frontpage: false
archive: false
gallery_date:
copy_html: >-
  Mixed media work 2015-7 mostly in chalk pastel, gouache, crayon and pencil.
  &nbsp;Some are worked into mono prints.
homepage_description_markdown:
main_image_path: /uploads/stormatavebury.jpg
main_image_caption:
images:
  - image_path: /uploads/stones1small.jpg
    image_title: Stones
    image_description: Collage on board
  - image_path: /uploads/clumpssmall.jpg
    image_title: Clumps
    image_description: Mixed media on board
  - image_path: /uploads/whiteh4.jpg
    image_title: White Horses
    image_description:
  - image_path: /uploads/phantom1-smaller.jpg
    image_title: Phantom 1
    image_description: Pastel over monoprint
  - image_path: /uploads/phantom2-smaller.jpg
    image_title: Phantom 2
    image_description: Pastel over monoprnt
  - image_path: /uploads/untitled1-smaller.jpg
    image_title: Untitled horse 1
    image_description: Monoprint
  - image_path: /uploads/untitled2-smaller.jpg
    image_title: Untitled horse 2
    image_description: Monoprnt

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

