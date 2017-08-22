## Installation
Please install by using the composer command.

    composer require openforce/debug-container

Next, add ServiceProvider to *providers* in *config/app.php*


    'providers' => array(
        /*
         * Package Service Providers...
         */
        Openforce\DebugCOntainer\DebugContainerServiceProvider::class,
        /*
         * Application Service Providers...
         */
    ),


## Usage

    php artisan debug:container
