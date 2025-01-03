---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
html, body {
    height: 100%;
    margin: 0;
    background-color: rgb(14, 14, 14);
}

img {
    display: block;
    -webkit-user-select: none; /* 禁止用户选择图片 */
    margin: auto;
    cursor: zoom-in;
    background-color: hsl(0, 0%, 90%);
    transition: background-color 300ms; /* 背景色过渡效果 */
}

@media (max-width: 725px) {
    img {
        width: 100%; /* 在较小屏幕上图片宽度自适应 */
        height: auto;
    }
}
