# CronJobMailer

## Steps for Testing CronJob

1. Pull This master Branch 
2. Run Command - php artisan migrate
3. Run Command - php artisan serve
4. go to URL http://127.0.0.1:8000/register and Register 2 or 3 dummy entries
5. go to App\Console\Commands\RegisteredUsers.php file and edit your own Mail Address in handle() function
6. On Local Server Run Command php artisan schedule:run  