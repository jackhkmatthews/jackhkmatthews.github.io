---
layout: project
icon: "https://res.cloudinary.com/dmqr7syhe/image/upload/c_scale,q_100,w_200/v1576588215/jackhkmatthews.com/icons/responsive-image-icon_uofa9h.png"
title: "Responsive Images"
github: "https://gitlab.com/jackhkm/responsive-images"
liveSite: "https://jackhkmatthews-responsive-imgs.herokuapp.com/"
imageLg: "https://res.cloudinary.com/dmqr7syhe/image/upload/c_scale,w_1000/v1576598020/jackhkmatthews.com/images/responsive-images_ereiu9.png"
imageSm: "https://res.cloudinary.com/dmqr7syhe/image/upload/c_scale,w_500/v1576598020/jackhkmatthews.com/images/responsive-images_ereiu9.png"
year: 2019
---

## Summary

After working with lazy loaded responsive images for some time, I decided to conduct a technical audit of the different approaches I’d come across working on projects of clients and my own. I created a Polymer playground project to better demonstrate the pros and cons of each approach and my conclusions.

## Favourite Bit

Recognising that even when `<div>`s and `<img>`s have the same intrinsic dimensions and styling, they will be rendered differently, which can in turn be overcome by using SVG data URIs as `src`s. As a result, placeholder content can always match the dimensions of the image, which is waiting to be loaded.

## Tech

Polymer, Intersection Observer, src-set, `<picture>`
