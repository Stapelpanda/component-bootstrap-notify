# component-bootstrap-notify
Bootstrap notify for the @robloach/component-installer

Simple `composer.json` file to allow [bootstrap-notify](https://github.com/mouse0270/bootstrap-notify) to be installed by [RobLoach/component-installer](https://github.com/RobLoach/component-installer)

## Installing
Setup Composer to include this repository:

  	{
    	...
    	"require": {
      	...
      	"components/bootstrap-notify": "^3"
    	},
    	"repositories": [
    	  	{ "type": "vcs", "url": "https://github.com/StapelPanda/components-bootstrap-notify" }
    	]
  	}

Install using composer `composer require components/bootsrap-notify`

## Usage

Using `RequireJS`

		require(['bootstrap-notify']);
    define(['jquery'], function($){
        $.notify('<strong>My First Notify</strong> Jeay!');
    });
