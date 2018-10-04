# Materialize Rails Template

A regular Materalize SASS Rails Template that consits of the following GEMs:
* [materialize-sass](https://github.com/mkhairi/materialize-sass)
* [material_icon](https://github.com/Angelmmiguel/material_icons)
* [materialize-form](https://github.com/jamesfwz/materialize-form)
* [devise](https://github.com/plataformatec/devise)
* [jquery-datatables](https://github.com/mkhairi/jquery-datatables)
* [high_voltage](https://github.com/thoughtbot/high_voltage)
* [jquery-turbolinks](https://github.com/kossnocorp/jquery.turbolinks)
* [rails-ujs](https://github.com/rails/jquery-ujs)

Inspired by [mkhairi's materialize-rails](https://github.com/mkhairi/materialize-rails). The original template is written in `slim` and the database is connected to his own `postgres` server. I modified his template so that people can run his code locally by using `sqlite3` database or deploy it to a server and use `postgres` database easily (asuming that you are using Heroku PaaS). Since not everyone have experiences in slim, I decided to rewrite it to regular `html` and did some modifications and corrections. Also, major components can be found in materialize-sass's [documentation](http://materializecss.com).

I made a `slim` version of the original template created by [mkhairi](https://github.com/mkhairi) with database fix and without any modification. You can obtain it [here](https://github.com/melvinchng/Materialize-Rails-Slim).

### More Information
This template is written in such a way that you can develop on top of the template. By default, the template is optimized for mobile devices and will scale accordingly. It contains a few different headers and can be changed easily in `app/views/application.html.erb`. `/demos` is generated by `scaffold` command and contains two attributes: `title` and `body`. The attributes are created for demo purpose. `/parts` contains most of the Materialize sample code. 

### Minimum Requirements
 * Ruby 2.4.1
 * Rails 5.0

### Demo
* [Example site](http://materialize-rails-template.herokuapp.com)

### Known Issue:
 * If you are using Windows platform, uninstall all the `bcrypt` gems and reinstall the gems manually using the following command: `gem install bcrypt --platform=ruby`.