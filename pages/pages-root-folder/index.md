---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header-chair2-bravo-207676-unsplash.jpg

# These are the articles that are displayed on the front page

widget1:
  title: "Chicago Bikeshare Analysis"
  url: 'https://mishaberrien.com/chicago-bikeshare-analysis/'
  image: widget1-kuan-693106-unsplash.jpg
  text: 'The Chicago Transportation Authority (CTA) opened the first 75 Divvy Stations in June 2013. The first stations were clustered around the Loop area in Central Chicago. By the end of 2013, more than 300 stations were up and running around Chicago’s North, West and Southern sides.'
widget2:
  title: "Map of Tulsa, Ok Traffic Accidents in 2014"
  url: 'https://mishaberrien.com/tulsa-traffic-safety/'
  image: widget2-riku-lu-3512-unsplash.jpg
  text: 'An interactive visualization of all reported traffic accidents in 2014 in the city of Tulsa.'
widget3:
  title: "Bikeshare Interactive Map"
  url: 'https://mishaberrien.com/divvy-bike-interactive-map/'
  image: widget3-sawyer-bengtson-256255-unsplash.jpg
  text: 'Interactive map of Chicago showing bikeshare usage.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
url: /index/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
#callforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text: Inform me about new updates and features ›
#  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<!-- <div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div> -->
