# Installation 💻

- Get an Hosting Account or Web Server that supports ```PHP (V. 7.4 =>)``` + ```MySQL/MariaDB``` (also works locally with Docker or Xampp for example)

- Download ShibeShip here: [https://github.com/dogeorg/ShibeShip/](https://github.com/dogeorg/ShibeShip/)

- Upload all files (excluding ```shibeship.sql``` and ```readme.md```) to your Hosting Account.

- Now edit the file ```inc/_config.php```, rename it to ```inc/config.php``` and add your [gigawallet server](https://gigawallet.dogecoin.org) and database conections and settings

- Create a cron task to run every minute to poin to ```inc/cron.php```