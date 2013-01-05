# Bootstrap & Font-Awesome

The latest and greatest from Twitter and Fort-Awesome, setup and ready to go.

Checkout [Bootstrap][] and [Font-Awesome][] for more info.

## Create a CodeKit LESS Framework

1. Open [CodeKit][], add a new framework, and point to **bootstrap-fontAwesome/bootstrap** directory.

2. Add the **bootstrap-fontAwesome/font** directory to your project.

3. Drag your project directory into CodeKit.

4. Add this to the top of your main .less file:

	```css

	@import 'bootstrap.less';

	// Ensure this is the correct relative path to the font directory
	@fontAwesomePath: '../font';

	```
5. Save your work and CodeKit will compile your LESS into CSS and you should be good to go with Bootstrap and Font-Awesome!

-----

[@martylouis](http://twitter.com/martylouis)


[Bootstrap]: http://twitter.github.com/bootstrap
[Font-Awesome]: http://fortawesome.github.com/Font-Awesome/
[CodeKit]: http://incident57.com/codekit/