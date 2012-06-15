[Twitter Bootstrap](http://twitter.github.com/bootstrap) and [Font Awesome](http://fortawesome.github.com/Font-Awesome/)
======

I love these two awesome frameworks and CodeKit makes it easy to use for any of my projects.


Setting up with LESS and [CodeKit](http://incident57.com/codekit/)
------
1. In CodeKit, press **Command-F** to create a new framework, and point to the bootstrap directory.
2. Create a new project directory. *Include all of your HTML, CSS, and LESS directories.*
3. In CodeKit, press **Command-N** to create a new project, and point to that new project directory.
4. Copy the font directory into your project.
5. Create a new .less document and put this at the top of your code:
	
	```css
		
		@import: 'bootstrap.less'; //Import all the things!

		@fontAwesomePath: '../font'; // Ensure this is the correct relative path to where you placed font directory
		
	```
6. Hit **Save** and CodeKit will compile your LESS into CSS and you should be good to go with Bootstrap and Font-Awesome.


Twitter Bootstrap
------
Bootstrap provides simple and flexible HTML, CSS, and Javascript for popular user interface components and interactions. In other words, it's a front-end toolkit for faster, more beautiful web development. It's created and maintained by [Mark Otto](http://twitter.com/mdo) and [Jacob Thornton](http://twitter.com/fat) at Twitter.

To get started, checkout http://twitter.github.com/bootstrap!

[@TwBootstrap](http://twitter.com/TwBootstrap)


Font Awesome 2.0
------
The full suite of pictographic icons, examples, and documentation can be found at:

http://fortawesome.github.com/Font-Awesome/

[@fortaweso_me](http://twitter.com/fortaweso_me)

Contact
------
- [marty@martylouis.com](mailto:marty@martylouis.com)
- [@martylouis](http://twitter.com/martylouis)


Copyright and licenses
---------------------
###Twitter Bootstrap
Copyright 2012 Twitter, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

###Font-Awesome
Version 2.0 of the Font Awesome font, CSS, and LESS files are licensed under CC BY 3.0:
http://creativecommons.org/licenses/by/3.0/
A mention of 'Font Awesome - http://fortawesome.github.com/Font-Awesome'
in human-readable source code is considered acceptable attribution (most common on the
web). If human readable source code is not available to the end user, a mention in an 'About' 
or 'Credits' screen is considered acceptable (most common in desktop or mobile software).