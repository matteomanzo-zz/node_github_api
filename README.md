#GitHub Profiles

##What is it?
This program gets informations from the Github API, which is connected to our NodeJS server, and displays these informations on a graphical interface styled by jQuery.

<section align='center'>
  <img src='./screenshot.png' width=83%>
</section>

##Project's Aim

- Learn NodeJS and Express
- Set and use Node packages
- Build an API
- Create dynamic interfaces

##Technologies
| Languages  | Front End | Server    | Testing  |
| ---------- | --------- | --------- | -------- |
| JavaScript | jQuery    | Node      | Mocha    |
|            | HTML & CSS| Express.js| CasperJS |
|            |           |           | PhantomJS|

##How to run it
Clone the repository and change into the directory:
```
SSH:
$ git clone git@github.com:matteomanzo/node_github_api.git
HTTPS:
$ git clone https://github.com/matteomanzo/node_github_api.git
```
Change directory
```
$ cd node_github_api
```
Install the dependencies listed in the package.json 
```
$ npm install
```
Run the tests
```
$ grunt
```
Start the server using `node server.js`, then visit http://localhost:9999 to view the application

##Collaborators

- [Josh Bebbington](https://github.com/bebbs)
- [Matteo Manzo](https://github.com/matteomanzo)
