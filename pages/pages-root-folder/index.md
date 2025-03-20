---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "道德经"
  url: '/tao'
  image: widget-1-302x182.jpg
  text: '主要包含本人对道德经的实践，理解，以及以股入道的相关文章'
widget2:
  title: "交易"
  url: '/speculate'
  text: ''
  
widget3:
  title: "编程"
  url: '/code'
  image: widget-github-303x182.jpg
  text: ''

widget4:
  title: "创作"
  url: '/create'
  image: widget-github-303x182.jpg
  text: '一点生活感悟'

#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: /free
  text: 愿你自由。生命诚可贵，爱情价更高，若为自由故，两者皆可抛。
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

