# aspnetcore-travi-ci 
Aspnet Core Api continuous integration with Travis CI and deployment with Heroku

### Build status
[![Travis build status](https://img.shields.io/travis/bioyeneye/aspnetcore-travi-ci/master.svg?label=master&style=flat-square)](https://travis-ci.org/bioyeneye/aspnetcore-travi-ci)

### Setups

#### Generate Heroku API Key

```txt
heroku authorizations:create //for production
heroku auth:token //for development
```

#### Setup Travis Variables

```txt
  - Goto the settings tab on the application(https://travis-ci.com/github/username/projectname/settings)
  - Set Heroku key with herokuapikey name
  - Set Heroku application name with herokuapp
```
