# README
<h5>mPDF wrapper for Laravel 5.1</h5>

Begin by installing this package through Composer. Edit your project's composer.json file to require dbonke/mpdf-laravel5.1 .

    {
      "require": {
           "dbonke/mpdf-laravel5.1" : "dev-master"
        }
    }
    
Next update composer from the terminal:

    $ composer update
    
Once this operation is done, you'll need to add the ServiceProvider. Open `app/config/app.php` and add a new item to the providers array.

    dbonke\Mpdf\MpdfServiceProvider::class,
    
Optionally you can register the facade.

    'MPDF' => dbonke\Mpdf\Facades\Pdf::class,
    
<h5>License</h5>

This mPDF wraper for laravel 5.1 is open-sourced software licensed under the <a href="http://opensource.org/licenses/MIT">MIT license</a>
    
