# NodeNewman
The command line wrapper for [Postman API](https://www.postman.com/postman/workspace/postman-public-workspace/collection/12959542-c8142d51-e97c-46b6-bd77-52bb66712c9a?ctx=documentation) and [Newman](https://github.com/postmanlabs/newman)

# Why
This utility was developed to show a 'better' practice when demoing Newman. Newman excecute tests found within collections. Exporting the collections and saving the json opens the possibiity that the collection is out of date. This tool GETs the collection using the [Postman API](https://www.postman.com/postman/workspace/postman-public-workspace/collection/12959542-c8142d51-e97c-46b6-bd77-52bb66712c9a?ctx=documentation) and then immediatley calls Newmn.

# How to use
1. Obtain a Postman API key. Follow the instructions [here](https://learning.postman.com/docs/developer/intro-api/) on how to get a key. This will be used 
2. Obtain the collection id. This can found selecting the collection and clicking on the 'info' icon.

Syntax: 
```
node app.js --postman_key={YOUR_POSTMAN_API_KEY} --collection_uid={THE_COLLECTION_UID}
```
