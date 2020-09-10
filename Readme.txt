Steps to deploy on your local development

1. First clone the application to your designated local drive.
2. After you clone it setup your database config in .ENV file.
3. Run php artisan key:generate
4. Run the migration command.
5. Run composer install to update the dependencies.
6. Run npm install to update the vue components and dependencies.
7. Once you done all the setup, run the php artisan serve and npm run watch.
