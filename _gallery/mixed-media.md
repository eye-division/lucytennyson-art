---
title: Mixed media
permalink: /mixed-media/
display_title: true
display_image: true
thumb_crop: true
display_thumb_title: true
frontpage: false
archive: false
gallery_date: 2016-05-01 00:00:00
copy_html:
homepage_description_markdown: Homepage description for home page
main_image_path: /uploads/threefolkmusicains-smaller.jpg
main_image_caption:
images:
  - image_path: /uploads/swanagejazzstorm.jpg
    image_title: Swanage jazz
    image_description:
  - image_path: /uploads/swanagejazz-smaller-1.jpg
    image_title: Swanage jazz 2
    image_description:
  - image_path: /uploads/particle4-smaller.jpg
    image_title: The Theory of Everything 1
    image_description:
  - image_path: /uploads/particle5-smaller.jpg
    image_title: Theory of Everything 2
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
