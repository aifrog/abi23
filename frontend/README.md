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

# Deploy to heroku

````
heroku login
heroku create react-mperle05
heroku container:push web -a react-mperle05
heroku container:release web -a react-mperle05
heroku open
````

https://react-mperle05.herokuapp.com/