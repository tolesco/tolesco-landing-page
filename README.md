# Sinatra Boilerplate

Sinatra boilerplate for landing pages and APIs built with Sinatra 2.1.0 and Ruby 2.7.3 with [Bootstrap 5](https://getbootstrap.com/) and [Bootstrap Icons](https://icons.getbootstrap.com/) integrated.

## Pre-requisites

You will need to have Ruby 2.7.3 installed on your system. I recommended you to follow the [GoRails Setup Ruby on Rails Guide](https://gorails.com/setup) for install Ruby language in your system.

## Getting Started

Once you have Ruby 2.7.3 properly installed and configured you can make:
```
git clone https://github.com/tolesco/sinatra-boilerplate.git
cd sinatra-boilerplate
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

Francisco Rodríguez - [@tolesco](https://github.com/tolesco/) - francisco@tolesco.com
