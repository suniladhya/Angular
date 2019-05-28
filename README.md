# Installation
* npm cache clean --force (Incase it shows error while installation)
* npm install -g @angular/cli
# Extension like Bootstrap
* Can be done through CDN/ npm
## For CDN,
* Bootstrap CCS file
* Bootstrap JavaScript file

Open file src/index.html and insert
* the <link> element at the end of the head section to include the Bootstrap CSS file
* a <script> element to include jQuery at the bottom of the body section
* a <script> element to include the Bootstrap JavaScript file at the bottom of the body section

## For NPM,
* npm install bootstrap
* Add the file paths to the styles and scripts array in file .angular-cli.json
```
"styles": [
    "styles.css",
    "../node_modules/bootstrap/dist/css/bootstrap.min.css"
  ],
  "scripts": [
    "../node_modules/jquery/dist/jquery.min.js",
    "../node_modules/bootstrap/dist/js/bootstrap.min.js"
  ],
  ```
[using NGX-bootstrap](https://www.techiediaries.com/angular-bootstrap-ui/)
# Creating a new Application
ng new myApptest21 --routing=true --style=css -s -t --skipInstall=true --dryRun = true
[--style=css]
[--skipTests=true]
[--verbose=true]
[--minimal=true]
# Serving the Application
ng serve -o --port=200 --aot=true
# Style Guides
# Angular Communication
* RXJS is a js Library for reative programming with observables
* HttpClient Methods Returns observables
* Lots of RXJS operators are available to work with observables. And also return Observables.
* Steps To Start:
* Import and add HttpClientModule from @angular/common/http'

* 201 created: post
* 200 ok: Read
* 204 No Content: update, Delete

# Multiple Projects
[1. Working with multiple projects](https://medium.com/disney-streaming/combining-multiple-angular-applications-into-a-single-one-e87d530d6527)
| [2. Adding multiple Projects in same work space](https://www.techiediaries.com/angular-workspace/)
# Angular Testing 
[1](https://codecraft.tv/courses/angular/unit-testing/asynchronous/)
# Adding John Papa's Hacks

# Running a Forked project of Old version
* ng config -g cli.warnings.versionMismatch false

# Angular
[Angular Extension for visual Studio](https://i.ibb.co/vdrXL3q/Angular-Extensions.jpg)

