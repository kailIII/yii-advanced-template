Bryan Tan Yii Advanced Application Template
===========================================

**NOTE** Thank you for using Yii 2 Advanced Application Template - an application template that works out-of-box and can be easily customized to fit for your needs.
Yii 2 Advanced Application Template is best suitable for large projects requiring frontend and backend separation, deployment in different environments, configuration nesting etc.

DIRECTORY STRUCTURE
-------------------

```
protected
    config
        api/            contains api configurations
        backend/        contains backend configurations
        common/         contains shared configurations
        console/        contains console configurations
        frontend/       contains frontend configurations
        test/           contains test driven development configurations
    controllers
        api/            contains api controller
        backend/        contains backend controller
        frontend/       contains frontend controller
    models
        _base           contains base models (automatic generated by gii)
        _common         contains common classes used in backend, frontend and api
        api             contains api-specific classes
        backend         contains backend-specific classes
        frontend        contains frontend-specific classes

environment.php         contains environment-based
```

REQUIREMENTS
------------

The minimum requirement by Yii is that your Web server supports PHP 5.3.0.

In order for captcha to work you need either GD2 extension or ImageMagick PHP extension.

INSTALLATION
------------

### Installation ###
    1. /assets - create 'assets' folder in root directory
    2. /protected/runtime - create 'runtime' folder in protected directory
    3. /uploads - change to 777
    4  /protected/yiic.php , yiic.bat and yiic - change to 755 atleast. this is where we do our migration and unit testing
    5. /environment.php - add your absolute path to $local_path
    6. /environment-console.php - add your absolute path to $local_path
    7. /protected/yiic.php - add absolute path of the server,  change the $local_path.
    8. /protected/config/dbconnect.local.php - create a file and copy the format in dbconnect.sample.php (local development) and change the the configuration

GETTING STARTED
---------------

you should be able to access:

- the frontend using the URL `http://localhost/bryantan/`
- the backend using the URL `http://localhost/bryantan/backend/`
- the api using the URL `http://localhost/bryantan/api/`

###### Inspired By: http://www.yiiframework.com/wiki/63/organize-directories-for-applications-with-front-end-and-back-end-using-webapplicationend-behavior
###### Since: Oct 25, 2013
###### Author: bryantan16@gmail.com
###### Version: 1.0.0