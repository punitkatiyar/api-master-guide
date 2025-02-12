# api-master-guide
API master guide for developers 

# Create Your Local JSON Server

**JSON Server is a lightweight server that allows you to quickly create a REST API with a JSON file as a data source. It's useful for prototyping and front-end development, as it allows you to quickly create a fake API to work with before the real one is ready.**

**With JSON Server, you can create a server that serves static JSON data by creating a JSON file that contains your data and running the server with the json-server command. JSON Server will automatically create a REST API based on the data in your JSON file, with support for pagination, filtering, sorting, and more.**

## How To Setup JSON Server

- create a json file to store tha data

- create a package

- install the json-server package

- add code to package

```
 "serve-json": "json-server --watch db.json"
 "api": "json-server --watch db.json --port 4000 "
 
```

- run the server

```
npm run api
```
