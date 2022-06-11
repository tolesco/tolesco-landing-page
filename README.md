# Tolesco Landing Page

Tolesco landing page built with Sinatra 2.2.0 and Ruby 3.1.2 . CSS framework [Bootstrap 5.2.0-beta1](https://getbootstrap.com/) and [Bootstrap Icons](https://icons.getbootstrap.com/) integrated.

## Pre-requisites

You will need to have Ruby 3.1.2 installed on your system. I recommended you to follow the [GoRails Setup Ruby on Rails Guide](https://gorails.com/setup) for install Ruby language in your system.

## Getting Started

Once you have Ruby 3.1.2 properly installed and configured you can make:
```
git clone https://github.com/tolesco/tolesco-landing-page.git
cd tolesco-landing-page
bundle install
ruby app.rb
```
The app will be accessible through your [localhost:4567](http://localhost:4567) address.

### ENV Variables

If you need to use ENV variables in development make a copy of `.env-example` named `.env`, then remove `.env-example` file and edit `.env` file with your ENV variables:
```
cp .env-example .env
rm .env-example
```

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.

## Contact

Francisco Rodríguez - [@tolesco](https://github.com/tolesco/) - tolesco@gmail.com
