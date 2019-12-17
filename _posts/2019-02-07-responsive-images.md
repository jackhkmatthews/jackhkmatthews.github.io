---
layout: project
icon: "https://res.cloudinary.com/dmqr7syhe/image/upload/c_scale,q_100,w_200/v1576588215/jackhkmatthews.com/icons/responsive-image-icon_uofa9h.png"
title: "Responsive Images"
liveSite: "https://wdi-project-4-client.herokuapp.com/"
github: "https://github.com/jackhkmatthews/WDI_PROJECT_4_API"
imageLg: "https://res.cloudinary.com/dmqr7syhe/image/upload/c_scale,w_1000/v1575488120/jackhkmatthews.com/images/invest-smart_ubav3c.png"
imageSm: "https://res.cloudinary.com/dmqr7syhe/image/upload/c_scale,w_500/v1575488120/jackhkmatthews.com/images/invest-smart_ubav3c.png"
year: 2019
---

## Summary

After working with lazy loaded responsive images for some time, I decided to conduct a technical audit of the different approaches I'd come across on our own projects and on projects in the wild. I created a Polymer playground project to better demonstrate the pros and cons of each approach and my conclusions.

## Favourite Bit

Recognising that, even when `<div>`s and `<img>`s have the same intrinsic dimensions and styling, they will be rendered differently. Then discovering that this can be overcome by using SVG data URIs as `src`s. In this way placeholder content can always match the dimensions of the image which is waiting to be loaded.

## Tech

Polymer, Intersection Observer, src-set, `<picture>`
