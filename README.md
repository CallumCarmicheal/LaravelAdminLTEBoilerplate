# This is a fully configured and setup version of [acacha/adminlte-laravel](https://github.com/acacha/adminlte-laravel).  

Latest Build is for [commit 919ffd3](https://github.com/acacha/adminlte-laravel/commit/919ffd3eb61bea31b1fcda4602cd462cae7feb5c), [browse source for commit 919ffd3](https://github.com/acacha/adminlte-laravel/tree/919ffd3eb61bea31b1fcda4602cd462cae7feb5c).

All the node modules, bower resources, and pretty much everything else is setup and ready, all you need to do is All you need to do is setup the .env file and `php artisan migrate && php artisan serve` and your ready to go!

__Please note this is a very large repo, weighing in under a GIGABYTE, this is the size after everything is unpacked and configurated.__

If you are copying this directly into a git repo, make sure you goto [laravel's github repo and get the .gitignore](https://github.com/laravel/laravel/blob/master/.gitignore), i have removed a few things to make the modules appear on the repo.

## NPM Operations
Basically we have 2 sets of options for dev, prod (dev, dev-o, prod, prod-o). dev will call bower for AdminLTE and the -o will skip it, this is the same for any compiling scripts like watch, hot etc except lint.