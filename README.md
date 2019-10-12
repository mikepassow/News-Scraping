# News-Scraping

<h3>Heroku Link <a href= "https://intense-citadel-62906.herokuapp.com/">Here</a>


<h1>News Scraper</h1>
<p>This app allows users to view news articles, save their favorites onto another page, and comment on their favorites. Each article displayed includes a headline which is also a link to the source article and a description that includes the date of publish. Each   The app uses Node/Express for the server and routing, MongoDB/Mongoose for the database and models, Handlebars for the layout and views, & Cheerio/Request for scraping the data.</p>

<h3>Install dependencies</h3>
<ul>
<li>In your CLI, enter mongod</li>
<li>In a new CLI window, go to root of directory and enter node server.js</li>
<li>In browser, navigate to http://localhost:3000</li>
</ul>

<h3>Dependencies</h3>
<h2>You will need to npm install the following node modules:</h2>
<ul>
<li>express</li>
<li>express-handlebars</li>
<li>mongoose</li>
<li>cheerio</li>
<li>request</li>
</ul>

<p>Since I have included a package.json file, you do not need to install dependencies by name. Simply run the following in the root of your directory:</p>

<p>npm install</p>

<h3>Deployment</h3>
<h4>Follow these instructions to deploy your app live on Heroku</h4>

<ul>
<li>Create a heroku app in your project directory</li>
<li>heroku create "Project Name"</li>
<li>Provision mLab MongoDB add-on for your project</li>
<li>heroku add ons:create mongolab</li>
<li>Now your project should be successfully deployed on heroku.</li>
<ul>
