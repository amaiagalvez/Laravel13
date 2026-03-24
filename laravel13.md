# install berria

>> docker-compose.yml PHP 8.3 

composer global require laravel/installer

laravel new example-app

# martxan jarri

>> docker-compose.yml PHP 8.3 MARIADB 11.7 NODE 23-bullseye Laravel 13.0



==========================

>> demo0

  ```
  sudo chown amaia:amaia dc-data/
  sudo chown amaia:amaia dc-data/mysqldumps
  sudo chown amaia:amaia .phpunit.result.cache
  ```

>> [Pint](https://mlocati.github.io/php-cs-fixer-configurator/#version:3.75)
* Code reformat

>> [FakerPHP](https://fakerphp.org/)
* lang eta timezone
* funtzioak Factory barruan datuak sortzeko

>> Sessions taula => db lerroa ezabatzen da sesioa ixtean
* beste taula batean gorde?

>> Rutak => se comprueban en orden que tienen dentro del fichero web
* /posts/create
* /posts/{slug}

>> PHP ARTISAN
* php artisan make:controller NameController
* php artisan make:model Name
* php artisan make:migration create_yyyyy
* php artisan make:migration add_xxxxx_to_yyyyy_table

>>[Tailwind](https://tailwindcss.com)
* [Flowbite](https://flowbite.com/)
* [Sweet Alert 2](https://sweetalert2.github.io/)
* [Flux UI](https://fluxui.dev)
* [Heroicons](https://heroicons.com/)
  
>> Componentes

  => Componentes anonimos (no dependen de ninguna clase - alert)
  
  => Componentes de clase (para separar la logica de la vista - alert2)

  => layouts como componentes (app_clean)

>> Layouts (betikoak)
  @yield('content') => @section('content') .... @endsection <== bakarra
  @stack('css') => @push('css') ... @endpush <== se puede repetir y se van acumulando

>> Mutators && Casts
* configurar como guardar y mostrar los datos

>> Sanitize
* Limpiar los inputs

>> Locations
php artisan lang:publish

composer require laravel-lang/common
  php artisan lang:add eu
  php artisan lang:add es
  php artisan lang:add en
  php artisan lang:add fr

>> Mailables

php artisan vendor:publish --tag=laravel-mail

>>>>> https://www.youtube.com/watch?v=G1wRzlmKrKc&list=PLZ2ovOgdI-kVtF2yQ2kiZetWWTmOQoUSG&index=27

>> THEMES
* Frogatu Filament 
  * Bideoak: https://www.youtube.com/watch?v=979wNu6yEfQ
  * [Filament](https://filamentphp.com/)
* 