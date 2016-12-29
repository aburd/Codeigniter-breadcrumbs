Breadcrumbs is an small library that helps your manage HTML breadcrumbs with CodeIgniter.
__* No longer maintained__

## Instalation

* Put Breadcrumbs.php in application/library folder
* Put breadcrumbs.php in application/config folder

## Example of use

	// load Breadcrumbs
	$this->load->library('breadcrumbs');

	// add breadcrumbs (add breadcrumb to end)
	$this->breadcrumbs->push('Section', '/section',);

	// add breadcrumb with Base Site URL (add without index.php in the url)
	$this->breadcrumbs->push('Page', '/section/page', true);

	// unshift crumb (add breadcrumb to front)
	$this->breadcrumbs->unshift('Home', '/');

	// unshift crumb with Base Site URL (add without index.php in the url)
	$this->breadcrumbs->unshift('Home', '/');

	// output
	$this->breadcrumbs->show();

## License

Released under the MIT License, Copyright (c) 2012–ω Buti.
