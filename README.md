generic-django-project
======================

Generic project directory structure for new django applications.


从这里发现的这个项目： https://medium.com/cs-math/f29f6080c131
比较好的django目录结构：
The apps directory stores all of your customized django apps and the vendor directory stores any apps you do not want to install (or can’t install) using pip or easy_install. The bin directory stores all bash scripts that help you automate your development. I have scripts in here that deploy to staging & production servers, clean up directories, compress assets, backup databases, start/stop celery (locally), etc. The config directory stores all of your configuration files for databases, webservers, munin, celery, supervisor, etc. The media directory stores all static assets such as javascript, css, images, fonts, etc.The template directory stores all the html templates that make your site beautiful. Finally, the static directory is where your compressed assets get dumped into for production.

