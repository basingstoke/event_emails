#This project comes with Grunt Email Boilerplate

A grunt-ready HTML email template based on [HTML Email Boilerplate](http://htmlemailboilerplate.com/).

##Features

* SCSS stylesheets with [Compass](http://compass-style.org/)
* image optimization with [jpegtran](http://jpegclub.org/jpegtran/) and [OptiPNG](http://optipng.sourceforge.net/)
* inlining CSS styles with [grunt-premailer](https://github.com/dwightjack/grunt-premailer) and [Premailer](http://premailer.dialect.ca/)
* HTML templating with [EJS](https://github.com/visionmedia/ejs) and [more](https://github.com/dwightjack/grunt-ejs-render) 
* Environment specific code blocks in HTML with [grunt-preprocess](https://github.com/jsoverson/grunt-preprocess) 
* test email delivery with [grunt-nodemailer](https://github.com/dwightjack/grunt-nodemailer) and [NodeMailer](https://github.com/andris9/Nodemailer)

##Requirements

* Node.js >= 0.10.20 ([install wiki](https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager))
* Grunt-cli >= 0.1.7 and Grunt >=0.4.2 (`npm install grunt-cli -g`)
* Ruby >= 1.9.3 ([installers](http://www.ruby-lang.org/en/downloads/))
* Compass >= 0.12.2 (`gem install compass`)
* Premailer >= 1.8.0 (`gem install premailer` and, most of the time, `gem install hpricot`)

## Getting Started

To install the boilerplate 

1. install all dependencies

2. clone this git repo

	`git clone git://github.com/dwightjack/grunt-email-boilerplate.git`

3. install node dependencies:
	
	`cd grunt-email-boilerplate`

	`npm install`

4. Run the development task `grunt dev` and start editing email files in `src` folder (by default `email.html` and `scss/_main.scss`). By default, Grunt will try to open the email preview in your default browser; alternatively, preview URL is `http://localhost:8000/`.
