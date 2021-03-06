# Slim Framework 3 Skeleton - with Stripe Middleware

This is a simple stripe payment middleware with slim framework / twig example implementation.

## Install the Application

Run this command from the directory in which you want to install your new Slim Framework application.

    php composer.phar create-project slim/slim-stripe-skeleton [my-app-name]

Replace `[my-app-name]` with the desired directory name for your new application. You'll want to:

Go to `[my-app-name]\config` and edit the configuration to add your stripe credentials.

* Point your virtual host document root to your new application's `public/` directory.
* Ensure `logs/` is web writeable.

To run the application in development, you can also run this command. 

	php composer.phar start

Run this command to run the test suite

	php composer.phar test

That's it! Now go build something cool.
