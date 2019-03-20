# Update BookStack for Ubuntu 18.04

Instruction to update BookStack for Ubuntu Server 18.04

Bookstack: https://www.bookstackapp.com/

Ubuntu Server https://www.ubuntu.com/download/server

----




1) Connec to server via putty, go to directory

`cd /var/www/bookstack`

2) Run following code:

`sudo git pull origin release && composer install && php artisan migrate`

3) Clear Cache

`sudo php artisan cache:clear`


`sudo php artisan view:clear`



<img src="https://i.imgur.com/nAd5z1w.png">


----

If you have any questions, or comments please reach out to me on Twitter <a href="https://twitter.com/sultansolutions"> @SultanSolutions </a> 
