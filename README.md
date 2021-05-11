# XPFRAME
Official XPFRAME Documentation 
###### By XENONMC Devlopment Team

Hey, Welcome to our framework!  To get started on using our framework, lets install it first.

## Installation
Download the XPFRAME installer to get started, or just clone the repository to your project folder via git:
```bash
git clone https://xenonmc-dev/xpframe
````

## Getting started
Lets get started by creating our first page
Open up `Main.php` and terminal.  Make sure PHP-CLI is also installed, otherwise any kind of hosting software to run your application.  Make sure its PHP version is also set to the latest release.

NOTE: Your code goes between the `run()` method of the `Main` class

Creating a route
```php
// Initialize Router
$router = new Router();

// Register the event for a page with the URL of `/hello`
$router->on("get", "hello", function () {
    echo "Hello World";
});

// Find and process all router URL events
$router->handle_events();
```

###### An Official XENONMC Project
