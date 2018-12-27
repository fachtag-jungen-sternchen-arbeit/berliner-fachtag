---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
widget1:
  title: "4. Berliner Fachtag geschlechterreflektierter Jungen&#42;arbeit"
  image: widget1.jpg
  url: 'https://fachtag-jungen-sternchen-arbeit.github.io/berliner-fachtag/fachtag/'
  text: '<strong>Wann:</strong> 27. März 2019, 10:00 Uhr – 16:30 Uhr<br>
<strong>Wo:</strong> Haus der Jugend Anne Frank<br>
Mecklenburgische Str. 15, 10713 Berlin'
widget2:
  title: "Programm"
  url: 'https://fachtag-jungen-sternchen-arbeit.github.io/berliner-fachtag/programm/'
  text: 'Hier gehts zum geplanten Programm und den Workshops'
  image: widget2.jpg
widget3:
  title: "Anmeldung"
  url: 'https://fachtag-jungen-sternchen-arbeit.github.io/berliner-fachtag/anmeldung/'
  image: widget3.jpg
  text: 'Bitte melden Sie sich über das Anmeldeformular an.<br>
  <a href="https://goo.gl/forms/RwSkBJOwdzDOQY943">https://goo.gl/forms/RwSkBJOwdzDOQY943</a><br>
  Anmeldeschluß ist der 15. Februar 2019<br>'
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
