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
  title: "Lab News"
  url: 'https://rrhew.github.io/blog/'
  image: widget-1-302x182.jpg
  text: 'Check here for updates for the <em>Atmospheric Biogeochemistry Lab</em>'
widget2:
  title: "Research"
  url: 'https://rrhew.github.io/info/'
  text: '<em>Atmospheric Biogeochemistry Lab</em> focuses on the biosphere-atmosphere exchange of environmentally important trace gases:<br/>1. Halocarbons <br/>2. Methane and Hydrocarbons.<br/>3. Sulfur compounds.<br/> And atmospheric impacts associated with: <br/>5. Copper <br/>6. Fires'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Methods"
  url: 'https://rrhew.github.io/feeling-responsive'
  image: widget-github-303x182.jpg
  text: '<em>Feeling Responsive</em> is free and licensed under a MIT License. Make it your own and start building. The code is well-documented and explains you how it works.'
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
  url: https://tinyletter.com/rrhew
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
    <iframe width="1280" height="720" src="https://youtu.be/uVeTJSIbGm8" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
