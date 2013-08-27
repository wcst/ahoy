Ahoy
====

First things first – _welcome!_ 

We know sometimes it can be tough to integrate into a new team or workflow. So we are going to try to help out. We don't have all the answers, we don't claim to know everything. We do however, have some experience under our belt and we have found some things that work and cast aside others that don't. The following is a collection of resources and concepts we use, just so we are all on the same page.


##Philosophy & Stack
Our approach to front-end development is simple. Keep it [DRY](http://en.wikipedia.org/wiki/Don't_repeat_yourself), keep it modular. While we roll with an opinionated stack, we aren't tied to anything permanently. Our code, our process, our stack, it is ever-evolving.

We have a [Yeoman](http://yeoman.io) generator – [Stamp](https://github.com/kyledetella/generator-stamp) – that we built to scaffold out new projects. Take a look at that to get a bit more familiar with our style.

##Git
We use git as our version control system of choice. We run our client projects from [Beanstalk](http://beanstalkapp.com/) and our personal/internal libraries from [Github](http://github.com).

  + Learning Version Control - http://guides.beanstalkapp.com/
  + Github Guides (more than just github) – http://www.youtube.com/GitHubGuides
  + git-scm – http://git-scm.com/

##Grunt
[Grunt.js](http://gruntjs.com) has proven to be invaluable to our workflow.

  + Getting Started – http://gruntjs.com/getting-started
  + Our sample `Gruntfile` – https://gist.github.com/kyledetella/6347153

##CSS
We use Compass and SASS. We used to use LESS, we aren't opposed to it, we just found that SASS provides us with a bit more flexibility and modularity.
	
  + Learn SASS – http://sass-lang.com/
  + The SASS Way – http://thesassway.com/
  + OOCSS – http://coding.smashingmagazine.com/2011/12/12/an-introduction-to-object-oriented-css-oocss/
  + [grunt-contrib-compass](https://github.com/gruntjs/grunt-contrib-compass) – This is how we compile!
  + [bourbon.io](http://bourbon.io) – A mixin library for SASS

Also, take a look at the [WCST Style Guide for CSS](https://github.com/wcst/style#css).

##JS

You can see some general guidelines and patterns on the [WCST JS Style Guide](https://github.com/wcst/style#js).

###Modules
We keep it modular. Generally, our front-end code uses AMD (http://requirejs.org/docs/whyamd.html). We use [require.js](http://requirejs.org) and less frequently, [browserify](http://browserify.org/) for CommonJS support. 

  + [Writing Modular JavaScript With AMD, CommonJS & ES Harmony](http://addyosmani.com/writing-modular-js/)
  + [Shared Rendering In Node And The Browser](http://substack.net/shared_rendering_in_node_and_the_browser)

###Backbone
A lot of our projects use use [Backbone.js](http://backbonejs.org). The reasons are many, but mainly, we like the philosophy behind the library. It offers us some general structure, by _we_ define the architecture and conventions.

  + [Backbone patterns](http://ricostacruz.com/backbone-patterns/)
  + [Backbone tips and patterns](http://coding.smashingmagazine.com/2013/08/09/backbone-js-tips-patterns/)

###The DOM
jQuery is cool. Don't get me wrong, we rely on it, but we find value in vanilla javascript. In fact, there are a ton of basic DOM operations you can run a lot easier than you think! I could write it all down here, but there are some _great_ posts already on the subject.

  + [Weaning Yourself off jQuery](http://substack.net/weaning_yourself_off_jquery) 
  + [Native Equivalents of jQuery Methods](http://www.leebrimelow.com/native-methods-jquery/)

###Animation
Want to animate things? Yeah, thats always fun! Plus, the client wants it anyway, so...

  + [Greensock Animation Platform](http://www.greensock.com/gsap-js/)
  + [jQuery.transit](http://ricostacruz.com/jquery.transit/)

###Node.js
We use Node.js to rapidly upstart and prototype our front-end projects. On recent projects, we have used a full Node.js stack to power our front-end, backend, admin, and API alike.

Want to learn some [Node.js](http://nodejs.org)?

  + [An Absolute Beginners Guide to Node.js](http://blog.modulus.io/absolute-beginners-guide-to-nodejs)
  + [Node.js for Front-End developers](http://shop.oreilly.com/product/0636920023258.do)
 


##Links & Resources
 
  + Resources
  	+ [HTML5Rocks](http://www.html5rocks.com/en/)
  	+ [caniuse.com](http://caniuse.com/)
  	+ [MDN](https://developer.mozilla.org/en-US/)
  	+ [WebPlatform.org](http://www.webplatform.org/)
  	+ [CSS-Tricks *(invaluable)*](http://css-tricks.com)
  + Daily Reads
  	+ [Hacker News](https://news.ycombinator.com/)
  	+ [Monocle.io](http://monocle.io)
  	+ [SVBTLE](http://svbtle.com)
  	+ [DailyJS](http://dailyjs.com/)
  	+ [Net Magazine](http://www.netmagazine.com/)
	+ [The Verge](http://theverge.com)   
  + Google+ Communities
  	+ [CSS](https://plus.google.com/communities/106425668610348127113) 
  	+ [Node.js](https://plus.google.com/communities/115365528781941125390)
  	+ [JS](https://plus.google.com/communities/100875929141897651837)
 
