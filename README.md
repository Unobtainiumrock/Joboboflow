# JoboboFlow
JoboboFlow aids users in their job hunting process by providing tracking & data visualization tools. 

[Deployed Site Link](https://jobobo-flow.herokuapp.com/)

<img src="./README/landing-page.PNG">

## Features
Some of the features that make JoboboFlow really awesome include:

* Task tracking
<img src="./README/task-board.png">

* Data visualization
<img src="./README/visual-analysis.png">


## Why use JoboboFlow?
It's cumbersome to create and manage your job-hunt tracking system. Joboboflow fills that role of consolidating information that's most useful to users.


## How?
JoboboFlow collects data on the jobs its users apply to and saves the data into a MySQL database. This data is then queried to render job info to users.


## Technical Aspects

### Built With
* [Javascript](https://eloquentjavascript.net/)
* [Node](https://nodejs.org/en/)
* [MySQL](https://www.mysql.com/)

#### Node modules Used
* [Sequelize](http://docs.sequelizejs.com/)
* [Express](https://expressjs.com/)
* [mysql2](https://github.com/sidorares/node-mysql2)
* [express-handlebars](https://github.com/ericf/express-handlebars)


#### Middleware
* [body-parser](https://github.com/expressjs/body-parser)

#### CDN's
* [Bluebird](http://bluebirdjs.com/docs/getting-started.html)
* [JQuery](https://api.jquery.com/)

### Relations
Here's our models
<img src="./README/schema-tables.png">

### Routes
Here's our routes -minus the body content.


```javascript
router.get('/cohort',function(req,res) {
});

router.get("/api/cohort/:id/users",function(req,res) {
});

router.get('/admin',function(req,res) {
});

router.get('/', function (req, res) {
});

router.get('/chart', function (req, res) {
});

router.get("/api/admin/cohort/:id?/job-table",function(req,res) {
});

router.get("/api/jobs", function (req. res) {
});

router.get("/api/admin/cohort/:id?/users/:id?/job-search",function(req,res) {
});

router.post('/job/add', function (req, res) {
});

router.put("/job/changeLoc:id", function(req, res) {
});

router.put("/job/delete/:id",function(req,res){
});

router.post('/user/add', function(req, res) {
});

router.get('/user:id', function(req, res) {
});

router.get('/user/:id/jobs', function(req, res) {
});

router.post('/user/exists',function(req,res) {
});

router.post('/user/authenticate',function(req,res) {
});
```


## Stretch Goals
* Add a trash can that collects denied applications.
* Finish adding a login functionality for an Admin.
* Render jobs to users from the Indeed API.
* Implement Google OAuth with passport
* Add line graph data visualizations

## Authors

* **Kitty Shen**
* **Unobtainiumrock**
* **Hannah Lim**
* **Alexandra Goodwin**

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Cats Meowing kittykuma.com
* [Unobtainiumrock Industries ®](https://unobtainiumrock.github.io/portfolio-revamp/)
* [Alexandra Goodwin](https://github.com/alexgood1)
* [Hannah Lim](https://github.com/hannahlim213)

