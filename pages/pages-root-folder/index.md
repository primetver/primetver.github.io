---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: corp2-w.png
  title: 'Разработка решений для бизнеса на базе свободного ПО'
widget1:
  title: "Разработка"
  url: '/service/develop/'
  image: '/images/laptop-thumb.png'
  text: 'Комплексная автоматизация сложных корпоративных бизнес-процессов. Проектирование, разработка и внедрение решений, полностью основанные на свободном ПО. Разработка систем автоматизации внутреннего аудита.'
widget2:
  title: "Миграция"
  url: '/service/migration/'
  image: '/images/code2-thumb.png'
  text: 'Услуги по миграции и поддержке базе данных и информационных систем при поддержке российского вендора СУБД PostgreSQL. Перепроектирование и миграция проприетарных систем на свободное ПО.'
widget3:
  title: "Поддержка"
  url: '/service/support/'
  image: '/images/support-thumb.png'
  text: 'Расширенная техническая поддержка решений на базе свободного ПО, включая круглосуточную поддержку. Сопровождение эксплуатации и функциональное развитие информационных систем.'
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
# callforaction:
#   url: /service/
#   text: 'Подробнее о решениях на базе свободного ПО ›'
#   style: alert
permalink: /index.html
---
<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>