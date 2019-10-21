# trails-near-me
tutorial on mongoDB schema migrations

## How to Install

1. Clone to your machine
2. ``` cd project-folder && touch .env``` 
3. ```npm install && npm run install```
4. cd into root folder -> ```npm run start```

populate your .env file with:

```
TRAIL_API_KEY=<your key here>
```

## MVC design

- View -> MaterialUI react framework
- Model -> mongoDB w/ mongoose ODM
- Controller -> REST API built with node/express. folder structure based on MVC design

## External Resources

### Frameworks / Libraries

- MaterialUI and React.js using hooks for state management
- express.js to create API / server 
- mongoose.js to map from the mongoDB database
- axios to fetch data from external APIs
- migrate-mongo to run db migrations (the real reason behind this tutorial)

### published tutorial to build this on Medium

[link to medium]()

### external APIs

- trailapi -> a database of trails [link](https://english.api.rakuten.net/trailapi/api/trailapi/endpoints)

