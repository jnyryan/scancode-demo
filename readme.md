# heroku-simple-rack-site

A simple static page application that runs on Heroku

#Installation
	
	Prerequisites
	- Heroku account
	- Heroku toolbelt installed
	- Ruby and Bundler Gem installed
	
	1. Clone this Repo
	2. Login into Heroku
		heroku login
	3. Initialise the heroku site
		heroku create
	4. Push to Heroku.
		git push heroku master
		
	That's it!!!!

# The important bits

	Gemfile
		Tells the ruby interpreter whats needed and what to install
	
	config.ru
		configures RACK, the web server that will host the application
	
# The HTML

	All the html code and graphics are freely available from Twitter Bootstrap.

##References

	https://devcenter.heroku.com/articles/static-sites-ruby
	http://twitter.github.io/bootstrap/getting-started.html
	
# Testing

	To run and test it locally run the command
		rackup
	

