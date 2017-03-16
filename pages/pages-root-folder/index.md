---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  title: Hanneli's Universe
  background-color: "#334D5C"
  <!-- image_fullwidth: ht_header_unsplash_5.jpg -->
widget1:
  title: "Conferences"
  url: '/conferences'
  <!-- image: widget-1-302x182.jpg -->
  image: Conference-sq.png
  text: 'Check some of my presentations around the world. Several random subjects about technology and computers.'
widget2:
  title: "Posts"
  url: 'https://medium.com/@hannelita'
  image: writing-icon-23-sq.png
  text: '<em>Posts</em> about computers, technology, mathematics and random thoughts.'
widget3:
  title: "Hire me"
  url: '/hireme'
  image: icon_find_talent-200-sq.png
  text: '<em>Are you recruiting?</em> Let us see if we have a good match. Check this section and tell me more about the job positions you have.'
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
  url: /conferences/
  text: Check my work ›
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
