# Preparing the environment

npx create-react-app react-mperle05

## Video

https://www.youtube.com/watch?v=NeKm4zOVkO4

Minute: 00:00:00

## Starting the web server

````
npm start
````

# Some other useful JS frameworks

Bulma ist ein freies und Open-Source-CSS-Framework basierend auf Flexbox. Es enthält auf HTML und CSS basierende Gestaltungsvorlagen für Typografie, Formulare, Buttons, Tabellen, Grid-Systeme, Navigations- und andere Oberflächengestaltungselemente. 

Moment is used to format dates


````
npm install bulma moment
````

# Deploy to local docker

````
docker-compose build
docker-compose up

````













````
heroku login

npx create-react-app@3.x react-mperle05

cd react-mperle05
heroku create react-mperle05 --buildpack mars/create-react-app
heroku stack:set heroku-20
git push heroku master
heroku open
````