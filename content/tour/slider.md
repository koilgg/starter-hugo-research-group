---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: 👋 欢迎来到阿尔法老爷爷的魔法小屋
      content: 玛卡巴卡 玛卡巴卡...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: 1.jpg
    - title: 饿了吗，来份生日糕点吧 ☕️
      content: 'Yummy Yummy~~~'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: 2.jpg
    - title: 可以写下你的生日清单喔
      content: '我是叮当猫，喵~'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: 3.jpg
      link:
        icon: receipt
        icon_pack: fas
        text: 愿望清单
        url: ../menu/
---
