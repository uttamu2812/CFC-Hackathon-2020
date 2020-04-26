# CFC-Hackathon-2020

Three  module are there one for aplication implemented in ionic , one  is for backend service implemented in spring boot and another for chat server.

Covid19 - submodule is for backend spring boot application.

Fight to covid-19 is font end ionic application which can be converted in android,ios or browser platform.
  Prerequist nodejs,ionic,cordova,ADK,gradle.
  To run it.
  npm install.
  for browser- ionic serve
  for android 1. build .apk for it.


chat server is a nodeJS application
  To run it.
  npm install
  node server.js.

For testing app
json-server --watch Fight to covid-19/db.json

update branch and commit
git submodule foreach git pull origin master
git add module_1_name
git add module_2_name
......
git add module_n_name
git commit -m "update"
git push origin master
