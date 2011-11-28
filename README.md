#Sublime Text 2 : CodeIgniter Framework Snippets

A collection of community compiled snippets for Codeigniter for use with the Sublime Text 2 Editor http://www.sublimetext.com

##Install

To install: clone to SublimeCodeigniter within your Sublime Text 2 package folder.

###Linux

To install on Linux execute the following command:

```
git clone git://github.com/daylerees/SublimeCodeigniter.git ~/.config/sublime-text-2/Packages/SublimeCodeigniter
```

###Mac

To install on Mac OS execute the following command:

```
git clone git://github.com/daylerees/SublimeCodeigniter.git ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/SublimeCodeigniter
```
Enjoy!

##Quick Reference

Type the tab-trigger (shown in bold) followed by tab to expand the text, you may use tab to move between the various stop points within the code snippet.

You can also use `ctrl + space` to bring up a list of snippets.

(<?php inserted in examples only for syntax highlighting)

**cicontroller**

```php

<?php

/**
* 
*/
class ControllerName extends CI_Controller
{
	function index()
	{
		
	}
}

```

**cimodel**

```php

<?php

/**
* 
*/
class ModelName extends CI_Model
{
	function method_name()
	{
		
	}
}

```