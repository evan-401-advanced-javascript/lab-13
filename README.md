# LAB - 09

 ## API Server

 ### Author: Evan Brecht-Curry

 ### Links and Resources
* [submission PR](https://github.com/evan-401-advanced-javascript/lab-13/pull/1)
* [travis](https://www.travis-ci.com/evan-401-advanced-javascript/lab-13/builds/125003436)
* [deployment](https://lab-13-tokens.herokuapp.com/) 
* [docs](http://localhost:3000/docs/)


 ##### Exported Values and Methods

 ###### 
`get(signup) -> {object} 200 - request token`
`get(signin) -> {object} 200 - request token`


### Setup
#### `.env` requirements
* `MONGODB_URI` - mongodb://localhost:27017/lab-13
* `PORT` - 3000
* `SECRET` - secret
* `SINGLEUSE` - true
* `EXPIRATION` - true


 #### UML
![UML](uml.png)