#GitHub Profiles

##What is it?
This application shows you the GitHub users info, by typing the GitHub username.
This project is a Node application, served by Express, who hits the GitHub API and brings back data which will be elaborated and displayed by jQuery. Styled by CSS.

<section align='center'>
  <img src='./screenshot.png' width=83%>
</section>


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
