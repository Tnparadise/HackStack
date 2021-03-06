# HackStack - Don't start from scratch

HackStack is a baseline for a restful PHP website which allows you to focus on building out your idea instead of reimplementing common components.


While built with hackathons and MVPs in mind, HackStack uses production ready components and is designed to offer the best development and user experience.

## Features
Baked in:
* Dyanamic URL routing
* Twig templating with automatic caching
* Logging with automatic rotation and separate access and error logs
* Pre-configured templates and routing for:
    * 500, 404, and 403 HTTP errors
    * User authentication
* Cross-browser styling and consistency

## Components
HackStack is built on the shoulders of giants and uses a number of libraries:

* [Composer](https://github.com/composer/composer) for managing dependencies
* [Slim](https://github.com/composer/composer) as a lightweight routing engine and template renderer
* [Slim-Skeleton](https://github.com/codeguy/Slim-Skeleton) for common Slim components and setup, which includes:
    * [Monolog](https://github.com/Seldaek/monolog) for logging
    * [Twig](https://github.com/fabpot/Twig) for templating
    * [Slim-Views](https://github.com/codeguy/Slim-Views) for rendering Twig templates
* [Slim-Extras](https://github.com/codeguy/Slim-Extras) for some basic Slim middleware, including:
    * [CSRFGuard](https://github.com/codeguy/Slim-Extras/blob/master/Middleware/CsrfGuard.php) for handling and checking CSRF tokens
* [SwiftMailer](https://github.com/swiftmailer/swiftmailer) for handling email delivery
* [Bootstrap](https://github.com/twbs/bootstrap) for clean templating and styling
* [JQuery](https://github.com/jquery/jquery) for bootstrap interactions

Additionally, the following services and other attributions have contributed:

* [Bootstrap CDN](http://www.bootstrapcdn.com) for CDN sources of bootstrap styles
* [CDNJS](http://cdnjs.com/) for CDN sources of bootstrap javascript and jquery
* [Github](http://www.github.com) for the structure of a number of elements including the sign in element
* [Simple Line Icon Webfont](http://graphicburger.com/simple-line-icons-webfont/) for awesome clean icons

## How to Contribute

### Pull Requests

1. Fork the HackStack PHP repository
2. Create a new branch for your changes
    * For new features, your branch name should be prefaced with 'feature-'
    * For bug fixes & improvements, your branch name should be prefaced with 'fix-'
3. Send a pull request from each feature branch to the **development** branch

It is very important to separate new features or improvements into separate feature branches, and to send a
pull request for each branch. This allows us to review and pull in new features or improvements individually.

### Style Guide

You should try to match the styling of the existing code as much as possible.
