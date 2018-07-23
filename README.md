![OST HEADER IMAGE](https://i.imgur.com/3XB2GED.jpg)

# OST • GraphQL Server
### Quite possibly the _fastest_ way you can get started using crypto in your app.

By using [OST](https://ost.com) branded tokens you can set up a token economy inside any site/app/etc.  This is a small turn-key project that sets up a Node/Express development server running Apollo GraphQL so that you can ignore all the back end work while getting started developing front end services.

GraphQL allows for your front end service to ask for exactly what information it wants, and get a clean response. Apollo has written some very nice documentation on how to use GraphQL from React, Vue, Angular, plain JS, etc.  [Give it a look](https://www.apollographql.com/docs/react/) when you are ready to learn more.  

## Installation and Use
```Bash
cd ost-graphql-server
vi logic/conf.js # add your OST API keys and Apollo service ID
npm install
npm start
# Server should be running on localhost:<GRAPHQL_PORT>/graphiql!
```

## API Keys
 - Get OST Kit API keys from https://kit.ost.com/developer-api-console
 - Get an Apollo Engine service key from https://engine.apollographql.com 

### Dependencies
 - Node v8
 
#### Disclaimer
This is a development project and not meant for serious production use as-is.  We are not liable for _any_ outcome from this service, use at your own risk!  MIT Licensed.

### About
Visit [OST.com](https://ost.com) to learn more about OST. 

Made possible with support from [FUTURED](https://futured.org)

Want to support independent writing with your OST?  FUTURED: 0x0e082d72593f8e2B885B0ca61c5da843aefAcfB1
![FUTURED Logo](https://i.imgur.com/hvhyCFY.jpg)
