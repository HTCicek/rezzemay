# Rezzemay

#### BLUF

Check it out live [here](https://rezzemay.herokuapp.com)

#### What is Rezzemay?

Rezzemay is a web app that gives users a quick-to-set-up and easy-to-share single page resume/portfolio site. Create an account, enter in some information, and receive a site with your own personalized URI!

## Run it

```sh
git clone https://github.com/HTCicek/rezzemay.git
cd rezzemay
docker-compose build && docker-compose up

# don't mind the connection messages from api_1:
# # docker-compose.yml command for backend waits until postgres is accepting connections in order to migrate.
```

enter the web client from localhost:3001


## Web Client

Bootstrapped with create-react-app.
Libraries used include Semantic-UI, react-router, and jquery.

## Back end

Built with Ruby on Rails.
