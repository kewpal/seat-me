# Slim Framework 3 Skeleton Application

PHP - https://www.php.net/
Composer - https://getcomposer.org/
Git - https://git-scm.com/
Poedit - https://poedit.net/

## Install the Application

Run this command from the directory in which you want to install your new Slim Framework application.

    php composer.phar create-project slim/slim-skeleton [my-app-name]

Replace `[my-app-name]` with the desired directory name for your new application. You'll want to:

- Point your virtual host document root to your new application's `public/` directory.
- Ensure `logs/` is web writeable.

To run the application in development, you can run these commands

    cd [my-app-name]
    php composer.phar start

Run this command in the application directory to run the test suite

    php composer.phar test

That's it! Now go build something cool.
