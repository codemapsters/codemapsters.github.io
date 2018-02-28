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
  title: "Blog Articles"
  url: 'http://codemapsters.github.io/codemapsters/blog/'
  image: widget-1-302x182.jpg
  text: 'Check out our latest blog posts, topics include mapping and spatial data analysis with QGIS, Python, R, GeoPandas, ArcMap and more'
widget2:
  title: "Youtube Tutorials"
  url: 'http://codemapsters.github.io/codemapsters/info/'
  text: 'Learn better through video tutorials? Check out our channel which has most of our spatial data analysis and GIS blog posts'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "About Us"
  url: 'http://codemapsters.github.io/codemapsters/info'
  image: widget-github-303x182.jpg
  text: 'Learn more about us and our other projects which utilize the techniques posted here'
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
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
