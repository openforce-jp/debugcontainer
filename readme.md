## Installation
Please install by using the composer command.

    composer require openforce/debug-container:dev-master

Next, add ServiceProvider to *providers* in *config/app.php*


    'providers' => array(
        /*
         * Package Service Providers...
         */
        Openforce\DebugContainer\DebugContainerServiceProvider::class,
        /*
         * Application Service Providers...
         */
    ),


## Usage

    php artisan debug:container
