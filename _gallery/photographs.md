---
title: Photographs
permalink: /photographs/
display_title: true
display_image: true
thumb_crop: true
display_thumb_title: true
frontpage: false
archive: false
gallery_date:
copy_html:
homepage_description_markdown:
main_image_path: /assets/images/4b02eb2751e62.jpg
main_image_caption:
images:
  - image_path: /assets/images/4b02eb2751e62.jpg
    image_title: Manchester Canal - 9 Oct 2006 14.25
    image_description:
  - image_path: /assets/images/4b3929cbe9981.jpg
    image_title: Cape Cornwall - 1
    image_description:
  - image_path: /assets/images/4b392a36843ec.jpg
    image_title: Cape Cornwall - 2
    image_description:
  - image_path: /assets/images/4b392b9b2c032.jpg
    image_title: Cape Cornwall - 3
    image_description:
  - image_path: /assets/images/4b392bd11e62c.jpg
    image_title: Cape Cornwall - 4
    image_description:
  - image_path: /assets/images/4b392c0849cbb.jpg
    image_title: Cape Cornwall - 5
    image_description:
  - image_path: /assets/images/4b392c24e13c7.jpg
    image_title: Cape Cornwall - 6
    image_description:
  - image_path: /assets/images/4b392d8a6406e.jpg
    image_title: Cape Cornwall - 7
    image_description:
  - image_path: /assets/images/4b392c580650f.jpg
    image_title: Cape Cornwall - 8
    image_description:
  - image_path: /assets/images/4b392e8db619f.jpg
    image_title: Cape Cornwall - 9
    image_description:
  - image_path: /assets/images/4b392edf153f3.jpg
    image_title: Cape Cornwall - 10
    image_description:
  - image_path: /assets/images/4b392f36ca142.jpg
    image_title: Cape Cornwall - 11
    image_description:
  - image_path: /assets/images/4b392f56822ba.jpg
    image_title: Cape Cornwall - 12
    image_description:
  - image_path: /assets/images/4fa780f40a634.jpg
    image_title: Birmingham 7
    image_description:
  - image_path: /assets/images/4fa781676e634.jpg
    image_title: Birmingham 7
    image_description:
  - image_path: /assets/images/4fa781807cb8c.jpg
    image_title: Birmingham 7 -
    image_description:
  - image_path: /assets/images/4fa78190b2d92.jpg
    image_title: Birmingham 7 -
    image_description:
  - image_path: /assets/images/4fa781b712a27.jpg
    image_title: Birmingham 7 -
    image_description:
  - image_path: /assets/images/4fa781c81c0bb.jpg
    image_title: Birmingham 7 -
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
