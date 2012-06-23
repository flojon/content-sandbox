# Koala Content sandbox

Welcome to Koala Content. This is a sandbox for [KoalaContentBundle][2] to help you get started quickly.
KoalaContentBundle is a simple CMS built for the Symfony 2 framework using the amazing [Mercury Editor][1] as front end editor.
For more information how to install the bundle in an existing project go to the bundle project [KoalaContentBundle][2].

## Quick setup
1. Clone this repo `$ git clone https://github.com/flojon/content-sandbox.git`
2. Install [Composer][3] `$ curl -s http://getcomposer.org/installer | php`
3. Install depencies using Composer `$ php composer.phar install`
4. Install the parameters file and setup your database connection `$ cp app/config/parameters.yml.sample app/config/parameters.yml`
5. Run the setup command to install default content `$ php app/console koala_content:setup`

[1]: http://jejacks0n.github.com/mercury/ "Mercury Editor"
[2]: https://github.com/flojon/KoalaContentBundle "KoalaContentBundle"
[3]: http://getcomposer.org/ "Composer - Dependency manager for PHP"
